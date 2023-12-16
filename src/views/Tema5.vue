<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 5
      h1 Corte
    
    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-lg-10.mb-4.mb-lg-4
        .bloque-texto-g.color-light-orange.p-3.p-sm-4.p-md-5.mb-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema5/img01.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 Esta actividad se refiere a deslizar una herramienta llamada cortadora (las hay de varios tipos) por las líneas dibujadas en el trazo y sobre las telas extendidas.
      
    .tarjeta.color-light-gray
      .row.justify-content-center
        .col-lg-11
          SlyderA(tipo="b")
            .row.justify-content-center
              .col-12.mb-4
                .tarjeta.color-light-orange.p-3
                  .row.align-items-center.mb-4
                    .col-4
                      img(src='@/assets/curso/tema5/img02.svg' alt="Imagen decorativa")
                    .col-4 
                      h2.text-center Técnicas de corte
                    .col-4
                      img(src='@/assets/curso/tema5/img03.svg' alt="Imagen decorativa")
              
              p.mb-4 Existen muchas maneras de deslizar los útiles de corte por las líneas trazadas que corresponden a los trazos.
              p.mb-4 Para lograrlo hay técnicas manuales y técnicas sistematizadas, el valor que se invierte para adquirir cada una es proporcional a los resultados obtenidos.
              .row.justify-content-center
                .col-lg-5.mb-4
                  img(src='@/assets/curso/tema5/img04.png' alt="Imagen decorativa")
                .col-lg-5.mb-4
                  .tarjeta.color-secundario-punteado.p-0.mb-4
                    .tarjeta.color-primario.p-1
                      h4.text-center Convencional o manual
                  .tarjeta.color-secundario-punteado.p-3
                    p Se refiere a la manera como se viene cortando desde el inicio de la industrialización de la moda, utilizando máquinas y herramientas, con tracción manual, iguales o con muy pequeñas variaciones desde hace más de 60 años. 
                    p Estas máquinas cortadoras son orientadas de manera manual.

              .col-lg-5.mb-4
                img(src='@/assets/curso/tema5/img05.png' alt="Imagen decorativa")
              .col-lg-5.mb-4
                .tarjeta.color-secundario-punteado.p-0.mb-4
                  .tarjeta.color-secundario.p-1
                    h4.text-center Automatizado
                .tarjeta.color-secundario-punteado.p-3
                  p Existen sistemas de extendido y corte automatizados en el mercado. 
                  p Las órdenes de funcionamiento las emiten desde un software que abarca desde la elaboración de moldes, trazos y órdenes para extender, hasta finalizar con el proceso de cortar. 
                  p El extendido y el corte se realizan en una mesa diseñada para que pueda funcionar articulada con el software.
          
            .row.justify-content-center
              .tarjeta.color-light-orange.p-3.mb-4
                .row.align-items-center
                  .col-4
                    img(src='@/assets/curso/tema5/img06.svg' alt="Imagen decorativa")
                  .col-4 
                    h2.text-center Herramientas y equipos de corte
                  .col-4
                    img(src='@/assets/curso/tema5/img07.svg' alt="Imagen decorativa")
                    
              p.mb-4 En el área de trazo y corte se utiliza una serie de máquinas y herramientas propias para ese fin, unas con más nivel de tecnología que otras, entre ellas, unas diseñadas para grandes volúmenes y otras para pequeños lotes de producción.
              p.mb-4 Las más frecuentemente utilizadas son las siguientes:

              .row.justify-content-center
                .col-lg-11
                  .tarjeta-avatar-b.mb-4
                    img.iconV(src='@/assets/curso/tema5/img08.png' alt='AvatarTop')
                    .tarjeta.color-acento-contenido-punteado.p-0
                      .row.p-0
                        .col-2
                        .col-lg-10.mb-4
                          .tarjeta.color-acento-contenido-punteado.p-0
                            .tarjeta.color-acento-contenido.p-3
                              .h4.text-white Cortadoras de cuchilla vertical
                      .row.justify-content-center
                        .col-lg-10.mb-4
                          p.mb-4 Máquina eléctrica, provista de una cuchilla ubicada de manera vertical, que al activarla realiza un movimiento perpendicular y que le permite al empujarla avanzar, cortando las telas extendidas y permitiendo que las piezas queden sueltas para clasificarlas, y luego pasar a ensamblarlas, esta viene provista de unas cintas afiladoras que son intercambiables y que sirven al activarlas, para mantener la capacidad de corte en óptimas condiciones.
                          p.mb-4 Este tipo de máquina es empujada u operada manualmente por el encargado de esta función, se mueve la cortadora dentro del tendido, dejando las piezas separadas; el cambio de las cuchillas lo realiza el mismo operario, las cuchillas de estas máquinas vienen en longitudes de 4”, 6”, 8”, 10” (pulgadas). El material sobrante de tela que no corresponde a piezas que se van a confeccionar se llama retal, y hace parte del desperdicio.

                  .tarjeta-avatar-b.mb-5
                    img.iconV(src='@/assets/curso/tema5/img09.png' alt='AvatarTop')
                    .tarjeta.color-white-punteado.p-0
                      .row.p-0
                        .col-2
                        .col-lg-10.mb-4
                          .tarjeta.color-white-punteado.p-0
                            .tarjeta.color-secundario.p-3
                              h4.text-white Cortadora manual profesional
                      .row.justify-content-center
                        .col-lg-10.mb-4
                          p La fuente de su energía son baterías, se acciona de manera manual, no tiene la misma potencia que la eléctrica, sirve para cortar lotes de pocas unidades

                  .tarjeta-avatar-b.mb-5
                    img.iconV(src='@/assets/curso/tema5/img10.png' alt='AvatarTop')
                    .tarjeta.color-acento-botones-punteado.p-0
                      .row.p-0
                        .col-2
                        .col-lg-10.mb-4
                          .tarjeta.color-acento-botones-punteado.p-0
                            .tarjeta.color-acento-botones.p-3
                              h4.text-white Corte sin fin
                      .row.justify-content-center
                        .col-lg-10.mb-4
                          p En el caso de utilizar este tipo de máquina hay que tener en cuenta que es una máquina fija, inmóvil, estática y que el que se mueve es el tejido, se utiliza para cortes rectos, al empujar el material se le va dando la forma deseada, siguiendo las líneas del trazo.
                          p El tiempo que se emplea es mínimo, se pueden cortar grandes bloques de material, y hay seguridad en la relación útil de corte y materiales.

    separador
    #t_5_1.titulo-segundo(data-aos="fade-right")
      .h2 5.1 Control de calidad en el corte
    
    p.mb-4(data-aos="fade-left") Se puede definir calidad como el cumplimiento de especificaciones, teniendo en cuenta que estas o los requisitos del área de trazo y corte a cumplir son:

    .row.justify-content-center.mb-4(data-aos="zoom-in-up")
      .col-lg-10
        .tarjeta.color-light-green.p-0
          .row.align-items-center.mb-4
            .col-lg-1
            .col-lg-5
              br
              ul
                li 
                  i.fas.fa-angle-right
                  | Moldería.
                li 
                  i.fas.fa-angle-right
                  | Tejidos solicitados, principales y complementarios.
                li 
                  i.fas.fa-angle-right
                  | Cantidades totales por talla y color.
                li 
                  i.fas.fa-angle-right
                  | Superficie de la tela.
                li 
                  i.fas.fa-angle-right
                  | Ancho del trazo.
                li 
                  i.fas.fa-angle-right
                  | Numeración y alistamiento.
            .col-1
            .col-lg-5
              img(src='@/assets/curso/tema5/img11.png' alt="Imagen decorativa")

    p.mb-4(data-aos="fade-right") Desde el proceso de calidad se planean actividades que tengan como fin lograr el cumplimiento y evitar no conformidades.   Para hacer seguimiento al cumplimiento de especificaciones en las actividades que se realizan en el área de trazo y corte se recomienda el siguiente cuadro, basado en la herramienta de control PHVA.
    p.mb-4(data-aos="fade-left") A continuación, un ejemplo que muestra actividades asociadas al proceso que se debe controlar, qué tipo de control se debe hacer, la herramienta o instrumento a utilizar y cuál acción de mejora implementar.

    .titulo-sexto.color-acento-contenido(data-aos="zoom-in-down")
      h5 Tabla 2
      | Formato control de calidad
    .tabla-a.color-acento-contenido.mb-5.p-0(data-aos="zoom-in-up")
      table
        thead
          tr
            th
            th
            th  Formato control de calidad
            th
            th
          tr
            th
            th Colección: otoño
            th Ref.: 7000
            th Fecha:  abril 20/20
            th
          tr
            th Actividades
            th Control de calidad
            th Documento y/o herramienta
            th Hallazgos
            th Acciones de mejora
        tbody
          tr
            td Extender la tela
            td Cantidad de las capas de tela necesarias en la mesa de corte.
            td Ficha técnica que indique la cantidad de tela.
            td La tela estaba tensionada.
            td La tela debe dejarse reposar antes de proceder al corte.
          tr
            td Poner los moldes
            td Colocar el trazo sobre la tela, teniendo presente que no quede por fuera ninguna pieza.
            td Moldería y revisión de la ficha técnica.
            td La moldería quedó del tamaño adecuado a la tela.
            td Se evidenció que las piezas de las prendas caben a la perfección en el tamaño de la tela.
          tr
            td Cortar
            td Se procede a cortar los moldes de forma manual o a máquina.
            td Patrones, moldes.
            td Coinciden moldes y piezas cortadas.
            td Mantener el proceso.
          tr
            td Separar las piezas cortadas
            td Identificar la cantidad de piezas por prenda.
            td Muestra física.
            td La cantidad de piezas fue la indicada.
            td Continuar con este control. 
          tr
            td Empacar
            td Empacar cada paquete con su debido registro y código.
            td Ficha de registro.
            td La cantidad de paquetes fue la indicada.
            td El empaquetado de todo debe ser cuidadoso para que no falte ninguna pieza. 
          tr
            td Registro
            td Tener el registro de cuántas piezas por paquete hay y su respectivo código.
            td Ficha de registro.
            td Todas las piezas fueron hechas y registradas con éxito.
            td Corroborar que todas las piezas vayan completas. 

    h4.mb-4(data-aos="fade-right") Explicación de la tabla 2:

    p.mb-4(data-aos="fade-left") El objetivo es hacer seguimiento a las actividades que se realizan en el área de trazo y corte para verificar que sí se están cumpliendo las especificaciones requeridas.

    .row.mb-4(data-aos="zoom-in")
      .col-lg-10
        .tarjeta.color-gray-lineal.p-0
          .row.align-items-center.d-flex
            .col-4
              .tarjeta.color-primario.p-4
                .h4.text-white Columna actividades 
            .col-8
              p.mb-4 Se refiere a la actividad a la cual se le va a realizar el control de calidad.
        .tarjeta.color-gray-lineal.p-0
          .row.align-items-center.d-flex   
            .col-4
              .tarjeta.color-primario.p-4
                br
                .h4.text-white Columna control de calidad
                br
            .col-8
              p.mb-4 Indica qué aspecto de esa actividad se controlará, por ejemplo, si la actividad es la extendida se deben especificar todos los aspectos que componen la extendida (seleccionar telas, reposos, anchos, eliminar imperfectos, cantidad de tela, cantidad de tallas, etc.) y cuál de ellos se va a controlar.
        .tarjeta.color-gray-lineal.p-0
          .row.align-items-center.d-flex
            .col-4
              .tarjeta.color-primario.p-4
                .h4.text-white Columna documento/herramienta
            .col-8
              p.mb-4 Se refiere al instrumento o herramienta que se utiliza y que sirve para poder validar el cumplimiento del requisito o especificación, pueden ser documentos como fichas técnicas, órdenes de producción o similares, también se puede hacer uso de muestras físicas.
        .tarjeta.color-gray-lineal.p-0
          .row.align-items-center.d-flex
            .col-4
              .tarjeta.color-primario.p-4
                br
                .h4.text-white Columna hallazgos
                br
            .col-8
              p.mb-4 Aquí se consignan los hallazgos que se encontraron en la revisión o verificación, siempre dentro de los procesos productivos es importante realizar procesos de revisión, los cuales permiten encontrar si lo que se está haciendo está bien o no. En esta columna se registran los hallazgos.
        .tarjeta.color-gray-lineal.p-0
          .row.align-items-center.d-flex
            .col-4
              .tarjeta.color-primario.p-4
                .h4.text-white Columna acciones de mejora
            .col-8
              p.mb-4 De acuerdo con los hallazgos se toman decisiones sobre las acciones de mejora que se deben tomar.

    separador
    #t_5_2.titulo-segundo(data-aos="fade-right")
      .h2 5.2 Recomendaciones para el área de trazo y corte
    
    p.mb-4(data-aos="fade-left") A continuación, se definen algunas recomendaciones para garantizar la calidad en las secciones que realizan actividades de corte:

    .row
      .col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
        img(src='@/assets/curso/tema5/img12.png' alt="Imagen decorativa")
      .col-lg-7.mb-4.mb-lg-0(data-aos="fade-left")
        .row
          .col-2.mb-2
            img(src='@/assets/curso/tema5/img13.svg' alt="Imagen decorativa")
          .col-10
            p.mb-3 Al recibir las telas asegurarse de tener claro:  el nombre de la tela, la cantidad, para qué lotes está destinada, dónde y cómo se va a almacenar, etc.
          .col-2.mb-2
            img(src='@/assets/curso/tema5/img14.svg' alt="Imagen decorativa")
          .col-10 
            p.mb-4 Si las telas necesitan reposo previo, ejecutarlo.
          .col-2.mb-2
            img(src='@/assets/curso/tema5/img15.svg' alt="Imagen decorativa")
          .col-10
            p.mb-4 Al extender identificar las posibles irregularidades de la tela, proceder a marcarlas para luego reponer la pieza o cortar y sacar ese daño.
          .col-2.mb-2
            img(src='@/assets/curso/tema5/img16.svg' alt="Imagen decorativa")
          .col-10
            p.mb-4 Cuando se está cortando poner mucho cuidado con los “vencimientos de las telas”, con la posición y profundidad de los piquetes.
          .col-2.mb-2
            img(src='@/assets/curso/tema5/img17.svg' alt="Imagen decorativa")
          .col-10
            p.mb-2 Al momento de tiquetear debe tener en cuenta no colocar el tiquete donde van a ir costuras o piezas como tapas, bolsillos traseros, charreteras o pretinas, se recomienda etiquetar por el derecho de la tela para que cuando se vaya construyendo la prenda no quede escondida.
          .col-2.mb-2
            img(src='@/assets/curso/tema5/img18.svg' alt="Imagen decorativa")
          .col-10
            p.mb-2 Al amarrar las piezas se recomienda juntar las piezas iguales, por ejemplo, todas las aletillas juntas, todas las relojeras juntas, todos los bolsillos juntos, etc., ya que la primera operación que se hace en las plantas es precisamente juntar las piezas iguales para cargarlas a las máquinas con lo que se gana tiempo.
          .col-2.mb-2
            img(src='@/assets/curso/tema5/img19.svg' alt="Imagen decorativa")
          .col-10
            p.mb-4 Al ingresar los lotes a las plantas hacer entrega de toda la información y elementos que se tengan, adicional hacer una remisión en la que se especifique: corte, referencia, cantidades por talla, etc.
          .col-2.mb-2
            img(src='@/assets/curso/tema5/img20.svg' alt="Imagen decorativa")
          .col-10
            p.mb-4 Los pasadores deben venir cortados a la medida que el cliente los necesita, no de otra, ya que esto lleva a afinarlos, en lo posible enviar un retazo para posibles reposiciones.
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
<style lang="sass" scoped></style>
