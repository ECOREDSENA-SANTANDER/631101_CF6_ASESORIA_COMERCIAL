<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-primario
      .titulo-principal__numero
        span 2
      h1 Exhibición

    .row.justify-content-center.align-items-center(data-aos="zoom-in").mb-5
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

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-sm-12.col-md-10
        img(src='@/assets/curso/temas/tema2/img2.png', alt='')
      .col-lg-6.col-sm-12.col-md-12
        ol.lista-ol--cuadro.lista-ol--separador.fa-ol
          li
            .lista-ol--cuadro__vineta
              span 1
            span.mb-0 Aumentar la atención de los clientes sobre los productos.
          li
            .lista-ol--cuadro__vineta
              span 2
            span.mb-0 Aumentar la fidelidad del cliente hacia el punto de venta.
          li
            .lista-ol--cuadro__vineta
              span 3
            span.mb-0 Ofrecer el producto con creatividad.
          li
            .lista-ol--cuadro__vineta
              span 4
            span.mb-0 Brindar comodidad al cliente para adquirir el producto.
          li
            .lista-ol--cuadro__vineta
              span 5
            span.mb-0 Apoyar las actividades promocionales en el punto de venta.
          li
            .lista-ol--cuadro__vineta
              span 6
            span.mb-0 Generar recordación en el consumidor acerca del producto que necesita.
          li
            .lista-ol--cuadro__vineta
              span 7
            span.mb-0 Motivar la compra “impulsiva” del producto (compra irracional). 

    .row
      .cajon.color-acento-contenido.p-4.mb-4
        p El espacio en el punto de venta juega un papel importante en la exhibición del producto, que puede organizarse de acuerdo con la disposición que se tenga en el lugar. El administrador, como responsable del sitio y de la exhibición, deberá organizarlo según las secciones, espacios de circulación, ubicación de zonas y puntos de venta fríos o calientes, ubicación de elementos externos al establecimiento y áreas complementarias.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.col-md-12.col-sm-12
          .titulo-sexto.color-secundario.mb-4
            h5 Figura 4. 
            | Zonas frías y calientes según los accesos y la circulación
          img(src='@/assets/curso/temas/tema2/fig1.png', alt='La imagen presenta tres ejemplos de zonas frías y calientes distribuidas en punto de venta según los accesos y la circulación. De izquierda a derecha se presentan: zona con un punto de acceso, zona con dos puntos de acceso y zona con cuello de botella.')
          figcaption Nota. Tomada de Seggiaro (2017)

    p.mb-4 Este análisis debe realizarse de acuerdo con el espacio en el punto de venta, y definir los tipos de exhibición que se pueden aplicar. Los consumidores realizan gran parte de las decisiones de compra directamente en el piso de ventas, por lo que, una exhibición efectiva de los productos puede influir en varias de ellas.

    .row.justify-content-center.align-items-center.mb-5
      TabsC.color-acento-botones
        .py-3.py-md-4(titulo="Exhibición vertical").mb-0
          .row.justify-content-center
            .col-md-4
              img(src='@/assets/curso/temas/tema2/tab1-1.png', alt='Texto que describa la imagen')
            .col-md-7.mb-4.mb-md-0
              h4.mt-4 Exhibición vertical
              p En las exhibiciones verticales se organiza un mismo producto de arriba hacia abajo. Donde la exhibición de colores se recomienda hacerla de claro a oscuro y de izquierda a derecha.
        .py-3.py-md-4(titulo="Exhibición horizontal").mb-0
          .row.justify-content-center
            .col-md-4
              img(src='@/assets/curso/temas/tema2/tab1-2.png', alt='Texto que describa la imagen')
            .col-md-7.mb-4.mb-md-0
              h4.mt-4 Exhibición horizontal
              p El producto se dispone de izquierda a derecha en los distintos niveles de visibilidad: nivel de la cabeza, nivel de los ojos, nivel de las manos y nivel del suelo.
        .py-3.py-md-4(titulo="Exhibición bloque").mb-0
          .row.justify-content-center
            .col-md-4
              img(src='@/assets/curso/temas/tema2/tab1-3.png', alt='Texto que describa la imagen')
            .col-md-7.mb-4.mb-md-0
              h4.mt-4 Exhibición bloque
              p La marca se agrupa en una estantería ocupando dos o tres peldaños o entrepaños.
        .py-3.py-md-4(titulo="Exhibición mixta").mb-0
          .row.justify-content-center
            .col-md-4
              img(src='@/assets/curso/temas/tema2/tab1-3.png', alt='Texto que describa la imagen')
            .col-md-7.mb-4.mb-md-0
              h4.mt-4 Exhibición mixta
              p Puede decirse que es una combinación de la exhibición vertical y la horizontal. Se utiliza para llamar la atención de los consumidores de una forma más efectiva.
          
    p De acuerdo con la estrategia del comercio, pueden emplearse otras formas de exhibición, haciendo una combinación de las anteriores, o bien organizando los productos de una forma creativa, que pueda resultar asertiva al generar ventas.
    p.mb-4 Otro factor importante al momento de exhibir el producto es el uso de las vitrinas, aquí se muestra el producto en diferentes ángulos y, a pesar de que el consumidor no pueda acceder al producto, igualmente se siente atraído por este. Las vitrinas pueden clasificarse de la siguiente forma:

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
