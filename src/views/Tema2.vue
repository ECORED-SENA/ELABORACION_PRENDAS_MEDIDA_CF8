<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 2
      h1 Técnicas y proceso para arreglos de prendas

    p.mb-4 Las técnicas y procesos para el arreglo de las prendas inician con el análisis antropométrico y se desarrollan según la necesidad del cliente. Estos arreglos son adaptaciones y movimientos que se pueden aplicar tanto en los moldes como las prendas desarmadas, por lo que en este apartado se conocerán técnicas para alargar, acortar, ampliar, modificar cortes, hombros, tiro, costura y mangas.
    
    .row.mb-4
      .col-1
      .col-6.d-flex    
          .cajon.color-primario.fondo-a.p-4.d-flex.align-items-center 
            p Para alargar o ampliar una prenda se pueden reducir costuras, soltar ruedos y pinzas o añadir piezas textiles en boleros o en cortes; para reducir o acortar es más fácil ya que se tiene tela de sobra.
      .col-4
        figure
          img(src='@/assets/curso/tema2/img01.svg', alt='Texto que describa la imagen')          
      .col-1

    p.mb-4 Cuando se está alargando o acortando lo más recomendable es aplicarlo en partes bajas de la pieza que no comprometan otras partes, tal como lo indica la línea en contraste de las imágenes.

    figure.mb-4
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)    
    
    p.mb-4 En las técnicas y procesos para los arreglos de prendas, también existen aquellos que se enfocan en los insumos artesanales. Cuando se habla de técnicas manuales utilizadas por modistas y sastres, se refiere a <b>una cadena de pasos ejecutados con el cuidado en cada detalle y de forma artesanal</b>, por ende, los consumidores de estos productos valoran el arte que se esconde en cada prenda que adquiere un valor por este proceso.
    p.mb-4 De otra parte, <b>los tejidos utilizados en vestidos de noche, como terciopelo, raso y chiffon, son delicados y requieren mucha atención en su manipulación</b>. El terciopelo se cose en la dirección del pelo y las costuras se hacen con puntadas pequeñas para que no se mueva al montarlo. Las ballenas también conocidas como varillas en los corsés, generalmente se unen a mano y como suelen cortarse en telas de cuerpos finos o intermedios que requieren guateado, donde se forran en 2 entretelas, ubicando la más gruesa para el lado del forro.
    
    figure.mb-4
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)    

    //.align-items-center
    //.justify-content-center

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
