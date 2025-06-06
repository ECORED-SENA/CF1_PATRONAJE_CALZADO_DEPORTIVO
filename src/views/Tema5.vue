<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Fichas técnicas de diseño
    
    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema5/img1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La ficha técnica de diseño es un documento esencial que reúne la información detallada de un producto en desarrollo. Su objetivo es asegurar que, desde el diseño hasta la producción final, se sigan parámetros estandarizados que garanticen la calidad del artículo. Este instrumento es ampliamente utilizado en sectores como el calzado, la marroquinería, el textil y la manufactura en general.

    separador
    #t_5_1.titulo-segundo.color-acento-contenido
      h2 5.1  Características de la ficha técnica de diseño

    p Una ficha técnica bien elaborada debe contener diversos elementos que permitan comprender todas las características del producto. A continuación, se describen los apartados que la componen:

    .row.align-items-center
      .col-lg-4.d-lg-block.d-none
        figure
          img(src='@/assets/curso/tema5/img2.png', alt='', style="width: 400px").m-auto

      .col-lg-8
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg-7")
          .row(titulo="Información general")
            .col-12.mb-4.mb-md-0

              p.px-5 Incluye los datos básicos que identifican el producto y su registro documental:

              ul.lista-ul--color2.px-5
                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-3 Nombre del producto.

                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-3 Código o referencia.

                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-3 Fecha de creación y versión.


          div(titulo="Descripción del diseño")
            p.px-5 Define visual y dimensionalmente el producto para su correcta interpretación por parte del equipo técnico:

            ul.lista-ul--color2.px-5
              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3 Boceto o imagen del producto.

              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3 Especificaciones de forma y dimensiones.

          div(titulo="Materiales y componentes")
            p.px-5 Detalla los elementos físicos que conforman el producto, tanto estructurales como decorativos:

            ul.lista-ul--color2.px-5
              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3 Tipo de materiales utilizados (cuero, tela, sintético, etc.).

              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3 Herrajes, cremalleras, botones u otros accesorios.

              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3 Colores y texturas.

          div(titulo="Técnicas de fabricación")
            p.px-5 Define los procesos que se deben seguir para ensamblar las partes del producto:

            ul.lista-ul--color2.px-5
              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3 Tipo de costuras y uniones.

              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3 Métodos de ensamblaje (pegado, cosido, termosellado, etc.).

              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3 Tipo de curtido en caso de cuero.

    .row.align-items-center.mt-3
      .col-lg-8
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg-7")
          .row(titulo="Medidas y tallas")
            .col-12.mb-4.mb-md-0
              p.px-5 Especifica las dimensiones del producto y, si corresponde, la tabla de tallas según su aplicación:

              ul.lista-ul--color2.px-5
                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-3  Dimensiones en centímetros o pulgadas.

                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-3  Tabla de tallas en caso de calzado o prendas.

          div(titulo="Indicaciones de uso y cuidado")

            p.px-5 Proporciona instrucciones necesarias para preservar el producto y prevenir daños:

            ul.lista-ul--color2.px-5
              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3  Recomendaciones para su conservación.
 
              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-0 Restricciones de uso (temperaturas, humedad, exposición al sol, etc.).


          div(titulo="Observaciones y requisitos de calidad")

            p.px-5 Incluye datos adicionales relacionados con los estándares que deben cumplirse y pruebas necesarias:

            ul.lista-ul--color2.px-5
              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3 Pruebas de resistencia o durabilidad.

              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-0 Normativas aplicables.

      .col-lg-4.d-lg-block.d-none
        figure
          img(src='@/assets/curso/tema5/img3.png', alt='', style="width: 400px").m-auto

    separador
    #t_5_2.titulo-segundo.color-acento-contenido
      h2 5.2  Usos de la ficha técnica de diseño

    .row.align-items-center
      .col-lg-1.d-lg-block.d-none
        figure
          img(src="@/assets/curso/tema5/img4.svg", alt="", style="width: 85px").m-auto
      .col-lg-11
        p La ficha técnica cumple diversas funciones clave en el ciclo de vida del producto. No solo sirve como guía para la producción, sino que también es un documento de soporte para los procesos de control de calidad y gestión comercial.

    .row.justify-content-center.mt-4
      .col-lg-12(data-aos="fade-down")
        .row.d-flex.align-items-center.bg-7(data-aos="fade-right")
          .col-lg-auto.pe-lg-0.mb-4.mb-xl-0.d-flex.d-none.d-lg-block
            figure.m-0.p-0.w-100.h-100.d-flex
              img(src='@/assets/curso/tema5/img5.png', alt='', class="w-100 h-100 object-fit-cover", style="margin-left:-10px")
          .col-lg.d-flex
            ul.lista-ul--color3.p-2
              li.d-flex.bg-17.p-3
                i.fa-solid.fa-circle-check
                p.mb-0  #[b Facilita la producción: ]  sirve como guía clara para el equipo de fabricación.


              li.d-flex.bg-17.p-2.mt-2
                i.fa-solid.fa-circle-check
                p.mb-0  #[b Garantiza calidad y uniformidad: ]  asegura que todas las piezas del producto sean fabricadas bajo los mismos estándares.


              li.d-flex.bg-17.p-2.mt-2
                i.fa-solid.fa-circle-check
                p.mb-0  #[b Optimiza costos y tiempos: ]  al estandarizar el proceso, se reducen errores y retrabajos.


              li.d-flex.bg-17.p-2.mt-2
                i.fa-solid.fa-circle-check
                p.mb-0  #[b Sirve para cotizaciones: ]  permite a proveedores conocer los requerimientos específicos del producto.


              li.d-flex.bg-17.p-2.mt-2
                i.fa-solid.fa-circle-check
                p.mb-0  #[b Documento de referencia: ]  es útil en auditorías, certificaciones y control de calidad.

              li.d-flex.bg-17.p-2.mt-2
                i.fa-solid.fa-circle-check
                p.mb-0  En la industria del calzado y marroquinería, la ficha técnica es fundamental para coordinar todos los procesos desde el diseño hasta la manufactura y comercialización del producto.


          



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
