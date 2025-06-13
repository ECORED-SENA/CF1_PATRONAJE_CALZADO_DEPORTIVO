<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema: 'Aspectos técnicos del patronaje de calzado',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> identificar los conceptos clave relacionados con la estructura, materiales, tipologías, fases de producción y documentación técnica en el patronaje de calzado.',
      barajarPreguntas: true,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO.',
      preguntas: [
        {
          id: 1,
          texto: '¿Cuál es la función principal de la capellada en el calzado?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Define la altura del tacón.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Cubre el pie y define el diseño del calzado.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Sirve como base para pegar la suela.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Aumenta la resistencia del talón.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            '¿Qué tipo de calzado está diseñado para ofrecer protección en entornos laborales?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Deportivo.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Casual.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Industrial.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Ortopédico.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            '¿Qué material se caracteriza por ser biodegradable y utilizar taninos vegetales?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Cuero vegetal.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Cuero al cromo.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Cuero mixto.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Cuero porcino.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Cuál de las siguientes partes proporciona amortiguación entre la suela y la plantilla?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Tacón.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Cordonera.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Entresuela.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Cambrión.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto: '¿Qué característica tiene el calzado de tipo Oxford?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Diseño con punta de acero.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Estructura abierta con cordones externos.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Estructura cerrada con cordones internos.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Uso exclusivo de materiales sintéticos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Qué tipo de curtido genera un cuero más claro, con alta capacidad de teñido y sin metales pesados?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Curtido al cromo.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Curtido con aluminio.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Curtido vegetal.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Curtido mixto.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto: '¿Cuál es la función principal del proceso de desbaste?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Aumentar el grosor del material.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Mejorar la adherencia del pegamento.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Pulir la suela.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Redondear el diseño del tacón.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            '¿Qué tipo de máquina facilita la costura en zonas curvas del calzado?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Máquina de codo.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Máquina de columna.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Máquina doble aguja.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Sobrehiladora.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            '¿Qué tipo de suela se caracteriza por ser ligera, flexible y con gran capacidad de absorción de impactos?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'PVC.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'EVA.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Cuero.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'TR.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Cuál es uno de los usos principales de la ficha técnica de diseño?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Reemplazar el proceso de control de calidad.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Garantizar uniformidad y calidad en la producción.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Eliminar la necesidad de bocetos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Sustituir los manuales de fabricación.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto: 'El cambrión es un componente decorativo del calzado.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Verdadero.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 12,
          texto:
            'El cuero caprino se caracteriza por su resistencia y textura granulada.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Verdadero.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 13,
          texto:
            'El montaje <em>Strobel</em> se utiliza principalmente en calzado formal.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Verdadero.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 14,
          texto:
            'Los materiales textiles sintéticos como el poliéster permiten transpiración y son de bajo costo.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Verdadero.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 15,
          texto:
            'La ficha técnica de diseño incluye datos sobre materiales, procesos de ensamblaje y medidas.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Verdadero.',
              esCorrecta: true,
            },
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
}
</script>
