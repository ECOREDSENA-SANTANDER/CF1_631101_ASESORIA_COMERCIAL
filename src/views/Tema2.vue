<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Mercado
    
    .row.justify-content-center.align-items-center
      .col-lg-10
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/img39.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Se entiende el mercado como un grupo de compradores y vendedores de un bien en particular o servicio. Al respecto, economipedia indica que “el mercado es un proceso que opera cuando hay personas que actúan como compradores y otras como vendedores de bienes y servicios, generando la acción del intercambio”. 
    separador
    #t_2_1.titulo-segundo.mb-4
      h2 2.1 Tipos de mercados
    
    p.mb-4 Dependiendo del enfoque en el cual se ubiquen los mercados de acuerdo con Fernández (2009), tienen los siguientes tipos:
    
    .row.justify-content-center.align-items-center
      .col-lg-8
        .bg9.p-3
          ImagenInfografica.color-acento-contenido
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/temas/img40.svg', alt='')
            .tarjeta.color-acento-con.p-4(x="90.7%" y="50%" numero="") 
              h4.mb-4.text-white Según el tipo de productos
              ul.lista-ul
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0.text-white Mercado de materias primas.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0.text-white Mercado de productos industriales.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0.text-white Mercado de productos informáticos.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0.text-white Mercado de productos manufacturados.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0.text-white Mercado de servicios.
            .tarjeta.color-acento-con.p-4(x="24.5%" y="18.5%" numero="") 
              h4.mb-4.text-white De acuerdo con el tipo de demanda
              ul.lista-ul.text-white
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0 Mercado disponible.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0 Mercado real.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0 Mercado potencial.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0 Mercado meta.
            .tarjeta.color-acento-con.p-4(x="46.9%" y="59%" numero="") 
              h4.mb-4.text-white Desde el punto de vista geográfico
              ul.lista-ul.text-white
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0 Mercados locales y/o mercados regionales.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0 Mercados nacionales.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0 Mercados multinacionales y extranjeros.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0 Mercados globales.
            .tarjeta.color-acento-con.p-4(x="40.5%" y="82.5%" numero="") 
              h4.mb-4.text-white Según el tipo de consumo
              ul.lista-ul.text-white
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0 Mercado de consumo.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0 Mercado de servicios.
                li.d-flex.mb-2
                  i.fas.fa-circle-check.cr
                  p.mb-0 Mercadotecnia industrial.

    separador
    #t_2_2.titulo-segundo.mb-4
      h2 2.2 Clases de mercado
    
    .row.justify-content-center.align-items-end
      .col-lg-8.col-md-12.col-12.mb-4
        p.mb-4 Con base en la demanda, los mercados están construidos por personas, hogares, empresas o instituciones que demandan productos, así, las acciones de marketing de una empresa deben estar sistemáticamente dirigidas a cubrir los requerimientos particulares de estos mercados para proporcionarles una mejor satisfacción de sus necesidades específicas. Según el monto de la mercancía hay:
        .bg6.p-4
          ul.lista-ul
            li.d-flex.mb-1
              i.fas.fa-circle-check
              p.mb-0 #[b Mercado total.] Conformado por el universo con necesidades que pueden ser satisfechas por la oferta de una empresa.
            li.d-flex.mb-1
              i.fas.fa-circle-check
              p.mb-0 #[b Mercado potencial.] Conformado por todos los entes del mercado total que además de desear un servicio, un bien está en condiciones de adquirirlas.
            li.d-flex.mb-1
              i.fas.fa-circle-check
              p.mb-0 #[b Mercado meta.] Está configurado por los segmentos del mercado potencial que han sido seleccionados en forma específica, como destinatarios de la gestión de marketing, es el mercado que la empresa desea y decide captar.
            li.d-flex.mb-1
              i.fas.fa-circle-check
              p.mb-0 #[b Mercado real.] Representa el mercado al cual se ha logrado llegar a los consumidores de los segmentos del mercado meta que se han captado.
      .col-lg-4.col-md-7.col-7.mb-4
        img(src='@/assets/curso/temas/img41.png', alt='tema2')

    separador
    #t_2_3.titulo-segundo.mb-5
      h2 2.3 Otros tipos de mercados
    
    .row.justify-content-center
      .col-lg-6.col-md-6.mb-4
        .overflow-hidden.h-100.bg4.p-4
          img.img-a.img-t.mb-4(src='@/assets/curso/temas/img42.svg', alt='tema2')
          .row.justify-content-center.mb-3
            .col-12.mb-4
              .bg5.p-1 
                h3.text-center.mb-0 Mercado mayorista
          p.mb-4.text-center En este tipo de mercado es donde se venden mercaderías al por mayor y en grandes cantidades. Allí acuden, generalmente, los intermediarios y distribuidores a comprar en cantidad los productos que después han de revender a otros comerciantes, a precios mayores y caprichosamente elevados.
      .col-lg-6.col-md-6.mb-4
        .overflow-hidden.h-100.bg4.p-4
          img.img-a.img-t.mb-4(src='@/assets/curso/temas/img43.svg', alt='tema2')
          .row.justify-content-center.mb-3
            .col-12.mb-4
              .bg5.p-1 
                h3.text-center.mb-0 Mercado minorista
          p.mb-4.text-center Llamados también de retail o menudeo, donde se venden en pequeñas cantidades directamente a los consumidores. Una nueva modalidad de este tipo de mercados se tiene en los supermercados, los que constituyen grandes cadenas u organizaciones que mueven ingentes capitales. En aquellos se estila el "autoservicio", es decir, que el mismo consumidor elige los artículos que va a comprar, eliminándose el empleado dependiente y al pequeño comerciante que

    separador
    #t_2_4.titulo-segundo.mb-5
      h2 2.4 Características del mercado
    
    .row.justify-content-center.align-items-center
      .col-lg-4.col-md-7.col-7.mb-3
        img(src='@/assets/curso/temas/img44.svg', alt='tema2')
      .col-lg-8.col-md-12.col-12.mb-0
        p.mb-4 Debido a los rasgos que caracterizan el mercado, que es en donde se genera la aplicación de las estrategias de mercadeo y las condiciones de operación de los distintos oferentes de un bien o servicio en un mercado específico, se puede hablar de dos tipos de competencia:
        .bg6.p-4.mb-3
          ul.lista-ul
            li.d-flex.mb-0
              i.fas.fa-circle-check
              p.mb-0 #[b Competencia perfecta:] es aquella en la cual los productos compiten entre sí por su calidad, pero nada más. En este mercado no se necesitan aplicar herramientas de mercadeo.
        .bg6.p-4
          ul.lista-ul
            li.d-flex.mb-0
              i.fas.fa-circle-check
              p.mb-0 #[b Competencia imperfecta:] es aquella en la que intervienen factores externos a la propia dinámica del mercado, tales como regulaciones estatales, monopolios, grandes campañas publicitarias, estrategias desleales de mercado, entre otras como las herramientas de #[em marketing.]

    separador
    #t_2_5.titulo-segundo.mb-4
      h2 2.5 Estrategias del mercado
    
    .row.justify-content-center.align-items-end.mb-4
      .col-lg-8.col-md-12.col-12.mb-4
        p.mb-4 La demanda de un mercado la constituyen diversos tipos de compradores con diferentes necesidades, como empresa se quiere llegarles a todos, pero no siempre se puede atender a todos o la mayoría como se quisiera, y unos clientes son atendidos mejor que otros. 
        p.mb-4 Por tanto, cada empresa debe mirar a qué clientes puede atender mejor y que sean más rentables, para ello, se debe dividir el mercado y escoger a quien le se le puede llegar con el portafolio de productos que ofrece la compañía; este proceso según Kotler y Armstrong (2013), implica la segmentación de mercado, la selección de mercado meta, la diferenciación y el posicionamiento. 
        .cajon.color-acento-contenido.p-4
          p.mb-0 Luego de segmentado este mercado, se debe evaluar cómo poder llegarle a cada uno de esos segmentos definidos por la empresa, es ahí donde entran las estrategias. El pensamiento de Michael E. Porter citado por Fano (2015), describió la estrategia competitiva, como las acciones ofensivas o defensivas de una empresa para crear una posición defendible dentro de una industria, acciones que eran la respuesta a las cinco fuerzas competitivas que el autor indicó como determinantes de la naturaleza y el grado de competencia que rodeaba a una empresa y que, como resultado, buscaba obtener un importante rendimiento sobre la inversión. También es según el autor “la creación de una posición única y valiosa en el mercado”.
      .col-lg-4.col-md-7.col-7.mb-4
        img.img-a.img-t(src='@/assets/curso/temas/img46.png', alt='tema1')

    p.mb-5 Existen diversos tipos de estrategias:

    .row.justify-content-center(data-aos="fade-down")
      .col-md-6.col-lg-5.col-12.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/temas/img47.svg' alt='')
          .tarjeta.bg2
            .p-4.my-5
              h4.mb-4.text-center Estrategias de crecimiento
              .row.justify-content-center
                .col-lg-7.col-md-12.col-10
                  ul.lista-ul
                    li.d-flex.mb-2
                      i.fas.fa-circle-check
                      p.mb-0 De penetración.
                    li.d-flex.mb-2
                      i.fas.fa-circle-check
                      p.mb-0 De desarrollo de productos.
                    li.d-flex.mb-2
                      i.fas.fa-circle-check
                      p.mb-0 De desarrollo de mercados.
                    li.d-flex.mb-0
                      i.fas.fa-circle-check
                      p.mb-0 Diferenciación.
    
      .col-md-6.col-lg-5.col-12.mb-5
        .tarjeta-avatar
          img(src='@/assets/curso/temas/img48.svg' alt='')
          .tarjeta.bg2
            .p-4.my-5
              h4.mb-4.text-center Estrategias competitivas
              .row.justify-content-center
                .col-lg-7.col-md-12.col-10
                  ul.lista-ul
                    li.d-flex.mb-2
                      i.fas.fa-circle-check
                      p.mb-0 Líderes en costos.
                    li.d-flex.mb-2
                      i.fas.fa-circle-check
                      p.mb-0 Diferenciación.
                    li.d-flex.mb-2
                      i.fas.fa-circle-check
                      p.mb-0 Enfoque.
      .row.justify-content-center(data-aos="fade-down")
        .col-md-10.col-lg-8.col-12
          img.img-a.img-t.mt2(src='@/assets/curso/temas/img49.svg' alt='')

    separador
    #t_2_6.titulo-segundo.mb-4
      h2 2.6 Participación del mercado
    
    p.mb-4 Desde el punto de vista de la empresa, el mercado es un ámbito donde hay que conquistar un espacio para "colocar" los productos o servicios. Por ejemplo, para bebidas colas qué espacio del mercado de bebidas pertenece a la empresa tanto en dinero como en unidades, y esto se expresa normalmente en términos relativos. El concepto de participación de mercados es una comparación de las ventas de una compañía con las ventas totales de la industria; y puede ser actual o potencial.

    .row.justify-content-center.align-items-center.mb-0
      .col-lg-4
        .titulo-sexto.color-secundario.mb-5
          h5 Figura 12. 
          | Participación de mercado 
        img(src='@/assets/curso/temas/img50.svg' alt='Se presenta una grafica tipo torta, donde coca-cola tiene el 43.8 %, la pepsi tiene el 29.5 %, la kola real tiene el 23.4 %, grupo rojas tienen el 3 % y otros el 0.3 %')

    separador
    #t_2_7.titulo-segundo.mb-4
      h2 2.7 Pasos para definir el mercado

    p.mb-4 La empresa debe saber quienes  son los consumidores a los que va dirigida su oferta y cada decisión hacia ellos, a ese grupo de clientes se le llama “mercado objetivo” o “mercado meta”.  Con ese mercado meta se puede tomar la decisión de qué publicidad se va a usar, qué precio y qué programa de fidelización montar. Para ello, se deben llevar a cabo los siguientes pasos: 

    TabsC.color-primario
      .py-3.py-md-4.bg26.px-3(titulo="Segmentación")
        .row.justify-content-center.p-4
          .col-lg-12.col-md-12
            p.mb-4 Es el proceso de dividir un mercado en grupos de clientes potenciales con necesidades y/o características similares y que pueden requerir un producto diferente y/o una forma de comunicación diferente. De acuerdo con Kerin et al (2014, p. 228), la segmentación de mercados consiste en dividir a los compradores potenciales en grupos que: tienen necesidades comunes y responden de manera similar a una acción de #[em marketing]. ¿Qué se puede segmentar?: usos, deseos, poder de compra, residencia, actitudes, hábitos de compra.
            img.img-a.img-t(src='@/assets/curso/temas/img51.png', alt='')
      .py-3.py-md-4.bg26.px-3(titulo="Mercado meta")
        .row.justify-content-center.p-4
          .col-lg-12
            p.mb-4 Se refiere al grupo de personas ideales para adquirir tu servicio o producto, al que debemos dirigir nuestra atención y esfuerzos de marketing. ¿Cómo definir el mercado meta? Seguir estos pasos para poder definir el mercado objetivo:
            p.mb-4 Analizar los clientes existentes. Recolectar toda la información sobre los clientes actuales y potenciales y tratar de identificar características que tengan en común como edad, sexo, ubicación, intereses, etc.
            p.mb-4 #[b Conoce los beneficios de tu producto.] Cuáles son los elementos de tu producto, y sus beneficios con respecto a otros, así como cuáles son tus áreas de oportunidad.
            p.mb-4 #[b Investiga a tus competidores.] Revisar lo que hacen tus competidores más importantes.
            p.mb-4 #[b Segmenta a los consumidores.] Con la información muy valiosa acerca de los consumidores, es hora de comenzar a separarlos en diferentes grupos (a esto se le llama segmentar al mercado). Estos distintos grupos serán la base del mercado meta.
            p.mb-4 #[b Escribir el mercado meta.] Tener el mercado meta definido y en papel no solamente es para que tener claridad sobre esto, sino también servirá para el entorno con proveedores externos, ellos entiendan tanto como a quién va dirigido el producto (piensa en diseñadores, fotógrafos, publicistas, entre otros). Ejemplo: “El mercado meta son hombres y mujeres de 18 a 30 años, con un poder adquisitivo alto, que estén interesados en festivales de música electrónica y viajes”.
            p.mb-0 Redefinir el producto. Tomar decisiones para introducir cambios ajustados a lo que solicita ese segmento de mercado.
      .py-3.py-md-4.bg26.px-3(titulo="Posicionamiento")
        .row.justify-content-center.p-4
          .col-lg-8
            p.mb-4 Colocar la oferta de mercado en la mente del mercado meta. Para Kotler (2013), “una posición de producto es la forma en que un producto está definido por los consumidores en atributos importantes, el lugar que ocupa en la mente de los consumidores respecto a los productos competidores”. Esto es importante porque la empresa procura recordación en los consumidores a la hora de cumplir con sus necesidades.
            p.mb-4 El mapa de posicionamiento es una herramienta que permite medir la posición que ocupa nuestra marca o empresa en la mente del consumidor. Se tiene en cuenta los atributos que utiliza la competencia para posicionarse y con ellos se elabora el mapa. Este consiste en por lo menos dos coordenadas que corresponden a los atributos, por ejemplo, precio y calidad, tamaño y velocidad, color y textura, entre otros. Una vez que se determina el mapa, se ubicarán en el mismo a los competidores y a nuestra empresa o los productos, para saber el posicionamiento que podemos generar en nuestro segmento meta.
          .col-lg-4.col-md-9
            img.img-a.img-t(src='@/assets/curso/temas/img52.svg', alt='')
      .py-3.py-md-4.bg26.px-3(titulo="Comunicación")
        .row.justify-content-center.p-4
          .col-lg-12.col-md-12
            p.mb-4 Luego de definir el posicionamiento de la marca, la empresa debe desarrollar su estrategia de comunicación en los segmentos de mercado definidos.
            img.img-a.img-t(src='@/assets/curso/temas/img53.png', alt='')
      .py-3.py-md-4.bg26.px-3(titulo="Comunicación")
        .row.justify-content-center.p-4
          .col-lg-12.col-md-12
            p.mb-4 El siguiente paso es llegarle a esos segmentos o nichos de mercado a través de la estrategia de ventas para cada uno de los segmentos. La segmentación del mercado es una estrategia de #[em marketing] que permite obtener mejores resultados de ventas, en tanto que se basa en la división de nuestro mercado, entendido este como potenciales clientes, en distintos segmentos o nichos con necesidades, características y comportamientos comunes, para adaptar la oferta a sus requerimientos específicos.
            img.img-a.img-t(src='@/assets/curso/temas/img54.png', alt='')









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
