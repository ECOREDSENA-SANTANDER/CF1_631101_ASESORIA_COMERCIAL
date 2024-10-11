<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Bases de datos
    
    .row.justify-content-center.align-items-center.mb-3
      .col-lg-8.col-md-12.col-12.mb-4
        p.mb-4 Las bases de datos son una herramienta fundamental en el entorno informático hoy en día y tienen aplicación prácticamente en todos los campos como los negocios, organizaciones y en la vida personal. Su aplicabilidad responde a la necesidad de gestionar datos que provean información pertinente.
        .cajon.color-acento-contenido.p-4
          p.mb-0 Una base de datos es un conjunto de datos estructurado y almacenado de forma sistemática para facilitar su posterior utilización. Igualmente, es una colección organizada de información estructurada, o datos, típicamente almacenados electrónicamente en un sistema de computadora.
      .col-lg-4.col-md-7.col-7.mb-4
        img.img-a.img-t(src='@/assets/curso/temas/img70.svg', alt='tema1')

    .subt.mb-4(data-aos="fade-right")
      .d-flex.align-items-center.mb-1
        img(src='@/assets/curso/temas/icono.svg', alt='')
        h3.mb-0.ms-2 Tipo de dato (tipo de campo)
    
    p.mb-5 Cada sistema de base de datos tiene tipos de campos que pueden ser similares o diferentes; entre los más comunes se pueden nombrar:

    SlyderF(columnas="col-lg-6 col-xl-4 col-md-6").mb-5
      .tarjeta.color.p-4
        .row.justify-content-center
          .col-12
            img.img-a.img-t.mb-4(data-aos="zoom-in-left")(src='@/assets/curso/temas/img71.svg' alt='AvatarTop')
            .row.justify-content-center
              .col-10.mb-4
                .bgw.p-1 
                  h3.text-center.mb-0 Númerico
            p.text-center(data-aos="fade-right") Entre los diferentes tipos de campos numéricos se pueden encontrar enteros “sin decimales” y reales “decimales”.
      .tarjeta.color.p-4
        .row.justify-content-center
          .col-12
            img.img-a.img-t.mb-4(data-aos="zoom-in-left")(src='@/assets/curso/temas/img72.svg' alt='AvatarTop')
            .row.justify-content-center
              .col-10.mb-4
                .bgw.p-1 
                  h3.text-center.mb-0 Boleanos
            p.text-center(data-aos="fade-right") Poseen dos estados: verdadero “Sí” y falso “No”.
      .tarjeta.color.p-4
        .row.justify-content-center
          .col-12
            img.img-a.img-t.mb-4(data-aos="zoom-in-left")(src='@/assets/curso/temas/img73.svg' alt='AvatarTop')
            .row.justify-content-center
              .col-10.mb-4
                .bgw.p-1 
                  h3.text-center.mb-0 Memos
            p.text-center(data-aos="fade-right") Son campos alfanuméricos de longitud ilimitada. Presentan el inconveniente de no poder ser indexados.					
      .tarjeta.color.p-4
        .row.justify-content-center
          .col-12
            img.img-a.img-t.mb-4(data-aos="zoom-in-left")(src='@/assets/curso/temas/img74.svg' alt='AvatarTop')
            .row.justify-content-center
              .col-10.mb-4
                .bgw.p-1 
                  h3.text-center.mb-0 Fechas
            p.text-center(data-aos="fade-right") Almacenan fechas facilitando su explotación. Almacenar fechas de esta forma posibilita ordenar los registros por fechas o calcular los días entre una fecha y otra.
      .tarjeta.color.p-4
        .row.justify-content-center
          .col-12
            img.img-a.img-t.mb-4(data-aos="zoom-in-left")(src='@/assets/curso/temas/img75.svg' alt='AvatarTop')
            .row.justify-content-center
              .col-10.mb-4
                .bgw.p-1 
                  h3.text-center.mb-0 Alfanúmericos
            p.text-center(data-aos="fade-right") Contienen cifras y letras. Presentan una longitud limitada (255 caracteres).
      .tarjeta.color.p-4
        .row.justify-content-center
          .col-12
            img.img-a.img-t.mb-4(data-aos="zoom-in-left")(src='@/assets/curso/temas/img76.svg' alt='AvatarTop')
            .row.justify-content-center
              .col-10.mb-4
                .bgw.p-1 
                  h3.text-center.mb-0 Auto incrementables
            p.text-center(data-aos="fade-right") Son campos numéricos enteros que incrementan en una unidad su valor para cada registro incorporado. Su utilidad resulta: servir de identificador ya que resultan exclusivos de un registro.
    
    p.mb-5 Las bases de datos más conocidas son:

    .row.justify-content-center
      .col-lg-4.col-md-7.col-7.pe-lg-0.mb-lg-0.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/img77.png', style="width: 410px", alt='').m-auto
      .col-md-12.col-lg-6.bg1.ps-lg-0(data-aos="fade-right")
        .p-4.h-100
          .row.align-items-center.h-100
            .col-12
              ul.lista-ul
                li.d-flex.mb-2
                  i.fas.fa-circle-check
                  p.mb-0 Microsoft Access. También conocido como MS Access, es un sistema de gestión de bases de datos (SGBD) incluido en el paquete de programas de Microsoft Office. Igualmente un gestor de datos que recopila información relativa a un asunto o propósito particular, como el seguimiento de pedidos de clientes o el mantenimiento de una colección de música.
                li.d-flex.mb-2
                  i.fas.fa-circle-check
                  p.mb-0 Oracle.
                li.d-flex.mb-2
                  i.fas.fa-circle-check
                  p.mb-0 DB2 de IBM.
                li.d-flex.mb-2
                  i.fas.fa-circle-check
                  p.mb-0 SQL Server.

    separador
    #t_5_1.titulo-segundo.mb-4
      h2 5.1 Tipos de bases de datos
    
    p.mb-4 Hay muchos tipos diferentes de bases de datos, pero la mejor base de datos para una organización específica depende de cómo la organización pretende utilizar los datos; así se encuentran:

    .row.justify-content-center.align-items-center
      .col-lg-8.mb-4
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.col-xl-11.m-auto(titulo="Bases de datos relacionales")
            .row.justify-content-center.align-items-center(data-aos="fade-right")
              .col-lg-12
                p.mb-0 Son las bases de datos más usadas. Los elementos de una base de datos relacional se organizan como un conjunto de tablas con columnas y filas. La tecnología de base de datos relacional proporciona la manera más eficiente y flexible de acceder a información estructurada.
          .row.col-xl-11.m-auto(titulo="Bases de datos jerárquicas")
            .row.justify-content-center.align-items-center(data-aos="fade-right")
              .col-lg-12
                p.mb-0 Los datos se recogen mediante una estructura basada en nodos interconectados. Cada nodo puede tener un único padre y cero, uno o varios hijos. De este modo, se crea una estructura en forma de árbol invertido en el que todos sus nodos dependen en última instancia de uno denominado raíz.
          .row.col-xl-11.m-auto(titulo="Bases de datos en red")
            .row.justify-content-center.align-items-center(data-aos="fade-right")
              .col-lg-12
                p.mb-0 Es aquella base de datos formada por una serie de registros, los cuales están enlazados entre sí creando una red. Estos registros son similares a los campos en las bases de datos relacionales y cada uno de ellos contiene un único atributo o valor.
          .row.col-xl-11.m-auto(titulo="Bases de datos orientadas a objetos")
            .row.justify-content-center.align-items-center(data-aos="fade-right")
              .col-lg-12
                p.mb-0 El modelo extiende las capacidades de las bases de datos relacionales, de tal modo que estas pueden contener objetos, permitiendo así una integración más fácil con la propia arquitectura de los programas empleados para el manejo de la base de datos, en caso de que estos hayan sido desarrollados mediante programación orientada a objetos.
      .col-lg-4.col-md-7.col-9(data-aos="fade-left" data-aos-delay="500")
        img(data-aos="zoom-in-left")(src="@/assets/curso/temas/img78.png")

    separador
    #t_5_2.titulo-segundo.mb-4
      h2 5.2 Estructura de una base de datos
    
    .row.justify-content-center.align-items-center.mb-3
      .col-lg-4.col-md-7.col-7.mb-4
        img.img-a.img-t(src='@/assets/curso/temas/img79.svg', alt='tema1')
      .col-lg-8.col-md-12.col-12.mb-4
        p.mb-4 La denominación más completa de la estructura de una base de datos corresponde a cada uno de los elementos, formatos y normas que la integran y permiten su óptimo funcionamiento, permitiendo un almacenamiento eficiente de los datos, sin que estos se puedan perder durante la actuación del programa en el modo digital.
        p.mb-4 Permiten  almacenar, manipular y ordenar los datos, que son materia prima en cualquier sistema de información. 
        p.mb-0 También admiten unas operaciones básicas: adicionar, realizar búsquedas, recorrer y eliminar datos. 
      
    p.mb-4 Las estructuras de bases de datos se pueden combinar de varias maneras para formar estructuras más complejas como:

    TabsC.color-primario
      .py-3.py-md-4.bg10.px-3(titulo="Primitivas")
        .row.justify-content-center.p-4
          .col-lg-4
            h4.mb-4 Primitivas
            p.mb-4 Compuestas por otras estructuras de datos así:
          .col-lg-6
            ImagenInfografica.color-acent
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/temas/img80.svg', alt='')
              .tarjeta.color-acento-con.p-4(x="91.3%" y="34.2%" numero="") 
                h3.mb-4.text-white Char
                p.text-white El tipo de datos CHAR almacena datos de carácter en un campo de longitud fija. Los datos pueden ser una serie de letras, números y otros caracteres de un solo byte o varios bytes que pueden ser utilizados por el juego de códigos del entorno local de la base de datos.
              .tarjeta.color-acento-con.p-4(x="91.3%" y="50%" numero="") 
                h3.mb-4.text-white Int
                p.text-white Los tipos de datos INTEGER y SMALLINT albergan números enteros pequeños. Ambos tipos de datos se almacenan como enteros binarios con signo. Los valores INTEGER tienen 32 bits y pueden representar números enteros desde –2 31–1 hasta 2 31–1. Los valores SMALLINT solo tienen 16 bits.
              .tarjeta.color-acento-con.p-4(x="91.3%" y="68%" numero="") 
                h3.mb-4.text-white Float
                p.text-white Almacena números de coma flotante, donde 'm' es el número de dígitos de la parte entera y 'd' el número de decimales. DOUBLE (REAL): almacena número de coma flotante con precisión doble. Igual que FLOAT, la diferencia es el rango de valores posibles.
              .tarjeta.color-acento-con.p-4(x="7.9%" y="68%" numero="") 
                h3.mb-4.text-white Double
                p.text-white El tipo double es similar a float, pero se utiliza cuando la precisión de una variable de coma flotante no es suficiente. Las variables declaradas como tipo double pueden contener aproximadamente el doble de dígitos significativos que las variables de tipo float.
              .tarjeta.color-acento-con.p-4(x="7.9%" y="45%" numero="") 
                h3.mb-4.text-white Boolean
                p.text-white El tipo de dato lógico o booleano es en computación aquel que puede representar valores de lógica binaria, esto es 2 valores que, normalmente, representan falso o verdadero. Se utiliza normalmente en la programación, estadística, electrónica, matemáticas (álgebra booleana), entre otras.
      .py-3.py-md-4.bg10.px-3(titulo="No primitivas o simples")
        .row.justify-content-center.p-4
          .col-lg-11
            h3.mb-3 No primitivas o simples:
            p.mb-4 Se construyen a partir de estructuras primitivas y son cadenas, arreglos y registros. Se componen en lineales y no lineales.
            .row.justify-content-center.align-items-center.mb-0
              .col-lg-10
                .titulo-sexto.color-secundario.mb-5
                  h5 Figura 14. 
                  | Estructuras no lineales o simples
                img(src='@/assets/curso/temas/img81.svg' alt='En la figura se describen estructuras primitivas lineales: las estructuras de datos lineales incluyen pilas, colas y listas ligadas lineales. Estructuras primitivas no lineales: las estructuras de datos no lineales incluyen grafos y arboles')
      .py-3.py-md-4.bg10.px-3(titulo="Estructura de base de datos")
        .row.justify-content-center.p-4
          .col-lg-11
            h3.mb-3 Estructuras de base de datos dinámicas y estáticas
            p.mb-4 La principal diferencia entre ambas es que mientras las bases de datos estáticas son de solo lectura y no permite modificar o añadir datos, las bases de datos dinámicas son mucho más flexibles y sí permiten editar, actualizar o borrar datos.
            img.img-a.img-t(src='@/assets/curso/temas/img82.svg' alt='')
      .py-3.py-md-4.bg10.px-3(titulo="Diseño de base de datos")
        .row.justify-content-center.p-4
          .col-lg-11
            h3.mb-3 Diseño de base de datos
            p.mb-0 #[b Diseño conceptual:] consiste en la producción de un esquema conceptual, que es independiente de todas las consideraciones físicas.
            p.mb-4 #[b Diseño lógico:] elimina las construcciones que no se pueden representar en el modelo de base de datos escogido (relacional, orientado a objetos, etc).
            p.mb-4 El esquema lógico se traduce en un esquema físico para el SGBD escogido. Considera las estructuras de almacenamiento y los métodos de acceso necesarios para proporcionar un acceso eficiente a la base de datos de una memoria secundaria. 
            img.img-a.img-t(src='@/assets/curso/temas/img83.svg' alt='')

    separador
    #t_5_3.titulo-segundo.mb-4
      h2 5.3 Manejo de una base de datos
      
    p.mb-4 Una base de datos necesita desarrollarse en una herramienta específica, puede hacerse de manera elemental en un Excel o utilizar un software de base de datos. La Base de Datos de Mercadeo (BDM) es la columna vertebral de cualquier sistema de información y más aún en programas de mercadeo uno a uno. Para manejar una base de datos es importante conocer el proceso que lleva a construirla y manejarla.
    p.mb-4 El proceso de diseño consta de los siguientes pasos:
    
    .row.align-items-center.justify-content-center
      .col-lg-12
        .tarjeta.tarjeta--a
          SlyderA(tipo="b").p-4
            .row.justify-content-center.align-items-center
              .col-lg-7.mb-4.mb-md-0 
                p(data-aos="zoom-in-left") Determinar el propósito de la base de datos. Esto le ayudará a prepararse para los pasos restantes.
              .col-lg-4.col-md-10.mb-4.mb-md-0 
                figure
                  img.img-a.img-t(src='@/assets/curso/temas/img84.svg', alt='Texto que describa la imagen')
            .row.justify-content-center.align-items-center
              .col-lg-7.mb-4.mb-md-0 
                p(data-aos="zoom-in-left") Buscar y organizar la información necesaria. Recopile todos los tipos de información que podría querer registrar en la base de datos, como los nombres de producto y los números de pedido.
              .col-lg-4.col-md-10.mb-4.mb-md-0 
                figure
                  img.img-a.img-t(src='@/assets/curso/temas/img85.svg', alt='Texto que describa la imagen')
            .row.justify-content-center.align-items-center
              .col-lg-7.mb-4.mb-md-0.my-4
                p(data-aos="zoom-in-left") El funcionamiento del hardware sin fallas es la base para dotar a un sistema una alta disponibilidad. Para saber cómo presentar el valor de alta disponibilidad a ofrecer se debe tener en cuenta la norma IEEE 762/2006 que suministra el método del cálculo de este indicador para sistemas eléctricos pero es aplicable a todo sistema eléctrico o electrónico.
                p(data-aos="zoom-in-rigth") En dicha norma se mencionan algunos indicadores como lo son: fiabilidad, disponibilidad, tiempo medio entre paradas (MTBF, Mid Time Between Failures), duración de las paradas (MTTR, o Mid Time To Repair), número de paradas por mantenimiento y tiempo total perdido por mantenimiento.
                p(data-aos="zoom-in-left") Para poder realizar este cálculo se necesita tener registrado en una tabla un registro por cada parada de los servicios con los siguientes datos:
                ul.lista-ul.left
                  li.d-flex.mb-1
                    i.fas.fa-circle-check
                    p.mb-0 Servicio que ha parado.
                  li.d-flex.mb-1
                    i.fas.fa-circle-check
                    p.mb-0 Motivo de la parada (mantenimiento, actualización, falla, etc.).
                  li.d-flex.mb-1
                    i.fas.fa-circle-check
                    p.mb-0 Duración de la parada (en minutos o segundos).
              .col-lg-4.col-md-10.mb-4.mb-md-0 
                figure
                  img.img-a.img-t(src='@/assets/curso/temas/img86.svg', alt='Texto que describa la imagen')
            .row.justify-content-center.align-items-center
              .col-lg-7.mb-4.mb-md-0 
                p(data-aos="zoom-in-left") Convertir los elementos de información en columnas. Decida qué información quiere almacenar en cada tabla. Cada elemento se convierte en un campo y se muestra como una columna en la tabla. Por ejemplo, una tabla de clientes de seguros podría incluir campos como se muestra en la figura.
              .col-lg-4.col-md-10.mb-4.mb-md-0 
                figure
                  img.img-a.img-t(src='@/assets/curso/temas/img87.svg', alt='Texto que describa la imagen')
            .row.justify-content-center.align-items-center
              .col-lg-7.mb-4.mb-md-0 
                p(data-aos="zoom-in-left") Especificar las claves principales. Elija la clave principal de cada tabla. La clave principal es una columna que se usa para identificar cada fila; un ejemplo podría ser Id. de producto o Id. de pedido
              .col-lg-4.col-md-10.mb-4.mb-md-0 
                figure
                  img.img-a.img-t(src='@/assets/curso/temas/img88.svg', alt='Texto que describa la imagen')
            .row.justify-content-center.align-items-center
              .col-lg-7.mb-4.mb-md-0.my-4
                p(data-aos="zoom-in-left") Establecer las relaciones de tablas. Busque en cada tabla y decida cómo se relacionan los datos en una tabla con los datos de otras tablas. Agregue campos a las tablas o cree tablas para aclarar las relaciones, según sea necesario.
                p(data-aos="zoom-in-rigth") Las relaciones consisten en una colección, o conjunto, de relaciones de la misma naturaleza. Ejemplo: Dados los conjuntos de entidades “Cliente" y “Factura", todas las relaciones de la forma cliente-factura, permiten obtener la información de los clientes y sus respectivas facturas.
                p(data-aos="zoom-in-left") La dependencia o asociación entre los conjuntos de entidades es llamada participación. En el ejemplo anterior los conjuntos de entidades “Factura" y “Cliente" participan en el conjunto de relaciones factura-cliente. Se llama grada del conjunto de relaciones a la cantidad de conjuntos de entidades participantes en la relación.
              .col-lg-4.col-md-10.mb-4.mb-md-0 
                figure
                  img.img-a.img-t(src='@/assets/curso/temas/img90.svg', alt='Texto que describa la imagen')
            .row.justify-content-center.align-items-center
              .col-lg-7.mb-4.mb-md-0.my-4
                p(data-aos="zoom-in-left") Perfeccionar el diseño. Analice el diseño en busca de errores. Cree las tablas y agregue unos cuantos registros de datos de ejemplo. Compruebe si puede obtener los resultados que quiere de las tablas. Haga algunos ajustes en el diseño, si es necesario. Ejemplos de relaciones que expresan cardinalidad:
                ul.lista-ul.left
                  li.d-flex.mb-1
                    i.fas.fa-circle-check
                    p.mb-0 Un policía (entidad) tiene (relación) un arma (entidad) siempre y cuando no realice funciones de oficina, pudiendo entonces tenerla o no asignada. Es una relación 0:1.
                  li.d-flex.mb-1
                    i.fas.fa-circle-check
                    p.mb-0 Cada esposo (entidad) está casado (relación) con una única esposa (entidad) y viceversa. Es una relación 1:1.
                  li.d-flex.mb-1
                    i.fas.fa-circle-check
                    p.mb-0 Una factura (entidad) se emite (relación) a un cliente (entidad) y sólo una, pero una cliente puede tener varias facturas emitidas a su nombre. Todas las facturas se emiten a nombre de alguien. Es una relación 1: N.
                  li.d-flex.mb-1
                    i.fas.fa-circle-check
                    p.mb-0 Un cliente (entidad) puede comprar (relación) varios servicios (entidad) y un servicio puede ser comprado por varios clientes distintos. Es una relación N:M.
              .col-lg-4.col-md-10.mb-4.mb-md-0 
                figure
                  img.img-a.img-t(src='@/assets/curso/temas/img89.svg', alt='Texto que describa la imagen')
            .row.justify-content-center.align-items-center
              .col-lg-7.mb-4.mb-md-0 
                p(data-aos="zoom-in-left") Aplicar las reglas de normalización. Aplique las reglas de normalización de datos para ver si las tablas están estructuradas correctamente. Haga algunos ajustes en las tablas, si es necesario. La normalización es el proceso de organizar de manera eficiente los datos dentro de una base de datos. Hay que organizar tablas y el establecimiento de relaciones y el establecimiento de relaciones entre ellas según reglas preestablecidas.
              .col-lg-4.col-md-10.mb-4.mb-md-0 
                figure
                  img.img-a.img-t(src='@/assets/curso/temas/img91.svg', alt='Texto que describa la imagen')

</template>

<script>
export default {
  name: 'Tema5',
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
