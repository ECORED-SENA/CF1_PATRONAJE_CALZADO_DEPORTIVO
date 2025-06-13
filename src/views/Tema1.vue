<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Anatomía del calzado

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La anatomía del calzado se refiere a la estructura y las partes que componen un zapato, cada una con una función específica que influye en la comodidad, durabilidad y estética del producto. Comprender la anatomía del calzado es fundamental para su diseño y fabricación, ya que permite elegir materiales adecuados, definir procesos de ensamblaje y garantizar el ajuste correcto al pie del usuario.

    separador
    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1  Partes del calzado

    .row.align-items-center
      .col-lg-1.d-none.d-lg-block
        figure
          img(src="@/assets/curso/tema1/img2.svg", alt="", style="width: 85px").m-auto
      .col-lg-11
        p El calzado está compuesto por diversas partes que cumplen funciones específicas para brindar comodidad, soporte y diseño. Cada elemento tiene un propósito particular, ya sea proteger el pie, mejorar el ajuste o garantizar la durabilidad del zapato. A continuación, se describen las principales partes del calzado y su importancia en la estructura y funcionalidad del mismo.

    .row.justify-content-center.mt-2
      .col-lg-10 
        .row.bg-3.px-5
          .titulo-sexto.color-acento-contenido.mb-3.mt-4
            h5 Figura 1. 
            span Partes estructurales de un zapato
          .col-lg-7.mb-4
            figure
              img(src='@/assets/curso/tema1/img3.svg', alt='Diagrama estructural de un zapato desglosado en sus diferentes partes. Se identifican componentes como la lengüeta, la capellada, la cordonera, la entresuela, el cambrillón, la plantilla estructural, la suela, el tacón y la tapa, cada uno señalado con etiquetas descriptivas. ', style="width: 505px")
          .col-lg-5.d-lg-block.d-none 
            figure
              img(src='@/assets/curso/tema1/img4.png', alt='', style="width: 295px")


    .row.bg-4.mt-4
      .col-12
        .p-5
          .tarjeta.tarjeta--azul.mb-6(style='background-color: white !important')
            .p-4.p-lg-5
              SlyderA(tipo="b")
                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    ul.lista-ul--color
                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Cordonera
                          p.mb-0 Zona del calzado con ojales o perforaciones por donde pasan los cordones, permitiendo el ajuste al pie.

                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Lengüeta
                          p.mb-0 Ubicada debajo de los cordones, protege el pie del contacto con los ojales y ajustes.

                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Capellada
                          p.mb-0 Parte superior del calzado que cubre el pie y define su diseño. Puede estar hecha de cuero, tela o materiales sintéticos.


                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema1/img5.png')
                  

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    ul.lista-ul--color
                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Entresuela
                          p.mb-0 Capa intermedia entre la suela y la plantilla, diseñada para mejorar la amortiguación en ciertos tipos de calzado.

                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Plantilla estructural
                          p.mb-0 Pieza ubicada sobre la suela y debajo de la plantilla de confort, que aporta soporte, estabilidad y distribución del peso.

                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Cambrión
                          p.mb-0 Refuerzo en la parte media del calzado, entre la suela y la plantilla estructural, que mantiene la forma y resistencia del zapato.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema1/img6.png')
                  

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    ul.lista-ul--color
                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Tacón
                          p.mb-0 Parte trasera y elevada del calzado, fabricada con diversos materiales (madera, plástico, goma, etc.), que proporciona altura, soporte y estabilidad.

                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Tapa
                          p.mb-0 Parte inferior del tacón en contacto con el suelo, hecha de materiales resistentes a la fricción, como caucho o plástico, para evitar desgaste y mejorar la tracción.

                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Suela
                          p.mb-0 Parte inferior del calzado que entra en contacto con el suelo, fabricada con materiales resistentes para mayor durabilidad y tracción.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema1/img7.png')
                  

    .row.bg-5
      .col-12
        .p-5
          p El zapato se compone de diversas secciones que cumplen funciones específicas en términos de ajuste, comodidad y protección. A continuación, se presentan sus partes externas más relevantes:
          .tarjeta
            .imgCont.m-auto
              .row.justify-content-center.mb-4
                ImagenInfografica.color-acento-contenido.mb-5
                  template(v-slot:imagen)
                    figure
                      img(src='@/assets/curso/tema1/img8.svg', alt='Diagrama de las partes externas de un zapato, donde se destacan componentes como la cordonera, la capellada, la puntera y el talón. Cada parte está señalada con etiquetas explicativas. ', style='')

                  .tarjeta.color-acento-contenido.p-4(x="11%" y="37%" numero="+" style='border-radius: 10px; background-color: #F2F8AC')
                    h5.mb-3.text-center Puntera
                    p.mb-0.text-center Parte frontal del calzado que protege los dedos. Su diseño varía según el tipo de zapato, brindando diferentes niveles de protección, confort y estilo.

                  .tarjeta.color-acento-contenido.p-4(x="20%" y="24%" numero="+" style='border-radius: 10px; background-color: #F2F8AC')
                    h5.mb-3.text-center Cordonera
                    p.mb-0.text-center Zona del calzado con ojales o perforaciones por donde pasan los cordones, permitiendo el ajuste al pie.

                  .tarjeta.color-acento-contenido.p-4(x="89%" y="58%" numero="+" style='border-radius: 10px; background-color: #F2F8AC')
                    h5.mb-3.text-center Talón
                    p.mb-0.text-center Parte trasera del calzado que envuelve y protege la zona del talón del pie, proporcionando soporte y estabilidad.

          p.mt-4 Los zapatos pueden presentar variaciones en su diseño, especialmente en la capellada, lo que influye en su estética y funcionalidad. A continuación, se describen algunas partes clave en su construcción:


    .row.bg-4
      .col-12
        .p-5
          .tarjeta.tarjeta--azul.mb-6(style='background-color: white !important')
            .p-4.p-lg-5
              SlyderA(tipo="b")
                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    ul.lista-ul--color
                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Capellada
                          p.mb-0 Corresponde a la parte superior del zapato que cubre el empeine y el dorso del pie. Su diseño puede variar según el tipo de calzado.

                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Bigotera
                          p.mb-0 Pieza de refuerzo ubicada en el empeine que proporciona soporte, mejora el ajuste y aporta diseño.

                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Chapeta
                          p.mb-0 Pieza ubicada en la parte superior del empeine, generalmente en la zona de la cordonera o lengüeta, que refuerza y mejora el ajuste.


                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema1/img9.png', alt='Ilustración comparativa de dos diseños de capellada en calzado. El primer diseño incluye elementos como la cordonera, la capellada y la bigotera, mientras que el segundo diseño resalta la capellada y la chapeta. ')
                  

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    ul.lista-ul--color
                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Capellada
                          p.mb-0 Parte superior de la bota que cubre el pie y define su diseño. Puede estar hecha de cuero, tela o materiales sintéticos.

                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Caña
                          p.mb-0 Parte de la bota que cubre la pierna, brindando protección, soporte y diseño. Su altura varía según el tipo de bota.

                      li.d-flex
                        i.fa-solid.fa-circle-check
                        .contenido
                          p.mb-0 
                            b Talón
                          p.mb-0 Parte trasera de la bota que envuelve y protege la zona del talón del pie, proporcionando soporte y estabilidad.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema1/img10.svg', alt='Diagrama de una bota que identifica sus partes principales. Se destacan la caña, ubicada en la parte superior; el talón, en la parte trasera inferior; y la capellada, en la zona frontal del calzado. ')
                  
    .titulo-tres.mt-4: h3 Refuerzos y elementos de soporte

    p Algunas partes del calzado mejoran la estabilidad y durabilidad:

    .bg_img_01
      .row.justify-content-center.mb-5
        .col-lg-4.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema1/img11.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Contrafuerte
            p.text-center.mb-0 Refuerzo en la parte trasera que proporciona estabilidad al talón.
        .col-lg-4.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema1/img12.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Puntera
            p.text-center.mb-0 Refuerzo en la parte frontal que protege los dedos, especialmente en zapatos de seguridad.
        .col-lg-4.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema1/img13.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Ojetes o pasadores
            p.text-center.mb-0 Aberturas para los cordones, que permiten ajustar el calzado al pie.

    p.mt-4 Estas partes pueden variar dependiendo del tipo de calzado (formal, deportivo, industrial, etc.).



</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
