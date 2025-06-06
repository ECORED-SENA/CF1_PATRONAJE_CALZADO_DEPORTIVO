<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.align-items-center
      .col-lg-1.d-none.d-lg-block
        figure
          img(src="@/assets/curso/intro/img1.png", alt="", style="width: 84px").m-auto
      .col-lg-11
        p El patronaje de calzado es un proceso fundamental en la fabricación de zapatos, ya que permite transformar un diseño en patrones precisos que servirán de base para su producción. Comprender los aspectos técnicos del patronaje es esencial para garantizar la calidad, comodidad y funcionalidad del calzado, asegurando un ajuste adecuado al pie y optimizando el proceso de fabricación.

    .row.align-items-center.justify-content-center
      .col-lg-9
        .row.justify-content-center
          .col-lg-5.d-none.d-lg-block
            figure
              img(src='@/assets/curso/intro/img2.png', alt='', style="width: 400px").m-auto
          .col-lg-7 
            p.p-4.bg-1 Este componente formativo proporciona conocimientos detallados sobre la estructura del calzado, los tipos de patrones, los materiales utilizados y las normas de diseño. Además, aborda la relación entre la anatomía del pie y la ergonomía del calzado, aspectos clave para lograr productos que se adapten a las necesidades del usuario. 

          p.mt-2.bg-2.p-4 También se estudian los sistemas de medidas y las adaptaciones requeridas para garantizar un correcto ajuste. A lo largo del componente, se explorarán las distintas fases de la fabricación del calzado, desde el diseño y corte hasta el ensamblaje y acabado final. Esto permitirá a los aprendices desarrollar competencias en la creación y modelado de patrones, comprendiendo cada etapa del proceso productivo y aplicando criterios técnicos para la elaboración de calzado de calidad.

      .col-lg-3.d-lg-block.d-none
        figure
          img(src='@/assets/curso/intro/gif1.gif', alt='', style="width: 295px").m-auto

</template>

<script>
export default {
  name: 'Introduccion',
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
