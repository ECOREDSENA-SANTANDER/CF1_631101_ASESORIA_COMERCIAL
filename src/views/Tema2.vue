<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Mercado
    
    separador
    #t_2_1.titulo-segundo.mb-4
      h2 2.1 Tipos de mercados
      
    separador
    #t_2_2.titulo-segundo.mb-4
      h2 2.2 Clases de mercado
    
    separador
    #t_2_3.titulo-segundo.mb-4
      h2 2.3 Otros tipos de mercados
    
    separador
    #t_2_4.titulo-segundo.mb-4
      h2 2.4 Características del mercado
    
    separador
    #t_2_5.titulo-segundo.mb-4
      h2 2.5 Estrategias del mercado
    
    separador
    #t_2_6.titulo-segundo.mb-4
      h2 2.6 Participación del mercado
    
    separador
    #t_2_7.titulo-segundo.mb-4
      h2 2.7 Pasos para definir el mercado
</template>

<script>
export default {
  name: 'Tema2',
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
