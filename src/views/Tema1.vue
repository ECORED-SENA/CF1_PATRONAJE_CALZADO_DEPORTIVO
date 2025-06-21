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
              img(src='@/assets/curso/tema1/img3.svg', alt='Diagrama estructural de un zapato desglosado en sus diferentes partes. Se identifican componentes como la lengüeta, la capellada, la cordonera, la entresuela, el cambrillón, la plantilla estructural, la suela, el tacón y la tapa, cada uno señalado con etiquetas descriptivas. ', style="width: 610px")
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
                    h5.mb-3.text-center Puntera reforzada	
                    p.mb-0.text-center Zona frontal robusta que protege los dedos ante impactos o roces, manteniendo la flexibilidad del calzado.

                  .tarjeta.color-acento-contenido.p-4(x="30%" y="22%" numero="+" style='border-radius: 10px; background-color: #F2F8AC')
                    h5.mb-3.text-center Ojaletes o pasadores	
                    p.mb-0.text-center Aberturas en el empeine por donde pasan los cordones, permitiendo un ajuste seguro y adaptado a cada deportista.

                  .tarjeta.color-acento-contenido.p-4(x="89%" y="47%" numero="+" style='border-radius: 10px; background-color: #F2F8AC')
                    h5.mb-3.text-center Contrafuerte	
                    p.mb-0.text-center Refuerzo en la parte trasera que proporciona estabilidad y sujeta el talón, previniendo torceduras y mejorando el control.


    separador
    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2  Función de cada parte en el diseño y confort

    p Cada componente del calzado tiene una función clave en la estructura y comodidad del zapato:
                  

    .bg_img_01
      .row.justify-content-center.mb-5
        .col-lg-3.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema1/img15.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Diseño y estética
            p.text-center.mb-0 La capellada define la apariencia visual del calzado.
        .col-lg-3.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema1/img15.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Soporte y estabilidad
            p.text-center.mb-0 La suela y la entresuela proporcionan equilibrio y amortiguación.
        .col-lg-3.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema1/img16.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Protección
            p.text-center.mb-0 Elementos como la plantilla estructural, puntera y contrafuerte evitan lesiones y refuerzan el calzado.

        .col-lg-3.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema1/img17.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Ajuste y comodidad
            p.text-center.mb-0 El forro, la plantilla y la lengüeta reducen la fricción y mejoran la experiencia del usuario.





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
