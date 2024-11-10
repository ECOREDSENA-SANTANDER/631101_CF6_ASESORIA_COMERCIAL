<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-primario
      .titulo-principal__numero
        span 3
      h1 Demostraciones

    .row.justify-content-center.align-items-center(data-aos="zoom-in").mb-5
      .col-sm-12.col-md-12.col-lg-12
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img1.png')})`}"
          )
          .bloque-texto-g__texto.p-5
            br
            p En el proceso de ventas la demostración se define como presentar pruebas y hechos que afirmen lo que se dice de un producto. La demostración es uno de los momentos más importantes en los cuales el consumidor puede estar en contacto con el producto y, a su vez, se pueden fortalecer sus argumentos y finalizar con el cierre de venta.
            br
            br
            p Puede decirse que el momento de la demostración es el más importante y decisivo que tiene un vendedor para cerrar un proceso de venta.
            br
            br



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
