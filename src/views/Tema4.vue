<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Extendida
    
    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-lg-10.mb-4.mb-lg-4
        .bloque-texto-g.color-light-red.p-3.p-sm-4.p-md-5.mb-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema4/img01.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 Es el proceso de colocar las telas de manera horizontal una sobre otra alineadas sobre la mesa de corte, cumpliendo especificaciones de largo del trazo y ancho de la tela. En el largo del trazo y sus respectivas tallas se definen las longitudes del extendido; las mesas son marcadas con cintas para las longitudes que se deben tener en cuenta para la cantidad de tela a extender. Desde el extendido se controla las cantidades por talla, de acuerdo con la longitud del trazo, como se muestra a continuación.

      .col-lg-10.mb-4
        .row.mb-4
          .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right")
            p.mb-4 Para proceder a extender se debe conocer cuál es la tela indicada y sus consideraciones, la ubicación de los rollos, cuál es el largo del trazo, las cantidades por talla y colores, la cantidad total, el tiempo presupuestado para esa actividad. Los anchos de las mesas donde se va a extender y cortar deben ser consecuentes con los anchos de los rollos y viceversa, y todo lo anterior a su vez con los anchos de los trazos donde van a ir dibujados los moldes y patrones que componen la prenda de vestir.
            img(src='@/assets/curso/tema4/img02.svg' alt="Imagen decorativa")
          .col-lg-6.mb-4.mb-lg-0(data-aos="fade-left")
            .titulo-sexto.color-acento-contenido
              p Extendido de tela
            img(src='@/assets/curso/tema4/img03.png' alt="Imagen decorativa")

        .h4(data-aos="fade-right") Cuidados durante la extendida
        p.mb-4(data-aos="fade-left") Hay muchas consideraciones que hay que tener en cuenta al momento de realizar la labor de extendida, y en el tema de producción se abordarán las más relevantes.
        .col-lg-10.mb-4
        .row.mb-4(data-aos="zoom-in")
          .col-lg-4.mb-4.mb-lg-0
            figure.mb-4
              img(src='@/assets/curso/tema4/img04.png' alt="Imagen decorativa")
          .col-lg-4.mb-4.mb-lg-0
            figure.mb-4
              img(src='@/assets/curso/tema4/img05.png' alt="Imagen decorativa")
          .col-lg-4.mb-4.mb-lg-0
            figure.mb-4
              img(src='@/assets/curso/tema4/img06.png' alt="Imagen decorativa")
        .row.mb-4(data-aos="zoom-in")
          .col-lg-4.d-flex.mb-4.mb-lg-0
            .tarjeta.color-light-green.p-4
              p Vigilar que las cantidades totales por talla y color se cumplan, de acuerdo con la hoja de producción y el plan establecido.
          .col-lg-4.d-flex.mb-4.mb-lg-0
            .tarjeta.color-light-orange.p-4
              p Estar muy pendientes de que las telas posean las características requeridas para el tipo de prenda y/o producto, no se pueden dejar pasar irregularidades, en un proceso siguiente no es fácil corregir lo que se deja pasar en la extendida.
          .col-lg-4.d-flex.mb-4.mb-lg-0
            .tarjeta.color-light-red.p-4
              p De acuerdo con los estándares de ejecución se planea y programa la realización de cada actividad, durante la extendida se debe vigilar que no se excedan estos tiempos.

        p.mb-4(data-aos="fade-right") En el video se puede apreciar un ejemplo de tipos de tendido con diferentes características del material:

        .video(data-aos="fade-left")
          iframe(width="560" height="315" src="https://www.youtube.com/embed/AQuKp0yivEw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    separador
    #t_4_1.titulo-segundo(data-aos="fade-right")
      .h2 4.1 Técnicas de extendida
    
    p.mb-4(data-aos="fade-left") La labor de extender la tela sobre la mesa de corte, cumpliendo especificaciones de largo de trazo y tallas se puede hacer de diferentes maneras, de acuerdo con la tecnología a utilizar, con la disposición de máquinas y herramientas, y con la cantidad de personas que se puede o debe utilizarse.
    p.mb-4(data-aos="fade-right") Actualmente, existen varias técnicas o metodologías a emplear:

    .tarjeta.tarjeta--azul.p-4.mb-5(data-aos="zoom-in")
      SlyderA(tipo="b")
        .row.justify-content-center.p-5
          .col-md-7.mb-4.mb-md-0
            .h4 Extendido manual
            p Inicialmente se marca el inicio y el final del trazo para saber desde y hasta donde se deben extender las telas; en un extremo de la mesa se debe colocar el rollo a extender, sostenido sobre un pedestal o mueble y que le permita su desenrolle, normalmente esta actividad la realizan dos operarios, uno a cada lado de la mesa, agarran y llevan una punta de la tela a cada extremo y se desplazan hasta donde está la marca del fin del trazo, ellos deben vigilar que la tela que están extendiendo no presente defectos como roturas, marras, imperfectos, etc., y proceder a marcarlos para luego ponerlos, o de acuerdo con el tamaño proceder a retirar ese tramo de tela que no sirve para construir prendas de vestir, y así evitar un reproceso más adelante, o tener que asumir una prenda de segunda; existen grados de tolerancia de acuerdo con las políticas de calidad de la empresa, que se consideran antes de tomar decisiones en este aspecto. 
          .col-md-4.mb-4.mb-md-0
            hr
            img(src='@/assets/curso/tema4/img07.png' alt="Imagen decorativa")
        
        .row.justify-content-center.p-5
          .h4 Extendido manual
          p Al terminar de devolverse los operarios, cada uno alrededor de la mesa revisando la calidad del extendido y de la tela, y cuidando el buen uso del tiempo, proceden a cortar la tela en el extremo de la mesa por donde iniciaron, para eso utilizan un útil de corte como bisturí o cuchilla, o tijeras.
          .col-md-7.mb-4.mb-md-0
            p En el extendido manual se utiliza en muchas ocasiones una cortadora de extremos. Este es un implemento eléctrico que tiene una cuchilla en medio de dos ranuras y que se desplaza en forma recta a través del ancho de la mesa. Sobre esta punta de la tela o extremo del trazo se coloca otra pieza pesada, varilla, rodillo o similar para evitar el deslice de la tela mientras dura la extendida y se procede de nuevo a la misma operación; de todas maneras con esta técnica el transporte de las telas sigue siendo manual.
          .col-md-4.mb-4.mb-md-0
            img(src='@/assets/curso/tema4/img08.png' alt="Imagen decorativa")

        .row.justify-content-center.p-5
          .col-md-7.mb-4.mb-md-0
            .h4 Extendido con carro
            p Extendido basado en un carro transportador del rollo de la tela, el cual tiene un accesorio donde se ubica el rollo o donde se coloca la tela, y por medio de ruedas ubicadas en un extremo de la mesa y en un carril ubicado en el otro extremo de la mesa se hace deslizar la tela sobre la mesa, cumpliendo especificaciones del trazo. El que hace que el carrito se mueva sigue siendo el operario.
          .col-md-4.mb-4.mb-md-0
            img(src='@/assets/curso/tema4/img09.png' alt="Imagen decorativa")

        .row.justify-content-center.p-5
          .col-md-7.mb-4.mb-md-0
            .h4 Extendido automatizado
            p En la actualidad la oferta de equipos para las áreas de trazo y corte son abundantes y con el avance de tecnologías 4.0, las alternativas son muchas; por medio de equipos que realizan de manera rápida y bien hecha la actividad de extendido se han beneficiado las empresas del sector moda. Son equipos que permiten colocar el rollo y ellos previa programación digital se encargan de desplazarse hasta a distancia correcta (largo del trazo), cortar el largo del tendido y en las cantidades que se le programó.
          .col-md-4.mb-4.mb-md-0
            img(src='@/assets/curso/tema4/img10.svg' alt="Imagen decorativa")

    p.mb-4(data-aos="fade-right") Para complementar la información se recomienda ver los siguientes videos, de esta manera podrá:
    .row.mb-5
      .col-md-5.mb-4.mb-md-0(data-aos="fade-right")
        .tarjeta.color-light-orange.p-4
          p.mb-4 Conocer el paso a paso para la realización del extendido de tela manual.
          a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/embed/NYypQR3FceU" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
            .anexo__texto
              p Instructiva extendedora de tela manual      
      .col-md-6.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-light-orange.p-4
          p.mb-4 Además, con la intensión de comparar los métodos se muestra la forma de uso adecuado de la tendedora de tela automática.
          a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/embed/J0Zq8rHcPeQ" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
            .anexo__texto
              p Tendedora de tela automática
    
    .h4(data-aos="fade-right") Recomendaciones generales para el extendido de algunas telas
    p.mb-4(data-aos="fade-left") En el proceso de extendido los tipos de telas son un elemento que tiene tratamientos especiales, a continuación se relacionan algunas recomendaciones importantes a tener en cuenta:

    .row.justify-content-center.mb-4
      .col-md-9.mb-4.mb-md-0(data-aos="zoom-in")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema4/img11.svg' alt='Imagen decorativa')
          .tarjeta.color-light-green.d-flex.align-content-center.flex-wrap
            .p-4
              p.mb-0 Cuando se está usando telas índigos con un volumen superior de 80 capas se recomienda utilizar la máquina vertical y el corte manual. Pero, en el corte automatizado se debe tener en cuenta la altura del tendido en relación con la capacidad de la máquina cortadora.
      .col-md-9.mb-4.mb-md-0(data-aos="zoom-in")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema4/img12.svg' alt='Imagen decorativa')
          .tarjeta.color-light-green.d-flex.align-content-center.flex-wrap
            .p-4
              p.mb-0 Se recomienda implementar el corte con bloqueo y manualmente cuando se usan tejidos preteñidos y que llevan case de rayas, esto genera una atención especial cuando las piezas no casan, pues es necesario generar piezas más grandes que permitan el repite de tela para logar que casen, cortándolo manualmente basado en el molde real, para ello, se usa una máquina automática si el preteñido no tiene case. 
      .col-md-9.mb-4.mb-md-0(data-aos="zoom-in")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema4/img13.svg' alt='Imagen decorativa')
          .tarjeta.color-light-green.d-flex.align-content-center.flex-wrap
            .p-4
              p.mb-0 Para validar si hay problemas de viro se rasga los extremos de tres capas, esto se implementa con el satín, chalís y chiffon; si se encuentra viro superior a 5 cm no se debe seguir con el extendido y se procede a revisar muchos más metros para ver si persiste esta tendencia. En caso de conservarla se debe devolver el material al proveedor.
      .col-md-9.mb-4.mb-md-0(data-aos="zoom-in")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema4/img14.svg' alt='Imagen decorativa')
          .tarjeta.color-light-green.d-flex.align-content-center.flex-wrap
            .p-4
              p.mb-0 Se debe revisar las tensiones de la máquina cuando se implementa el extendido automático, evitando encogimientos de la pieza, ya que las telas generalmente tienden a recuperar la tensión generada; de este proceso depende la calidad del corte.
      .col-md-9.mb-4.mb-md-0(data-aos="zoom-in")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema4/img15.svg' alt='Imagen decorativa')
          .tarjeta.color-light-green.d-flex.align-content-center.flex-wrap
            .p-4
              p.mb-0 Para extender tejidos que lleven peine y pelos se debe desde el inicio colocarlos hacia abajo, según el peso de la tela y el tipo de corte de la producción varía el número de capas en los tendidos.
      .col-md-9.mb-4.mb-md-0(data-aos="zoom-in")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema4/img15.svg' alt='Imagen decorativa')
          .tarjeta.color-light-green.d-flex.align-content-center.flex-wrap
            .p-4
              p.mb-0 Hay telas de mayor cuidado por su diseño, estampado o especificaciones técnicas del tejido y, desde el trazo se debe indicar estas especificaciones para tener en cuenta el sentido en la organización de capas (Clúster textil / Confección, diseño y moda, 2017).

    p.mb-4(data-aos="fade-right") En el siguiente video se explican las características del material desde trazo y corte:
    
    figure.mb-5(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/Ul-AmX5ioxQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    separador
    #t_4_2.titulo-segundo(data-aos="fade-right")
      .h2 4.2 Tipos de extendidos
    
    p.mb-4(data-aos="fade-left") Adicional a las técnicas de extendido según la tecnología también existen maneras de colocar las telas, a eso se le denomina tipos de extendido, los cuales se detallan a continuación.

    TabsA.color-acento-contenido.mb-5(data-aos="zoom-in-up")
      .tarjeta.color-sky-blue.p-4(titulo="Extendido cara arriba")
        .h4 Extendido cara arriba
        p Es la manera tradicional que se ha utilizado a través de los años, consiste en colocar la tela con el revés en sentido hacia la mesa y el derecho mirando hacia arriba. En el extremo inicial de la marcada se coloca el inicio del rollo y desde ahí avanza el carro, dejando el tejido sobre ella hasta finalizar en el otro extremo donde se efectúa el corte, teniendo cuenta el ancho del tejido. Este proceso se repite retrocediendo la máquina extendedora.
      .tarjeta.color-sky-blue.p-4(titulo="Extendido cara a cara")
        h4 Extendido cara a cara
        p Se denomina también zig-zag, se refiere a ir dejando tejido en los dos sentidos, cuando va hacia arriba y cuando va regresando. Una de sus ventajas es la buena utilización del tiempo, es un tipo de extendido rápido, que se inicia en cualquiera de los extremos donde queda el cabo de la tela, allí se inicia el deslizamiento de la máquina hacia el otro extremo, dejando el tejido al mismo tiempo, al finalizar se dobla el extremo opuesto y se retrocede con el carro. Es uno de los más utilizados en la elaboración de blue jeans y tejido liso.
      .tarjeta.color-sky-blue.p-4(titulo="Cara a cara girado")
        h4 Cara a cara girado
        p Igual al anterior, pero después de dar la primera pasada, al devolverse cortar y cambiar el sentido de la tela, de esa manera quedará una tela al derecho y otra al revés. Se utiliza con telas que tienen sentido y orientación a la apariencia. Es un proceso lento.
      .tarjeta.color-sky-blue.p-4(titulo="Escalonado o en espigas")
        h4 Escalonado o en espigas
        p Es muy normal que no todas las tallas se comercialicen en la misma cantidad, hay unas tallas que se venden más que otras, y esa información debe ser interpretada desde el área de trazo y corte. Por ese motivo se debe extender más la cantidad de tela en unas tallas que en otras, se tiene un ciclo de trabajo idéntico, pero cambia las longitudes y cantidades de las capas.

    .row.justify-content-center.mb-4
      .col-lg-2.mb-4.mb-lg-4.p-0(data-aos="fade-right")
        img(src='@/assets/curso/tema4/img17.svg' alt="Imagen decorativa")
      .col-lg-9.mb-4.mb-lg-4(data-aos="fade-left")
        br
        .tarjeta.color-light-orange.p-4
          p Después de terminar la extendida de la tela sobre la mesa en las cantidades solicitadas se procederá a fijar o pegar el trazo. Consiste en colocar el trazo sobre el tendido, valiéndose de grapas, ganchos o alfileres entre otros, cuidando que las medidas del trazo que se van a fijar coincidan con el ancho útil de la tela a utilizar.

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

<style lang="sass" scoped></style>
