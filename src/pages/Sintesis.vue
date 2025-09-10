<template>
  <div class="curso-main-container pb-3">
    <BannerInterno icono="fas fa-sitemap" titulo="Síntesis"></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5">
      <div class="row mb-5">
        <div class="col-xl-auto d-none d-xl-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/sintesis1.png" /></figure>
        </div>
        <div class="col-xl" data-aos="fade-left">
          <div class="row">
            <div class="col-lg">
              <div
                class="h-100 p-4 d-flex align-content-center flex-wrap"
                style="background-color:#CBF0F5;"
              >
                <p class="mb-0">
                  El siguiente diagrama proporciona una visión general
                  sintetizada de los principales temas abordados en este
                  componente. Este mapa conceptual ha sido diseñado para
                  facilitar la comprensión de las tecnologías clave que soportan
                  la automatización y el control de sistemas industriales.
                </p>
              </div>
            </div>
            <div class="col-lg-auto d-none d-lg-block">
              <figure><img src="@/assets/curso/sintesis2.svg" /></figure>
            </div>
          </div>
          <p class="mt-4">
            En el centro del diagrama se encuentra el concepto principal de
            Tecnologías de Automatización y Control, que se desglosa en temas
            fundamentales como sistemas de información, gestión de la
            variabilidad espacial y temporal, automatismos eléctricos,
            instrumentación y control, y sistemas hidráulicos y neumáticos. Cada
            uno de estos temas se descompone en subtemas que reflejan tanto los
            fundamentos teóricos como sus aplicaciones prácticas en entornos
            industriales.
          </p>
          <div
            class="p-4"
            style="background-color:#E3F0D4;border:2px #3BA935 dashed;border-radius:7px;"
          >
            <div class="row">
              <div
                class="col-md-auto d-none d-md-block"
                style="place-self:center;"
              >
                <figure><img src="@/assets/curso/sintesis3.svg" /></figure>
              </div>
              <div class="col-md" style="place-self:center;">
                <p class="mb-0">
                  Estos conceptos se entrelazan para ofrecer una perspectiva
                  integral de cómo las tecnologías permiten optimizar procesos,
                  mejorar la seguridad y la eficiencia, y preparar a los
                  estudiantes para resolver desafíos industriales mediante la
                  implementación de sistemas automatizados.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div>
        <p class="mb-5">
          El diagrama sirve como una guía visual para explorar los contenidos de
          este módulo, ayudando a los estudiantes a comprender rápidamente la
          interrelación de los temas y cómo estos se aplican en un entorno de
          producción moderna. Se recomienda utilizar este mapa conceptual como
          complemento al contenido detallado del componente, permitiendo una
          navegación más estructurada y efectiva de los conceptos presentados.
        </p>
      </div>

      <div
        class="row justify-content-center p-4"
        style="background-color:#F6F6F6;border-radius:20px;"
      >
        <div class="col-lg-10 mb-5 bgs p-4 brad">
          <figure data-aos="fade-up" data-aos-duration="750">
            <img
              class="mb-4"
              src="@/assets/curso/sintesis.svg"
              alt='En la síntesis se presenta una visión general de las "Tecnologías de automatización y control de sistemas industriales". Se estructura en seis áreas principales: automatización y control industrial, sistemas de información y gestión, gestión de variabilidad espacial y temporal, automatismos eléctricos e instrumentación, hidráulica y neumática, y la importancia de estos conocimientos. Cada rama incluye subtemas específicos que detallan los aspectos técnicos y aplicaciones en la industria moderna.'
            />
            <figcaption>Fuente. OIT, 2024.</figcaption>
          </figure>
        </div>
        <div class="col-auto">
          <a
            class="anexo mb-5"
            :href="obtenerLink('/downloads/Sintesis.pdf')"
            target="_blank"
          >
            <div class="anexo__icono">
              <img src="@/assets/bullets/icono-pdf.svg" />
            </div>
            <div class="anexo__texto">
              <p>Anexo. Síntesis</p>
            </div></a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Sintesis',
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
