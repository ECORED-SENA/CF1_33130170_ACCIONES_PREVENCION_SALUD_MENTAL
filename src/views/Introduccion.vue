<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .fondo-intro.mn.p-5
      p.mb-5(data-aos='fade-right') Este componente abordará los conceptos de salud mental desde una perspectiva positiva y el enfoque de derechos.  
      .tarjeta.color-acento-contenido.p-4.mb-5
        .row.justify-content-center.align-items-center
          .col-lg-2.col-4.mb-lg-0.mb-3: img(src='@/assets/curso/temas/1.svg', alt='')
          .col-lg-10
            p.mb-0 Al hablar de #[b salud mental] desde una perspectiva positiva, se refiere a la preservación de un auténtico estado de bienestar (ausencia de enfermedad) que permite a las personas afrontar la vida, relacionarse con su entorno y contribuir a su desarrollo. De esta manera, se pueden alcanzar altos niveles de satisfacción en todas sus dimensiones: individual, social y emocional. Sin embargo, este estado de bienestar puede verse afectado por múltiples factores que, aunque manejables adecuadamente, no causarán impactos reales sobre la salud. 
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-7(data-aos="fade-right")
          p.mb-0  Pero, si no se logra manejar de manera apropiada, la salud mental puede verse comprometida, #[b desencadenando trastornos mentales.] Para prevenir y manejar estas afectaciones, es necesario contar con información, conocer y hacer valer los derechos que, en materia de salud mental, poseen los colombianos.  
            br
            br
            |Asimismo, es fundamental tener claridad sobre los factores que inciden en el desarrollo de diferentes trastornos o enfermedades. Para ello, se tomará como referencia el concepto de salud mental establecido por la Organización Mundial de la Salud (OMS) y contemplado en los planes y programas delimitados por el Plan Decenal de Salud Pública 2022-2031 en la dimensión de convivencia social y salud mental. Se abordará la Ley 1616 de 2013, la cual establece la perspectiva de derechos en esta materia, y se conocerán los beneficios y el acceso al sistema en caso de requerir atención en salud mental.
        .col-lg-5.col-7(data-aos="fade-left"): img(src='@/assets/curso/temas/2.svg', alt='')
        
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass">
.fondo-intro
  background-image: url('../assets/curso/temas/fondo-intro.svg')
  background-repeat: no-repeat
  background-position: center
  background-size: contain
</style>
