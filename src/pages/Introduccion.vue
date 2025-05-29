<template>
  <div class="curso-main-container introduccion">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido" data-aos="flip-up">
        <div class="titulo-principal__numero">
          <span><i class="fas fa-info"></i></span>
        </div>
        <h1>Introducción</h1>
      </div>
      <div class="cont_intro">
        <div class="row">
          <div class="col-xl-auto d-none d-xl-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/intro1.svg" /></figure>
          </div>
          <div class="col-xl" data-aos="fade-left">
            <div
              class="p-4"
              style="background-color:#E3F0D4;border:2px #3BA935 dashed;border-radius:7px;"
            >
              <p class="mb-0">
                La automatización y el control industrial representan la base de
                los sistemas modernos de producción, permitiendo que los
                procesos operen de manera eficiente, segura y precisa. En el
                contexto de una industria cada vez más digitalizada, los
                conocimientos sobre sistemas de información, gestión de datos
                espaciales y temporales, automatismos eléctricos,
                instrumentación y control, así como sistemas hidráulicos y
                neumáticos, se han convertido en competencias esenciales para
                cualquier profesional técnico. Este componente proporciona una
                visión integral y práctica de estos temas fundamentales en la
                automatización, capacitando a los estudiantes para enfrentar los
                desafíos tecnológicos de la industria moderna.
              </p>
            </div>
            <p class="mt-4 mb-0">
              Comenzando con una introducción a los sistemas de información,
              exploraremos cómo se estructuran y aplican en el ámbito industrial
              para optimizar la recopilación, análisis y toma de decisiones
              basada en datos. Luego, la gestión de la variabilidad espacial y
              temporal permite entender cómo los datos de ubicación y tiempo
              influyen en la producción, facilitando aplicaciones como la
              agricultura de precisión y la logística avanzada.
            </p>
          </div>
        </div>
        <div
          class="p-4 mt-4"
          style="background-color:#CBF0F5;"
          data-aos="fade-up"
        >
          <div class="row">
            <div
              class="col-md-auto d-none d-md-block"
              style="place-self:center;"
            >
              <figure><img src="@/assets/curso/intro2.svg" /></figure>
            </div>
            <div class="col-md" style="place-self:center;">
              <p class="mb-0">
                En los módulos de automatismos eléctricos e instrumentación y
                control, los estudiantes aprenderán los principios de los
                circuitos automatizados, la lógica de control programable (PLC)
                y el uso de sensores para monitorear y regular variables
                críticas. Estos conocimientos son esenciales para diseñar,
                implementar y mantener sistemas de control efectivos en entornos
                industriales. Finalmente, el estudio de hidráulica y neumática
                completará el panorama, proporcionando una comprensión sobre el
                uso de fluidos y gases para transmitir potencia y ejecutar
                movimientos precisos y de gran fuerza.
              </p>
            </div>
          </div>
        </div>
        <figure class="mt-4" data-aos="zoom-in-up" data-aos-duration="500">
          <div class="video">
            <iframe
              width="560"
              height="315"
              src="https://www.youtube.com/embed/2g2YJRwAYLM?si=wSocEgWwSxR3dT_n"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen="allowfullscreen"
            ></iframe>
          </div>
        </figure>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
