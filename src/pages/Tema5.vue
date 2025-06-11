<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido" data-aos="flip-up">
        <div class="titulo-principal__numero"><span>5</span></div>
        <h1>Hidráulica y neumática</h1>
      </div>
      <div
        class="p-4"
        style="background-color:#E3F0D4;border-radius:7px;border:2px #3BA935 dashed;"
        data-aos="fade-up"
      >
        <div class="row">
          <div class="col-md-auto d-none d-md-block">
            <figure><img src="@/assets/curso/tema5/1.svg" /></figure>
          </div>
          <div class="col-md">
            <p class="mb-0">
              La hidráulica y neumática son dos ramas de la automatización
              industrial que se basan en el uso de fluidos para transmitir
              energía y realizar trabajo mecánico. La hidráulica emplea
              líquidos, generalmente aceite, para generar movimientos precisos y
              de gran fuerza, mientras que la neumática utiliza gases,
              comúnmente aire comprimido, para lograr movimientos rápidos y
              flexibles. Estas tecnologías tienen aplicaciones diversas en la
              industria, desde sistemas de elevación y prensas hidráulicas hasta
              herramientas neumáticas y sistemas de transporte. Este capítulo
              proporciona una introducción a los principios fundamentales de la
              hidráulica y neumática, detalla sus componentes y explora
              aplicaciones comunes en la automatización industrial. Además, se
              incluyen actividades prácticas y simulaciones para estudiantes en
              modalidad remota, permitiendo la práctica y comprensión de estos
              sistemas.
            </p>
          </div>
        </div>
      </div>
      <Separador></Separador>
      <div class="cont_4_1">
        <div class="titulo-segundo" data-aos="flip-up">
          <h2 id="t_5_1">5.1 Principios básicos de hidráulica y neumática</h2>
        </div>
        <p data-aos="fade-left">
          Tanto la hidráulica como la neumática se fundamentan en los principios
          de la mecánica de fluidos y las leyes físicas que rigen el
          comportamiento de líquidos y gases.
        </p>
        <div class="row mt-4">
          <div class="col-lg" data-aos="fade-right">
            <AccordionRED tipo="a" clase-tarjeta="tarjeta">
              <div
                class="row col-xl-11 m-auto"
                titulo="Principio de Pascal en hidráulica"
              >
                <p>
                  Este principio establece que una presión ejercida en un fluido
                  confinado se transmite uniformemente en todas las direcciones.
                  Este concepto es la base de los sistemas hidráulicos,
                  permitiendo transmitir grandes fuerzas a través de pequeñas
                  presiones, lo cual es ideal en prensas y sistemas de
                  elevación.
                </p>
              </div>
              <div
                class="row col-xl-11 m-auto"
                titulo="Ley de Boyle y Ley de Charles en neumática"
              >
                <p>
                  La Ley de Boyle establece que, en un gas a temperatura
                  constante, el volumen es inversamente proporcional a la
                  presión. La Ley de Charles indica que el volumen de un gas es
                  directamente proporcional a su temperatura. Estos principios
                  ayudan a entender cómo se comporta el aire comprimido en
                  sistemas neumáticos y cómo se puede controlar la presión para
                  realizar trabajo.
                </p>
              </div>
              <div
                class="row col-xl-11 m-auto"
                titulo="Ventajas y limitaciones"
              >
                <p>
                  La hidráulica permite obtener movimientos con gran fuerza y
                  precisión, pero su mantenimiento es más complejo debido a
                  posibles fugas de aceite. La neumática es más sencilla y de
                  bajo costo, pero es menos precisa y tiene limitaciones en
                  cuanto a la fuerza que puede generar.
                </p>
              </div>
            </AccordionRED>
          </div>
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
            <figure><img src="@/assets/curso/tema5/2.png" /></figure>
          </div>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_5_2">
          5.2 Componentes de los sistemas hidráulicos y neumáticos
        </h2>
      </div>
      <div class="row">
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/tema5/3.png" /></figure>
        </div>
        <div class="col-lg" data-aos="fade-left">
          <div class="p-4 h-100" style="background-color:#F3F0EA;">
            <div class="row">
              <div class="col-md-auto d-none d-md-block">
                <figure><img src="@/assets/curso/tema5/4.svg" /></figure>
              </div>
              <div class="col-md">
                <p class="mb-0">
                  Cada sistema tiene componentes específicos que permiten la
                  generación, control y transmisión de energía para realizar
                  trabajo mecánico. Los sistemas hidráulicos y neumáticos están
                  compuestos por elementos clave que permiten la generación,
                  control y transmisión de energía para realizar el trabajo.
                  Cada componente desempeña un papel específico dentro del
                  sistema y su correcta selección e instalación son
                  fundamentales para el funcionamiento eficiente de la
                  automatización.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        class="titulo-sexto color-acento-contenido mt-5"
        data-aos="fade-down"
      >
        <h5>Tabla 3.</h5>
        <span>Componentes de los sistemas hidráulicos y neumáticos.</span>
      </div>
      <div class="tabla-a color-acento-botones" data-aos="fade-up">
        <table>
          <caption class="fw-normal">
            Fuente: OIT, 2024.
          </caption>
          <thead style="border:0 !important;">
            <tr class="text-center" style="background-color:#78B62E;">
              <th>Imagen</th>
              <th>Elemento</th>
              <th>Definición</th>
            </tr>
          </thead>
          <tbody class="text-center">
            <tr style="background-color:#fff;">
              <td style="border:0;border-right:1px #AFAFAF solid;">
                <figure>
                  <img
                    class="d-inline"
                    src="@/assets/curso/tema5/5.svg"
                    style="max-width:170px;"
                  />
                </figure>
              </td>
              <td style="border-right:1px #AFAFAF solid;">
                Bomba hidráulica y compresor neumático
              </td>
              <td style="border:0;">
                En hidráulica, la bomba transforma la energía mecánica en
                presión del fluido. En neumática, el compresor genera el aire
                comprimido necesario para el funcionamiento del sistema.
              </td>
            </tr>
            <tr style="background-color:#F6F6F6;">
              <td style="border:0;border-right:1px #AFAFAF solid;">
                <figure>
                  <img
                    class="d-inline"
                    src="@/assets/curso/tema5/6.svg"
                    style="max-width:170px;"
                  />
                </figure>
              </td>
              <td style="border-right:1px #AFAFAF solid;">
                Válvulas de control
              </td>
              <td style="border:0;">
                Las válvulas permiten controlar el flujo y la dirección del
                fluido en ambos sistemas, regulando la velocidad y la presión en
                los actuadores. Entre ellas se encuentran las válvulas de
                control de presión, de caudal y direccionales.
              </td>
            </tr>
            <tr style="background-color:#fff;">
              <td style="border:0;border-right:1px #AFAFAF solid;">
                <figure>
                  <img
                    class="d-inline"
                    src="@/assets/curso/tema5/13.png"
                    style="max-width:170px;"
                  />
                </figure>
              </td>
              <td style="border-right:1px #AFAFAF solid;">
                Actuadores (cilindros y motores)
              </td>
              <td style="border:0;">
                Estos dispositivos convierten la energía del fluido en
                movimiento lineal (cilindros) o rotativo (motores). Los
                actuadores son el componente que realiza el trabajo físico en el
                sistema.
              </td>
            </tr>
            <tr style="background-color:#F6F6F6;">
              <td style="border:0;border-right:1px #AFAFAF solid;">
                <figure>
                  <img
                    class="d-inline"
                    src="@/assets/curso/tema5/14.jpg"
                    style="max-width:170px;"
                  />
                </figure>
              </td>
              <td style="border-right:1px #AFAFAF solid;">
                Filtros y secadores
              </td>
              <td style="border:0;">
                Los filtros en hidráulica y los secadores en neumática son
                esenciales para remover impurezas y humedad, protegiendo los
                componentes y asegurando una operación eficiente.
              </td>
            </tr>
            <tr style="background-color:#fff;">
              <td style="border:0;border-right:1px #AFAFAF solid;">
                <figure>
                  <img
                    class="d-inline"
                    src="@/assets/curso/tema5/15.jpg"
                    style="max-width:170px;"
                  />
                </figure>
              </td>
              <td style="border-right:1px #AFAFAF solid;">
                Acumuladores y reservorios
              </td>
              <td style="border:0;">
                En hidráulica, los acumuladores almacenan energía bajo presión
                para su uso posterior, mientras que los reservorios contienen el
                fluido que será recirculado en el sistema.
              </td>
            </tr>
          </tbody>
        </table>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_5_3">5.3 Aplicaciones en la automatización industrial</h2>
      </div>
      <p data-aos="fade-left">
        Los sistemas hidráulicos y neumáticos tienen aplicaciones específicas en
        la automatización industrial que varían según las necesidades de fuerza,
        precisión y velocidad de los procesos. Estos sistemas pueden encontrarse
        en líneas de ensamblaje, máquinas de inyección de plástico, sistemas de
        elevación y en mecanismos de seguridad.
      </p>
      <div class="cont_1_4 mt-5 pt-4 pb-4 pb-xl-5 pt-xl-5">
        <div class="tarjeta bg-white p-4 p-lg-5 pb-lg-4">
          <CarouselRED tipo="b">
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0" style="place-self:center;">
                <h5>Aplicaciones de la hidráulica</h5>
                <p class="mt-4">
                  La hidráulica es ideal en aplicaciones que requieren gran
                  fuerza y precisión, como prensas hidráulicas, maquinaria de
                  construcción (grúas, excavadoras) y sistemas de elevación. Su
                  capacidad para manejar cargas pesadas hace que estos sistemas
                  sean indispensables en industrias como la automotriz,
                  metalúrgica y construcción.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema5/7.png" />
                </figure>
              </div>
            </div>
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0" style="place-self:center;">
                <h5>Aplicaciones de la neumática</h5>
                <p class="mt-4">
                  La neumática es adecuada para aplicaciones que requieren
                  movimientos rápidos y repetitivos, como en líneas de
                  ensamblaje, herramientas neumáticas y sistemas de embalaje. Es
                  común en industrias que necesitan realizar operaciones
                  ligeras, pero repetitivas, como la manufactura de alimentos,
                  farmacéutica y empaques.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema5/8.png" />
                </figure>
              </div>
            </div>
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0" style="place-self:center;">
                <h5>Sistemas combinados</h5>
                <p class="mt-4">
                  En algunas aplicaciones industriales, los sistemas hidráulicos
                  y neumáticos se combinan para aprovechar las ventajas de
                  ambos. Por ejemplo, en maquinaria agrícola, un sistema
                  hidráulico puede manejar la carga, mientras que un sistema
                  neumático controla la dosificación de semillas o
                  fertilizantes, optimizando el proceso.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema5/9.png" />
                </figure>
              </div>
            </div>
          </CarouselRED>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_5_4">5.4 Control de sistemas hidráulicos y neumáticos</h2>
      </div>
      <p data-aos="fade-left">
        El control de los sistemas hidráulicos y neumáticos es esencial para la
        automatización y sincronización de sus funciones en procesos
        industriales. Las técnicas de control pueden variar desde sistemas de
        encendido y apagado simples hasta configuraciones avanzadas que utilizan
        controladores programables.
      </p>
      <div class="row mt-4">
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/tema5/10.png" /></figure>
        </div>
        <div class="col-lg" data-aos="fade-left">
          <div
            class="h-100 p-3 p-lg-4 d-flex align-content-center flex-wrap"
            style="background-color:#78B62E;border-radius:10px;"
          >
            <ul class="lista-ul mb-0">
              <li class="d-flex bg-white p-2" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong>Control todo-nada (On/Off):</strong> es el método de
                  control más básico, en el que las válvulas abren o cierran el
                  paso del fluido según una señal de entrada. Es adecuado para
                  aplicaciones simples que no requieren ajustes continuos de la
                  presión o caudal.</span
                >
              </li>
              <li class="d-flex bg-white p-2 mb-0" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong>Control proporcional:</strong> las válvulas
                  proporcionales permiten un ajuste gradual de la presión y
                  caudal, haciendo que los actuadores respondan suavemente y de
                  forma precisa. Este control es importante en aplicaciones que
                  requieren precisión, como el posicionamiento de cilindros en
                  maquinaria.</span
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="row mt-4">
        <div class="col-lg" data-aos="fade-right">
          <div
            class="h-100 p-3 p-lg-4 d-flex align-content-center flex-wrap"
            style="background-color:#01B9D1;border-radius:10px;"
          >
            <ul class="lista-ul mb-0">
              <li class="d-flex bg-white p-2" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong>Control mediante PLCs:</strong> los controladores
                  lógicos programables (PLCs) se utilizan para gestionar de
                  forma automática el funcionamiento de válvulas y actuadores en
                  sistemas hidráulicos y neumáticos. Los PLCs permiten integrar
                  sensores de presión y caudal, y ajustar las condiciones de
                  operación en tiempo real según las necesidades del
                  proceso.</span
                >
              </li>
              <li class="d-flex bg-white p-2 mb-0" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong
                    >Protocolos de comunicación en redes industriales:</strong
                  >
                  para aplicaciones que requieren monitoreo y control remoto,
                  los protocolos de comunicación como Modbus y Profibus permiten
                  integrar los sistemas hidráulicos y neumáticos en redes
                  industriales, facilitando la supervisión centralizada y la
                  eficiencia en el control de procesos.</span
                >
              </li>
            </ul>
          </div>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema5/11.png" /></figure>
        </div>
      </div>
      <div
        class="titulo-sexto color-acento-contenido mt-5"
        data-aos="fade-down"
      >
        <h5>Figura 2.</h5>
        <span>La hidráulica y neumática en la automatización industrial.</span>
      </div>
      <div class="p-3 p-lg-4 pt-xl-5 pb-xl-5" style="background-color:#EAEFF4;">
        <figure data-aos="fade-up">
          <img
            src="@/assets/curso/tema5/12.svg"
            alt="En el diagrama «La hidráulica y neumática en la automatización industrial», el mapa conceptual ilustra seis áreas principales: fundamentos de hidráulica con líquidos, uso de gases en neumática, aplicaciones industriales (incluyendo sistemas de elevación y herramientas), principios fundamentales, exploración de aplicaciones comunes y actividades prácticas para estudiantes. Cada rama incluye subtemas específicos que detallan aspectos y usos de estos sistemas."
          />
        </figure>
      </div>
      <figcaption class="mt-2 fw-normal">Fuente: OIT, 2024.</figcaption>
      <p class="mt-4" data-aos="fade-right">
        La comprensión de los sistemas hidráulicos y neumáticos es fundamental
        para la automatización industrial, ya que permiten realizar movimientos
        y trabajos mecánicos de manera precisa y controlada. Se recomienda para
        profundizar consultar el siguiente material:
      </p>
      <div class="row mt-4 justify-content-center">
        <div class="col-lg mb-4 mb-lg-0 col-md-6" data-aos="fade-up">
          <a
            class="anexo ms-0"
            href="https://www.youtube.com/watch?v=jR4oJUIh3jw"
            target="_blank"
          >
            <div class="anexo__icono">
              <img src="@/assets/bullets/icono-video.svg" />
            </div>
            <div class="anexo__texto">
              <p class="fw-normal">
                <strong>Enlace video.</strong> “Principles of Hydraulic and
                Pneumatic Systems”.
              </p>
            </div></a
          >
        </div>
        <div class="col-lg col-md-6" data-aos="fade-up">
          <a
            class="anexo ms-0"
            href="https://www.festo.com/manuales/hidraulica_neumatica.pdf"
            target="_blank"
          >
            <div class="anexo__icono">
              <img src="@/assets/bullets/icono-link.svg" />
            </div>
            <div class="anexo__texto">
              <p class="fw-normal">
                <strong>Enlace web.</strong> Manual Básico de Hidráulica y
                Neumática.
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
  name: 'Tema5',
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
