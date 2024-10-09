<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Técnica de recolección de datos 
    
    separador
    #t_4_1.titulo-segundo.mb-4
      h2 4.1 Técnicas
      
    separador
    #t_4_2.titulo-segundo.mb-4
      h2 4.2 Instrumentos para la recolección de información

</template>

<script>
export default {
  name: 'Tema4',
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
