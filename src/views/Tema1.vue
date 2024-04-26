<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Concepto de salud mental positiva 
    .fondo-1.mn.p-5
      p.mb-5(data-aos='fade-right') La Organización Mundial de la Salud (OMS) define la salud mental como: 
      .row.justify-content-center.mb-4
        .col-lg-5.mb-lg-0.mb-3
          .bloque-texto-c.color-acento-contenido.p-4
            i.fas.fa-quote-right(style="color: #12263f; font-size: 30px")
            h4.mb-2 Un estado de bienestar en el que el individuo desarrolla sus capacidades, puede afrontar las tensiones normales de la vida, trabajar de manera productiva y fructífera, y es capaz de contribuir a su comunidad.
            span.fst-italic - (World Health Organization, 2001).
        .col-lg-3.col-5: img(src='@/assets/curso/temas/3.png', alt='').mb-4.mb-lg-0
        .col-lg-4
          p La salud debe concebirse de manera integral, considerando que los aspectos #[b biológicos, psicológicos y sociales] forman parte del #[span.color-acento-contenido bienestar] y convergen constantemente.  
          .cajon-b.color-secundario.p-3
            p.mb-0 #[b Por ejemplo] 
              br
              br
              |Es conocido que las situaciones de estrés no manejadas adecuadamente pueden provocar afectaciones físicas, como enfermedades cardiovasculares o problemas gastrointestinales. Asimismo, el diagnóstico de una enfermedad física grave puede desencadenar angustia y depresión. De la misma manera, las condiciones sociales pueden generar estrés, angustia y ansiedad, como sucede en casos de dificultades económicas, desempleo o exclusión social. 
      h5 En la siguiente figura  se resume el concepto de salud mental.
      .row.justify-content-center.mb-5
        .col-lg-8
          .titulo-sexto.color-acento-contenido(data-aos='fade-right')
            h5 Figura 1.
            span Concepto de salud mental
          img(src='@/assets/curso/temas/4.svg', alt='Estado de bienestar que permita afrontar la vida, relacionarse, trabajar y aportar al desarrollo de la comunidad.Debe entenderse como un proceso dinámico e integral, donde lo biológico, psicológico y social confluyan de forma permanente.Los determinantes sociales afectan de manera directa la salud mental de las personas: violencia, pobreza, exclusión.Factores como la soledad, la carencia afectiva y las débiles redes de apoyo, inciden negativamente en el bienestar de las personas en el ámbito individual y colectivo.') 
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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

<style lang="sass">
.fondo-1
  background-image: url('../assets/curso/temas/fondo-1.svg')
  background-repeat: no-repeat
  background-position: center
  background-size: contain
</style>
