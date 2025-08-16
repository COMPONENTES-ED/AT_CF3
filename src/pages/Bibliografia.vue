<template>
  <div class="curso-main-container referencias">
    <BannerInterno
      icono="fas fa-book"
      titulo="Referencias bibliográficas"
    ></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div v-for="ref in orderedData" :key="ref.link" class="referencias__item">
        <span v-html="ref.referencia"></span
        ><a v-if="ref.link" class="ms-1" :href="ref.link" target="_blank"
          ><span v-html="ref.link"></span
          ><i class="ms-1 fas fa-external-link-alt"></i
        ></a>
        <hr class="my-3" />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Referencias',
  data: () => ({
    referencias: [
      {
        referencia:
          'AUTOMATIZACION INDUSTRIAL [@automatizacionindustrial]. (n.d.). ¿Qué es la AUTOMATIZACIÓN INDUSTRIAL? | Curso de Automatizacion Industrial #1. [Video]. Youtube. Recuperado el 11 de junio de 2025, de',
        link: 'https://www.youtube.com/watch?v=2upZSEaqj7k&t=43s',
      },
      {
        referencia:
          'CADe SIMU. (2021). Simulador de Circuitos de Automatización Eléctrica. [Simulador].',
        link: 'https://cadesimu.software.informer.com/download',
      },
      {
        referencia:
          'de Castro Lozano Cristóbal Romero Morales, A. I. H. M. P. C. (n.d.). Introducción a SCADA. [Documento PDF]. Uco.es. Recuperado el 11 de junio de 2025, de',
        link:
          'http://www.uco.es/grupos/eatco/automatica/ihm/descargar/scada.pdf',
      },
      {
        referencia:
          'De Ingeniería, M. [MentalidadDeIngenier%C3%ADa]. (s/f). Conceptos Básicos del Controlador de Lógica Programable. [Video]. Youtube. Recuperado el 11 de junio de 2025, de',
        link: 'https://www.youtube.com/watch?v=NPsepHRSCls',
      },
      {
        referencia:
          'Edu.co. (n.d.). [Documento PDF]. Recuperado el 11 de junio de 2025, de',
        link:
          'https://fiet.unicauca.edu.co/deic/sites/default/files/deic/programa/PLC.pdf',
      },
      {
        referencia:
          'Esri. (2021). ArcGIS Geographic Information System. Environmental Systems Research Institute.',
        link: 'https://www.arcgis.com',
      },
      {
        referencia:
          'Famic Technologies. (2021). Automation Studio – Pneumatic and Hydraulic Circuit Simulation. [Simulador].',
        link: 'https://www.automationstudio.com',
      },
      {
        referencia:
          'Factory I/O. (2021). Industrial Automation Simulation. [Simulador]. Real Games.',
        link: 'https://factoryio.com/',
      },
      {
        referencia:
          'Fazt [@FaztTech]. (s/f). ¿Qué es ERP? - Conoce porque un ERP vital para empresas. [Video] Youtube. Recuperado el 11 de junio de 2025, de',
        link: 'https://www.youtube.com/watch?v=6Mncbrp80To&t=92s',
      },
      {
        referencia:
          'Festo.com. (n.d.). [Documento PDF]. Recuperado el 12 de junio de 2025, de',
        link: 'https://media.festo.com/media/2923_documentation.pdf',
      },
      {
        referencia:
          'Festo.com. (n.d.). [Documento PDF]. Recuperado el 12 de junio de 2025, de',
        link: 'https://media.festo.com/media/241396_documentation.pdf',
      },
      {
        referencia:
          'Google Earth Engine. (s/f). Google.com. Recuperado el 11 de junio de 2025, de',
        link: 'https://earthengine.google.com/',
      },
      {
        referencia:
          'Guest. (2022, mayo 3). Lógica cableada y programada. [Documento PDF]. Pdfcoffee.com.',
        link:
          'https://pdfcoffee.com/logica-cableada-y-programada-2-pdf-free.html',
      },
      {
        referencia:
          'Inductive Automation. (2021). Ignition – SCADA/HMI Software.',
        link: 'https://inductiveautomation.com/',
      },
      {
        referencia:
          'MathWorks. (2021). MATLAB – Instrumentation Simulation. [Simulador].',
        link: 'https://www.mathworks.com/products/matlab.html',
      },
      {
        referencia:
          'Mecatrónica, B. [@Biwy-mecatronica]. (n.d.). 01 Sistemas Neumáticos e Hidráulicos (Introducción), y Válvulas. [Video]. Youtube. Recuperado el 11 de junio de 2025, de',
        link: 'https://www.youtube.com/watch?v=2m6o49C98Mc',
      },
      {
        referencia:
          'RealPars. (2019, June 17). PID Control Explained [Video]. YouTube.',
        link: 'https://www.youtube.com/watch?v=wkfEZmsQqiA',
      },
      {
        referencia:
          'Spatial without Compromise. (n.d.). Qgis.org. Recuperado el 11 de junio de 2025, de',
        link: 'https://qgis.org/',
      },
      {
        referencia:
          'Unirioja.es. (n.d.). [Documento PDF]. Recuperado el 11 de junio de 2025, de',
        link: 'https://dialnet.unirioja.es/descarga/articulo/5280242.pdf',
      },
    ],
  }),
  computed: {
    orderedData() {
      return [...this.referencias].sort((a, b) => {
        const afl = this.quitarAcentos(a.referencia.split(' ')[0].toLowerCase())
        const bfl = this.quitarAcentos(b.referencia.split(' ')[0].toLowerCase())
        if (afl < bfl) return -1
        if (afl > bfl) return 1
        return 0
      })
    },
  },
  methods: {
    quitarAcentos(str) {
      return str.normalize('NFD').replace(/[\u0300-\u036f]/g, '')
    },
  },
}
</script>

<style lang="sass">
.referencias
  &__item
    &:last-child
      hr
        display: none
    a
      color: $blue
      text-decoration: underline
      overflow-wrap: break-word
</style>
