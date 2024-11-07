<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-primario
      .titulo-principal__numero
        span 2
      h1 Exhibición

    .row.justify-content-center.align-items-center(data-aos="zoom-in").mb-4
      .col-sm-12.col-md-12.col-lg-12
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img1.png')})`}"
          )
          .bloque-texto-g__texto.p-5
            br
            p Las actividades que permiten mostrar los productos en el punto de venta y colocarlos al alcance del cliente para su compra se denominan exhibición. Esta se concibe como la clasificación, selección, colocación y presentación de los productos en el lugar de venta, con el objetivo de atraer la atención tanto del comprador actual como del potencial.
            br
            br
            p La exhibición del producto, en el punto de venta, se realiza con el uso de muebles o elementos especiales que lo ponen al alcance de los clientes.
            br
            br

    p.mb-5.text-center Entre los propósitos de la exhibición, se tienen:


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

<style lang="sass"></style>
