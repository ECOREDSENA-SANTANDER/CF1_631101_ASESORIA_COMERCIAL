<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Técnica de recolección de datos 
    
    .row.justify-content-center.align-items-center
      .col-lg-10
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/img64.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Cuando se realiza una investigación para obtener una información del mercado, se hace necesario conocer la manera cómo se obtiene dicha información, llamada recolección de datos. Luego de definido se procede a realizar el trabajo de campo que implica la selección, capacitación y supervisión de las personas que reúnen los datos. Se debe tener en cuenta que el trabajo de campo depende de la modalidad de la recolección de los datos: observación, entrevistas telefónicas, personales, por correo o electrónicas, encuestas.
    separador
    #t_4_1.titulo-segundo.mb-4
      h2 4.1 Técnicas
      
    .row.justify-content-center.align-items-center.mb-2
      .col-lg-8.col-md-12.col-12
        p.mb-5 Existen diferentes métodos y técnicas de recolección de datos que pueden ser de utilidad. La elección del método depende de la estrategia, el tipo de variable, la precisión deseada, el punto de recolección y las habilidades del encuestador. 
        .row.justify-content-center.align-items-center(data-aos="fade-left")
          .col-lg-12.mb-lg-0
            .bloque-texto-f.color-secundario.pt-4.px-5
              .bloque-texto-f__comillas
                i.fas.fa-quote-left
                i.fas.fa-quote-right
              .row.justify-content-center.align-items-center.mb-2
                .col-lg-11.mb-lg-0
                  h3.bloque-texto-f__texto(data-aos="fade-left") Las técnicas de recolección de datos son mecanismos e instrumentos que se utilizan para reunir y medir información de forma organizada y con un objetivo específico.
                  .bloque-texto-f__autor.mb-3
                    p.mb-0.text-right.pe-5 (Caro, 2019).
      .col-lg-4.col-md-7.col-7.mb-4
        img.img-a.img-t(src='@/assets/curso/temas/img65.svg', alt='tema1')

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4
        .titulo-sexto.color-secundario.mb-5
          h5 Figura 13. 
          | Técnicas de recolección de información
        img.mb-3(src='@/assets/curso/temas/img66.svg', alt='En la figura se presenta un diagrama que enuncia los diferentes métodos para recolectar datos: entrevistas personales, entrevistas telefónicas, cuestionarios, observación, encuestas online, focus group y paneles online.')
        figcaption Nota. Tomada de QuestionPro: https://www.questionpro.com/blog/es/recoleccion-de-datos-para-investigacion/

    .row.justify-content-center.align-items-center
      .col-lg-12
        .bg3.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2.d-none.d-lg-block.ps-lg-5
              img.img-a.img-t.mbt(src="@/assets/curso/temas/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-3.text-white #[b Técnica de recolección de datos]
                  p.mb-2.text-white En el siguiente documento se pueden revisar las técnicas de recolección de información a profundidad:
                .col-lg-auto.pe-lg-5
                  a.boton.color-acento-botones(href="https://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF" target="_blank")
                    span Ir al sitio
                    i.fas.fa-file-download

    separador
    #t_4_2.titulo-segundo.mb-4
      h2 4.2 Instrumentos para la recolección de información

    .row.justify-content-center.align-items-end.mb-3
      .col-lg-8.col-md-12.col-12.mb-4
        p.mb-4 En este nivel se tiene claro la clase de investigación o proyecto que se desea realizar; por tanto, es el momento de trazar un plan que lleve a obtener la información para cumplir con el proyecto y escoger el método a utilizar que resuelva el problema planteado. Se debe responder a la pregunta ¿Con qué…? Mientras que en la observación se utiliza un guion de observación, notas de campo, listas de chequeo, registros, entre otros, en la entrevista se utiliza el cuestionario o instrumento de preguntas; para la encuesta se utiliza el cuestionario o instrumento o escalas de actitud. 
        .cajon.color-acento-contenido.p-4
          p.mb-4.my-4 Se determinan los métodos y se escoge el más conveniente a utilizar. Kendall y Kendall (2011, p. 115) aportan dos métodos para la recolección de datos: el interactivo y el intrusivo.
      .col-lg-4.col-md-7.col-7.mb-4
        img.img-a.img-t(src='@/assets/curso/temas/img67.png', alt='tema1')

    .row.justify-content-center
      .col-lg-6.col-md-6.mb-4
        .overflow-hidden.h-100.bg4.p-4
          img.img-a.img-t.mb-4(src='@/assets/curso/temas/img68.svg', alt='tema2')
          .row.justify-content-center.mb-3
            .col-12.mb-4
              .bg5.p-1 
                h3.text-center.mb-0 Método interactivo
          p.mb-4.text-center Consiste en tener contacto con alguien, este método se propone utilizar herramientas básicas como: entrevista, cuestionarios y talleres de trabajo de JAD (diseño conjunto de aplicaciones), este último demanda cierta especialización. 
      .col-lg-6.col-md-6.mb-4
        .overflow-hidden.h-100.bg4.p-4
          img.img-a.img-t.mb-4(src='@/assets/curso/temas/img69.svg', alt='tema2')
          .row.justify-content-center.mb-3
            .col-12.mb-4
              .bg5.p-1 
                h3.text-center.mb-0 Método intrusivo
          p.mb-4.text-center Permiten a los analistas realizar una descripción más clara y completa de los requerimientos para este método, plantea la observación, investigación y el muestreo; es muy utilizado en la investigación aplicada. 







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
