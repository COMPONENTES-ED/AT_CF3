<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido" data-aos="flip-up">
        <div class="titulo-principal__numero"><span>3</span></div>
        <h1>Automatismos eléctricos</h1>
      </div>
      <div class="row">
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/tema3/1.png" /></figure>
        </div>
        <div class="col-lg" data-aos="fade-left">
          <div class="p-4 h-100" style="background-color:#F3F0EA;">
            <div class="row">
              <div class="col-md-auto d-none d-md-block">
                <figure><img src="@/assets/curso/tema3/2.svg" /></figure>
              </div>
              <div class="col-md">
                <p class="mb-0">
                  Los automatismos eléctricos son sistemas diseñados para operar
                  y controlar dispositivos de manera automática, sin necesidad
                  de intervención humana directa. Estos sistemas son esenciales
                  en la automatización industrial, permitiendo que los procesos
                  sean más eficientes, seguros y precisos. Utilizan componentes
                  eléctricos, como relés, contactores y controladores lógicos
                  programables (PLCs), que permiten gestionar y supervisar
                  maquinaria y procesos. A continuación, se explorarán los
                  fundamentos de los automatismos eléctricos, sus componentes
                  clave y las aplicaciones prácticas en el entorno industrial.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="cont_3_1">
        <Separador></Separador>
        <div class="titulo-segundo" data-aos="flip-up">
          <h2 id="t_3_1">3.1 Fundamentos de automatismos eléctricos</h2>
        </div>
        <div class="row">
          <div class="col-lg" data-aos="fade-right">
            <p>
              La automatización eléctrica permite a los dispositivos y sistemas
              operar automáticamente mediante la creación de secuencias lógicas
              y la integración de controladores. Para implementar sistemas de
              automatismos eléctricos, es fundamental comprender la diferencia
              entre <strong>lógica cableada y lógica programable</strong>.
            </p>
            <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
              <div class="row">
                <div class="col-auto pe-0">
                  <figure><img src="@/assets/curso/tema1/9.svg" /></figure>
                </div>
                <div class="col ps-2" style="place-self:center;">
                  <h3 class="mb-0 pe-4">Lógica cableada</h3>
                </div>
              </div>
            </div>
            <p>
              La lógica cableada es el método tradicional, basado en el uso de
              dispositivos físicos, como relés y contactores, que están
              cableados para crear secuencias de control. Este tipo de lógica es
              común en sistemas sencillos, pero es menos flexible, ya que los
              cambios en el proceso requieren ajustes en el cableado físico.
            </p>
            <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
              <div class="row">
                <div class="col-auto pe-0">
                  <figure><img src="@/assets/curso/tema1/9.svg" /></figure>
                </div>
                <div class="col ps-2" style="place-self:center;">
                  <h3 class="mb-0 pe-4">Lógica cableada</h3>
                </div>
              </div>
            </div>
            <div
              class="p-4"
              style="background-color:#E3F0D4;border-radius:7px;border:2px #3BA935 dashed;"
            >
              <p class="mb-0">
                Los controladores lógicos programables (PLCs) permiten
                implementar secuencias de control complejas mediante
                programación, en lugar de cableado físico. Esto facilita la
                modificación y ampliación de los sistemas y ofrece una mayor
                flexibilidad. Los PLCs permiten integrar sensores y actuadores
                en una misma red de control, haciéndolos esenciales para
                aplicaciones industriales complejas.
              </p>
            </div>
          </div>
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
            <figure><img src="@/assets/curso/tema3/3.png" /></figure>
          </div>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_3_2">3.2 Componentes clave en los automatismos eléctricos</h2>
      </div>
      <p data-aos="fade-left">
        Los sistemas de automatización eléctrica están compuestos por diversos
        elementos que permiten el control automático de procesos. A
        continuación, se describen algunos de los componentes clave:
      </p>
      <div class="cont_3_2 mt-4">
        <div class="row">
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/tema3/5.png" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-left">
            <AccordionRED tipo="a" clase-tarjeta="tarjeta">
              <div
                class="row col-xl-11 m-auto"
                titulo="3.2.1. Relés y contactores"
              >
                <p>
                  Los relés y contactores son dispositivos electromecánicos que
                  actúan como interruptores. Los relés se utilizan en
                  aplicaciones de bajo voltaje, mientras que los contactores
                  pueden manejar corrientes más altas. Su función es abrir o
                  cerrar circuitos eléctricos en función de una señal de
                  control.
                </p>
              </div>
              <div
                class="row col-xl-11 m-auto"
                titulo="3.2.2. Interruptores de posición y sensores"
              >
                <p>
                  Los sensores y los interruptores de posición detectan cambios
                  en el sistema, como la presencia o posición de un objeto.
                  Existen diferentes tipos de sensores, incluyendo sensores de
                  proximidad, sensores de presión, y encoders, cada uno con
                  aplicaciones específicas.
                </p>
              </div>
              <div
                class="row col-xl-11 m-auto"
                titulo="3.2.3. PLCs (Controladores Lógicos Programables)"
              >
                <p>
                  Los PLCs son el núcleo de muchos sistemas de automatización
                  moderna. Estos dispositivos permiten programar y controlar
                  secuencias de operaciones, facilitando el control de procesos
                  industriales. Un PLC se conecta a sensores y actuadores y
                  ejecuta un programa que controla las salidas en función de las
                  entradas recibidas.
                </p>
              </div>
              <div
                class="row col-xl-11 m-auto"
                titulo="3.2.4. Elementos finales de control"
              >
                <p>
                  Los actuadores y motores reciben las señales de control de los
                  PLCs y ejecutan acciones físicas en el proceso, como mover un
                  brazo robótico, abrir una válvula o arrancar un motor.
                </p>
              </div>
            </AccordionRED>
          </div>
        </div>
        <Separador></Separador>
        <div class="titulo-segundo" data-aos="flip-up">
          <h2 id="t_3_3">
            3.3 Aplicaciones prácticas en automatismos eléctricos
          </h2>
        </div>
      </div>
      <p data-aos="fade-left">
        Los automatismos eléctricos tienen aplicaciones en diversas áreas de la
        industria, desde el control de sistemas de iluminación hasta el
        funcionamiento automatizado de líneas de producción. Algunas
        aplicaciones comunes incluyen:
      </p>
      <div class="cont_1_4 mt-5 pt-4 pb-4 pb-xl-5 pt-xl-5">
        <div class="tarjeta bg-white p-4 p-lg-5 pb-lg-4">
          <CarouselRED tipo="b">
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0" style="place-self:center;">
                <h5>Control de motores</h5>
                <p class="mt-4">
                  Los motores eléctricos son fundamentales en aplicaciones
                  industriales. Los automatismos eléctricos permiten controlar
                  el arranque, paro e inversión de giro de motores de manera
                  automática y segura, utilizando contactores y relés de
                  protección. En sistemas más avanzados, los PLCs gestionan
                  secuencias de control de varios motores.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema3/6.png" />
                </figure>
              </div>
            </div>
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0" style="place-self:center;">
                <h5>Sistemas de transporte y manipulación</h5>
                <p class="mt-4">
                  En líneas de producción, los sistemas de transporte y
                  manipulación requieren automatización para coordinar el
                  movimiento de materiales. Los sensores y PLCs controlan la
                  velocidad y dirección de transportadores, asegurando que los
                  materiales se muevan de forma sincronizada en la línea.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema3/7.png" />
                </figure>
              </div>
            </div>
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0" style="place-self:center;">
                <h5>Control de temperatura y climatización</h5>
                <p class="mt-4">
                  En entornos donde se requiere mantener condiciones de
                  temperatura específicas, los automatismos eléctricos permiten
                  integrar sensores de temperatura y sistemas de control, que
                  ajustan automáticamente los sistemas de calefacción y
                  enfriamiento para mantener el ambiente dentro de los límites
                  requeridos.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema3/8.png" />
                </figure>
              </div>
            </div>
          </CarouselRED>
        </div>
      </div>
      <p class="mt-4" data-aos="fade-right">
        Se recomiendan los siguientes recursos de acceso libre para
        complementar:
      </p>
      <div class="row mt-4 justify-content-center">
        <div class="col-lg mb-4 mb-lg-0 col-md-8" data-aos="fade-up">
          <a
            class="anexo ms-0 h-100"
            href="https://www.youtube.com/watch?v=NPsepHRSCls"
            target="_blank"
            style="max-width:fit-content;"
          >
            <div class="anexo__icono">
              <img src="@/assets/bullets/icono-video.svg" />
            </div>
            <div class="anexo__texto">
              <p class="fw-normal">
                <strong>Enlace video.</strong> Video- Básicos del Controlador de
                Lógica Programable.
              </p>
            </div></a
          >
        </div>
        <div class="col-lg mb-4 mb-lg-0 col-md-8" data-aos="fade-up">
          <a
            class="anexo ms-0 h-100"
            href="https://pdfcoffee.com/logica-cableada-y-programada-2-pdf-free.html"
            target="_blank"
            style="max-width:fit-content;"
          >
            <div class="anexo__icono">
              <img src="@/assets/bullets/icono-link.svg" />
            </div>
            <div class="anexo__texto">
              <p class="fw-normal">
                <strong>Enlace web.</strong> Lógica Cableada y lógica
                programada.
              </p>
            </div></a
          >
        </div>
        <div class="col-lg mb-4 mb-lg-0 col-md-8" data-aos="fade-up">
          <a
            class="anexo ms-0 h-100"
            href="https://fiet.unicauca.edu.co/deic/sites/default/files/deic/programa/PLC.pdf"
            target="_blank"
            style="max-width:fit-content;"
          >
            <div class="anexo__icono">
              <img src="@/assets/bullets/icono-link.svg" />
            </div>
            <div class="anexo__texto">
              <p class="fw-normal">
                <strong>Enlace web.</strong> Fundamentos de Programación de PLCs
                - Ladder Logic
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
  name: 'Tema3',
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
