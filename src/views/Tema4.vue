<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-primario
      .titulo-principal__numero
        span 4
      h1 Presentaciones

    .row.justify-content-center.align-items-center(data-aos="zoom-in").mb-5
      .col-sm-12.col-md-12.col-lg-12
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema4/img1.png')})`}"
          )
          .bloque-texto-g__texto.p-5
            br
            p Una presentación de ventas se puede definir como un guión o argumento que el equipo de ventas de una organización utiliza para ofrecer sus productos a los clientes. Esta presentación puede llevarse a cabo en persona, por teléfono, videollamada, videoconferencia, o cualquier otro medio disponible. No obstante, algunas empresas consideran que el contacto personal es de mayor importancia.
            br
            br
            p Una presentación en el proceso de ventas no se limita a una llamada o a un encuentro personal; forma parte de un conjunto de acciones diseñadas para cerrar la venta. Esta presentación puede incluir una conversación inicial, una reunión, una llamada o videollamada, el envío de una propuesta e incluso una demostración.
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
