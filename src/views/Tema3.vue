<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Principios básicos de usabilidad

    figure.mt-5
      img(src="@/assets/curso/temas/tema-3-1.svg", alt="")
    .row.mt-5
      .col-12.col-lg-9
        p La usabilidad es un término que recoge una valoración de la calidad de la experiencia de usuario cuando interactúa con un producto o sistema. Para medirla se hace a través del estudio de la relación que se produce entre las herramientas diseñadas y los usuarios que las usan, para determinar la eficiencia en el uso de los diferentes elementos ofrecidos en las pantallas y la efectividad en el cumplimiento de las tareas que se pueden llevar a cabo a través de ellas. En conclusión, se puede definir la usabilidad como la disciplina que estudia el diseño de aplicaciones móviles o sitios web para que los usuarios puedan interactuar de forma fácil, fluida e intuitivamente.
        p.mt-3 Existen varios aspectos relacionados con el uso de aplicaciones y la manera en que las personas se relacionan con esas aplicaciones que se les ofrecen. Básicamente estos estudios han proporcionado un conjunto de comprobación de estos aspectos, como mecanismo de variación. Dicha validación debe ser hecha a través de diferentes aspectos, entre los que se cuentan los siguientes:
      .col-4.col-lg-3.offset-4.offset-lg-0
        figure
          img(src="@/assets/curso/temas/tema-3-2.svg", alt="")
    .row.mt-5
      .col-8.offset-2.rounded-20.borde-primario-4
        .row.py-2
          .col-4.align-self-center
            figure.borde-gris-der
              img.imagen_flotante_animada(data-aos="fade-up" src="@/assets/curso/temas/tema-3-3.svg", alt="").w-50.margin-0-auto
          .col-8.pt-4.px-4
            .h4 Facilidad de aprendizaje
            p.mt-3 Se puede emplear una unidad de tiempo para determinar lo que demoran los usuarios en usarla de manera correcta y realizar las operaciones básicas y comunes.
    .row.mt-5
      .col-8.offset-2.rounded-20.borde-primario-4
        .row.py-3
          .col-4.align-self-center
            figure.borde-gris-der
              img.imagen_flotante_animada(src="@/assets/curso/temas/tema-3-13.svg", alt="").w-25.margin-0-auto
          .col-8.pt-4.px-4
            .h4 Facilidad y eficiencia de uso
            p.mt-3 Se puede usar una unidad de tiempo para establecer cuanto tiempo se demora un usuario en realizar una operación completa de su quehacer con la herramienta de trabajo.
    .row.mt-5
      .col-8.offset-2.rounded-20.borde-primario-4
        .row.py-3
          .col-4.align-self-center
            figure.borde-gris-der
              img.imagen_flotante_animada(src="@/assets/curso/temas/tema-3-4.svg", alt="").w-50.margin-0-auto
          .col-8.pt-4.px-4
            .h4 Facilidad de recordar el funcionamiento
            p.mt-3 Capacidad de recordar las características y forma de uso de un sistema; se debe usar para volver a emplearlo en el futuro.
    .row.mt-5
      .col-8.offset-2.rounded-20.borde-primario-4
        .row.py-3
          .col-4.align-self-center
            figure.borde-gris-der
              img.imagen_flotante_animada(src="@/assets/curso/temas/tema-3-5.svg", alt="").w-50.margin-0-auto
          .col-8.pt-4.px-4
            .h4 Frecuencia y gravedad de errores
            p.mt-3  Mensajes de error a los usuarios para apoyarlos cuando deban enfrentar errores determinados en el sistema. Por ejemplo, cuando en un sistema de facturación se intenta hacer una factura sin relacionar, al menos, un producto o servicio a facturar.
    .row.mt-5
      .col-8.offset-2.rounded-20.borde-primario-4
        .row.py-3
          .col-4.align-self-center
            figure.borde-gris-der
              img.imagen_flotante_animada(src="@/assets/curso/temas/tema-3-6.svg", alt="").w-50.margin-0-auto
          .col-8.pt-4.px-4
            .h4 Satisfacción subjetiva
            p.mt-3 Indica lo satisfechos que quedan los usuarios después haber usado el sistema, debido al diseño presentado y es subjetiva porque depende de la percepción de cada usuario.
    p.mt-5 Los anteriores aspectos aplican, en principio, a cualquier tipo de aplicación web o móvil, sin embargo, el compendio de buenas prácticas para aplicaciones móviles se destaca por aspectos como los relacionados a continuación:
    .row.mt-5
      .col-10.offset-1
        LineaTiempoD.color-acento-botones
          .row(numero="1" titulo="Definir con simplicidad y claridad la estructura de los contenidos ")
            .col-1.mx-3
              figure
                img(src="@/assets/curso/temas/tema-3-7.svg", alt="", style="min-width: 30px")
            .col-9
              p Generalmente, la recomendación es organizarlos de acuerdo con una jerarquía consistente temáticamente o según las relaciones y procesos de negocio de la aplicación.
          .row(numero="2" titulo="Establecer un diseño “limpio”")
            .col-1.mx-3
              figure
                img(src="@/assets/curso/temas/tema-3-8.svg", alt="", style="min-width: 30px")
            .col-9
              p Correcta tipografía, imágenes y recursos gráficos que hagan fácil al usuario encontrar lo que busca, separando los contenidos con una clasificación lógica.
          .row(numero="3" titulo="Ceder el control al usuario")
            .col-1.mx-3
              figure
                img(src="@/assets/curso/temas/tema-3-9.svg", alt="", style="min-width: 30px")
            .col-9
              p Los usuarios no sienten una experiencia positiva si en algún momento se sienten perdidos mientras interactúan con el sistema. Se debe garantizar que el usuario sepa dónde se encuentra y cómo acceder a otro enlace o funcionalidad.
          .row(numero="4" titulo="Facilitar la interacción")
            .col-1.mx-3
              figure
                img(src="@/assets/curso/temas/tema-3-10.svg", alt="", style="min-width: 30px")
            .col-9
              p Permitir que el usuario pueda desarrollar varias acciones de forma fácil e intuitiva aporta a la satisfacción, sin embargo, si estas opciones no se presentan como un diseño limpio, se puede lograr un efecto adverso.
          .row(numero="5" titulo="Simplificar y sintetizar")
            .col-1.mx-3
              figure
                img(src="@/assets/curso/temas/tema-3-11.svg", alt="", style="min-width: 30px")
            .col-9
              p La regla básica para aplicar este principio es: “todo lo que no es necesario sobra”. Con ello se evita sobrecargar el sistema con información u operaciones superfluas.
          .row(numero="6" titulo="Adaptar para todo tipo de dispositivos")
            .col-1.mx-3
              figure
                img(src="@/assets/curso/temas/tema-3-12.svg", alt="", style="min-width: 30px")
            .col-9
              p Otro elemento básico es la adaptabilidad a diferentes dispositivos.

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
