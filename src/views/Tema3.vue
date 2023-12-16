<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Planeación del área de trazo y corte
    
    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-lg-10.mb-4
        .bloque-texto-g.color-sky-blue.p-3.p-sm-4.p-md-5.mb-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema3/img01.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 Saber aprovechar de la manera adecuada los recursos de que se dispone en el área de trazo y corte es importante para poder cumplir cabalmente con los propósitos y proyectos. Se hace referencia a un área en metros cuadrados (m&sup2;), a unas dimensiones de las mesas, al número de personas, a los horarios de trabajo, a las máquinas, a las herramientas y a las materias primas e insumos, como se muestra a continuación.

    .row.justify-content-center.mb-4(data-aos="flip-up")
      .titulo-sexto.color-acento-contenido
        p.mb-0 Corte industrial
      .col-lg-10.mb-4
        .bloque-texto-g.color-sky-blue.p-3.p-sm-4.p-md-5.mb-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema3/img02.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Es importante conocer todas las órdenes de corte con sus características: referencia, cantidad, tela, prioridades, cliente, fechas presupuestadas, eso le permite al supervisor dimensionar los recursos necesarios para cumplir con sus propósitos y determinar la necesidad de conseguir más recursos, o en la eventualidad que después de hacer los cálculos necesarios encuentre capacidad ociosa, y pueda ofrecer el servicio a terceros.

        
    .row.justify-content-center.mb-4(data-aos="zoom-in")
      .col-lg-8.mb-4.mb-lg-0.p-0
        .row.align-items-center.mb-4
          .col-lg-3.mb-4.mb-lg-0.p-0
            br
            img(src='@/assets/curso/tema3/img03.png' alt="Imagen decorativa")
          .col-lg-1.mb-4.mb-lg-0.p-0
            br
            img(src='@/assets/curso/tema3/img04.svg' alt="Imagen decorativa")
          .col-lg-8.mb-4.mb-lg-0.p-0
            img(src='@/assets/curso/tema3/img05.svg' alt="Imagen decorativa")
    
    p.mb-4(data-aos="fade-right") Determinar los estándares de fabricación para cada proceso es una actividad compleja, debido a que es diferente a la acción de determinar estándares de operaciones de ensamble, las cuales permiten calcular de manera unitaria los tiempos de fabricación, utilizando formatos diseñados para ese fin.

    .tarjeta.color-light-gray.p-4
      .row.justify-content-center.mb-4
        .col-lg-10.mb-4.mb-lg-0.p-0
          .row.align-items-center.mb-4
            .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right")
              .h4 Determinar la capacidad instalada
              p La capacidad instalada en una organización, unidad productiva o sección es el potencial o volumen máximo de cantidades de productos y/o servicios que se pueden elaborar o fabricar en un período de tiempo determinado, con un número de personas disponibles y con recursos complementarios que sean coherentes con esa línea de producción como insumos, máquinas, herramientas, esta información se puede definir de la siguiente manera:
            .col-lg-5.mb-4.mb-lg-0(data-aos="fade-left")
              img(src='@/assets/curso/tema3/img06.png' alt="Imagen decorativa")
          
          .h4(data-aos="fade-right") Capacidad instalada de área
          p.mb-4(data-aos="fade-left") Uno de los elementos a tener en cuenta para calcular la capacidad de unidades que se pueden cortar es conocer el área que se dispone para realizar las actividades de trazo y corte. Dimensionar esa área ayuda a distribuir los puestos de trabajo.
          p.mb-4(data-aos="fade-right") Para establecer esta capacidad de producción por m&sup2; es importante:

          .tarjeta.tarjeta--azul.p-4.mb-5(data-aos="zoom-in")
            SlyderA(tipo="b")
              .row.justify-content-center
                .col-md-11.mb-4.mb-md-0
                  p.mb-4 El tipo de prenda a producir y el tamaño de los moldes.
                  img(src='@/assets/curso/tema3/img07.png' alt="Imagen decorativa")
              .row.justify-content-center
                .col-md-6.mb-4.mb-md-0
                  .h4 Las actividades que se realizan
                  p.mb-4 La capacidad de producción se mide definiendo el rango de actividades que se van a ejecutar, desde el trazo hasta entregar lotes organizados y listos para confeccionar, determinando las actividades que se van a realizar.
                .col-md-5.mb-4.mb-md-0
                  img(src='@/assets/curso/tema3/img08.png' alt="Imagen decorativa")
              .row.justify-content-center
                .col-md-6.mb-4.mb-md-0
                  .h4 Materiales e insumos a intervenir e inventarios necesarios
                  p.mb-4 De acuerdo con la cantidad de unidades de los lotes a producir y las materias primas que se necesitan se puede establecer la capacidad de producción.
                .col-md-5.mb-4.mb-md-0
                  img(src='@/assets/curso/tema3/img09.png' alt="Imagen decorativa")
              .row.justify-content-center
                .col-md-6.mb-4.mb-md-0
                  .h4 Materiales e insumos a intervenir e inventarios necesarios
                  p.mb-4 De acuerdo con la cantidad de unidades de los lotes a producir y las materias primas que se necesitan se puede establecer la capacidad de producción.
                .col-md-5.mb-4.mb-md-0
                  img(src='@/assets/curso/tema3/img10.png' alt="Imagen decorativa")
          
          p.mb-4(data-aos="fade-right") Con la información presentada se puede empezar a deducir realmente cuántos metros cuadrados se necesitan o cuántas unidades se pueden cortar con el área existente. Hacer esa relación sobre el área que tiene y compararla con lo que se necesita para producir lo esperado ayuda a tomar decisiones en la etapa del plan.
          .h4(data-aos="fade-left") Capacidad instalada de mesas
          p.mb-4(data-aos="fade-right") Esta capacidad se calcula teniendo cuenta referencias, tallas, trazos y clases de tela, así:

          .row.justify-content-center.mb-4(data-aos="flip-up")
            .col-lg-10.mb-4
              .bloque-texto-g.color-sky-blue.p-3.p-sm-4.p-md-5.mb-4
                .bloque-texto-g__img(
                  :style="{'background-image': `url(${require('@/assets/curso/tema3/img11.png')})`}"
                )
                .bloque-texto-g__texto.p-4
                  .h4 Cantidades por referencia
                  p Esto define el largo de las mesas que se necesita o viceversa, de las dimensiones de las mesas que se disponen en el sitio de trabajo dependerá cuántas unidades se pueden extender y cortar.
          .row.justify-content-center.mb-4(data-aos="flip-up")
            .col-lg-10.mb-4
              .bloque-texto-g.color-sky-blue.p-3.p-sm-4.p-md-5.mb-4
                .bloque-texto-g__img(
                  :style="{'background-image': `url(${require('@/assets/curso/tema3/img12.png')})`}"
                )
                .bloque-texto-g__texto.p-4
                  .h4 Cantidades por talla
                  p Se puede contar con una alta programación de lotes para el proceso,  pero muy pocas tallas de estos.  En ese caso, el largo de la mesa no será necesario que sea de gran tamaño. Esa información es muy importante para determinar la capacidad de producción.

          .row.justify-content-center.mb-4(data-aos="flip-up")
            .col-lg-10.mb-4
              .bloque-texto-g.color-sky-blue.p-3.p-sm-4.p-md-5.mb-4
                .bloque-texto-g__img(
                  :style="{'background-image': `url(${require('@/assets/curso/tema3/img13.png')})`}"
                )
                .bloque-texto-g__texto.p-4
                  .h4 Materiales e insumos a intervenir e inventarios necesarios
                  p De acuerdo con la cantidad de unidades de los lotes a producir y las materias primas que se necesitan se puede establecer la capacidad de producción.

            .row.justify-content-center.mb-4(data-aos="flip-up")
              .col-lg-10.mb-4
                .bloque-texto-g.color-sky-blue.p-3.p-sm-4.p-md-5.mb-4
                  .bloque-texto-g__img(
                    :style="{'background-image': `url(${require('@/assets/curso/tema3/img14.png')})`}"
                  )
                  .bloque-texto-g__texto.p-4
                    .h4 Al largo de los trazos
                    p Por políticas o necesidades de la empresa en ocasiones se programan varias referencias que van con el mismo tejido para extenderlas y cortarlas al mismo tiempo, esa condición hace que se tenga muy presente la relación del trazo con el largo de la mesa.
              
            .row.justify-content-center.mb-4(data-aos="flip-up")
              .col-lg-10.mb-4
                .bloque-texto-g.color-sky-blue.p-3.p-sm-4.p-md-5.mb-4
                  .bloque-texto-g__img(
                    :style="{'background-image': `url(${require('@/assets/curso/tema3/img15.png')})`}"
                  )
                  .bloque-texto-g__texto.p-4
                    .h4 Cantidad de clases de telas a utilizar 
                      p Hay prendas que no llevan una sola tela, llevan tela principal y otras telas complementarias, en ese caso hay que hacer varios tendidos y varios cortes, eso requiere más tiempo y afecta la capacidad de producción.

          .h4(data-aos="fade-right") Capacidad instalada de mano de obra directa
          p.mb-4(data-aos="fade-left") Definitivamente este cálculo de la disponibilidad de mano de obra directa se tasa en unidad de medida de tiempo, su valoración se realiza en minutos invertidos por cada trabajador, se calcula que 480 minutos (8 horas) es el tiempo que se puede disponer de un empleado para las diferentes funciones, conociendo esta condición y los estándares de las actividades se puede establecer la capacidad de producción.
          p.mb-4(data-aos="fade-right") Un estándar es la cantidad de tiempo que se utiliza realizando una actividad en condiciones normales, para cada actividad es importante determinar lo que se emplea para extender, cortar y tiquetear.
          p.mb-4(data-aos="fade-left") Sumando los tiempos estándar de cada actividad da como resultado el tiempo que se requiere para que cada unidad pueda ser procesada, luego se multiplica por el número de operarios x 480 minutos, y el resultado se divide en el estándar de las operaciones, así se obtienen las unidades que la planta de corte puede producir en un día.

          .tarjeta.color-light-green.p-3.mb-4(data-aos="zoom-in-up")
            .row.justify-content-center
              .col-md-11
                .row.align-items-center
                  .col-md-1.mb-4.mb-md-0
                    img(src='@/assets/curso/tema3/img16.svg' alt="Imagen decorativa")
                  .col-md-5.mb-4.mb-md-0
                    p La fórmula a aplicar para calcular la capacidad instalada de una planta de producción es la siguiente:
                  .col-md-1
                    p.fst-italic CI=
                  .col-md-4
                    p.fst-italic.text-decoration-underline.text-center.mb-0 N° de operaciones*horas de trabajo
                    p.fst-italic.text-center.mb-0 Estándar de trabajo
          
          p.mb-4(data-aos="fade-right") A continuación, un ejemplo de una sección que tiene 5 operarios que trabajan 8 horas diarias y, la sumatoria de estándar de las operaciones a realizar suma 4 minutos.

          
          .row.mb-4(data-aos="zoom-in-up")
            .col-md-5
              .tarjeta.color-light-orange.p-4
                p.mb-0
                  strong No. de operarios = 
                  | 5
                p.mb-0
                  strong  Horario de trabajo diario = 
                  | 480 minutos
                p.mb-0
                  strong Duración de la actividad = 
                  | 4 minutos
            .col-md-3.d-flex
              .tarjeta.color-light-orange.p-4
                .row.align-items-center
                  .col-md-1
                    p.fst-italic CI=
                  .col-md-5
                    p.fst-italic.text-decoration-underline.text-center.mb-0 5 x 480
                    p.fst-italic.text-center.mb-0 4
                  .col-md-5
                    p.fst-italic = 600
          
          p.mb-4(data-aos="fade-right") También como se puede observar a continuación.

          .titulo-sexto.color-acento-contenido(data-aos="zoom-in-down")
            h5 Tabla 1
            | Cálculo de capacidad instalada diaria
          
          .row.mb-4(data-aos="zoom-in-up")
            .col-md-12.mb-4.mb-md-0
              .tabla-b.color-acento-contenido.mb-5
                table
                  thead
                    tr
                      th.text-white No. de operarios
                      th.text-white Jornada diaria de trabajo en minutos
                      th.text-white Total minutos instalados
                  tbody
                    tr
                      td 5
                      td 480
                      td 2400
                    tr
                      td
                      td Estándar de las operaciones =
                      td 4
                    tr
                      td
                      td.colspan Producción diaria =
                      td 600
            .h4(data-aos="fade-right") Explicación de la tabla 1:
            p.mb-4(data-aos="fade-left") Para calcular la capacidad de producción de una sección dedicada la manufactura se depende de:
            .row.mb-4
              .col-md-6.mb-4.mb-md-0(data-aos="fade-right")
                .tarjeta-avatar
                  img(src='@/assets/curso/tema3/img17.svg' alt="Imagen decorativa")
                  .tarjeta.color-light-green.p-3
                    br
                    br
                    .h4.text-center.mt-5 El número de personas
                    p Mientras más o menos personas participen de una actividad se ejecutará más o menos rápido.
              .col-md-6.mb-4.mb-md-0(data-aos="fade-left")
                .tarjeta-avatar
                  img(src='@/assets/curso/tema3/img18.svg' alt="Imagen decorativa")
                  .tarjeta.color-light-green.p-3
                    br
                    br
                    .h4.text-center.mt-5 El horario de trabajo
                    p Si se le dedica muchos o menos minutos a una labor, de esa manera la ejecutará, en más o menos tiempo.
            
            p.mb-4(data-aos="fade-right") De acuerdo con lo anterior, según el número de personas y el horario de trabajo se obtiene la cantidad de tiempo (minutos) que se tiene disponible en esa sección de trabajo. Esta cantidad de tiempo se divide o se reparte entre el tiempo que se demora la actividad a realizar (estándar).
            .h4(data-aos="fade-left") Primera columna:
            p.mb-4(data-aos="fade-right") No. de operarios 
              strong se multiplica por la segunda columna: 
              | horario de trabajo, ahí se obtienen los minutos disponibles (tercera columna), se dividen entre 4 minutos (estándar de la actividad), y el resultado son las unidades que se pueden producir en un día.
            .h4(data-aos="fade-left") De zona de alistamiento
            p.mb-4(data-aos="fade-right") Existen dos actividades después del corte y antes de que salgan las piezas a los siguientes procesos, se llaman tiqueteado y alistamiento.

            .row.justify-content-center.mb-4.mt-5(data-aos="flip-up")
              .col-lg-12.mb-4
                .titulo-sexto.color-acento-contenido.mb-2
                  p.mb-0 Tiqueteado
                .bloque-texto-g.color-sky-blue.p-3.p-sm-4.p-md-5.mb-4
                  .bloque-texto-g__img(
                    :style="{'background-image': `url(${require('@/assets/curso/tema3/img19.png')})`}"
                  )
                  .bloque-texto-g__texto.p-4
                    .h4 Tiqueteado
                    |
                    |
                    br
                    br
                    p.mb-0 Consiste en colocar adhesivos a las piezas ya cortadas, el adhesivo lleva información importante como # corte, talla, consecutivo, entre otros, y ayuda a identificar operaciones y ubicación de lotes; es fundamental para el seguimiento de la producción en la planta, igualmente, facilita al momento de ensamblar  las piezas que las prendas de vestir no presenten tonalidades, y de esta manera evitar en las plantas de producción que se mezclen  los diferentes lotes de producción, cobrando importancia este proceso en la cadena de producción. Un ejemplo a continuación:

            .row.justify-content-center.mb-4(data-aos="flip-up")
              .col-lg-12.mb-4
                .titulo-sexto.color-acento-contenido.mb-2
                  p.mb-0 Paquetes para proceso
                .bloque-texto-g.color-sky-blue.p-3.p-sm-4.p-md-5.mb-4
                  .bloque-texto-g__img(
                    :style="{'background-image': `url(${require('@/assets/curso/tema3/img20.png')})`}"
                  )
                  .bloque-texto-g__texto.p-4
                    .h4 Alistamiento
                    |
                    |
                    br
                    br
                    p 
                      strong Realizados los procesos de trazado, extensión, corte y etiqueta 
                      |
                      |
                      br
                      br
                      | Se procede a organizar las prendas para el siguiente proceso, habitualmente sigue ensamble o confección, pero en ocasiones después de cortar y antes de confeccionar pueden existir procesos como el estampado o bordado, de acuerdo con el destinatario se deben empacar las piezas cortadas, acompañadas de documentos que permitan continuar con los procesos.
                    |
                    |
                    br
                    br
                    p.mb-0 Los paquetes amarrados deben de ir bien sujetos o embalados para evitar pérdidas de piezas y marcados para facilitar su identificación.  En algunas ocasiones se les debe anexar insumos, plantillas, moldes, entre otros, como se ilustra en la siguiente figura.

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

<style lang="sass" scoped></style>
