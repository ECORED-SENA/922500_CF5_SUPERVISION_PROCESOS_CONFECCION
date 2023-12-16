<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Trazo
    
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-lg-10.mb-4.mb-lg-0
        .bloque-texto-g.color-light-orange.p-3.p-sm-4.p-md-5.mb-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/img01.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 Es un dibujo de los moldes de la prenda que se va a cortar, se debe ubicar de acuerdo con el ancho de la tela y evitando al máximo dejar espacios vacíos, ya que eso hace parte del desperdicio de la tela.
            p.mb-4 Primero se realiza un prototipo, este se hace a partir de un trazo para poderlo cortar, con esta actividad se puede ir determinando el consumo de material, lo cual es fundamental para lograr calcular con exactitud el costo de las prendas, pues de aquí se extrae el consumo promedio por prenda.
      .col-lg-10.mb-4.mb-lg-0(data-aos="zoom-in")
        img(src='@/assets/curso/tema2/img02.svg' alt="Imagen decorativa")

    p.mb-4(data-aos="fade-right") Para realizar el trazo es importante tener en cuenta la orientación de la tela y el aplome de los moldes, cuáles piezas van a lo largo o en sentido de la urdimbre, y cuáles van a través, o sea, en sentido de la trama. También hay piezas que se deben dibujar en diagonal como es el caso de los sesgos.
    p.mb-4(data-aos="fade-left") El aprovechamiento adecuado de los materiales es el resultado de elaborar un buen trazo, ya que está directamente relacionado con el aprovechamiento y/o desperdicio del recurso, que, en la mayoría de los casos, representa el mayor porcentaje del costo de la prenda.
    p.mb-4(data-aos="fade-right") Este procedimiento de trazo se puede realizar de manera manual o mediante un software, en el mercado hay numerosas ofertas de estos programas como pueden ser:

    .row.mb-4(data-aos="zoom-in")
      .col-lg-3.mb-4.mb-lg-0
        img(src='@/assets/curso/tema2/img03.svg' alt="Imagen decorativa")
      .col-lg-3.mb-4.mb-lg-0
        img(src='@/assets/curso/tema2/img04.svg' alt="Imagen decorativa")
      .col-lg-3.mb-4.mb-lg-0
        img(src='@/assets/curso/tema2/img05.svg' alt="Imagen decorativa")
      .col-lg-3.mb-4.mb-lg-0
        img(src='@/assets/curso/tema2/img06.svg' alt="Imagen decorativa")

    separador
    #t_2_1.titulo-segundo(data-aos="fade-right")
      .h2 2.1 Sistemas para elaborar trazos
    
    p.mb-5(data-aos="fade-left") El trazo como proceso fundamental de la manufactura textil define la ruta a seguir en relación con el método, el cálculo de tiempo y los materiales; durante mucho tiempo y en determinadas producciones se usa este proceso de forma manual, pero con el aumento de la producción en masa y aprovechando los adelantos tecnológicos aparecen escenarios de automatización del proceso, generando nuevas opciones como  se puede ver a continuación.
    
    .row.justify-content-center.mb-4(data-aos="zoom-in")
      .col-md-10.mb-4.mb-md-0
        TabsB.color-acento-contenido.mb-5
          .py-4.py-md-5(titulo="Trazo manual" :icono="require('@/assets/curso/tema2/img07.svg')")
            .tarjeta.tarjeta--azul.p-4.mb-5
              SlyderA
                .row.justify-content-center
                  .col-md-7.mb-4.mb-md-0
                    .h4 Trazo manual
                    p.mb-4 Se colocan los moldes sobre la tela o un papel que tenga las dimensiones de la tela, se dibujan teniendo en cuenta la simetría requerida, la orientación de los hilos del tejido, la cantidad de tallas a dibujar, y verificando el número de piezas por prenda. Es fundamental esta actividad para establecer los costos de la prenda, ya que es en esta donde se empiezan a definir los consumos de las materias primas más relevantes.
                  .col-md-4.mb-4.mb-md-0
                    img(src='@/assets/curso/tema2/img09.png' alt="Imagen decorativa")
                
                .row.justify-content-center
                  .col-md-11.mb-4.mb-md-0
                    .h4 Trazo manual
                    p.mb-4 El sistema manual es muy obsoleto, en la medida que al día de hoy, año 2021, la oferta de software para elaborar trazos es muy copiosa. Aun así, en muchos departamentos de diseño, sobre todo al elaborar muestras iniciales, se utilice esta técnica, usando moldes en cartulina, acetatos u otro material medianamente rígido para dar utilidad a los moldes durante el mayor tiempo posible.
                    .row.align-items-center
                      .col-md-3.mb-4.mb-md-0.p-1
                        img(src='@/assets/curso/tema2/img10.svg' alt="Imagen decorativa")
                      .col-md-9.mb-4.mb-md-0
                        .tarjeta.color-white.p-4
                          p.mb-3 Verificar que los moldes correspondan al modelo que se quiere producir. La cantidad de piezas por prenda también es tema de atención, en este sistema manual el aplome de los moldes, la simetría y la marcada de los piquetes es un tema que se debe procurar no pasar por alto.

          .py-4.py-md-5(titulo="Trazo sistematizado" :icono="require('@/assets/curso/tema2/img08.svg')")
            .tarjeta.tarjeta--azul.p-4.mb-5
              SlyderA
                .row.justify-content-center
                  .col-md-6.mb-4.mb-md-0
                    .h4 Trazo sistematizado
                    p.mb-4 Este tipo de trazo se realiza por medio de un software diseñado para ese fin, las medidas de los moldes o patrones se digitalizan o se le dan las medidas en el programa, o si ya se tienen en un archivo, simplemente se le da la indicación de cuál es la referencia que se va a trabajar y qué tallas se van a utilizar.
                  .col-md-5.mb-4.mb-md-0
                    img(src='@/assets/curso/tema2/img11.svg' alt="Imagen decorativa")
                .row.justify-content-center
                  .col-md-6.mb-4.mb-md-0
                    .h4 Trazo sistematizado
                    p.mb-4 Se le da la medida del ancho de la tela y las cantidades de tallas a dibujar, lo que significa una proporción. El programa con esa información procede a elaborar el trazo con criterios de cumplir las órdenes que se le dieron, procurando el mejor uso del recurso tela y evitando el desperdicio; este sistema es mucho más rápido que el manual, y la información y patrones o moldes permanecen mejor guardados sin peligro de pérdidas y deterioros.
                  .col-md-4.mb-4.mb-md-0
                    img(src='@/assets/curso/tema2/img12.png' alt="Imagen decorativa")
                .row.justify-content-center.p-5
                  .col-md-6.mb-4.mb-md-0
                    .h4 Trazo sistematizado
                    p Este sistema también es más ágil cuando se trata de buscar información que tenga que ver con moldes, trazos anteriores y/o verificar piezas con las que se tienen dudas. Luego de tener este trazo de manera digital se envía esta información a un plotter para que imprima el trazo y sea llevado a la sala de corte.  En el mercado hay ofertas de software que permiten sistematizar las actividades de trazo y mejorar su relación con materiales, uso del tiempo y respuesta óptima a necesidades actuales del sector. 
                    p A continuación, algunas: 
                      strong Lectra, Optitex, Diamino, Gerber.
                  .col-md-5.mb-4.mb-md-0
                    img(src='@/assets/curso/tema2/img13.svg' alt="Imagen decorativa")
        
        .tarjeta.color-light-orange.p-4(data-aos="flip-up")
          .row.align-items-center
            .col-md-7.mb-4.mb-md-0
              p.mb-4 Para conocer cómo realizar un proceso de trazo y corte consulte el siguiente documento:
            .col-md-4.mb-4.mb-md-0
              a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo1_pisantex_trazo_y_corte.pdf')" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-pdf.svg")
                .anexo__texto
                  p Procesos de trazo y corte Pizantex

    separador
    #t_2_2.titulo-segundo(data-aos="fade-right")
      .h2 2.2 Elementos y equipos para trazar
    
    p.mb-4(data-aos="fade-left") A continuación, se presentan las diferencias más relevantes entre el proceso de trazo manual y el sistematizado:

    .tarjeta--container.row.mb-4
      .col-md.tarjeta.color-primario.p-0(data-aos="fade-right")
        br        
        .h2.text-center Trazo manual
        .tarjeta.color-light-orange.p-4
          p.mb-4 Cuando se hace referencia al trazo manual solo se necesita:
          ul.lista-ul
            li 
              i.fas.fa-angle-right
              | Papel sulfito o papel de trazo, y elemento donde se van a dibujar los moldes.
            li 
              i.fas.fa-angle-right
              | Los moldes que habitualmente están en cartulina, acetato u otro material rígido, durable y fácil de cortar, con el fin de que no se deteriore muy rápido.
            li 
              i.fas.fa-angle-right
              | Un instrumento de marcado que puede ser un lápiz, marcador, lapicero, lápiz de color, etc.
            li 
              i.fas.fa-angle-right
              | Instrumento de medición como metro, regla, cinta, escuadra.
            li 
              i.fas.fa-angle-right
              | Ficha técnica y/o muestra física.
          .row.justify-content-center.mb-4
            .col-md-10.mb-4.mb-md-0
              .titulo-sexto.color-acento-contenido
                p Elementos trazo manual
              img(src='@/assets/curso/tema2/img14.png' alt="Imagen decorativa")
      .col-md.tarjeta.color-secundario.p-0(data-aos="fade-left")
        br        
        .h2.text-center.text-black Trazo sistematizado
        .tarjeta.color-light-green.p-4
          p.mb-4 Cuando se hace referencia al trazo sistematizado se necesita:
          ul.lista-ul
            li 
              i.fas.fa-angle-right
              | Un programa o software con las propiedades necesarias para este fin, es decir,  ubicar la moldería en un área igual a la tela que va a utilizar. Normalmente va articulado con la función de creación de moldes o patrones, y en muchos casos está articulado con otras actividades de la línea de producción.
            li 
              i.fas.fa-angle-right
              | Un hardware o equipo que permita utilizar el software.
            li 
              i.fas.fa-angle-right
              | Papel sulfito o papel de trazo, que normalmente va instalado en la máquina que va a imprimir el trazo: plotter.
          br
          .row.justify-content-center.mb-4
            .col-md-10.mb-4.mb-md-0
              .titulo-sexto.color-acento-contenido
                p Plotter trazo sistematizado
              img(src='@/assets/curso/tema2/img15.png' alt="Imagen decorativa")

    separador
    #t_2_3.titulo-segundo(data-aos="fade-right")
      .h2 2.3 Área de la sección de trazo y corte

    .row.align-items-center.mb-4
      .col-md-6.mb-4.mb-md-0(data-aos="fade-right")
        p.mb-4 En las empresas que realizan actividades de trazo y corte se debe designar un área apropiada para ese fin, que sea coherente con los muebles que se van a emplear para las labores, se recomienda que sea un área rectangular para poder ubicar mesas y estanterías, pues ambas tienen la misma figura geométrica.
        p.mb-4 La proporción del ancho con respecto al largo se sugiere que sea de 1 a 2, si se dispone de un área que no cumpla estos principios, se hace un dibujo del área y se ubicaran los puestos de trabajo necesarios para ejecutar las labores de corte, extendida y alistamiento, de acuerdo con el área disponible, es decir, con los metros cuadrados se puede determinar la capacidad instalada para entregar piezas cortadas, tal como se muestra en la siguiente figura.
      .col-md-6.mb-4.mb-md-0(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido
          p Ejemplo de área de corte y ubicación de mesas
        img(src='@/assets/curso/tema2/img16.svg' alt="Imagen decorativa")
    
    .row.justify-content-center.mb-4
      .col-md-10.mb-4.mb-md-0
        .tarjeta.color-light-orange.p-4
          .row.justify-content-center.mb-4
            .col-md-10.mb-4.mb-md-0
              p.mb-4(data-aos="zoom-in") El tipo de prenda que se va a producir y las cantidades esperadas ayudan a definir también qué dimensiones deben tener las áreas de trabajo. Si el tipo de prenda es pequeño, los moldes o patrones también serán pequeños: ropa interior, vestidos de baño, fajas, pañoletas, etc., no será necesaria un área muy grande y, si los lotes de producción son pequeños de acuerdo con las características de la organización, los largos de los trazos también pueden ser pequeños, y por supuesto las mesas de extendido y corte serán pequeñas, como se muestra en la siguiente figura.
              .titulo-sexto.color-acento-contenido
                p Plotter trazo sistematizado
              .row
                .col-md-6.d-flex.mb-4.mb-md-0(data-aos="fade-right")
                  img(src='@/assets/curso/tema2/img17.png' alt="Imagen decorativa")
                .col-md-6.d-flex.mb-4.mb-md-0(data-aos="fade-left")
                  .tarjeta.color-white.p-4
                    p En Colombia del 100% de las organizaciones dedicadas a producir prendas de vestir, el 95% de ellas son mipymes, de tal manera que sus lotes de producción no son de muchas unidades. Por esta razón, se  encuentra que muchas compañías no necesitan un área muy grande para extender y cortar telas para fabricar prendas de vestir.
    
    .row.justify-content-center.mb-4
      .col-md-6.mb-4.mb-md-0(data-aos="zoom-in-down")
        .tarjeta-avatar
          img.iconH(src='@/assets/curso/tema2/img18.png' alt='AvatarTop')
          .tarjeta.color-light-gray.p-4
            p De acuerdo con los presupuestos de ventas que hay que satisfacer deben ser calculadas las áreas de trazo, corte y costura; si por alguna razón la capacidad instalada propia no cumple con esos requisitos de satisfacer la demanda se procederá a contratar servicios de trazo y corte con terceros.

    .row.justify-content-center.mb-4(data-aos="zoom-in-up")
      .col-md-6.mb-4.mb-md-0
        figure.mb-4
          img(src='@/assets/curso/tema2/img19.svg' alt="Imagen decorativa")
        .tarjeta.color-light-green.p-4
          p.mb-4 Para tener un excelente desempeño en la planeación del área de trazo y corte es importante definir cuáles actividades se van a realizar y en qué consiste cada una de ellas. El conocer qué recursos llegan y de dónde permite entender, planear y dirigir mejor la sección, y conocer los procesos que se van a llevar a cabo, con esos recursos se facilita hacer el mejor uso de ellos.
  
    separador
    #t_2_4.titulo-segundo(data-aos="fade-right")
      .h2 2.4 Ingreso, recepción, almacenamiento y reposo de telas
    
    p.mb-4(data-aos="fade-left") A la sección de trazo y corte entra gran cantidad de recursos, entre ellos, información necesaria para programar actividades que permitan cumplir con los objetivos. Esta información tiene que ver con:

    .row.justify-content-center.mb-4
      .col-md-8.mb-4.mb-md-0(data-aos="zoom-in-up")
        LineaTiempoD.color-acento-contenido
          .row.justify-content-center(numero="1" titulo="Recepción de información")
            .col-md-12.mb-4.mb-md-0
              p.mb-4 Una de las entradas importantes para registrar, planear y programar actividades en el corte es la información que viene en documentos como:
              strong Fichas técnicas: 
              | en este documento viene especificado el molde que se va a utilizar en el trazo, un dibujo de la silueta, la tela principal y las telas complementarias, y demás observaciones que vienen desde el departamento de diseño, y que consideran son necesarias para trabajar en el área de trazo y corte.  
            .col-md-6
              a.anexo.mb-4(:href="obtenerLink('/downloads/ORDEN_DE_PRODUCCION.pdf')" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-pdf.svg" alt="Imagen decorativa")
                .anexo__texto
                  p Orden de producción.
          .row.justify-content-center(numero="2" titulo="Orden de corte o de producción")
            .col-md-12.mb-4.mb-md-0
              p.mb-4 Toda la información que tiene que ver con cantidades totales programadas, por tallas, por color vienen en este documento, adicional la fecha de programación y de proyección de la entrega más unos espacios en los que se elaborará la liquidación de corte. De acuerdo con la naturaleza, tamaño y políticas de la empresa, la programación y la liquidación de corte se hacen en documentos distintos o en el mismo formato. 
              p.mb-4 La diferencia entre ambas informaciones es que en la programación es lo que se proyecta, y la liquidación es lo que realmente se cortó. 
            .col-md-10
              figure
                img(src='@/assets/curso/tema2/img21.png' alt="Imagen decorativa")
          .row.justify-content-center(numero="3" titulo="Inventario de materiales disponibles")
            .col-md-12.mb-4.mb-md-0
              p.mb-4 La información de los materiales e insumos que se tienen y los que se van a tener le permite al supervisor de planta de confección poder visualizar mejor su plan, sin esa información no puede calcular, por ejemplo, tiempos de entrega.
            .col-md-10
              figure
                img(src='@/assets/curso/tema2/img22.png' alt="Imagen decorativa")
          .row.justify-content-center(numero="4" titulo="Disponibilidad de maquinaria y herramientas")
            .col-md-12.mb-4.mb-md-0
              p.mb-4 Además de poseer información con respecto a las cantidades que se van a trazar y cortar, de conocer las especificaciones técnicas que hay que considerar para los lotes de producción, de saber cuáles materiales e insumos necesita, el tecnólogo debe conocer de qué equipos, máquinas y herramientas dispone para poder planear la ubicación y custodia de estos recursos.
            .col-md-10
              figure
                img(src='@/assets/curso/tema2/img23.png' alt="Imagen decorativa")
    
    separador
    #t_2_5.titulo-segundo(data-aos="fade-right")
      .h2 2.5 Planeación del área de trazo y corte
    
    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-md-8.mb-4.mb-md-0
        .tarjeta.color-light-orange.p-4 
          .row.justify-content-center
            .col-md-6.mb-4.mb-md-0
              p Las prendas de vestir en su composición y en un alto porcentaje están compuestas por un material definido como  tejido; los materiales e insumos que ingresan al área de trazo y corte son habitualmente telas principales y telas complementarias, en ocasiones solo se emplea un tejido para elaborar la prenda, pero otras veces, se complementan con forros, sesgos, combinaciones, entretelas, etc.
            .col-md-4.mb-4.mb-md-0
              img(src='@/assets/curso/tema2/img24.svg' alt="Imagen decorativa")

    .cajon.color-primario.p-4(style="background-color:#FFE2D6;" data-aos="zoom-in")
      .h4 Cuidados al recibir los materiales
      ul.lista-ul
        li 
          i.fas.fa-angle-right
          | Verificar que los tipos de tejidos cumplan con las características solicitadas, en lo que tiene que ver con especificaciones técnicas y composiciones.
        li 
          i.fas.fa-angle-right
          | Revisar la presentación en que vienen las telas: rollos, paquetes, retazos, bolsas.
        li 
          i.fas.fa-angle-right
          | Registrar las cantidades de cada uno de los rollos, especificando # de rollo, color y destinación.
        li 
          i.fas.fa-angle-right
          | Existen máquinas revisadoras de telas que algunas organizaciones poseen, sirven para detectar errores en el metraje y en la presentación de la tela.

    separador
    #t_2_6.titulo-segundo(data-aos="fade-right")
      .h2 2.6 Almacenamiento

    .row.justify-content-center
      .col-md-3.d-flex.mb-4.mb-md-0(data-aos="fade-right")
        .tarjeta.color-light-green.p-4
          p.mb-4 Los criterios para el almacenamiento de las materias primas tienen que ver con:
          ul.lista-ul
            li 
              i.fas.fa-angle-right
              | El peso de los rollos.
            li 
              i.fas.fa-angle-right
              |	La composición de los tejidos.
            li 
              i.fas.fa-angle-right
              |	La frecuencia de utilización.
            li 
              i.fas.fa-angle-right
              |	La presentación.
            li 
              i.fas.fa-angle-right
              |	El tamaño de los rollos.
      .col-md-9.mb-4.mb-md-0(data-aos="fade-left")
        img(src='@/assets/curso/tema2/img25.png' alt="Imagen decorativa")
    
    .tarjeta.color-light-gray.p4
      .row.justify-content-center.p-4
        .col-md-3.mb-4.mb-md-0(data-aos="fade-right")
          .titulo-sexto.color-acento-contenido
            p Almacenamiento inadecuado
          img(src='@/assets/curso/tema2/img26.png' alt="Imagen decorativa")
        .col-md-7.mb-4.mb-md-0(data-aos="fade-left")
          br
          br
          br
          br
          p.mb-4 A las telas blancas hay que darles un tratamiento especial de ubicación. De acuerdo con las consideraciones que se le dé al manejo de las materias primas se puede contar con unos materiales en estado óptimo para ser trabajados de manera acertada y con el mejor aprovechamiento, evitando despilfarros o problemas de deterioro y, que después no se puedan utilizar como se desea.
          p Deben estar los materiales muy bien identificados con su ubicación para que sean accesibles de manera rápida, y con criterios de tener desplazamientos menores.
      .row.justify-content-center.p-4
        .col-md-3.mb-4.mb-md-0(data-aos="fade-right")
          .titulo-sexto.color-acento-contenido
            p Bodega de telas
          img(src='@/assets/curso/tema2/img27.png' alt="Imagen decorativa")
        .col-md-7.mb-4.mb-md-0(data-aos="fade-left")
          br
          br
          br
          .h4  Recomendaciones generales para el almacenamiento
          ul.lista-ul
            li 
              i.fas.fa-angle-right
              |	No es conveniente dejar que la luz esté directamente y durante mucho tiempo sobre los rollos, ya que afectan su presentación, debido a que los componentes de la tela reaccionan con los rayos de luz y pueden producir deterioro.
            li 
              i.fas.fa-angle-right
              |	Para los tejidos blancos y/o claros se sugiere que estén protegidos con bolsas oscuras.
            li 
              i.fas.fa-angle-right
              |	Para eliminar o controlar el riesgo de contagio con humedad del piso y suciedades se utilizan estanterías o estibas para colocar los rollos.
            li 
              i.fas.fa-angle-right
              |	Para evitar que los rollos se deformen en su almacenamiento se recomienda ubicarlos de forma horizontal en la misma dirección y con el menor número de niveles.
    .tarjeta.color-light-green.mb-4(data-aos="zoom-in-up")
      .row.justify-content-center.p-4
        .col-md-4.mb-4.mb-md-0
          p Para profundizar en el almacenamiento de telas se recomienda leer el documento:
        .col-md-4.mb-4.mb-md-0
          a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo2_Almacenamiento_de_telas_y_sus_cuidados.pdf')" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-pdf.svg" alt="Imagen decorativa")
            .anexo__texto
              p Almacenamiento de telas y sus cuidados

    separador
    #t_2_7.titulo-segundo(data-aos="fade-right")
      .h2 2.7 Reposo de telas
    
    p.mb-4(data-aos="fade-left") Las telas luego del proceso de tejeduría y al ser dispuestas en rollos, para evitar su deterioro y aprovechar el almacenaje adquieren tensiones en sus tejidos. Una característica de los tejidos en mayor o menor grado de acuerdo con su composición es la de estirar y recuperar. Reposar la tela consiste en desplegarla o desenrollarla antes de extenderla para que se libere de las tensiones adquiridas en su presentación en rollo, al perder las tensiones, adquiere sus dimensiones normales. Un ejemplo en la siguiente figura.

    .col-xl-10.m-auto.mt-5(data-aos="flip-up")
      .titulo-sexto.color-acento-contenido
        p.mb-0 Telas 
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/tema2/img28.png')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 Si no se tiene en cuenta esta precaución y se extiende sin dejar reposar la tela, esta recupera sus dimensiones normales, y al cortar las piezas saldrán con medidas diferentes a las de los moldes originales, causando un daño, que en muchos casos es irreparable, ya que se tiene que aprovechar este corte en otro tipo de prenda con dimensiones más pequeñas; el tiempo que se deba dejar reposando una tela depende de su composición y de sus fibras con mayor o menor elasticidad.



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

<style lang="sass" scoped></style>
