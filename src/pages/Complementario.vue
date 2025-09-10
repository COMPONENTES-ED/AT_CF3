<template>
  <div class="curso-main-container complementario">
    <BannerInterno
      icono="far fa-folder-open"
      titulo="Material complementario"
    ></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="table-responsive">
        <table>
          <thead>
            <tr>
              <th colspan="3" scope="col">Tema</th>
              <th colspan="5" scope="col">Referencia APA del material</th>
              <th colspan="2" scope="col">Tipo</th>
              <th colspan="2" scope="col">Enlace</th>
            </tr>
          </thead>
          <tbody>
            <tr
              v-for="(item, index) in computedData"
              :key="'complementario-' + index"
            >
              <td
                class="text-start"
                colspan="3"
                scope="row"
                v-html="item.tema"
              ></td>
              <td
                class="text-start"
                colspan="5"
                scope="row"
                v-html="item.referencia"
              ></td>
              <td colspan="2" v-html="item.tipo"></td>
              <td colspan="2">
                <div class="complementario__enlaces">
                  <a
                    v-for="(link, linkIndex) of item.link"
                    :key="linkIndex"
                    class="complementario__btn"
                    :href="link"
                    target="_blank"
                    ><i class="fas fa-external-link-alt"></i
                  ></a>
                </div>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'MaterialComplementario',
  computed: {
    complementarioData() {
      return [
        {
          tema: 'Introducción a los Sistemas de Información',
          referencia:
            'Fazt [@FaztTech]. (n.d.). <em>¿Qué es ERP? - Conoce porque un ERP vital para empresas.</em> [Video] Youtube.',
          tipo: 'Video',
          link: 'https://www.youtube.com/watch?v=kDPW2Lle2gQ',
        },
        {
          tema: 'Introducción a los Sistemas de Información',
          referencia:
            'de Castro Lozano Cristóbal Romero Morales, A. I. H. M. P. C. (n.d.). <em>Introducción a SCADA.</em> [Documento PDF]. Uco.es.',
          tipo: 'Documento',
          link:
            'http://www.uco.es/grupos/eatco/automatica/ihm/descargar/scada.pdf',
        },
        {
          tema: 'Gestión de la Variabilidad Espacial y Temporal',
          referencia: '<em>Spatial without Compromise.</em> (n.d.). Qgis.org.',
          tipo: 'Software (GIS)',
          link: 'https://qgis.org',
        },
        {
          tema: 'Gestión de la Variabilidad Espacial y Temporal',
          referencia: '<em>Google Earth Engine.</em> (n.d.). Google.com.',
          tipo: 'Plataforma en la nube',
          link: 'https://earthengine.google.com/',
        },
        {
          tema: 'Automatismos Eléctricos',
          referencia:
            'AUTOMATIZACION INDUSTRIAL [@automatizacionindustrial]. (n.d.). <em>¿Qué es la AUTOMATIZACIÓN INDUSTRIAL?| Curso de Automatizacion Industrial #1.</em>  [Video]. Youtube.',
          tipo: 'Video',
          link: 'https://www.youtube.com/watch?v=2upZSEaqj7k&t=43s',
        },
        {
          tema: 'Automatismos Eléctricos',
          referencia:
            'Guest. (2022, mayo 3). Logica cableada y programada. [Documento PDF]. Pdfcoffee.com.',
          tipo: 'Pagina Web Documento PDF',
          link:
            'https://pdfcoffee.com/logica-cableada-y-programada-2-pdf-free.html',
        },
        {
          tema: 'Automatismos Eléctricos',
          referencia: '<em>Cade Simu</em>  (s/f). [Simulador] Cade-simu.com. ',
          tipo: 'Simulador',
          link: 'https://cadesimu.software.informer.com/download',
        },
        {
          tema: 'Instrumentación y Control',
          referencia:
            'MATLAB [@MATLAB]. (s/f). <em>What is PID control? | understanding PID control, part 1.</em> [Video]. Youtube.',
          tipo: 'Video',
          link: 'https://www.youtube.com/watch?v=wkfEZmsQqiA',
        },
        {
          tema: 'Instrumentación y Control',
          referencia: 'Festo.com. (n.d.). [Documento PDF].',
          tipo: 'Documento PDF',
          link: 'https://media.festo.com/media/2923_documentation.pdf',
        },
        {
          tema: 'Instrumentación y Control',
          referencia:
            'MathWorks. (2021). MATLAB – Instrumentation Simulation. [Simulador]. https://www.mathworks.com/products/matlab.html',
          tipo: 'Simulador',
          link: 'https://www.mathworks.com/products/matlab.html',
        },
        {
          tema: 'Hidráulica y Neumática',
          referencia:
            'Mecatrónica, B. [@Biwy-mecatronica]. (s/f). 01 <em>Sistemas Neumáticos e Hidráulicos (Introducción), y Válvulas.</em> [Video].  Youtube. Recuperado el 11 de junio de 2025, de https://www.youtube.com/watch?v=2m6o49C98Mc',
          tipo: 'Video',
          link: 'https://www.youtube.com/watch?v=jR4oJUIh3jw',
        },
        {
          tema: 'Hidráulica y Neumática',
          referencia: 'Festo.com. (n.d.). [Documento PDF].',
          tipo: 'Documento PDF',
          link: 'https://media.festo.com/media/241396_documentation.pdf',
        },
        {
          tema: 'Hidráulica y Neumática',
          referencia: '<em>FluidSIM.</em> (s/f). [Simulador]. Festo.com. ',
          tipo: 'Simulador',
          link: 'https://www.automationstudio.com',
        },
        {
          tema: 'General (Aplicable a Varios Temas)',
          referencia:
            'Factory I/O. (2021). <em>Industrial Automation Simulation.</em> [Simulador]. Real Games.',
          tipo: 'Simulador',
          link: 'https://factoryio.com/',
        },
      ]
    },
    computedData() {
      const data = this.complementarioData
      return data.map(item => {
        let nuevoLink = []
        if (item.link) {
          if (typeof item.link === 'string') {
            nuevoLink.push(item.link)
          } else {
            nuevoLink = item.link
          }
        } else if (item.descarga) {
          if (typeof item.descarga === 'string') {
            nuevoLink.push(this.obtenerLink(item.descarga))
          } else {
            item.descarga.forEach(link => {
              nuevoLink.push(this.obtenerLink(link))
            })
          }
        }
        return {
          ...item,
          link: nuevoLink,
        }
      })
    },
  },
}
</script>

<style lang="sass">
.complementario
  &__enlaces
    display: flex
    justify-content: center
    flex-wrap: wrap
    a
      margin: 0 5px
  &__btn
    font-size: 1.5em
    line-height: 1em
table
  width: calc(100% - 1px)
  min-width: 800px
  thead
    background-color: $color-sistema-e
    th
      border-color: $color-sistema-e
  th, td
    padding: 25px 20px
    text-align: center
</style>
