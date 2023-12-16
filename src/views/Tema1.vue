<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Generalidades de trazo y corte
    
    p.mb-4(data-aos="fade-right") En el siguiente recurso se presentan las generalidades básicas a tener en cuenta en las operaciones de trazo y corte.

    figure.mb-5(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2eLBX1rwZXw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    p.mb-4(data-aos="fade-right") La cadena de trazo y corte es uno de los procesos de mayor importancia en el proceso de la manufactura textil. Un error implica poner en riesgo la producción y genera pérdidas económicas, por ello, tenga presente que la tela representa un 80% del costo final de la prenda.

</template>

<script>
export default {
  name: 'Tema1',
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
