<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo_banner.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Negocios Verdes
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Negocios Verdes
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 621102
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 3984 Horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 27 meses
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              //- li.mb-3.banner-principal__datos__item
              //-   p.h6.mb-0.me-3.banner-principal__datos__item__titulo Requisito de ingreso: 
              //-   .banner-principal__datos__item__texto
              //-     ul.lista-ul
              //-       li
              //-         i.lista-ul__vineta
              //-         p Solicitud de las Instituciones del Sistema General de Seguridad Social en Salud.
              //-       li
              //-         i.lista-ul__vineta
              //-         p Profesionales, tecnólogos y técnicos de salud que brindan atención a las víctimas de ataque con agentes químicos.
              //-       li
              //-         i.lista-ul__vineta
              //-         p Cumplir con el trámite de selección definido por el Centro de Formación.
              //-       li
              //-         i.lista-ul__vineta
              //-         p Se requiere que el aprendiz AVA (Ambientes Virtuales de Aprendizaje) tenga dominio de elementos básicos en el manejo de herramientas informáticas y de comunicación como correo electrónico, chat, procesadores de texto, software para presentaciones, navegadores de Internet, y otros sistemas y herramientas tecnológicas necesarias para la formación virtual.

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/vQevR3qzy14" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Las estrategias del Biocomercio se han desarrollado desde hace 17 años a partir de los acuerdos de la Conferencia Mundial de Desarrollo Sostenible (Sudáfrica, 2002) y Conferencia de las Naciones Unidas sobre comercio y desarrollo (Biotrade). Su propósito es definir cómo se deben transformar los procesos productivos para asegurar el desarrollo sostenible a partir de un conjunto de principios y criterios que responden y apoyan los objetivos de los convenios de diversidad biológica internacional, abordando una gran variedad de problemáticas relevantes como: la erradicación de la pobreza, el desarrollo social y económico, la protección del medio ambiente, el calentamiento global, los objetivos de desarrollo del milenio, entre muchos otros.
      br
      br
      | Colombia, no es ajena a estos procesos, es por esto que el SENA cumpliendo la función que le compete al estado de formar al sector productivo, desarrolló el programa Negocios Verdes, con el fin de desarrollar negocios innovadores y competitivos, basados en el aprovechamiento sostenible de la biodiversidad nativa, a través de lineamientos claros que promuevan principios de biocomercio (Minambiente, 2014).
      br
      br
      | El SENA ofrece este programa con todos los elementos de formación profesional, sociales, tecnológicos y culturales, metodologías de aprendizaje innovadoras, acceso a tecnologías de última generación, estructurado sobre métodos más que contenidos, lo que potencia la formación de ciudadanos librepensadores, con capacidad crítica, solidarios y emprendedores, con manejo de conceptos y normativa ambiental, investigación de mercados y unidades productivas reales, cadena de suministro, estrategias de mercadeo, desarrollo de productos y servicios y, la negociación de los mismos, que lo acreditan y lo hacen pertinente y coherente con su misión, innovando permanentemente de acuerdo con las tendencias, cambios tecnológicos y las necesidades del sector empresarial y de los trabajadores, impactando positivamente la productividad, la competitividad, la equidad y el desarrollo del país.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p Los negocios verdes, están comprendidos por actividades económicas, en las que se ofertan bienes o servicios, que originan impacto ambiental positivo y subvencionan a su conservación, como capital natural, que soporta el desarrollo de los territorios (Ministerio de medio ambiente y desarrollo sostenible, 2014)”.
      br
      br
      | Colombia, el segundo país más biodiverso y una de las doce naciones más megadiversas de la tierra (Colciencias , 2019) tiene una ventaja comparativa para desarrollar negocios internacionales a partir de esta riqueza, que suscite el bienestar y desarrollo, coadyuve con la subsistencia de la biodiversidad (UNCTAD, 2010), a la vez que pueda ser generador de ingresos a la población con pobreza monetaria (para el año 2018 fue del 27% y la pobreza extrema fue de 7,2% en el total nacional (DANE, 2018)), tal como ha quedado demostrado con los 1.414 negocios verdes, confirmados por el Ministerio de Ambiente y desarrollo sostenible, que aportan a la empleabilidad en el país, con una cifra de ocupación de más de 20.000 personas en el año 2019 (Minambiente, 2019).
      br
      br
      | El SENA, atendiendo a su rol, como uno de los actores sectoriales en generación de conocimiento, innovación y valor agregado del PRNB (Programa nacional de biocomercio sostenible) en articulación con las agendas de competitividad, productividad e innovación (Mincit), presenta la Tecnología en Negocios verdes, dando alcance al objetivo general del Programa Nacional de Biocomercio Sostenible, consistente en desarrollar negocios innovadores y competitivos, basados en el aprovechamiento sostenible de la biodiversidad nativa, a través de lineamientos claros que promuevan principios de biocomercio (Minambiente, 2014)


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a<br>desarrollar

    ul.lista-ul--color
      li 
        i.lista-ul__vineta
        | Estructurar sistema de gestión ambiental según procedimiento
      li 
        i.lista-ul__vineta
        | Categorizar negocios sostenibles según criterios verdes normativa.
      li 
        i.lista-ul__vineta
        | Formular el plan según objetivos y metodologías.
      li 
        i.lista-ul__vineta
        | Planear la integración de las cadenas de suministro según mejores prácticas y modelos de gestión.
      li 
        i.lista-ul__vineta
        | Negociar productos o servicios de acuerdo con objetivos estratégicos.
      li 
        i.lista-ul__vineta
        | Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
      li 
        i.lista-ul__vineta
        | Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos productivo y social.
      li 
        i.lista-ul__vineta
        | Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.
      li 
        i.lista-ul__vineta
        | Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
      li 
        i.lista-ul__vineta
        | Ejercer derechos fundamentales del trabajo en el marco de la constitución política y los convenios internacionales.
      li 
        i.lista-ul__vineta
        | Orientar investigación formativa según referentes técnicos.
      li 
        i.lista-ul__vineta
        | Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
      li 
        i.lista-ul__vineta
        | Aplicación de conocimientos de las ciencias naturales de acuerdo con situaciones del contexto productivo y social.
      li 
        i.lista-ul__vineta
        | Utilizar herramientas informáticas de acuerdo con las necesidades de manejo de información.
      li 
        i.lista-ul__vineta
        | Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
      li 
        i.lista-ul__vineta
        | Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el Marco Común Europeo de referencia para las lenguas.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de<br>ingreso

    ul.lista-ul--color
      li 
        i.lista-ul__vineta
        | Nivel académico adecuado para caracterizar al aspirante de acuerdo con el perfil de egreso: media académica, grado 11.
      li 
        i.lista-ul__vineta
        | Requiere certificación académica.
      li 
        i.lista-ul__vineta
        | No requiere formación para el trabajo y desarrollo humano.
      li 
        i.lista-ul__vineta
        | No requiere experiencia laboral.
      li 
        i.lista-ul__vineta
        | Edad mínima definida en la ley: 16 años.
      li 
        i.lista-ul__vineta
        | Requisitos adicionales:
        ul.lista-ul--color
          li 
            i.lista-ul__vineta
            | Presentar resultado de la prueba o examen de estado de la educación media.
          li
            i.lista-ul__vineta
            | Título de bachiller o su equivalente validación aprobada por la entidad competente.
      li 
        i.lista-ul__vineta
        | El aspirante debe tener interés relacionado con el emprendimiento; preferencia por el trabajo en equipo, liderazgo y comunicación asertiva, vocación de servicio; preferencia por trabajos que exigen el cumplimiento de normas, procedimientos, estándares, protocolos; interés en la formación técnica aplicada a la industria; gusto por actividades laborales de incentivar el desarrollo sostenible, disposición para comercializar productos con enfoque ambiental; disposición para respetar jerarquías y acatar órdenes; preferencia por el trabajo operativo, interés por la investigación de productos y servicios verdes, motivación para la organización de actividades ambientales.
  
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de<br>egreso

    p.mb-4 El egresado del programa Tecnología en negocios verdes es un talento humano formado integralmente bajo el enfoque por competencias con capacidad de determinar las oportunidades de mercado, recopilar información para realizar análisis de tendencias del mercado verde y negociar productos con criterios de sostenibilidad (económica, social, ambiental); con un alto sentido de responsabilidad social-empresarial potenciando la calidad del talento humano, el trabajo en equipo y liderazgo. Podrá desempeñarse en empresas comercialización de bienes y servicios de la biodiversidad, en cargos de coordinador de mercadeo o supervisor de ventas.
      br
      br
      | Los principales productos del trabajo del egresado son: 

    ul.lista-ul--color
      li 
        i.lista-ul__vineta
        | Informe de caracterización del entorno ambiental del negocio.
      li 
        i.lista-ul__vineta
        | Categorización del negocio verde de acuerdo al marco referencial.
      li 
        i.lista-ul__vineta
        | Propuesta de condiciones y características de la cadena de suministro.
      li 
        i.lista-ul__vineta
        | Plan de comercialización de productos verdes.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia<br>metodologíca

    p.mb-5 Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      | Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:

    .row.g-4.justify-content-center
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='../assets/curso/01.svg', alt='El instructor - tutor')
        p.text-center
          strong El instructor - tutor
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='../assets/curso/02.svg', alt='El entorno')
        p.text-center
          strong El entorno
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='../assets/curso/03.svg', alt='Las TIC')
        p.text-center
          strong Las TIC
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='../assets/curso/04.svg', alt='El trabajo colaborativo')
        p.text-center
          strong El trabajo colaborativo



  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
