<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Materiales e insumos para calzado

    .row.align-items-center
      .col-lg-4.d-lg-block.d-none
        figure
          img(src='@/assets/curso/tema3/img1.png', alt='', style="width: 400px").m-auto
      .col-lg-5
        p.p-4.bg-2 Los materiales e insumos son esenciales en la fabricación de calzado, ya que determinan su calidad, resistencia, durabilidad, comodidad y presentación.  Los materiales utilizados en el calzado se pueden clasificar en cueros, sintéticos, textiles y materiales para suelas. Cada tipo presenta características específicas que influyen en el diseño y funcionalidad del producto final.
      .col-lg-3.d-lg-block.d-none
        figure
          img(src='@/assets/curso/tema3/img2.png', alt='', style="width: 295px").m-auto

    separador
    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1  Cueros

    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/img3.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El cuero es un material natural obtenido a partir de la piel de animales como bovinos, ovinos, caprinos y porcinos. Se somete a un proceso de curtido que evita su descomposición y mejora su resistencia, durabilidad y flexibilidad. Se clasifica según el tipo de curtido, el acabado superficial y la procedencia animal.

    .titulo-tres.mt-4: h3 Clasificación del cuero según el tipo de curtido

    p El proceso de curtido define muchas de las propiedades del cuero, como su resistencia, color, textura y comportamiento frente a la humedad.

    TabsA.color-acento-botones.mb-5
      .tarjeta.clr-paleYellow.p-4(titulo="Cuero al cromo")
        .row.align-items-center
          .col-lg-7
            h4 Cuero al cromo
            p Cuero flexible y resistente, con color uniforme por el uso de sales de cromo y buena capacidad para el teñido. Se utiliza en calzado, tapicería y vestimenta.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema3/img4.png', alt='', style="width: 400px").m-auto

      .tarjeta.clr-paleYellow.p-4(titulo="Cuero vegetal")
        .row.align-items-center
          .col-lg-7
            h4 Cuero vegetal
            p Cuero más rígido, biodegradable y con tonos naturales. Utiliza taninos de origen vegetal. Se emplea en artículos artesanales y marroquinería.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema3/img5.png', alt='', style="width: 400px").m-auto

      .tarjeta.clr-paleYellow.p-4(titulo="Cuero vegetal")
        .row.align-items-center
          .col-lg-7
            h4 Cuero mixto
            p Combina curtido al cromo y vegetal, ofreciendo resistencia mecánica y menor impacto ambiental. Se utiliza en calzado de calidad media-alta.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema3/img6.png', alt='', style="width: 400px").m-auto

    .titulo-tres.mt-4: h3 Curtidos alternativos

    p Existen métodos de curtido que evitan el uso de metales pesados, ofreciendo opciones más sostenibles o adecuadas para usos específicos.

    .row.bg-4
      .col-12
        .p-5
          .tarjeta.tarjeta--azul.mb-6(style='background-color: white !important')
            .p-4.p-lg-5
              SlyderA(tipo="b")
                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Curtido con aluminio #[i (Wet White)]	

                    p Utiliza sales de aluminio en lugar de cromo. Genera un cuero más claro, con alta capacidad de teñido. Es más ecológico que el curtido al cromo, aunque menos resistente al agua. Se usa en cuero para guantes, ropa y calzado fino.      

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema3/img7.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Curtido con titanio

                    p   Emplea sales de titanio, evitando metales pesados. Más biodegradable y seguro para el ambiente. Produce un cuero suave y claro, pero con menor resistencia. Se usa en cuero para guantes, ropa y calzado fino.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema3/img8.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Curtido con aldehídos #[i (Wet White)	]

                    p  Utiliza glutaraldehído o formaldehído. Genera un cuero flexible y suave, aunque menos resistente. Algunas variantes eliminan el formaldehído por motivos ambientales. Se usa en interiores de automóviles y calzado. 

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema3/img9.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Curtido con sílice

                    p Usa compuestos de dióxido de silicio (SiO₂), sin metales. Es una técnica reciente y de bajo impacto ambiental. El cuero resultante es ligero y flexible. Se aplica en guantes, tapicería, marroquinería, ropa y calzado fino.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema3/img10.png', alt='')

    .titulo-tres.mt-4: h3 Clasificación del cuero según el acabado superficial

    p Los tratamientos aplicados a la superficie del cuero modifican su textura, apariencia y resistencia, y determinan su uso final.

    .row.bg-8
      .col-12 
        .p-5 
          .carousel-bg
            .row.justify-content-center.align-items-center.mb-5
              .col-lg-3.d-none.d-lg-block
                figure(data-aos="zoom-in")
                  img(src="@/assets/curso/tema3/img11.png", alt="alt", style="width: 305px").m-auto
              .col-lg-8
                SlyderF.custom.mb-5(columnas="col-lg-6 col-md-6 col-xl-6")
                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema3/img12.svg", alt='', style="width: 90px").m-auto
                    p.text-center
                      b Cuero plena flor
                    p.text-center.mb-0 Es la capa más superficial de la piel, sin lijado ni alteraciones. Ofrece la mejor calidad y máxima durabilidad. Se utiliza en calzado de lujo y tapicería.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema3/img13.svg", alt='', style="width: 90px").m-auto
                    p.text-center
                      b Cuero flor corregido
                    p.text-center.mb-0 Ha sido lijado para eliminar imperfecciones y recibe un acabado artificial. Presenta una textura más uniforme. Se usa en calzado industrial y tapicería.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema3/img14.svg", alt='', style="width: 90px").m-auto
                    p.text-center
                      b Gamuza o ante
                    p.text-center.mb-0 Presenta una textura suave y aterciopelada. Se obtiene del lado interno de la piel, usualmente de la capa media. Es común en calzado casual y de invierno.


                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema3/img15.svg", alt='', style="width: 90px").m-auto
                    p.text-center
                      b Nobuk
                    p.text-center.mb-0 Se produce lijando la capa superior del cuero. Tiene una textura similar a la gamuza, pero con mayor resistencia. Se usa en botas y calzado elegante.

                  .tarjeta.tarjeta--slyder.p-4
                    .row.justify-content-center.mb-3
                      .col-8
                        img(src="@/assets/curso/tema3/img16.svg", alt='', style="width: 90px").m-auto
                    p.text-center
                      b Cuero charol
                    p.text-center.mb-0 Tratado con barniz o plástico para un acabado brillante. Ofrece una apariencia llamativa y elegante. Se emplea en zapatos formales y de fiesta.

          .titulo-tres.mt-4: h3 Clasificación del cuero según la procedencia animal

          p La especie de origen del cuero influye en su textura, grosor, resistencia y aplicaciones específicas.

    TabsC.color-acento-botones
      .py-3.py-md-4.bg-9(titulo="Cuero vacuno")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/img17.png', style="width:480px").m-auto

          .col-md-6
            h4 Cuero vacuno
            p Cuero resistente, de grosor medio a grueso. Fácil de trabajar y ampliamente disponible. Se usa en calzado, marroquinería y tapicería.
      .py-3.py-md-4.bg-9(titulo="Cuero ovino")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/img18.png', style="width:480px").m-auto

          .col-md-6
            h4 Cuero ovino (cordero)
            p Suave, ligero y flexible, con textura fina. Se utiliza principalmente en vestimenta y forros de calzado.

      .py-3.py-md-4.bg-9(titulo="Cuero caprino")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/img19.png', style="width:480px").m-auto

          .col-md-6
            h4 Cuero caprino (cabra)
            p Fino, resistente y con textura granulada característica. Más compacto que el ovino. Se emplea en calzado de alta calidad y guantes.

      .py-3.py-md-4.bg-9(titulo="Cuero porcino")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/img20.png', style="width:480px").m-auto

          .col-md-6
            h4 Cuero porcino
            p Grueso, con poros visibles. Económico, aunque menos estético. Se usa en forros de calzado y guantes.


      .py-3.py-md-4.bg-9(titulo="Cuero exótico")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/img21.png', style="width:480px").m-auto

          .col-md-6
            h4 Cuero exótico (cocodrilo, serpiente, avestruz)
            p Presenta texturas únicas, patrones naturales llamativos y alto costo. Se utiliza en calzado de lujo y bolsos exclusivos.


    separador
    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2  Sintéticos

    .row.align-items-center
      .col-lg-1.d-none.d-lg-block
        figure
          img(src="@/assets/curso/tema3/img22.svg", alt="", style="width: 85px").m-auto
      .col-lg-11
        p Los materiales sintéticos son compuestos desarrollados artificialmente, principalmente a partir de derivados del petróleo y polímeros. Han sido diseñados para imitar o incluso mejorar las propiedades de los materiales naturales como el cuero y los textiles. En la industria del calzado, su uso es ampliamente extendido gracias a su bajo costo, alta versatilidad, resistencia a la humedad, durabilidad y facilidad de limpieza. Su clasificación puede hacerse según su composición química o según su estructura y aplicación específica en el calzado.

    TabsB.color-acento-botones.mt-4
      .py-4.py-md-5.bg-9(titulo="Poliuretano (PU)" :icono="require('@/assets/curso/tema3/img23.svg')")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/img24.png', style="width:480px").m-auto
          .col-md-6
            h4 Poliuretano (PU)	
            p Material ligero, flexible y resistente al agua y al desgaste. Imita la textura del cuero y es fácil de moldear y teñir. Se utiliza como sustituto del cuero en calzado, bolsos y chaquetas.

      .py-4.py-md-5.bg-9(titulo="Policloruro de vinilo (PVC)	" :icono="require('@/assets/curso/tema3/img23.svg')")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/img25.png', style="width:480px").m-auto
          .col-md-6
            h4 Policloruro de vinilo (PVC)	
            p Impermeable, económico y muy resistente, aunque con poca transpirabilidad. Puede ser rígido o flexible. Se emplea en botas de lluvia, calzado industrial, suelas y partes estructurales del calzado.

      .py-4.py-md-5.bg-9(titulo="Etilvinilacetato (EVA)" :icono="require('@/assets/curso/tema3/img23.svg')")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/img26.png', style="width:480px").m-auto
          .col-md-6
            h4 Etilvinilacetato (EVA)

            p Espumoso, muy ligero y flexible, con excelente amortiguación y resistencia a impactos. Se usa en plantillas, suelas de calzado deportivo y calzado casual.

      .py-4.py-md-5.bg-9(titulo="Nylon y poliéster	" :icono="require('@/assets/curso/tema3/img23.svg')")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/img27.png', style="width:480px").m-auto
          .col-md-6
            h4 Nylon y poliéster	

            p Alta resistencia a la tensión y al desgaste, se secan rápidamente y permiten transpiración. Se utilizan en tejidos para zapatillas deportivas, forros internos y refuerzos.

      .py-4.py-md-5.bg-9(titulo="Microfibra sintética" :icono="require('@/assets/curso/tema3/img23.svg')")
        .row.align-items-center
          .col-md-6.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/img28.png', style="width:480px").m-auto
          .col-md-6
            h4 Microfibra sintética	

            p Textura similar al cuero natural, duradera, ligera y transpirable. Se usa en calzado deportivo y de lujo como alternativa sin origen animal.

    .titulo-tres.mt-4: h3 Clasificación de los materiales sintéticos según su estructura y aplicación en el calzado

    .row.align-items-center
      .col-lg-1.d-none.d-lg-block
        figure
          img(src="@/assets/curso/tema3/img22.svg", alt="", style="width: 85px").m-auto
      .col-lg-11
        p En la industria del calzado, los materiales sintéticos han ganado protagonismo gracias a su versatilidad, resistencia y adaptabilidad a diferentes estilos y necesidades. Pero no todos los materiales sintéticos son iguales. Su estructura y la función que cumplen dentro del zapato marcan la diferencia. A continuación, se presenta cómo se clasifican según su forma y aplicación.

    .row.mt-4.align-items-center
      .col-lg-5.d-lg-block.d-none
        figure
          img(src='@/assets/curso/tema3/img29.png', alt='', style="width: 500px").m-auto
      .col-lg-7
        .row.align-items-center.bg-10.p-4
          .col-lg-5.d-lg-block.d-none
            figure
              img(src='@/assets/curso/tema3/img30.png', alt='', style="width: 270px").m-auto
          .col-lg-7
            p
              b ¿Sabías qué?

            p Lo invitamos a escuchar el siguiente Pódcast:
            TarjetaAudio.color-primario.mb-3.bg-11.p-4(
              texto="Descubre los materiales sintéticos en el calzado"
              :audio="require('@/assets/componentes/audios/audio-ej.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorTarjetaAudio")

    separador
    #t_3_3.titulo-segundo.color-acento-contenido
      h2 3.3 Textiles

    .row.align-items-center
      .col-lg-1.d-none.d-lg-block
        figure
          img(src="@/assets/curso/tema3/img31.svg", alt="", style="width: 85px").m-auto
      .col-lg-11
        p Los textiles utilizados en la fabricación de calzado son materiales formados por fibras entrelazadas, ya sean naturales o sintéticas. Se caracterizan por su flexibilidad, ligereza, transpirabilidad y adaptabilidad al movimiento. Son ideales para calzado deportivo, casual y de verano, ya que permiten una buena ventilación y comodidad durante su uso prolongado.

    .row.bg-12
      .col-12
        .p-5
          .row.align-items-center
            .col-lg-4.d-lg-block.d-none
              figure
                img(src='@/assets/curso/tema3/img32.png', alt='', style="width: 400px").m-auto
            .col-lg-5.p-4.bg-2
              figure
                img(src="@/assets/curso/tema3/img22.svg", alt="", style="width: 85px")
              p.mt-4 La clasificación de los textiles en el calzado se realiza principalmente en función del origen de las fibras con las que se elaboran: naturales o sintéticas.
            .col-lg-3.d-lg-block.d-none
              figure
                img(src='@/assets/curso/tema3/img33.png', alt='', style="width: 295px").m-auto

          .titulo-tres.mt-4: h3 Textiles de fibras naturales

          p Estas fibras provienen de fuentes vegetales o animales y se caracterizan por su suavidad, capacidad de absorción de humedad, transpirabilidad y confort. Son biodegradables y utilizadas comúnmente en calzado artesanal o de verano.

          .titulo-sexto.color-acento-contenido.mb-3.mt-4
            h5 Tabla 1.  
            span  Textiles de fibras naturales
          
          table
            thead
              tr(style="background-color: #E0EE33")
                th Niveles del lenguaje
                th Origen
                th Características
                th Usos en calzado
            tbody
              tr(style="background-color: #F6F6F6")
                td Algodón
                td Vegetal (planta de algodón)
                td Es una fibra suave al tacto, altamente absorbente, transpirable e hipoalergénica. Tiene buena resistencia al lavado y es cómoda para el contacto directo con la piel.
                td Se emplea en forros internos, plantillas y la parte superior de zapatillas ligeras o calzado casual.
              tr(style="background-color: #FFFFFF")
                td Lino
                td Vegetal (tallo de lino)
                td Es una fibra fuerte, fresca al tacto, ligera y biodegradable. Posee propiedades antibacterianas y excelente capacidad de absorción de humedad.
                td Se utiliza en alpargatas, sandalias y calzado de verano por su frescura y textura natural.
              tr(style="background-color: #F6F6F6")
                td Lana
                td Animal (ovejas, alpacas)
                td Actúa como aislante térmico natural. Es flexible, elástica, y tiene la capacidad de absorber la humedad sin perder la sensación de calor.
                td Se emplea en botas de invierno, pantuflas y zapatillas térmicas.
              tr(style="background-color: #FFFFFF")
                td Seda
                td Animal (gusano de seda)
                td Es una fibra suave, brillante y delicada. Tiene una alta resistencia a la tracción y una textura lujosa, aunque es costosa y requiere cuidados especiales.
                td Se utiliza en calzado de lujo y como detalle decorativo en diseños especiales.

    .titulo-tres.mt-4: h3 Textiles de fibras sintéticas

    p Estas fibras se producen mediante procesos químicos y polímeros derivados del petróleo. Suelen ser más resistentes, duraderas y fáciles de mantener que las fibras naturales, además de tener un costo menor.

    TabsA.color-acento-botones.mb-5
      .tarjeta.clr-paleYellow.p-4(titulo="Poliéster")
        .row.align-items-center
          .col-lg-7
            h4 Poliéster
            p Fibra ligera, resistente a la tracción y al desgaste. Se seca rápido, no absorbe humedad y conserva su forma. Se utiliza en zapatillas deportivas, forros interiores, tejidos transpirables y mallas técnicas.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema3/img34.png', alt='', style="width: 385px").m-auto

      .tarjeta.clr-paleYellow.p-4(titulo="Nylon")
        .row.align-items-center
          .col-lg-7
            h4 Nylon
            p Muy fuerte y resistente a la abrasión, estiramiento y deformación. Suave y duradera. Se emplea en tenis deportivos, refuerzos laterales, forros internos y mallas transpirables.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema3/img35.png', alt='', style="width: 385px").m-auto

      .tarjeta.clr-paleYellow.p-4(titulo="Elastano (<em>Lycra o Spandex</em>)")
        .row.align-items-center
          .col-lg-7
            h4 Elastano (#[i Lycra o Spandex])
            p Alta elasticidad, adaptable al movimiento y resistente al sudor y la deformación. Aporta ajuste al calzado. Se usa en zapatillas deportivas y tejidos que requieren ajuste, como botines deportivos o interiores elásticos.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema3/img36.png', alt='', style="width: 385px").m-auto

      .tarjeta.clr-paleYellow.p-4(titulo="Acrílico")
        .row.align-items-center
          .col-lg-7
            h4 Acrílico
            p Fibra sintética suave, con tacto similar a la lana. Resiste la exposición solar y es térmica. Se emplea en botas de invierno, tejidos térmicos y calzado para climas fríos
          .col-lg-5
            figure
              img(src='@/assets/curso/tema3/img37.png', alt='', style="width: 385px").m-auto

    .row.justify-content-center.align-items-center
      .col-lg-10
        .row.p-4.justify-content-center.align-items-center.bg-13
          .col-lg-3.d-lg-block.d-none
            figure
              img(src='@/assets/curso/tema3/img38.png', alt='', style="width: 180px").m-auto
          .col-lg-9
            p Los textiles en el calzado proporcionan confort, ventilación y versatilidad, desempeñando un papel fundamental en la creación de diseños innovadores y prácticos. La selección de fibras naturales o sintéticas dependerá del estilo del calzado, las exigencias del usuario y el entorno en el que se utilizará.

    .row.bg-14
      .col-12
        .p-5
          separador
          #t_3_4.titulo-segundo.color-acento-contenido
            h2 3.4 Suelas

          .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5
            .bloque-texto-g__img(
              :style="{'background-image': `url(${require('@/assets/curso/tema3/img39.png')})`}"
            )
            .bloque-texto-g__texto.p-4
              p.mb-0 Las suelas son una de las partes más importantes del calzado, ya que están en contacto directo con el suelo y cumplen funciones clave como proporcionar tracción, soporte, estabilidad y amortiguación. El material con el que se fabrican las suelas influye directamente en el rendimiento, la durabilidad, el peso y la comodidad del calzado. A continuación, se describen los materiales más utilizados en su fabricación, cada uno con sus características particulares y aplicaciones específicas.

          .titulo-tres.mt-4: h3 Materiales comunes utilizados en suelas

          p Esta clasificación incluye los materiales más empleados en la fabricación de suelas, abarcando tanto compuestos naturales como sintéticos. Cada material se selecciona en función del tipo de calzado, el entorno de uso y las necesidades del usuario.

    .row.bg-4
      .col-12
        .p-5
          .tarjeta.tarjeta--azul.mb-6(style='background-color: white !important')
            .p-4.p-lg-5
              SlyderA(tipo="b")
                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Caucho

                    p Es un material natural o sintético altamente resistente al desgaste y con excelentes propiedades antideslizantes. Tiene buena flexibilidad y amortiguación. Se comporta bien en condiciones húmedas o terrenos irregulares.    

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema3/img40.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b EVA (etilvinilacetato)	

                    p   Es una espuma ligera, flexible y con gran capacidad de absorción de impactos. Ofrece suavidad al andar y reduce la fatiga. Es resistente al agua y de bajo peso.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema3/img41.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Poliuretano

                    p  Es un material sintético muy duradero, elástico y resistente a la abrasión. Tiene una buena capacidad de amortiguación y conserva su forma con el uso prolongado. Puede ser rígido o expandido.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema3/img42.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b TR (termoplástico)	

                    p Es un material termoplástico con buena resistencia al desgaste, flexibilidad y apariencia estética. Permite diseños detallados y colores variados.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema3/img43.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b Cuero

                    p   Aunque es menos común hoy en día, el cuero aún se emplea en suelas por su apariencia sofisticada, transpirabilidad y resistencia moderada. Ofrece un andar natural y elegante.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema3/img44.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b PVC (cloruro de polivinilo)	

                    p  Es un plástico económico, impermeable y resistente a productos químicos. Tiene buena rigidez y durabilidad, aunque poca flexibilidad.

                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema3/img45.png', alt='')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-md-7.mb-4.mb-md-0.mt-lg-0.mt-4
                    p
                      b PVC expandido (expanso)	

                    p Es una versión espumada del PVC, más ligera y flexible. Tiene propiedades amortiguadoras y permite reducir el peso del calzado sin sacrificar volumen.
                    
                  .col-md-5
                    figure
                      img(src='@/assets/curso/tema3/img46.png', alt='')

</template>

<script>
export default {
  name: 'Tema3',
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
