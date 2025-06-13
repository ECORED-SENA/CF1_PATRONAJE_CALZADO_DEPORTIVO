<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Tipologías de calzado: características y usos

    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El calzado es un elemento esencial en la vestimenta, diseñado para proteger los pies y proporcionar comodidad, estilo y funcionalidad según la ocasión y la actividad. Existen diversas tipologías de calzado, cada una con características y usos específicos que responden a necesidades particulares, desde el ámbito deportivo hasta el formal o industrial.

    separador
    #t_2_1.titulo-segundo.color-acento-contenido
      h2 2.1  Clasificación del calzado según su uso     

    p El calzado se clasifica principalmente según la función y el entorno en el que se usa. Algunas de las principales categorías son:

    .row.bg-4
      .col-12
        .p-5
          .tarjeta.tarjeta--azul.mb-6(style='background-color: white !important')
            .p-4.p-lg-5
              SlyderA(tipo="b")
                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Formal

                    p Diseñado para eventos elegantes, trabajo de oficina o reuniones formales. Ejemplos: zapatos Oxford, Derby, mocasines y tacones de vestir.        

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema2/img2.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Deportivo

                    p Creado para brindar soporte y amortiguación en actividades físicas. Ejemplos: tenis para correr, calzado de fútbol, zapatillas de baloncesto.     

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema2/img3.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Casual

                    p Ideal para el día a día, combinando comodidad y estilo. Ejemplos: zapatillas urbanas, baletas, sandalias, botines.     

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema2/img4.png', alt='')


                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Industrial

                    p Diseñado para entornos de trabajo que requieren protección especial. Ejemplos: botas de seguridad con punta de acero, calzado dieléctrico, botas antideslizantes.       

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema2/img5.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Ortopédico

                    p Especialmente diseñado para corregir o aliviar problemas en los pies. Ejemplos: zapatos con plantillas anatómicas, calzado con soporte para el arco.       

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema2/img6.png', alt='')

    separador
    #t_2_2.titulo-segundo.color-acento-contenido
      h2 2.2  Diferencias entre modelos de calzado

    p Cada modelo de calzado se distingue por su diseño, estructura y materiales, los cuales influyen en su funcionalidad, comodidad y uso. A continuación, se presentan las diferencias clave entre los distintos tipos de calzado.

    .row.align-items-center
      .col-lg-3.d-lg-block.d-none
        figure
          img(src='@/assets/curso/tema2/img7.png', alt='', style="width: 400px").m-auto

      .col-lg-9
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg-7")
          .row(titulo="Forma y estructura")
            .col-12.mb-4.mb-md-0

              p.px-5 El Oxford tiene una estructura cerrada con cordones internos, mientras que el Derby es más flexible con cordones abiertos. El mocasín es un zapato sin cordones, fácil de poner y quitar. El calzado con velcro es ideal para niños o personas con movilidad reducida, mientras que el elástico permite un ajuste sin sujetadores adicionales.

          div(titulo="Materiales")
            p.px-5 El calzado varía en materiales según su función y uso. El cuero es duradero, transpirable y elegante. Los materiales sintéticos son ligeros, económicos y fáciles de limpiar, además de ofrecer resistencia al agua. Las mallas y lonas son cómodas y transpirables.

          div(titulo="Función y comodidad	")
            p.px-5 Los tenis están diseñados para absorber impactos, mientras que los zapatos formales priorizan la estética y la elegancia.

    .row.align-items-center.mt-3
      .col-lg-9
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg-7")
          .row(titulo="Suela y amortiguación")
            .col-12.mb-4.mb-md-0

              ul.lista-ul--color2.px-5
                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-3  #[b Plana vs. Con tacón:] los zapatos planos brindan estabilidad y comodidad, mientras que los de tacón realzan la postura y la elegancia. 

                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-3  #[b Goma vs. Cuero:] las suelas de goma ofrecen mayor tracción y amortiguación, mientras que las de cuero son más rígidas y elegantes, pero menos antideslizantes. 

                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-0 #[b Flexible vs. Rígida:] los tenis deportivos tienen suelas flexibles para amortiguar impactos, mientras que las botas de seguridad tienen suelas rígidas para mayor protección.

          div(titulo="Protección y soporte")
            ul.lista-ul--color2.px-5
              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3  #[b Bota vs. Zapato bajo:] Las botas cubren el tobillo o la pierna, brindando mayor protección, mientras que los zapatos bajos permiten mayor movilidad. 

              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-0 #[b Punta de acero vs. Punta reforzada:] En el calzado industrial, las botas con punta de acero protegen contra impactos fuertes, mientras que las de punta reforzada ofrecen protección media sin el peso del acero.


          div(titulo="Estilo y uso")
            ul.lista-ul--color2.px-5
              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3 #[b Casual vs. Formal:] los zapatos casuales priorizan la comodidad y versatilidad, mientras que los formales buscan elegancia y sofisticación. 

              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-0 #[b Deportivo vs. Urbano:]  los tenis deportivos están diseñados para alto rendimiento, mientras que los urbanos combinan estilo y comodidad para el día a día.


      .col-lg-3.d-lg-block.d-none
        figure
          img(src='@/assets/curso/tema2/img8.png', alt='', style="width: 400px").m-auto

    p.mt-4 Cada modelo de calzado se adapta a diferentes necesidades, estilos y actividades, por lo que conocer sus diferencias ayuda a elegir el más adecuado para cada ocasión.

    separador
    #t_2_3.titulo-segundo.color-acento-contenido
      h2 2.3 Función de cada parte en el diseño y #[i confort]

    p Cada componente del calzado tiene una función clave en la estructura y comodidad del zapato:

    .bg_img_01.mt-4
      .row.justify-content-center.mb-5
        .col-lg-3.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema2/img9.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Diseño y estética
            p.text-center.mb-0 La capellada define la apariencia visual del calzado.
        .col-lg-3.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema2/img10.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Soporte y estabilidad
            p.text-center.mb-0 La suela y la entresuela proporcionan equilibrio y amortiguación.
        .col-lg-3.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema2/img11.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Protección
            p.text-center.mb-0 Elementos como la plantilla estructural, puntera y contrafuerte evitan lesiones y refuerzan el calzado.

        .col-lg-3.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema2/img12.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Ajuste y comodidad
            p.text-center.mb-0 El forro, la plantilla y la lengüeta reducen la fricción y mejoran la experiencia del usuario.

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
