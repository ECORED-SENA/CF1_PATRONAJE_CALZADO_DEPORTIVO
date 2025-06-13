<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Fases del proceso productivo de calzado

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/img1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La fabricación de calzado es un proceso que involucra varias etapas, desde el diseño hasta el acabado final. Cada fase es crucial para garantizar un producto de calidad, cómodo y funcional. A continuación, se explican las principales etapas de la producción de calzado.

    .row.bg-15
      .col-12
        .p-5
          separador
          #t_4_1.titulo-segundo.color-acento-contenido
            h2 4.1  Diseño y desarrollo del producto

          p En esta primera fase del proceso se define la estética, funcionalidad y estructura del calzado. Este proceso incluye:

          .carousel-bg
            .row.justify-content-center.align-items-center.mb-5
              .col-lg-3.d-none.d-lg-block
                figure(data-aos="zoom-in")
                  img(src="@/assets/curso/tema4/img2.png", alt="alt", style="width: 295px").m-auto
              .col-lg-8
                SlyderF.custom.mb-5(columnas="col-lg-6 col-md-6 col-xl-6")
                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema4/img3.svg", alt='', style="width: 90px").m-auto
                    p.text-center
                      b Investigación de tendencias
                    p.text-center.mb-0 Se analizan modas, colores, materiales y necesidades del mercado.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema4/img4.svg", alt='', style="width: 90px").m-auto
                    p.text-center
                      b Bocetos
                    p.text-center.mb-0 Se crean dibujos técnicos del producto a desarrollar.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema4/img5.svg", alt='', style="width: 90px").m-auto
                    p.text-center
                      b Elaboración de patrones
                    p.text-center.mb-0 Se generan moldes en papel o software especializado, que servirán como base para el corte de materiales.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema4/img6.svg", alt='', style="width: 90px").m-auto
                    p.text-center
                      b Desarrollo de prototipos
                    p.text-center.mb-0 Se elaboran prototipos para verificar que el calzado cumple con las especificaciones técnicas del producto y se ajustas de ser necesario.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema4/img7.svg", alt='', style="width: 90px").m-auto
                    p.text-center
                      b Pruebas de ajuste y ergonomía
                    p.text-center.mb-0 Se desarrollan muestras físicas para verificar la comodidad y el ajuste antes de la producción masiva.

          separador
          #t_4_2.titulo-segundo.color-acento-contenido
            h2 4.2 Corte de materiales

          p El proceso de corte es la primera etapa en la fabricación del calzado, donde se obtienen las piezas que conformarán la parte superior (capellada) y otras secciones.

          .titulo-tres.mt-4: h3 Materiales más utilizados en el corte

    .row.bg-4
      .col-12
        .p-5
          .tarjeta.tarjeta--azul.mb-6(style='background-color: white !important')
            .p-4.p-lg-5
              SlyderA(tipo="b")
                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Cuero natural

                    p Material flexible, resistente y transpirable. Brinda durabilidad y un acabado elegante, común en calzado formal y de alta calidad.  

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema4/img8.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Sintéticos (PU, PVC)

                    p   Alternativas económicas y ecológicas al cuero. Son ligeros, fáciles de limpiar y resistentes al agua, ideales para calzado casual e industrial.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema4/img9.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Textiles (lona, malla, microfibra)

                    p  Materiales transpirables y ligeros, empleados en calzado deportivo y casual. Ofrecen comodidad y adaptabilidad al pie.
                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema4/img10.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Espumas y refuerzos

                    p Proporcionan amortiguación, comodidad y estructura al calzado. Se utilizan en plantillas, suelas y refuerzos internos para mejorar la ergonomía.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema4/img1.png', alt='')


    .titulo-tres.mt-4: h3 Métodos de corte

    p Existen diversas técnicas para el corte de materiales en la fabricación de calzado. Cada método ofrece ventajas según el tipo de material y el nivel de precisión requerido.

    TabsC.color-acento-botones
      .py-3.py-md-4.bg-9(titulo="Manual")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema4/img12.png', style="width:480px").m-auto

          .col-md-6
            h4 Manual
            p Uso de tijeras o cuchillas para cortar piezas siguiendo plantillas de papel o cartón.
      .py-3.py-md-4.bg-9(titulo="Troquelado")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema4/img13.png', style="width:480px").m-auto

          .col-md-6
            h4 Troquelado
            p Empleo de moldes de acero afilados (troqueles) que, mediante presión, cortan las piezas con alta precisión.

      .py-3.py-md-4.bg-9(titulo="Corte láser")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema4/img14.png', style="width:480px").m-auto

          .col-md-6
            h4 Corte láser
            p Tecnología de precisión utilizada en materiales como cuero, sintéticos y textiles.

      .py-3.py-md-4.bg-9(titulo="Cuero porcino")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema4/img15.png', style="width:480px").m-auto

          .col-md-6
            h4 Corte automatizado
            p Corte programado con cuchilla oscilante que ofrece mayor precisión.


    separador
    #t_4_3.titulo-segundo.color-acento-contenido
      h2 4.3 Desbaste

    p El desbaste es una etapa clave en la fabricación del calzado, ya que prepara las piezas para su ensamblaje y pegado. Este proceso consiste en rebajar, lijar o desgastar los bordes del cuero para mejorar la adherencia del pegamento y garantizar una unión firme entre las piezas.

    .row.align-items-center.mt-3
      .col-lg-8
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg-7")
          .row(titulo="Objetivos")
            .col-12.mb-4.mb-md-0

              ul.lista-ul--color3.px-5
                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-3  Eliminar impurezas en los bordes del material. 

                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-3  Reducir el grosor en zonas específicas para facilitar el ensamblaje. 


                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-0 Mejorar la adhesión del pegamento o adhesivos. 

                li.d-flex
                  i.fa-solid.fa-circle-check
                  .contenido
                    p.mb-0 Asegurar una mejor calidad estética del producto final.


          div(titulo="Proceso")
            ul.lista-ul--color3.px-5
              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-3  #[b Selección de piezas:]  Identificación de las áreas a desbastar, como la suela, el corte o las uniones.

              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-0 #[b Control de presión y grosor:]  Aplicación precisa de la presión para evitar daños en el material.


              li.d-flex
                i.fa-solid.fa-circle-check
                .contenido
                  p.mb-0 #[b Limpieza:]  Eliminación de residuos generados antes de continuar con la fabricación.


          div(titulo="Herramientas utilizadas")
            p.px-5 Uso de maquinaria desbastadora y cuchillas para lograr un acabado preciso.

      .col-lg-4.d-lg-block.d-none
        figure
          img(src='@/assets/curso/tema4/gif3.gif', alt='', style="width: 400px").m-auto

    .row.bg-16
      .col-12
        .p-5 
          separador
          #t_4_4.titulo-segundo.color-acento-contenido
            h2 4.4  Armado del calzado

          p El armado es el proceso en el que se ensamblan las distintas partes de la capellada antes de la costura. Esta etapa es fundamental para garantizar la estabilidad y durabilidad del calzado.

          .row.justify-content-center.align-items-center
            .col-lg-10
              .row.p-4.justify-content-center.align-items-center.bg-13
                .col-lg-3.d-lg-block.d-none
                  figure
                    img(src='@/assets/curso/tema4/img17.png', alt='', style="width: 300px").m-auto
                .col-lg-9
                  .row.align-items-center.bg-17.p-2
                    .col-lg-2.d-none.d-lg-block
                      figure
                        img(src="@/assets/curso/tema4/img18.svg", alt="", style="width: 76px").m-auto
                    .col-lg-10
                      p.mb-0 
                        b Pegado provisional
                      p Se usa adhesivo temporal para posicionar las piezas antes de coserlas.

                  .row.align-items-center.bg-17.p-2.mt-2
                    .col-lg-2.d-none.d-lg-block
                      figure
                        img(src="@/assets/curso/tema4/img19.svg", alt="", style="width: 76px").m-auto
                    .col-lg-10
                      p.mb-0 
                        b Unión de refuerzos y forros

                      p Se agregan materiales internos para dar estructura y mejorar la durabilidad.

    separador
    #t_4_5.titulo-segundo.color-acento-contenido
      h2 4.5   Costura del calzado

    p La costura es una etapa esencial en la fabricación del calzado, ya que une las piezas de la capellada, proporcionando forma y resistencia. Existen diferentes tipos de costura según el material y la funcionalidad requerida.

    .bg_img_01
      .row.justify-content-center.mb-5
        .col-lg-4.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema4/img20.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Costura simple

            p.text-center.mb-0 Unión de dos piezas con una línea recta de puntadas, utilizada en estructuras básicas.
        .col-lg-4.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema4/img21.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Costura doble (doble pespunte)

            p.text-center.mb-0 Refuerzo adicional para unir materiales gruesos, mejorando la resistencia y durabilidad.
        .col-lg-4.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-3
              figure
                img(src="@/assets/curso/tema4/img22.svg", alt="alt", style="width: 92px").m-auto
            h4.text-center Costura en zigzag

            p.text-center.mb-0 Aporta mayor elasticidad en materiales sintéticos y textiles, evitando rupturas por tensión.

    .titulo-tres.mt-4: h3 Máquinas de coser utilizadas

    p En la fabricación del calzado se emplean diferentes tipos de máquinas de coser, cada una diseñada para cumplir funciones específicas según la estructura y material del calzado.

    TabsA.color-acento-botones.mb-5
      .tarjeta.clr-paleYellow.p-4(titulo="Máquinas de codo")
        .row.align-items-center
          .col-lg-7
            h4 Máquinas de codo
            p Facilitan la costura en zonas curvas del calzado, permitiendo un mejor ajuste en áreas difíciles de alcanzar.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema4/img24.png', alt='', style="width: 400px").m-auto

      .tarjeta.clr-paleYellow.p-4(titulo="Máquinas de columna o poste")
        .row.align-items-center
          .col-lg-7
            h4 Máquinas de columna o poste
            p Brindan mayor maniobrabilidad en materiales rígidos, lo que facilita el ensamblaje en calzado estructurado.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema4/img23.png', alt='', style="width: 400px").m-auto

      .tarjeta.clr-paleYellow.p-4(titulo="Máquinas de doble aguja")
        .row.align-items-center
          .col-lg-7
            h4 Máquinas de doble aguja
            p Generan costuras reforzadas, especialmente utilizadas en calzado industrial y deportivo para mayor resistencia.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema4/img25.png', alt='', style="width: 400px").m-auto
              figcaption.mt-2 Imágen tomada de: máquina de poste dos agujas. (s. f.)

      .tarjeta.clr-paleYellow.p-4(titulo="Máquina de costura sobrehilada")
        .row.align-items-center
          .col-lg-7
            h4 Máquina de costura sobrehilada
            p Realiza costuras en zigzag o sobrehilado para unir la capellada con la plantilla o reforzar los bordes del corte mediante la inserción de un cordón o pita.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema4/img26.png', alt='', style="width: 400px").m-auto
              figcaption.mt-2 Imágen tomada de: máquina sobrehiladora. (s. f.). 

    separador
    #t_4_6.titulo-segundo.color-acento-contenido
      h2 4.6  Montaje del calzado

    p El montaje es la fase en la que la capellada se ajusta a la horma para darle la forma final al zapato y unirla a la suela. Existen distintos métodos de montaje según el tipo de calzado y el nivel de flexibilidad requerido.

    .row.bg-4
      .col-12
        .p-5
          .tarjeta.tarjeta--azul.mb-6(style='background-color: white !important')
            .p-4.p-lg-5
              SlyderA(tipo="b")
                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Montaje #[i Strobel]

                    p Utilizado en calzado deportivo, consiste en coser la capellada a una plantilla flexible antes de añadir la suela, proporcionando mayor comodidad y flexibilidad.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema4/img27.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Montaje #[i String]

                    p  Variante del Strobel en la que la capellada se une a la plantilla mediante un cordón pasado a lo largo de su contorno, lo que otorga mayor resistencia y flexibilidad.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema4/img28.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Montaje con pegado

                    p  Se adhiere la capellada a la suela utilizando pegamento de alta resistencia, asegurando una fijación firme y duradera.
                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema4/img29.png', alt='')


    .titulo-tres.mt-4: h3 Proceso de montaje paso a paso

    p El montaje del calzado sigue una serie de etapas que garantizan la correcta fijación de la capellada a la suela, asegurando la durabilidad y comodidad del producto.

    .row.mt-4
      .col-lg-8
        TabsA.color-acento-botones.mb-5
          .tarjeta.clr-paleYellow.p-4(titulo="Colocación de la horma")
            .row.align-items-center
              .col-lg-12
                h4 Colocación de la horma
                p La capellada se ajusta a una horma con la forma deseada para darle estructura.


          .tarjeta.clr-paleYellow.p-4(titulo="Tensado y fijación")
            .row.align-items-center
              .col-lg-12
                h4 Tensado y fijación	

                p Se estiran las piezas para eliminar arrugas y se fijan con clavos o adhesivo.


          .tarjeta.clr-paleYellow.p-4(titulo="Unión de la suela")
            .row.align-items-center
              .col-lg-12
                h4 Unión de la suela	

                p La suela se adhiere mediante pegado, costura o vulcanización, dependiendo del tipo de calzado.


          .tarjeta.clr-paleYellow.p-4(titulo="Prensado y moldeado final")
            .row.align-items-center
              .col-lg-12
                h4 Prensado y moldeado final	

                p Se aplica calor y presión para mejorar la adherencia y dar el acabado final.


      .col-lg-4.d-lg-block.d-none
        figure
          img(src='@/assets/curso/tema4/img30.png', alt='', style="width: 400px").m-auto

    separador
    #t_4_7.titulo-segundo.color-acento-contenido
      h2 4.7  Acabado y control de calidad

    p Esta fase final garantiza que el calzado cumpla con los estándares de calidad y tenga un acabado estético adecuado antes de su distribución.

    .row.justify-content-center.align-items-center.bg-1.p-4
      .col-lg-4.d-lg-block.d-none
        figure
          img(src='@/assets/curso/tema4/gif4.gif', alt='', style="width: 300px").m-auto
      .col-lg-8
        .row.align-items-center.bg-17
          ul.lista-ul--color.p-2
            li.d-flex
              i.fa-solid.fa-circle-check
              p.mb-0  #[b Pulido y limpieza.]  Eliminación de restos de pegamento e imperfecciones para mejorar la presentación. 


        .row.align-items-center.bg-17.mt-2
          ul.lista-ul--color.p-2
            li.d-flex
              i.fa-solid.fa-circle-check
              p.mb-0  #[b Verificación de costuras y adherencia.]   Inspección de las uniones entre suela y capellada para evitar desprendimientos. 

        .row.align-items-center.bg-17.mt-2
          ul.lista-ul--color.p-2
            li.d-flex
              i.fa-solid.fa-circle-check
              p.mb-0  #[b Pruebas de flexión y resistencia.]   Evaluación de la durabilidad del calzado simulando su uso real. 



        .row.align-items-center.bg-17.mt-2
          ul.lista-ul--color.p-2
            li.d-flex
              i.fa-solid.fa-circle-check
              p.mb-0  #[b Empaque y etiquetado. ]   Colocación de etiquetas y empaques antes del almacenamiento y distribución.



</template>

<script>
export default {
  name: 'Tema4',
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
