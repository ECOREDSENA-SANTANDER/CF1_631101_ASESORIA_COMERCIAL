<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 La identificación de nichos de mercado es una parte fundamental de una buena asesoría comercial, además de comprender al cliente, sus necesidades y deseos, en este componente se trabaja información referente a técnicas de recolección de información acerca de los diferentes tipos de mercados y cómo dicha información para beneficio de las empresas. En el siguiente cuadro se presenta un diagrama con los conceptos y temas tratados dentro de este.

    .row.justify-content-center
      .col-lg-12.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="En el diagrama se presenta la estructura de contenidos relacionados con la identificación de nichos de mercado, organizada en cuatro áreas principales: Mercadeo, Mercado, Segmentación de mercado y Técnicas de recolección de datos. Cada área desglosa subtemas específicos que abarcan desde estrategias y pasos para definir mercados hasta técnicas e instrumentos para la recolección de información, brindando un marco integral para el análisis y comprensión del mercado.")
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
