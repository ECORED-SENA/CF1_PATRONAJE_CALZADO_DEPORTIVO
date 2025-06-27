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
        '<b> Objetivo:</b> identificar los conceptos clave relacionados con la estructura, materiales, tipologías, fases de producción y documentación técnica en el patronaje de calzado deportivo.',
      barajarPreguntas: true,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO.',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Cuál es la función principal de la capellada en el calzado deportivo?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La amortiguación del impacto.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Cubrir y proteger la parte superior del pie.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Aumentar el peso del zapato.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Reducir el desgaste de la suela.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            '¿Qué tipo de cuero se caracteriza por su rigidez y uso de taninos vegetales?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Cuero al cromo.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Cuero porcino.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Cuero vegetal.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Cuero sintético.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            '¿Cuál es una ventaja de los materiales sintéticos en el calzado?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Transpirabilidad natural.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Resistencia a la humedad y bajo costo.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Fácil descomposición.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Mayor peso y rigidez.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Qué material se usa comúnmente en la entresuela por su capacidad de amortiguación?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'PVC.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Cuero.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'EVA.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Lona.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto: '¿Cuál es una característica del calzado ortopédico?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Diseño elegante para eventos formales.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Uso exclusivo para ambientes industriales.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Soporte para corregir problemas del pie.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Alta resistencia al fuego.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Cuál es el objetivo del proceso de desbaste en la fabricación de calzado?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Aplicar color a los materiales.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Mejorar la adherencia del pegamento.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Cosido de la capellada.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Insertar refuerzos en la suela.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto:
            '¿Qué tipo de máquina de coser se utiliza para zonas curvas del calzado?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Máquina recta.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Máquina de codo.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Máquina industrial.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Máquina láser.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto: '¿Qué característica tiene el cuero caprino?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Textura granulada y resistencia.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Alta rigidez y grosor.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Costo elevado y poca durabilidad.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Poca flexibilidad.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto: '¿Qué permite una ficha técnica de diseño?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Reducir el tamaño del calzado.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Estandarizar la producción y asegurar la calidad.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Elaborar nuevos modelos sin control.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Distribuir productos sin identificación.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Qué material textil es ideal para calzado de verano por su frescura y ligereza?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Poliéster.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Lino.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Nylon.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Microfibra.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto:
            'La puntera del calzado tiene una función decorativa únicamente.',
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
            'El montaje Strobel proporciona mayor comodidad y flexibilidad.',
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
          id: 13,
          texto:
            'El PVC es un material natural común en la fabricación de calzado.',
          imagen: require('@/assets/actividad/imagen1.png'),
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
            'La suela influye directamente en la seguridad y estabilidad del calzado deportivo.',
          imagen: require('@/assets/actividad/imagen2.png'),
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
            'La plantilla no tiene ninguna influencia en la estabilidad del pie.',
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
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
