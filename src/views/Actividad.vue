<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    #Actividad                
      <Actividad :cuestionario="cuestionario" />

</template>

<script>
import Actividad from '@/components/actividad/Actividad'
export default {
  name: 'ActividadDidactica',
  components: { Actividad },
  data: () => ({
    cuestionario: {
      tema: 'Identificación de nichos de mercado.',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> apropiarse de los conocimientos asociados a la identificación de nichos de mercado, así como las técnicas e instrumentos de recolección de datos para crear una base de datos necesarios para el manejo de los mercados y grupo de clientes potenciales.',
      barajarPreguntas: false,
      preguntas: [
        {
          id: 1,
          texto:
            'Proceso mediante el cual las empresas crean valor para sus clientes y generan fuertes relaciones con ellos para, en reciprocidad, captar valor de los clientes.',
          imagen: require('@/assets/componentes/img1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Mercadeo', esCorrecta: true },
            { id: 'b', texto: 'Mercado', esCorrecta: false },
            { id: 'c', texto: 'Posicionamiento', esCorrecta: false },
            { id: 'd', texto: 'Participación de mercados', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            'Proceso que opera cuando hay personas que actúan como compradores y otras como vendedores de bienes y servicios, generando la acción del intercambio.',
          imagen: require('@/assets/componentes/img2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Mercado', esCorrecta: true },
            { id: 'b', texto: 'Mercadeo', esCorrecta: false },
            { id: 'c', texto: 'Posicionamiento', esCorrecta: false },
            { id: 'd', texto: 'Ventas', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            'Es la forma en que un producto está definido por los consumidores en atributos importantes, el lugar que ocupa en la mente de los consumidores respecto a los productos competidores.',
          imagen: require('@/assets/componentes/img3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Posicionamiento', esCorrecta: true },
            { id: 'b', texto: 'Segmentación', esCorrecta: false },
            { id: 'c', texto: 'Mercado', esCorrecta: false },
            { id: 'd', texto: 'Ventas', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            'Actividades relacionadas con la venta o la cantidad de bienes vendidos en un período de tiempo determinado. La entrega de un servicio por un costo también se considera una venta.',
          imagen: require('@/assets/componentes/img4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Ventas', esCorrecta: true },
            { id: 'b', texto: 'Segmentación', esCorrecta: false },
            { id: 'c', texto: 'Mercado', esCorrecta: false },
            { id: 'd', texto: 'Posicionamiento', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto:
            'Proceso de dividir un mercado en grupos de clientes potenciales con necesidades y/o características similares y que pueden requerir un producto diferente y/o una forma de comunicación diferente.',
          imagen: require('@/assets/componentes/img1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Segmentación', esCorrecta: true },
            { id: 'b', texto: 'Mercado', esCorrecta: false },
            { id: 'c', texto: 'Posicionamiento', esCorrecta: false },
            { id: 'd', texto: 'Ventas', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            'Es una comparación de las ventas de una compañía con las ventas totales de la industria; y puede ser actual o potencial.',
          imagen: require('@/assets/componentes/img2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Participación de mercados', esCorrecta: true },
            { id: 'b', texto: 'Segmentación', esCorrecta: false },
            { id: 'c', texto: 'Mercado', esCorrecta: false },
            { id: 'd', texto: 'Posicionamiento', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto:
            'Método para la recolección de la información que consiste en tener contacto con alguien, este método se propone utilizar herramientas básicas como: entrevista, cuestionarios y talleres de trabajo.',
          imagen: require('@/assets/componentes/img3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Interactivo', esCorrecta: true },
            { id: 'b', texto: 'Intrusivo', esCorrecta: false },
            { id: 'c', texto: 'Observación', esCorrecta: false },
            { id: 'd', texto: 'Persuasivo', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            'Colección organizada de información estructurada, o datos, típicamente almacenados electrónicamente en un sistema de computadora, para facilitar su posterior utilización. ',
          imagen: require('@/assets/componentes/img4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Base de datos', esCorrecta: true },
            { id: 'b', texto: 'Método intrusivo', esCorrecta: false },
            { id: 'c', texto: 'Base de datos relacional', esCorrecta: false },
            {
              id: 'd',
              texto: 'Base de datos orientada a objetos',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            'En este tipo de base de datos se crea una estructura en forma de árbol invertido, en el que todos sus nodos dependen en última instancia de uno denominado raíz.',
          imagen: require('@/assets/componentes/img1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Jerárquicas', esCorrecta: true },
            { id: 'b', texto: 'Relacionales', esCorrecta: false },
            { id: 'c', texto: 'En red', esCorrecta: false },
            { id: 'd', texto: 'Orientadas a objetos', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            'Estructuras de bases de datos compuestas por otras estructuras de datos.',
          imagen: require('@/assets/componentes/img2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Primitivas', esCorrecta: true },
            { id: 'b', texto: 'No primitivas o simples', esCorrecta: false },
            {
              id: 'c',
              texto: 'Estructura de base de datos',
              esCorrecta: false,
            },
            { id: 'd', texto: 'Diseño de base de datos', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
  computed: {},
  methods: {},
}
</script>
