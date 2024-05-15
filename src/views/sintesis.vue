<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 A continuación, se presenta una síntesis de la temática estudiada en el componente formativo

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="El mapa conceptual presenta la síntesis del componente sobre la salud mental en Colombia alrededor de tres núcleos principales: definiciones y conceptos de salud mental positiva; el marco normativo que incluye leyes y resoluciones específicas; y un tercer núcleo sobre los factores y riesgos asociados con la salud mental, incluyendo los determinantes sociales y la violencia intrafamiliar, así como las estrategias de afrontamiento de crisis. Finalmente, se destacan los beneficios y coberturas disponibles en el ámbito de la salud mental, tales como terapias y servicios de hospitalización.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
