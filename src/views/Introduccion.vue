<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .bloque-texto-a.color-primario.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-4.mb-4.mb-lg-0
          h2.mb-0 Bienvenidos al componente formativo:  Confección de prendas de vestir
        .col-lg-8
          .bloque-texto-a__texto.p-4
            p La confección de prendas de vestir es uno de los pilares fundamentales en el oficio de la modistería. En este componente se relacionan técnicas que requieren de una gran precisión y que requieren de la utilización de máquinas e insumos para constatar que el patronaje y los trazos sean coherentes con la prenda deseada. Siguiendo el paso a paso de la interpretación de diseños bajo los lineamientos establecidos garantizando su calidad. 
    
    p.mb-5 En el desarrollo de proyectos que tienen como finalidad la elaboración de prendas de vestir, es elemental incorporar los métodos y procedimientos apropiados con altos modelos de calidad. Por ello, <b>este componente trata de la modificación de prendas desde un análisis del cuerpo, anomalías de cuerpos y adaptación de la prenda acorde a las necesidades y asesoría al cliente.</b> Durante el proceso de arreglos se aplicarán técnicas de modistería y procesos artesanales, desde los análisis del cuerpo hasta la adaptación de las piezas según los requerimientos de ajuste, el desarmado y procesos de adaptación manuales y en máquinas de coser. La comunicación con el cliente y una asesoría según la silueta y anomalías del cuerpo son las herramientas clave para lograr una atención óptima y acorde a las necesidades reales.

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
