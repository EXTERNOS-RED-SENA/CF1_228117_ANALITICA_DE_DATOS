<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      .row.justify-content-center.mb-4
        .col-lg-4.col-8.mb-lg-0.mb-4.my-lg-0.my-3.j1
          img.img-fluid.img-a(src='@/assets/template/images/cf1/122.png')
        .col-lg-8.my-lg-0.my-3
          .row.justify-content-center.align-items-center
            .col-lg-7.my-lg-0.my-3
              .bg30.text-white.p-3.brad.j1.h-100
                p
                  | El siguiente diagrama proporciona una visión general sintetizada de los principales temas abordados en este componente sobre la recolección de datos para análisis. Este mapa está diseñado para ayudar al lector a visualizar la interrelación entre las diversas áreas que constituyen el proceso de recolección de datos en el contexto estadístico a partir de los diversos tipos de fuentes y de las técnicas que se pueden usar para la recolección y el análisis de los datos.
            .col-lg-5.my-lg-0.col-8.mb-lg-0.mb-4.my-3.j1
              img.img-fluid.img-a(src='@/assets/template/images/cf1/106.png')
          .row.justify-content-center.align-items-center.bg19.br-d.p-4.brad
            .col-lg-auto
              img.img-a.img-t(src='@/assets/template/images/cf1/121.png' alt='')
            .col.pt-lg-0.pt-md-4
              p.mb-0
                | En el origen del diagrama se encuentra el concepto principal de "Recolección de datos para análisis", del cual se derivan temas fundamentales: conceptos generales de estadística, población y muestra en estadística, procesos estadísticos, técnicas de muestreo, inferencia estadística, requerimientos para la recolección de datos, fuentes de datos y determinación de la muestra. Cada una de estas áreas se subdivide en conceptos clave, reflejando la estructura y el contenido del componente.
      p.mb-5
        | Este diagrama actúa como una guía visual para explorar los conceptos presentados en el texto, permitiendo al lector comprender rápidamente la amplitud y la organización de los temas tratados, así como sus conexiones. Al revisar este mapa, el aprendiz podrá observar cómo los diferentes aspectos de la estadística y la recolección de datos se entrelazan para formar un proceso integral y sistemático. Se invita a utilizar este diagrama como un complemento al contenido detallado del componente, sirviendo como una referencia rápida y un recordatorio visual de los conceptos esenciales en la recolección de datos para análisis estadístico.
  
  
      .row.justify-content-center
        .col-lg-10.mb-5.col-8.mb-lg-0.mb-4.bgs.brad.p-5
          figure
            img(src="@/assets/template/images/cf1/sintesis.svg", alt="«Síntesis temática del componente», allí se mencionan los principales temas tratados sobre la limpieza y transformación de datos —como sus fundamentos, importación, técnicas, herramientas y prácticas— y algunos subtemas que los integran.")
        .col-auto
          a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-pdf.svg")
            .anexo__texto
              p Anexo. Síntesis
  
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
