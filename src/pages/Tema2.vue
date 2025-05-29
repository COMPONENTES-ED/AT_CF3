<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido" data-aos="flip-up">
        <div class="titulo-principal__numero"><span>2</span></div>
        <h1>Gestión de la variabilidad espacial y temporal</h1>
      </div>
      <div class="row">
        <div class="col-lg" data-aos="fade-right">
          <div
            class="h-100 p-4 d-flex align-content-center flex-wrap"
            style="background-color:#E4F7FA;"
          >
            <p class="mb-0">
              La gestión de la variabilidad espacial y temporal se refiere al
              análisis y control de las diferencias que ocurren en los
              parámetros de un proceso o sistema en función de su ubicación y
              del tiempo. Esta disciplina permite entender cómo varían ciertas
              variables clave (como temperatura, humedad, productividad, etc.)
              en distintas áreas geográficas y a lo largo del tiempo, lo que
              resulta esencial en sectores como la agricultura, la logística y
              la manufactura avanzada. Mediante el uso de herramientas como los
              Sistemas de Información Geográfica (GIS) y el análisis de datos,
              es posible identificar patrones, optimizar recursos y mejorar la
              toma de decisiones. Este capítulo explora los conceptos básicos,
              las técnicas y las aplicaciones de la gestión de la variabilidad
              espacial y temporal en entornos industriales y productivos.
            </p>
          </div>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema2/1.png" /></figure>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_2_1">2.1 Conceptos de variabilidad espacial y temporal</h2>
      </div>
      <p data-aos="fade-left">
        Se refiere a las diferencias en las condiciones de un parámetro
        específico en función de su ubicación geográfica. Por ejemplo, en la
        agricultura, las propiedades del suelo, la humedad y los niveles de
        nutrientes pueden variar significativamente en diferentes partes de un
        campo. La variabilidad temporal, por otro lado, se centra en los cambios
        de una variable en un mismo lugar a lo largo del tiempo, como las
        variaciones estacionales de temperatura o precipitación.
      </p>
      <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
        <div class="row">
          <div class="col-auto pe-0">
            <figure><img src="@/assets/curso/tema1/9.svg" /></figure>
          </div>
          <div class="col ps-2" style="place-self:center;">
            <h3 class="mb-0 pe-4">
              Importancia de la variabilidad espacial y temporal en la industria
            </h3>
          </div>
        </div>
      </div>
      <div class="p-4 pt-xl-5 pb-xl-5" style="background-color:#E3F0D4;">
        <div class="row">
          <div
            class="col-lg-auto d-none d-lg-block"
            data-aos="fade-right"
            style="place-self:center;"
          >
            <figure><img src="@/assets/curso/tema2/2.svg" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-up" style="place-self:center;">
            <ol class="lista-ol--cuadro mb-0">
              <li class="d-flex mb-3">
                <div
                  class="lista-ol--cuadro__vineta"
                  style="background-color:#78B62E;"
                >
                  <span class="fw-bold" style="color:#12263F;">1</span>
                </div>
                <span
                  >En sectores como la agricultura de precisión, conocer la
                  variabilidad espacial del suelo y las condiciones climáticas
                  permite aplicar insumos de forma diferenciada, optimizando
                  recursos como agua y fertilizantes.</span
                >
              </li>
              <li class="d-flex mb-3">
                <div
                  class="lista-ol--cuadro__vineta"
                  style="background-color:#78B62E;"
                >
                  <span class="fw-bold" style="color:#12263F;">2</span>
                </div>
                <span
                  >En la logística, la gestión temporal permite optimizar rutas
                  de transporte en función de la demanda horaria y del tráfico,
                  mejorando los tiempos de entrega y reduciendo costos.</span
                >
              </li>
              <li class="d-flex mb-0">
                <div
                  class="lista-ol--cuadro__vineta"
                  style="background-color:#78B62E;"
                >
                  <span class="fw-bold" style="color:#12263F;">3</span>
                </div>
                <span
                  >En manufactura, el análisis de variabilidad permite
                  identificar patrones en la producción, predecir fallos y
                  mejorar el control de calidad en distintas etapas del
                  proceso.</span
                >
              </li>
            </ol>
          </div>
        </div>
      </div>
      <div
        class="titulo-sexto color-acento-contenido mt-5"
        data-aos="fade-down"
      >
        <h5>Tabla 1.</h5>
        <span>Técnicas de análisis espacial y temporal</span>
      </div>
      <div class="row">
        <div class="col-lg-8" data-aos="fade-right">
          <div class="tabla-a color-acento-botones">
            <table>
              <caption class="fw-normal">
                Fuente: OIT, 2024.
              </caption>
              <thead style="border:0 !important;">
                <tr class="text-center" style="background-color:#78B62E;">
                  <th>Retos para alcanzar la sostenibilidad</th>
                  <th>Uso</th>
                </tr>
              </thead>
              <tbody>
                <tr style="background-color:#F6F6F6;">
                  <td
                    class="fw-bold"
                    style="width:30%;border-right:1px #AFAFAF solid;"
                  >
                    Mapeo de datos geoespaciales
                  </td>
                  <td style="border:0;">
                    Utilización de mapas para visualizar y analizar datos que
                    tienen una componente espacial, como las condiciones de un
                    terreno.
                  </td>
                </tr>
                <tr style="background-color:#fff;">
                  <td class="fw-bold" style="border-right:1px #AFAFAF solid;">
                    Análisis de series temporales
                  </td>
                  <td style="border:0;">
                    Evaluación de datos que varían en el tiempo para identificar
                    patrones, tendencias y ciclos que afectan el proceso.
                  </td>
                </tr>
                <tr style="background-color:#F6F6F6;">
                  <td class="fw-bold" style="border-right:1px #AFAFAF solid;">
                    Interpolación espacial
                  </td>
                  <td style="border:0;">
                    Método estadístico que permite estimar el valor de una
                    variable en puntos no muestreados, basándose en la
                    información de puntos cercanos.
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
        <div class="col-lg-4 d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema2/3.png" /></figure>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_2_2">
          2.2 Técnicas de Recolección y Análisis de Datos Espaciales y
          Temporales
        </h2>
      </div>
      <p data-aos="fade-left">
        Para gestionar adecuadamente la variabilidad espacial y temporal, es
        fundamental contar con métodos eficientes para la recolección y análisis
        de datos. Estos datos se obtienen mediante sensores, drones, estaciones
        meteorológicas y otros dispositivos, y se procesan con herramientas de
        análisis espacial y software estadístico.
      </p>
      <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
        <div class="row">
          <div class="col-auto pe-0">
            <figure><img src="@/assets/curso/tema1/9.svg" /></figure>
          </div>
          <div class="col ps-2" style="place-self:center;">
            <h3 class="mb-0 pe-4">Recolección de datos espaciales</h3>
          </div>
        </div>
      </div>
      <TabsC class="color-acento-contenido">
        <div class="py-3 py-md-4" titulo="Sensores de suelo y clima">
          <div class="row p-4 col-xl-11 m-auto">
            <div class="col-md-auto mb-4 mb-md-0 col-7 m-auto">
              <figure><img src="@/assets/curso/tema2/5.svg" /></figure>
            </div>
            <div class="col-md">
              <h5>Sensores de suelo y clima</h5>
              <p class="mb-0">
                Utilizados en agricultura para medir propiedades del suelo (como
                humedad y nutrientes) y condiciones climáticas. Miden variables
                críticas como la humedad, temperatura, y niveles de nutrientes.
                En agricultura, estos sensores permiten realizar mapeos
                detallados de los suelos en función de su variabilidad.
              </p>
            </div>
          </div>
        </div>
        <div class="py-3 py-md-4" titulo="Drones y satélites">
          <div class="row p-4 col-xl-11 m-auto">
            <div class="col-md-auto mb-4 mb-md-0 col-7 m-auto">
              <figure><img src="@/assets/curso/tema2/6.svg" /></figure>
            </div>
            <div class="col-md">
              <h5>Drones y satélites</h5>
              <p class="mb-0">
                Proporcionan imágenes aéreas y datos precisos de áreas amplias,
                útiles en agricultura y gestión de recursos naturales, así como
                imágenes de alta resolución de grandes extensiones, útiles para
                detectar patrones de crecimiento, estrés hídrico y distribución
                de cultivos en un campo.
              </p>
            </div>
          </div>
        </div>
        <div class="py-3 py-md-4" titulo="Estaciones GPS y GIS">
          <div class="row p-4 col-xl-11 m-auto">
            <div class="col-md-auto mb-4 mb-md-0 col-7 m-auto">
              <figure><img src="@/assets/curso/tema2/7.svg" /></figure>
            </div>
            <div class="col-md">
              <h5>Estaciones GPS y GIS</h5>
              <p class="mb-0">
                Herramientas que permiten ubicar puntos de medición y asociarlos
                con datos específicos, facilitando la creación de mapas
                detallados. Localizan y registran datos geográficos precisos que
                permiten la creación de mapas detallados y su integración en
                plataformas GIS para análisis avanzado.
              </p>
            </div>
          </div>
        </div>
      </TabsC>
      <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
        <div class="row">
          <div class="col-auto pe-0">
            <figure><img src="@/assets/curso/tema1/9.svg" /></figure>
          </div>
          <div class="col ps-2" style="place-self:center;">
            <h3 class="mb-0 pe-4">Recolección de datos temporales</h3>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg" data-aos="fade-right">
          <div
            class="h-100 p-3 p-lg-4 d-flex align-content-center flex-wrap"
            style="background-color:#01B9D1;border-radius:10px;"
          >
            <ul class="lista-ul mb-0">
              <li class="d-flex bg-white p-2" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong>Sensores en tiempo real:</strong> dispositivos que
                  recogen datos continuamente en intervalos regulares,
                  permitiendo monitorear cambios temporales.</span
                >
              </li>
              <li class="d-flex bg-white p-2 mb-0" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong>Registros manuales y automatizados:</strong>
                  recopilación de datos en tiempos específicos, útil en análisis
                  de tendencias y comportamiento a lo largo de las
                  estaciones.</span
                >
              </li>
            </ul>
          </div>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema2/8.png" /></figure>
        </div>
      </div>
      <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
        <div class="row">
          <div class="col-auto pe-0">
            <figure><img src="@/assets/curso/tema1/9.svg" /></figure>
          </div>
          <div class="col ps-2" style="place-self:center;">
            <h3 class="mb-0 pe-4">Análisis de datos espaciales y temporales</h3>
          </div>
        </div>
      </div>
      <div class="cont_1_2">
        <div class="row justify-content-center">
          <div class="col-lg mb-4 mb-lg-0 col-md-9" data-aos="zoom-in">
            <div
              class="p-4 h-100 bg-white text-center cont_1_3"
              style="box-shadow:0px 4px 20px rgba(0,0,0,.1);border-radius:14px;"
            >
              <figure class="mb-3">
                <img
                  class="d-inline"
                  src="@/assets/curso/tema2/9.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Software de análisis geoespacial (GIS)</h5>
              <p>
                Herramientas como Arcgis y QGIS que permiten visualizar,
                analizar y gestionar datos espaciales.
              </p>
            </div>
          </div>
          <div class="col-lg mb-4 mb-lg-0 col-md-9" data-aos="zoom-in">
            <div
              class="p-4 h-100 bg-white text-center cont_1_3"
              style="box-shadow:0px 4px 20px rgba(0,0,0,.1);border-radius:14px;"
            >
              <figure class="mb-3">
                <img
                  class="d-inline"
                  src="@/assets/curso/tema2/10.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Análisis estadístico</h5>
              <p>
                Uso de herramientas como Excel, R y Python para analizar
                patrones temporales, identificar correlaciones y realizar
                pronósticos.
              </p>
            </div>
          </div>
          <div class="col-lg mb-4 mb-lg-0 col-md-9" data-aos="zoom-in">
            <div
              class="p-4 h-100 bg-white text-center cont_1_3"
              style="box-shadow:0px 4px 20px rgba(0,0,0,.1);border-radius:14px;"
            >
              <figure class="mb-3">
                <img
                  class="d-inline"
                  src="@/assets/curso/tema2/11.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Modelos predictivos</h5>
              <p>
                Técnicas avanzadas que permiten predecir el comportamiento
                futuro de las variables en función de datos históricos.
              </p>
            </div>
          </div>
        </div>
        <Separador></Separador>
        <div class="titulo-segundo" data-aos="flip-up">
          <h2 id="t_2_3">
            2.3 Aplicaciones en agricultura de precisión y otros sectores
          </h2>
        </div>
        <p data-aos="fade-left">
          La gestión de la variabilidad espacial y temporal tiene numerosas
          aplicaciones prácticas, especialmente en sectores como la agricultura,
          la logística, el medio ambiente y la manufactura. A continuación, se
          describen algunas aplicaciones clave en diferentes sectores.
        </p>
        <div class="row mt-4">
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/tema2/12.png" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-left">
            <AccordionRED tipo="a" clase-tarjeta="tarjeta">
              <div
                class="row col-xl-11 m-auto"
                titulo="Agricultura de precisión"
              >
                <p>
                  La agricultura de precisión utiliza datos espaciales y
                  temporales para optimizar el uso de recursos en el campo.
                  Mediante sensores de suelo y drones, se puede identificar la
                  variabilidad del terreno y aplicar fertilizantes, riego y
                  pesticidas solo en las áreas que lo necesitan, reduciendo
                  costos y minimizando el impacto ambiental.
                </p>
              </div>
              <div
                class="row col-xl-11 m-auto"
                titulo="Gestión de recursos naturales"
              >
                <p>
                  Los sistemas de monitoreo ambiental utilizan datos espaciales
                  y temporales para gestionar y proteger recursos naturales como
                  bosques, ríos y costas. Los mapas de uso del suelo y los datos
                  de calidad del agua permiten evaluar el estado de los recursos
                  y planificar su explotación de forma sostenible.
                </p>
              </div>
              <div class="row col-xl-11 m-auto" titulo="Logística y transporte">
                <p>
                  En la logística, el análisis de la variabilidad temporal
                  permite planificar rutas óptimas y reducir los tiempos de
                  entrega. El análisis de datos históricos de tráfico y patrones
                  de demanda permite ajustar los horarios y rutas de entrega
                  para mejorar la eficiencia operativa.
                </p>
              </div>
              <div
                class="row col-xl-11 m-auto"
                titulo="Control de calidad en manufactura"
              >
                <p>
                  En manufactura, el monitoreo espacial y temporal ayuda a
                  identificar variaciones en la calidad del producto en
                  diferentes partes de la línea de producción. Esto permite
                  hacer ajustes precisos en los procesos para mantener
                  estándares de calidad y detectar fallos potenciales antes de
                  que afecten al producto final.
                </p>
              </div>
            </AccordionRED>
          </div>
        </div>
      </div>
      <div
        class="titulo-sexto color-acento-contenido mt-5"
        data-aos="fade-down"
      >
        <h5>Tabla 2.</h5>
        <span
          >Herramientas y <em>software</em> para la gestión de la variabilidad
          espacial y temporal</span
        >
      </div>
      <div class="row">
        <div class="col-lg-8" data-aos="fade-right">
          <div class="tabla-a color-acento-botones">
            <table>
              <caption class="fw-normal">
                Fuente: OIT, 2024.
              </caption>
              <thead style="border:0 !important;">
                <tr class="text-center" style="background-color:#78B62E;">
                  <th colspan="2">
                    Herramientas para trabajar la gestión de la variabilidad
                    espacial y temporal
                  </th>
                </tr>
              </thead>
              <tbody class="text-center">
                <tr style="background-color:#fff;">
                  <td style="border-right:1px #AFAFAF solid;">
                    <strong>QGIS (Quantum GIS):</strong> un <em>software</em> de
                    código abierto para la gestión de datos geoespaciales,
                    utilizado para el mapeo y análisis de datos espaciales.
                  </td>
                  <td style="border:0;">
                    <a href="https://qgis.org" target="_blank"
                      >https://qgis.org</a
                    >
                  </td>
                </tr>
                <tr style="background-color:#F6F6F6;">
                  <td style="border-right:1px #AFAFAF solid;">
                    <strong>ArcGIS:</strong> una plataforma de análisis de datos
                    geoespaciales de pago que permite visualizar, analizar y
                    compartir datos espaciales
                  </td>
                  <td style="border:0;">
                    <a href="https://www.arcgis.com" target="_blank"
                      >https://www.arcgis.com</a
                    >
                  </td>
                </tr>
                <tr style="background-color:#fff;">
                  <td style="border-right:1px #AFAFAF solid;">
                    <strong>Google Earth Engine:</strong> una plataforma basada
                    en la nube que permite el análisis de imágenes satelitales y
                    otros datos geoespaciales.
                  </td>
                  <td style="border:0;">
                    <a href="https://earthengine.google.com/" target="_blank"
                      >https://earthengine.google.com/</a
                    >
                  </td>
                </tr>
                <tr style="background-color:#F6F6F6;">
                  <td style="border:0;" colspan="2">
                    <strong
                      >Python y R para análisis de series temporales:</strong
                    >
                    ambos lenguajes de programación ofrecen bibliotecas
                    específicas como Pandas, Numpy y Forecast, que permiten
                    analizar y modelar series temporales para predecir
                    tendencias y patrones.
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
        <div class="col-lg-4 d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema2/13.png" /></figure>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
