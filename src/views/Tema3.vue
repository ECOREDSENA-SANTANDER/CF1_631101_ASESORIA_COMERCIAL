<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Segmentación del mercado
    
    separador
    #t_3_1.titulo-segundo.mb-4
      h2 3.1 Bases para segmentar mercados de consumo masivo
      
    separador
    #t_3_2.titulo-segundo.mb-4
      h2 3.2 Requisitos para segmentar
    
    separador
    #t_3_3.titulo-segundo.mb-4
      h2 3.3 Estrategias de cobertura de un mercado meta
    
    separador
    #t_3_4.titulo-segundo.mb-4
      h2 3.4 Pasos para segmentar un mercado
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
