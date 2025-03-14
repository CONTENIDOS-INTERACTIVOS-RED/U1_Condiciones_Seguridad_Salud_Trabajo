<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Objetivos, indicadores y resultados esperados'")
  .container.tarjeta.tarjeta--blanca.px-4.pt-4.px-md-5.pt-md-5.pb-0.overflow-hidden

    .bg-color-5.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") En la estructuración de un proyecto, los objetivos son declaraciones que describen los resultados que se espera lograr mediante la implementación del proyecto. Se dividen en objetivo general y objetivos específicos, cada uno con un propósito distinto pero complementario.
        .col-lg-auto
          figure
            img(src='@/assets/curso/tema3/1.png', alt='')

    h2.mb-5(data-aos="fade-up") Objetivos
    p(data-aos="fade-up") Basado en la formulación clara del problema a través de preguntas que aborden síntomas, causas, consecuencias y posibles soluciones, los objetivos (general y específicos) de un proyecto se formulan para responder a estas preguntas y guiar las acciones hacia una solución efectiva.

    h2.mb-5(data-aos="fade-up") Objetivo general
    p(data-aos="fade-up").mb-5 Este objetivo responde a la pregunta central que guía el proyecto y es una declaración amplia del propósito principal, alineado con la necesidad de resolver el problema planteado. Debe ser lo suficientemente concreto para que sea operativo, pero lo bastante flexible para permitir distintas soluciones.

    .row.justify-content-center.align-items-start.mb-5
      .col-lg-8
        h3.mb-3(data-aos="fade-up") Ejemplo
        p(data-aos="fade-up").mb-4 Si el problema planteado es: #[strong ¿Cómo podemos optimizar el proceso XYZ para reducir costos en un 10%?,] el objetivo general podría ser: #[strong optimizar el proceso XYZ para reducir los costos operativos en un 10% en los próximos 12 meses.]

        .bg-color-4.p-4(data-aos="fade-left").mb-4
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema3/3.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Los objetivos específicos descomponen el objetivo general en metas concretas, enfocadas en los diferentes aspectos identificados durante la formulación del problema: síntomas, causas y posibles soluciones. Estos objetivos responden preguntas clave como: ¿Qué se necesita mejorar?, ¿Qué cambios deben implementarse?, ¿Cómo se medirán los avances?
        
        p(data-aos="fade-up").mb-0 Cada objetivo específico debe estar diseñado para abordar una parte específica del problema y debe ser medible, permitiendo evaluar el progreso hacia el cumplimiento del objetivo general.
      .col-lg-4
        figure
          img(src="@/assets/curso/tema3/2.png", data-aos="zoom-in").mb-4.mb-lg-0


    h3.mb-3(data-aos="fade-up") Ejemplo
    p(data-aos="fade-up").mb-4 Partiendo del mismo problema, los objetivos específicos podrían ser:

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6
        .bg-color-1.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/4.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Identificar y reducir los tiempos muertos en el proceso XYZ en un 15% mediante la implementación de un sistema automatizado.

      .col-lg-6
        .bg-color-2.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/5.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Reducir el consumo de materias primas en el proceso XYZ en un 5% mediante la optimización de las técnicas de producción.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6
        .bg-color-2.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/6.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Capacitar al personal en el uso de las nuevas tecnologías implementadas, alcanzando un nivel de competencia del 90% en los primeros 3 meses.

      .col-lg-6
        .bg-color-2.p-4(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/7.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Evaluar y modificar el flujo de trabajo para mejorar la eficiencia operativa en un 8%.

    h2.mb-5(data-aos="fade-up") Justificación, resultados e indicadores

    .row.mb-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema3/8.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left")  La justificación, los resultados e indicadores de un proyecto es fundamental para garantizar su coherencia y efectividad. La justificación permite contextualizar la relevancia del proyecto, identificando las necesidades o problemas que se desean abordar y estableciendo su importancia en un ámbito específico. Los resultados, por su parte, representan las metas concretas que se pretenden alcanzar, sirviendo como guía para las acciones y asegurando que el esfuerzo esté alineado con los objetivos propuestos. Finalmente, los indicadores se convierten en herramientas esenciales para medir el progreso y evaluar el impacto del proyecto, proporcionando datos claros que respaldan la toma de decisiones y la mejora continua. Este enfoque integral asegura no solo la viabilidad, sino también la sostenibilidad y relevancia del proyecto a lo largo del tiempo.

    .bg-full-width.bg-color-4
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7
            h2.mb-4(data-aos="flip-up") Justificación, resultados e indicadores
            p.mb-4(data-aos="fade-right") En el documento Justificación, resultados e indicadores se presentan tres elementos clave que estructuran y orientan el desarrollo de un proyectos. Lo invitamos a consultar el documento para ampliar esta información.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_3.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Justificación, resultados e indicadores

          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/9.png', alt='')

    .bg-full-width.border-top.actividad.bg-color-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>
</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema3',
  components: {
    BannerInterno,
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Matemática financiera',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '¿Cuál es el objetivo principal de la formación en seguridad y salud en el trabajo?',
            imagen: require('@/assets/actividad/imagen1.png'),
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Aumentar la producción',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Proteger la salud de los trabajadores',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Reducir costos',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Mejorar la imagen corporativa',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              '¿Qué norma establece el Sistema General de Riesgos Laborales en Colombia?',
            imagen: require('@/assets/actividad/imagen1.png'),
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Ley 1562 de 2012',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Decreto 1072 de 2015',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Resolución 0312 de 2019',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'ISO 45001:2018',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              '¿Qué entidad supervisa el cumplimiento de la Ley 1562 de 2012?',
            imagen: require('@/assets/actividad/imagen1.png'),
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Ministerio de Salud',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Ministerio del Trabajo',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Asociación de Riesgos Laborales',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Organización Internacional del Trabajo',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              'La Resolución 0312 de 2019 establece estándares mínimos para:',
            imagen: require('@/assets/actividad/imagen1.png'),
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'El desarrollo organizacional',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'La educación formal',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'La seguridad y salud en el trabajo',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'La gestión ambiental',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto: '¿Qué aspecto se enfatiza en la normativa ISO 45001?',
            imagen: require('@/assets/actividad/imagen1.png'),
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Reducción de costos',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Liderazgo y compromiso',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Reinversión de utilidades',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Aumento de ventas',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
