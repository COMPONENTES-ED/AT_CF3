<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido" data-aos="flip-up">
        <div class="titulo-principal__numero"><span>1</span></div>
        <h1>Introducción a los sistemas de información</h1>
      </div>
      <div class="row" data-aos="fade-up" data-aos-duration="750">
        <div class="col-lg pe-lg-0">
          <div
            class="h-100 p-4 d-flex align-content-center flex-wrap"
            style="background-color:#D7E1EB;"
          >
            <p class="mb-0">
              En el contexto industrial, los sistemas de información desempeñan
              un rol fundamental en la gestión y optimización de los procesos
              productivos. Estos sistemas permiten recopilar, almacenar,
              procesar y analizar grandes volúmenes de datos, facilitando la
              toma de decisiones y el control eficiente de las operaciones. La
              automatización y el control industrial dependen cada vez más de
              estos sistemas para mejorar la precisión, reducir tiempos de
              inactividad, y aumentar la eficiencia y la calidad de los
              productos. Este capítulo explora los conceptos básicos, las
              estructuras y las aplicaciones de los sistemas de información en
              el entorno industrial.
            </p>
          </div>
        </div>
        <div class="col-lg-auto ps-lg-0 d-none d-lg-block">
          <figure><img src="@/assets/curso/tema1/1.png" /></figure>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_1_1">1.1 Conceptos básicos de los sistemas de información</h2>
      </div>
      <div class="cont_1_1">
        <p data-aos="fade-left">
          Un sistema de información (si) es un conjunto de elementos
          interrelacionados que recopilan, procesan y distribuyen información
          para apoyar la toma de decisiones y el control en una organización.
          Estos sistemas combinan recursos humanos, tecnología y procesos de
          negocio para gestionar la información de manera eficiente y eficaz. En
          un entorno industrial, los sistemas de información permiten controlar
          cada fase del proceso de producción, desde la adquisición de materias
          primas hasta la entrega del producto final, manteniendo la calidad y
          minimizando errores.
        </p>
        <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
          <div class="row">
            <div class="col-auto pe-0">
              <figure><img src="@/assets/curso/tema1/9.svg" /></figure>
            </div>
            <div class="col ps-2" style="place-self:center;">
              <h3 class="mb-0 pe-4">
                Componentes de un sistema de información
              </h3>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/tema1/3.png" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-left">
            <AccordionRED tipo="a" clase-tarjeta="tarjeta">
              <div
                class="row col-xl-11 m-auto"
                titulo="&lt;em&gt;Hardware&lt;/em&gt;"
              >
                <p>
                  Equipos físicos como servidores, computadoras, dispositivos de
                  entrada/salida y redes de comunicación.
                </p>
              </div>
              <div
                class="row col-xl-11 m-auto"
                titulo="&lt;em&gt;Software&lt;/em&gt;"
              >
                <p>
                  Programas y aplicaciones que procesan la información,
                  incluyendo sistemas operativos y <em>software</em> de gestión
                  empresarial.
                </p>
              </div>
              <div class="row col-xl-11 m-auto" titulo="Datos">
                <p>
                  Información bruta que se convierte en conocimiento útil una
                  vez procesada.
                </p>
              </div>
              <div class="row col-xl-11 m-auto" titulo="Procedimientos">
                <p>
                  Reglas y políticas que definen cómo se gestionan los datos y
                  los procesos de información.
                </p>
              </div>
              <div class="row col-xl-11 m-auto" titulo="Personas">
                <p>
                  Usuarios y técnicos que interactúan con el sistema para
                  asegurar su funcionamiento y mantenimiento.
                </p>
              </div>
            </AccordionRED>
          </div>
        </div>
      </div>
      <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
        <div class="row">
          <div class="col-auto pe-0">
            <figure><img src="@/assets/curso/tema1/9.svg" /></figure>
          </div>
          <div class="col ps-2" style="place-self:center;">
            <h3 class="mb-0 pe-4">
              Tipos de sistemas de información en la industria
            </h3>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg" data-aos="zoom-in">
          <AccordionRED tipo="a" clase-tarjeta="tarjeta">
            <div
              class="row col-xl-11 m-auto"
              titulo="Sistemas de control de procesos"
            >
              <p>
                Monitorean y controlan variables de procesos industriales en
                tiempo real, como la temperatura, presión y flujo.
              </p>
            </div>
            <div
              class="row col-xl-11 m-auto"
              titulo="Sistemas de gestión de la producción (mes)"
            >
              <p>
                Integran y controlan actividades de producción, asegurando la
                eficiencia y calidad en cada etapa del proceso productivo.
              </p>
            </div>
            <div
              class="row col-xl-11 m-auto"
              titulo="Sistemas de gestión de recursos empresariales (ERP)"
            >
              <p>
                Integran áreas clave de la organización como finanzas,
                inventario, y recursos humanos, proporcionando una visión
                completa y sincronizada de las operaciones.
              </p>
            </div>
          </AccordionRED>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema1/4.png" /></figure>
        </div>
      </div>
      <Separador></Separador>
      <div class="cont_1_2">
        <div class="titulo-segundo" data-aos="flip-up">
          <h2 id="t_1_2">
            1.2 Funciones y beneficios de los sistemas de información en la
            industria
          </h2>
        </div>
        <p data-aos="fade-left">
          Los sistemas de información en la industria desempeñan funciones
          críticas que mejoran la eficiencia, seguridad y calidad en los
          procesos de producción. Entre sus principales funciones se encuentran
          la captura de datos en tiempo real, el análisis predictivo, la gestión
          de inventarios, y la optimización de recursos. Los beneficios de
          implementar estos sistemas en entornos industriales son numerosos:
        </p>
        <div class="row mt-4">
          <div class="col-lg mb-4 mb-lg-0 col-md-6" data-aos="zoom-in">
            <div
              class="p-4 h-100 bg-white text-center cont_1_3"
              style="box-shadow:0px 4px 20px rgba(0,0,0,.1);border-radius:14px;"
            >
              <figure class="mb-3">
                <img
                  class="d-inline"
                  src="@/assets/curso/tema1/5.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Optimización de procesos</h5>
              <p>
                Permiten que los procesos productivos sean más eficientes,
                reduciendo tiempos de ciclo y minimizando los recursos
                necesarios.
              </p>
            </div>
          </div>
          <div class="col-lg mb-4 mb-lg-0 col-md-6" data-aos="zoom-in">
            <div
              class="p-4 h-100 bg-white text-center cont_1_3"
              style="box-shadow:0px 4px 20px rgba(0,0,0,.1);border-radius:14px;"
            >
              <figure class="mb-3">
                <img
                  class="d-inline"
                  src="@/assets/curso/tema1/6.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Toma de decisiones basada en datos</h5>
              <p>
                Proporcionan información confiable y en tiempo real, permitiendo
                a los gestores tomar decisiones informadas y precisas.
              </p>
            </div>
          </div>
          <div class="col-lg mb-4 mb-lg-0 col-md-6" data-aos="zoom-in">
            <div
              class="p-4 h-100 bg-white text-center cont_1_3"
              style="box-shadow:0px 4px 20px rgba(0,0,0,.1);border-radius:14px;"
            >
              <figure class="mb-3">
                <img
                  class="d-inline"
                  src="@/assets/curso/tema1/7.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Reducción de costos</h5>
              <p>
                Al optimizar los procesos y mejorar el uso de recursos, los
                sistemas de información ayudan a reducir costos operativos y de
                mantenimiento.
              </p>
            </div>
          </div>
          <div class="col-lg mb-4 mb-lg-0 col-md-6" data-aos="zoom-in">
            <div
              class="p-4 h-100 bg-white text-center cont_1_3"
              style="box-shadow:0px 4px 20px rgba(0,0,0,.1);border-radius:14px;"
            >
              <figure class="mb-3">
                <img
                  class="d-inline"
                  src="@/assets/curso/tema1/8.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Mejora de la calidad del producto</h5>
              <p>
                El control riguroso de los parámetros de producción asegura que
                los productos cumplan con los estándares de calidad.
              </p>
            </div>
          </div>
        </div>
        <Separador></Separador>
        <div class="titulo-segundo" data-aos="flip-up">
          <h2 id="t_1_3">
            1.3 Sistemas de información para la toma de decisiones
          </h2>
        </div>
        <p data-aos="fade-left">
          Los sistemas de información se han convertido en una herramienta
          esencial para la toma de decisiones estratégicas en la industria. A
          continuación, se presentan algunos de los sistemas más comunes que
          apoyan este proceso:
        </p>
      </div>
      <div class="cont_1_4 mt-5 pt-4 pb-4 pb-xl-5 pt-xl-5">
        <div class="tarjeta bg-white p-4 p-lg-5 pb-lg-4">
          <CarouselRED tipo="b">
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0" style="place-self:center;">
                <h5>SCADA (supervisión, control y adquisición de datos)</h5>
                <p class="mt-4">
                  Es un sistema de supervisión y control que recopila datos en
                  tiempo real de sensores y dispositivos distribuidos en el
                  entorno industrial. Los sistemas SCADA permiten el monitoreo y
                  control de operaciones desde una ubicación centralizada,
                  asegurando la eficiencia y seguridad en procesos críticos.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema1/11.png" />
                </figure>
              </div>
            </div>
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0" style="place-self:center;">
                <h5>Sistemas MES (<em>Manufacturing Execution System</em>)</h5>
                <p class="mt-4">
                  Un sistema MES gestiona y controla las operaciones de
                  fabricación en tiempo real. Facilita el seguimiento de cada
                  producto en la línea de producción, asegurando la trazabilidad
                  y el cumplimiento de los estándares de calidad.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema1/12.png" />
                </figure>
              </div>
            </div>
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0" style="place-self:center;">
                <h5>ERP (<em>Enterprise Resource Planning</em>)</h5>
                <p class="mt-4">
                  Este sistema integra diversas áreas de la empresa, como
                  finanzas, producción, logística y recursos humanos, en una
                  única plataforma. Los ERP optimizan la planificación de
                  recursos y mejoran la visibilidad general de la organización,
                  permitiendo a los gerentes tomar decisiones informadas basadas
                  en datos centralizados.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema1/13.png" />
                </figure>
              </div>
            </div>
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0" style="place-self:center;">
                <h5>
                  CMMS (<em>Computerized Maintenance Management System</em>)
                </h5>
                <p class="mt-4">
                  Un sistema de gestión de mantenimiento que ayuda a programar,
                  ejecutar y monitorear las actividades de mantenimiento de los
                  equipos industriales. El CMMS reduce el tiempo de inactividad
                  no planificado y prolonga la vida útil de los equipos,
                  mejorando la productividad general.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema1/14.png" />
                </figure>
              </div>
            </div>
          </CarouselRED>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_1_4">
          1.4 Aplicaciones de los sistemas de información en la industria
        </h2>
      </div>
      <div class="row mt-4">
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/tema1/15.png" /></figure>
        </div>
        <div class="col-lg" data-aos="fade-left">
          <div
            class="h-100 p-3 p-lg-4 d-flex align-content-center flex-wrap"
            style="background-color:#01B9D1;border-radius:10px;"
          >
            <ul class="lista-ul mb-0">
              <li class="d-flex bg-white p-2" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong>Automatización y control de procesos:</strong> los
                  sistemas de información permiten monitorear y controlar
                  procesos industriales en tiempo real, mejorando la precisión y
                  reduciendo los errores humanos. Un ejemplo es la
                  automatización de líneas de producción en la industria
                  automotriz, donde cada etapa del ensamblaje se controla de
                  manera automática y precisa.</span
                >
              </li>
              <li class="d-flex bg-white p-2" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong>Gestión de la cadena de suministro:</strong> mediante
                  el uso de sistemas ERP y MES, las empresas pueden gestionar y
                  optimizar la cadena de suministro, desde la adquisición de
                  materiales hasta la distribución del producto final. Esto es
                  particularmente útil en industrias como la alimentaria y
                  farmacéutica, donde el control de inventarios y la
                  trazabilidad son esenciales.</span
                >
              </li>
              <li class="d-flex bg-white p-2 mb-0" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong>Mantenimiento predictivo:</strong> a través de
                  sistemas de información y sensores de monitoreo, es posible
                  predecir fallos en los equipos y realizar mantenimiento
                  preventivo antes de que ocurra una falla. Esto reduce los
                  tiempos de inactividad y mejora la eficiencia operativa, como
                  en plantas de energía y manufactura avanzada.</span
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
      <p class="mt-4" data-aos="fade-right">
        Se recomienda profundizar sobre los sistemas de información a través del
        siguiente material:
      </p>
      <div class="row mt-4 justify-content-center">
        <div class="col-lg mb-4 mb-lg-0 col-md-8" data-aos="fade-up">
          <a
            class="anexo ms-0 h-100"
            href="https://www.youtube.com/watch?v=6Mncbrp80To"
            target="_blank"
            style="max-width:fit-content;"
          >
            <div class="anexo__icono">
              <img src="@/assets/bullets/icono-video.svg" />
            </div>
            <div class="anexo__texto">
              <p class="fw-normal">
                <strong>Enlace video.</strong> Video - ¿Qué es ERP? - Conoce
                porque un ERP vital para empresas.
              </p>
            </div></a
          >
        </div>
        <div class="col-lg mb-4 mb-lg-0 col-md-8" data-aos="fade-up">
          <a
            class="anexo ms-0 h-100"
            href="https://www.cursosaula21.com/que-es-la-simulacion-de-procesos-industriales/"
            target="_blank"
            style="max-width:fit-content;"
          >
            <div class="anexo__icono">
              <img src="@/assets/bullets/icono-link.svg" />
            </div>
            <div class="anexo__texto">
              <p class="fw-normal">
                <strong>Enlace web.</strong> Lectura - Qué es la simulación de
                procesos industriales.
              </p>
            </div></a
          >
        </div>
        <div class="col-lg mb-4 mb-lg-0 col-md-8" data-aos="fade-up">
          <a
            class="anexo ms-0 h-100"
            href="https://dialnet.unirioja.es/descarga/articulo/5280242.pdf"
            target="_blank"
            style="max-width:fit-content;"
          >
            <div class="anexo__icono">
              <img src="@/assets/bullets/icono-link.svg" />
            </div>
            <div class="anexo__texto">
              <p class="fw-normal">
                <strong>Enlace web.</strong> Lectura - Los sistemas SCADA en la
                automatización industrial.
              </p>
            </div></a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tema1',
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
