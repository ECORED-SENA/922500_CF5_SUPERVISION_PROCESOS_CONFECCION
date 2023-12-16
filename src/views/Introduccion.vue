<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .tarjeta.color-sky-blue.p-4
      .row
        .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right")
          img(src='@/assets/curso/intro/img01.svg' alt="Imagen decorativa")
        .col-lg-6.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-5
            img(src='@/assets/curso/intro/img02.svg' alt="Imagen decorativa")
          p.mb-4 La fabricación de ropa incluye numerosas actividades para hacer una prenda, incluye procesos como corte, costura y acabado. Todo el proceso de fabricación se divide en una serie de suboperaciones necesarias para la confección de una prenda en particular; algunas de estas operaciones varían según el tipo de equipo disponible, los métodos de trabajo utilizados y las habilidades de los trabajadores, siendo los trazos y cortes dos procesos principales de producción de prendas.

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
