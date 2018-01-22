<template>
  <div class="container-fluid" id="inicio">
    <div class="navbar-fixed ">
      <nav class="grey darken-4 " id="elementos">
        <div class="nav-wrapper ">
          <a href="#" class="brand-logo right">
            <img class="" id="clogo"src="./dist/comdahllogo.png" alt="Logo"></img>
          </a>
          <a href="#" data-activates="mobile-demo"  class="button-collapse grey darken-4 dropdown-button btn" ><i class="material-icons" id="burger">menu</i></a>
          <ul id="nav" class="center hide-on-med-and-down">
            <li><a href="#trees">INICIO</a></li>
            <li><a href="#contenedor-principal">SOBRE NOSOTROS</a></li>
            <li><a href="#requisitos">REQUISITOS</a></li>
            <li><a href="#servicios1">SERVICIOS</a></li>
            <li><a href="#blacky">BENEFICIOS</a></li>
          </ul>
          <ul id="mobile-demo" class="grey darken-4 dropdown-content ">
            <li><a href="#trees">INICIO</a></li>
            <li><a href="#contenedor-principal">SOBRE NOSOTROS</a></li>
            <li><a href="#requisitos">REQUISITOS</a></li>
            <li><a href="#servicios1">SERVICIOS</a></li>
            <li><a href="#blacky">BENEFICIOS</a></li>
          </ul>
        </div>
      </nav>
    </div>
    <!--  Frase Principal-->
    <div class="fixed-bg center" id="trees">
      Apoyamos a todos aquellos que con
      esfuerzo y sacrificio dan fertilidad a
      nuestras tierras catrachas, con el
      compromiso que nos caracteriza.
    </div>
    <!--  VIRTUDES-->
    <div class="-long3 -lightgreen" id="virtudes">
      <div id="icon_container"class="row">
        <div class="col s6 m4  -center">
          <i class="large material-icons">directions_walk</i>
          <br>
          TRABAJO
        </div>
        <div class="col s6 m4  -center">
          <i class="large material-icons">trending_up</i>
          <br>
          DESARROLLO
        </div>
        <div class="col s12 m4  -center">
          <i class="large material-icons">accessibility</i>
          <br>
          SOLIDARIDAD
        </div>
      </div>
    </div>
    <!--  ¿Qué es COMDAHL?-->
    <div class="row center" >
      <div class="col s6 -white -long2 -right" id="contenedor-principal">
        <div class="typewriter">
          <h1>¿Qué es COMDAHL?</h1>
        </div>
      </div>
      <div class="col s6 flow-text -white -left -long2 " id="contenedor-principal">
        <p>
          <br>
          Es una asociación autónoma de personas unidas voluntariamente <br>
          con la intención de hacerle frente a las necesidades y aspiraciones <br>
          económicas, sociales y culturales comunes a todos los miembros  <br>
          mediante participación solidaria y responsable de sus miembros.
        </p>
      </div>
    </div>
    <!--  Mision Vision-->
    <div class="row" id="MV">
      <div class="col m6 -lightgreen -long2 " id="contenedorVMision">

        <div >
          <h1 id="MVision"><i class="medium material-icons" id="mis">settings</i> MISIÓN</h1>
        </div>
        <p>
          Promover y desarrollar bienes y servicios de asistencia técnica especializada en procesos productivos,
          comerciales, administrativos y tecnológicos, que favorezcan el desarrollo humano sostenible y el crecimiento
          patrimonial de las economías familiares, como una contribución eficaz para el desarrollo del sector cooperativo
          agropecuario hondureño.
        </p>
        <br><br><br><br>
      </div>
      <div class="col m6 -green -long2  " id="contenedorVMision">

        <div >

          <h1 id="MVision"><i class="medium material-icons" id="vis">remove_red_eye</i>VISIÓN</h1>
        </div>
        <div>
          <p>
                        Ser la organización cooperativa líder en la promoción y desarrollo de bienes y servicios agropecuarios,
                        privilegiando la óptima utilización de los recursos naturales, el capital
                        social, la tecnología y el trabajo humano, en el marco de los
                        valores y principios cooperativistas universales, para contribuir
                        a elevar la calidad de vida de las familias productoras y el
                        crecimiento de la economía social en el país.
          </p>
        </div>
      </div>
    </div>
    <!--  Valores-->
    <div class="-long4 center -blue">
      <div class="flow-text"id="valores">
        <h1>VALORES COOPERATIVOS</h1>
        <div class="container row">
          <div class="col s4 m4 -center -long1 -yellow" id="contenedorValor">
            Igualdad
          </div>
          <div class="col s4 m4 -center -long1 -lightgreen" id="contenedorValor">
            Ayuda Mutua
          </div>
          <div class="col s4 m4 -center -long1 -green" id="contenedorValor">
            Respeto
          </div>
          <div class="col s4 m4 -center -long1 -green" id="contenedorValor">
            Compromiso
          </div>
          <div class="col s4 m4 -center -long1 -yellow" id="contenedorValor">
            Confianza
          </div>
          <div class="col s4 m4 -center -long1 -lightgreen" id="contenedorValor">
            Honestidad
          </div>
        </div>
      </div>
    </div>
    <!--  Frase secundaria-->
    <div class="container" id="frase3">
      <p>Somos una cooperativa orgullosamente hondureña, creada por un grupo de ingenieros agrónomos con el objetivo de generar bienestar socioeconomico,
        fomentar el emprendimiento y las buenas prácticas agropecuarias entre sus miembros y la comunidad que actúa. Actualmente, cuenta con profesionales de diversas áreas
        siendo el capital humano su riqueza más valiosa.
      </p>
    </div>
    <!--  Imagen-->
    <div class="fixed-bg -center -long3 -frase1 -blue" id="leaves">
    </div>
    <!--  Proyectos-->
    <div class="-long4 center -blue">
      <div class="flow-text"id="valores">
        <br>
        <h1>Nuestros Proyectos</h1>
        <br>
        <div class="container">
          <div class="slider">
            <ul class="slides">
              <li>
                <img src="./dist/salud.jpg">
                <div class="caption center-align">
                  <h3>Clínica Médica</h3>
                  (próximamente)
                </div>
              </li>
              <li>
                <img src="./dist/DesarrolloComunal.jpg">
                <div class="caption left-align">
                  <h3>Desarrollo comunal localizado en aldea el limón, Cerro de Hula </h3>
                  (próximamente)
                </div>
              </li>
              <li>
                <img src="./dist/Agropecuaria.jpg">
                <div class="caption left-align">
                  <h3>Agropecuaria Comercial COMDAHL </h3>
                  (próximamente)

                </div>
              </li>
              <li>
                <img src="./dist/Veterinario.jpg">
                <div class="caption right-align">
                  <h3>Laboratorio Veterinario COMDAHL</h3>
                  (próximamente)

                </div>
              </li>
              <li>
                <img src="./dist/areasProtegidas.jpg">
                <div class="caption center-align">
                  <h3>Proyecto Alfa y Omega COMDAHL (Protección de Áreas Protegidas Privadas)</h3>
                  (próximamente)

                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <!--  Requisitos-->
    <div class=" center -black" id="requisitos">
      <h1>¡SÚMATE!</h1>
      <ul class="collapsible popout" data-collapsible="accordion">
        <li>
          <div class="-frase3 collapsible-header">Podrán ser parte de COMDAHL:</div>
          <div class="collapsible-body">
            <p>1)	1.	Las personas mayores de 18 años en pleno goce de sus derechos ciudadanos estudiantes o egresados de las carreras de las ciencias agrícolas o carreras afines : </p>
            <p>(Ingeniería forestal, Economía agrícola, administración agropecuaria, licenciatura en turismo, Ingeniería ambiental, etc.), </p>
            <p>con pleno goce de sus derechos ciudadanos.</p>
            <br>
            <p>2)	Personas auspiciadas o recomendadas por una persona que ya es miembro de COMDAHL.</p>
            <br>
            <p>3)	Empresas o instituciones con personería jurídica en economía social y solidaria.</p>
          </div>
        </li>
        <li>
          <div class="collapsible-header">Para poder afiliarse una persona natural deberá presentar:</div>
          <div class="collapsible-body">
            <p>1)	Llenar formato de afiliación;</p>
            <p>2)	Presentar fotocopia de identidad y RTN ;</p>
            <p>3)	Pagar una cuota de ingreso NO rembolsable de L. 2,000.00;</p>
            <p>4)	Presentar declaración de beneficiarios (as).</p>
          </div>
        </li>
        <li>
          <div class="collapsible-header"> Para poder afiliarse las empresas o instituciones con personería jurídica deberán presentar:</div>
          <div class="collapsible-body">
            <p>1)	Personería jurídica;</p>
            <p>2)	Estatuto Social o documento equivalente;</p>
            <p>3)	Certificación del acta de Junta Directiva en donde conste la decisión             de afiliarse a la cooperativa;</p>
            <p>4)	Certificación del punto de acta de la Junta Directiva que acredite la persona que ostenta la representación legal de conformidad a su estatuto;</p>
            <p>5)	Constancia de inscripción de la junta directiva en la unidad de Registro               y Seguimiento de Sociedades Civiles (URSAC) o su equivalente;</p>
            <p>6)	Documentos personales del representante legal¬.</span></p>
          </div>
        </li>
      </ul>
    </div>

    <div class="row" id="servicios1">
      <div class="col s12 -lightgreen -long2 " id="contenedorVMision">

        <div >
          <i class="large material-icons" id="person">person</i>
          <h1 id="STEC"> SERVICIOS DE ASISTENCIA TÉCNICA</h1>
          <br>
        </div>
        <div class="col s12 m12 l6 xl3">
          <div class="card">
            <div class="card-image waves-effect waves-block waves-light">
              <img class="activator" src="./dist/ambiente.JPG">
            </div>
            <div class="card-content">
              <span class="card-title activator grey-text text-darken-4"><span style="font-size:1em;">Inocuidad de alimentos y medio Ambiente</span><i class="material-icons right">more_vert</i></span>
            </div>
            <div class="card-reveal">
              <span class="card-title grey-text text-darken-4"><i class="material-icons right">close</i></span>
              <p> <span style="font-size:18px; font-weight:bold;">1.</span> <span style="font-size:18px">Elaboración de auditorías, licencias, planes de contingencia ambiental, diagnósticos rurales rápidos y levantamiento de información en campo</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">2.</span> <span style="font-size:18px">Asistencia técnica especializada en buenas prácticas agrícolas y buenas prácticas de manufactura</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">3.</span> <span style="font-size:18px">Registro de insumos agrícolas  (Regencia )</span></p>
            </div>
          </div>
        </div>
        <div class="col s12 m12 l6 xl3">
          <div class="card">
            <div class="card-image waves-effect waves-block waves-light">
              <img class="activator" src="./dist/maiz.JPG">
            </div>
            <div class="card-content">
              <span class="card-title activator grey-text text-darken-4">Producción y comercialización de Granos Básicos y Hortalizas<i class="material-icons right">more_vert</i></span>
            </div>
            <div class="card-reveal">
              <span class="card-title grey-text text-darken-4"><i class="material-icons right">close</i></span>
              <p> <span style="font-size:18px; font-weight:bold;">1.</span> <span style="font-size:18px">Asistencia técnica especializada en producción de granos básicos, hortalizas y mercado</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">2.</span> <span style="font-size:18px">Asesoramiento en conservación y manejo de granos básicos, Capacitación en la elaboración y uso de silos</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">3.</span> <span style="font-size:18px">Preparación de suelos de forma mecánica y asesoría en equipo agrícola.</span></p>
            </div>
          </div>
        </div>
        <div class="col s12 m12 l6 xl3">
          <div class="card">
            <div class="card-image waves-effect waves-block waves-light">
              <img class="activator" src="./dist/cow.jpg">
            </div>
            <div class="card-content">
              <span class="card-title activator grey-text text-darken-4">Producción y comercialización Pecuaria<i class="material-icons right">more_vert</i></span>
            </div>
            <div class="card-reveal">
              <span class="card-title grey-text text-darken-4"><i class="material-icons right">close</i></span>
              <p> <span style="font-size:18px; font-weight:bold;">1.</span> <span style="font-size:18px">Asesoramiento técnico especializado en porcinocultura, avicultura, apicultura, bovinos y especies menores</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">2.</span> <span style="font-size:18px">Asistencia técnica especializada en sanidad animal</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">3.</span> <span style="font-size:18px">Asistencia técnica especializada en manejo de pastos y forraje</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">4.</span> <span style="font-size:18px">Asistencia técnica especializada en producción y transformación de leche</span></p>
            </div>
          </div>
        </div>
        <div class="col s12 m12 l6 xl3">
          <div class="card">
            <div class="card-image waves-effect waves-block waves-light">
              <img class="activator" src="./dist/cacao.jpg">
            </div>
            <div class="card-content">
              <span class="card-title activator grey-text text-darken-4"><span style="font-size:.8em;">Producción y comercialización de Cultivos perennes Agroindustriales</span><i class="material-icons right">more_vert</i></span>
            </div>
            <div class="card-reveal">
              <span class="card-title grey-text text-darken-4"><i class="material-icons right">close</i></span>
              <p> <span style="font-size:18px; font-weight:bold;">1.</span> <span style="font-size:18px">Asistencia técnica especializada en establecimiento de viveros, desarrollo y mantenimiento de fincas en palma africana</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">2.</span> <span style="font-size:18px">Asistencia técnica especializada en café, cacao, caña de azúcar y administración de fincas</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">3.</span> <span style="font-size:18px">Asistencia técnica especializada en cítricos, aguacate, rambután, mangostín, banano y plátano, piña, ajonjolí, marañón, mango, papaya y otros.</span></p>
            </div>
          </div>
        </div>
        <div class="col s12 m12 l6 xl3">
          <div class="card">
            <div class="card-image waves-effect waves-block waves-light">
              <img class="activator" src="./dist/informatica.jpg">
            </div>
            <div class="card-content">
              <span class="card-title activator grey-text text-darken-4">Informática<i class="material-icons right">more_vert</i></span>
            </div>
            <div class="card-reveal">
              <span class="card-title grey-text text-darken-4"><i class="material-icons right">close</i></span>
              <p> <span style="font-size:18px; font-weight:bold;">1.</span> <span style="font-size:18px">Asistencia técnica especializada en elaboración, diseño y mantenimiento de páginas web</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">2.</span> <span style="font-size:18px">Asistencia técnica especializada en Marketing</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">3.</span> <span style="font-size:18px">Asistencia técnica especializada en Diseño Gráfico</span></p>
            </div>
          </div>
        </div>
        <div class="col s12 m12 l6 xl3">
          <div class="card">
            <div class="card-image waves-effect waves-block waves-light">
              <img class="activator" src="./dist/obra.jpeg">
            </div>
            <div class="card-content">
              <span class="card-title activator grey-text text-darken-4"><span style="font-size: .8em">Obras civiles y de construcción</span><i class="material-icons right">more_vert</i></span>
            </div>
            <div class="card-reveal">
              <span class="card-title grey-text text-darken-4"><i class="material-icons right">close</i></span>
              <p> <span style="font-size:18px; font-weight:bold;">1.</span> <span style="font-size:18px">Desarrollo de anteproyectos arquitectónicos, construcción, supervisión y asesoría técnica.</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">2.</span> <span style="font-size:18px">Asistencia técnica especializada en Gestión de riesgo, desastres y desarrollo municipal</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">3.</span> <span style="font-size:18px">Desarrollo de obras civiles, obras hidrosanitarias, calles y terracerías.</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">4.</span> <span style="font-size:18px">Formulación y supervisión de proyectos, licencia sanitaria, ambiental y proyectos de seguridad</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">5.</span> <span style="font-size:18px">Alquiler de equipo de Construcción</span></p>
            </div>
          </div>
        </div>
        <div class="col s12 m12 l6 xl3">
          <div class="card">
            <div class="card-image waves-effect waves-block waves-light">
              <img class="activator" src="./dist/logistica.jpg">
            </div>
            <div class="card-content">
              <span class="card-title activator grey-text text-darken-4">Servicios de Logística<i class="material-icons right">more_vert</i></span>
            </div>
            <div class="card-reveal">
              <span class="card-title grey-text text-darken-4"><i class="material-icons right">close</i></span>
              <p> <span style="font-size:18px; font-weight:bold;">1.</span> <span style="font-size:18px">Servicios de logística de camiones refrigerados, plataforma, rastras, contenedores secos, tractores agrícolas, montacargas, bomba de agua, moto niveladora, retroexcavadoras  y otros equipos agrícolas.</span></p>
            </div>
          </div>
        </div>
        <div class="col s12 m12 l6 xl3">
          <div class="card">
            <div class="card-image waves-effect waves-block waves-light">
              <img class="activator" src="./dist/proyectos.jpg">
            </div>
            <div class="card-content">
              <span class="card-title activator grey-text text-darken-4">Proyectos<i class="material-icons right">more_vert</i></span>
            </div>
            <div class="card-reveal">
              <span class="card-title grey-text text-darken-4"><i class="material-icons right">close</i></span>
              <p> <span style="font-size:18px; font-weight:bold;">1.</span> <span style="font-size:18px">Análisis, formulación y evaluación de proyectos Agropecuarios</span></p>
              <p> <span style="font-size:18px; font-weight:bold;">2.</span> <span style="font-size:18px">Monitoreo y seguimiento de proyectos</span></p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row" id="RAC">
      <div class="col s12 -green -long2  " id="contenedorVMision">
        <div >
          <i class="large material-icons" id="money">attach_money</i>
          <h1 id=""><span style="text-align:center;">SERVICIOS FINANCIEROS</span></h1>
        </div>
        <div>
          <br>
          <h5 ><span style="text-align:center;">Ofrecemos diversas modalidades de ahorro y crédito con tasas de interés competitivas:</span></h5>
          <br>
          <div class="col s6 m6 l6 xl6" id="AH">
            <h5><span style="padding-left:15%;">AHORROS</span></h5>
            <ul id="ahorros">
              <li>• Ahorro de aportaciones</li>
              <li>•	Ahorro Retirables</li>
              <li>•	Ahorros Navideños</li>
              <li>•	Ahorro a plazo fijo</li>
              <li>• Ahorro para niños</li>
            </ul>
          </div>
          <div class="col s6 m6 l6 xl6" id="CR">
            <h5><span style="padding-left:15%;">CRÉDITOS</span></h5>
            <ul id="credito">
              <li>•	Crédito Agropecuario</li>
              <li>•	Crédito Fiduciario</li>
              <li>•	Crédito Hipotecario</li>
              <li>•	Crédito Colectivo para proyectos</li>
              <li>•	Créditos Automáticos</li>
              <li>•	Líneas de crédito</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!--  Beneficios-->
    <div class="fixed-bg -long4 -frase1 center" id="blacky">
      <div class="flow-text"id="beneficios1">
        <h1><i class="medium material-icons">star</i>BENEFICIOS</h1>
        <div class="container row">
          <div class="col s4 m4 -center -long6" id="beneficios">
            <h3>1.</h3>
            <br>
            Capacitaciones formativas en diversas áreas.
          </div>
          <div class="col s2 m4 -center -long6" id="beneficios">
            <h3>2.</h3>
            <br>
            Acceso a servicios de asistencia técnica con descuento.
          </div>
          <div class="col s2 m4 -center -long6" id="beneficios">
            <h3>3.</h3>
            <br>
            Cobertura de servicios de <br> nivel nacional
          </div>
          <div class="col s2 m4 -center -long6" id="beneficios">
            <h3>4.</h3>
            <br>
            Pocas restricciones para el acceso a créditos agropecuarios.
          </div>
          <div class="col s2 m4 -center -long6" id="beneficios">
            <h3>5.</h3>
            <br>
            Ahorro y crédito con tasas de interés competitivas.
          </div>
          <div class="col s2 m4 -center -long6" id="beneficios">
            <h3>6.</h3>
            <br>
            Participación en sorteos promocionales.
          </div>
          <div class="col s2 m4 -center -long6" id="beneficios">
            <h3>7.</h3>
            <br>
            Seguro médico y seguro de vida.
          </div>
          <div class="col s2 m4 -center -long6" id="beneficios">
            <h3>8.</h3>
            <br>
            Acceso a Buro de Becas Educativas.
          </div>
          <div class="col s6 m4 -center -long6" id="beneficios">
            <h3>9.</h3>
            <br>
            Acceso Buro de Empleos Disponibles.
          </div>
        </div>
      </div>
    </div>



  </div>
</template>

<script>
export default {
  name: 'inicio',
  mounted(){
    $(document).ready(function(){
      $('.collapsible').collapsible();
    });

    $(document).ready(function(){
      $('.slider').slider();
    });
    $('.dropdown-button').dropdown({
      inDuration: 300,
      outDuration: 225,
      constrainWidth: false, // Does not change width of dropdown to that of the activator
      hover: true, // Activate on hover
      gutter: 0, // Spacing from edge
      belowOrigin: false, // Displays dropdown below the button
      alignment: 'left', // Displays dropdown with edge aligned to the left of button
      stopPropagation: false // Stops event propagation
    }
  );
  //smooth scroll
  $('a[href*="#"]')
  // Remove links that don't actually link to anything
  .not('[href="#"]')
  .not('[href="#0"]')
  .click(function(event) {
    // On-page links
    if (
      location.pathname.replace(/^\//, '') == this.pathname.replace(/^\//, '')
      &&
      location.hostname == this.hostname
    ) {
      // Figure out element to scroll to
      var target = $(this.hash);
      target = target.length ? target : $('[name=' + this.hash.slice(1) + ']');
      // Does a scroll target exist?
      if (target.length) {
        // Only prevent default if animation is actually gonna happen
        event.preventDefault();
        $('html, body').animate({
          scrollTop: target.offset().top
        }, 1000, function() {
          // Callback after animation
          // Must change focus!
          var $target = $(target);
          $target.focus();
          if ($target.is(":focus")) { // Checking if the target was focused
            return false;
          } else {
            $target.attr('tabindex','-1'); // Adding tabindex for elements not focusable
            $target.focus(); // Set focus again
          };
        });
      }
    }
  });

}
}

</script>

<style scoped>
#clogo{
  height: 180px;
  width: 180px;
}
.card{
  overflow-y: auto;
}
.card-reveal{
  text-align: center;
}
#RAC{
  height: 780px;
}
#CR h5{
  font-weight: bold;
  text-decoration: underline;
  padding-right: 425px;
}
#AH{
  padding-left: 23%;
}
#CR{
  padding-right: 15%;
}
#credito li{
  text-align: left;
  margin-right: 255px;
  font-weight: bold;
}
#AH h5{
  font-weight: bold;
  text-decoration: underline;
  padding-left: 25%;
}
#ahorros li{
  text-align: left;
  margin-left: 45%;
  font-weight: bold;
}
#person{
  position: relative;
  top: 16px;
}
#money{
  position: relative;
  top: 16px;
}
#mis{
  position: relative;
  top: 8px;
  right: 10px;
}
#vis{
  position: relative;
  top: 8px;
  right: 10px;
}
.card-image {
  max-height: 100%;
  width: 100%;
  overflow: hidden;
  position: relative;
}

.card-image img {
  height: 270px;
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}
/* entire container, keeps perspective */
.flip-container {
  perspective: 1000px;
}
/* flip the pane when hovered */
.flip-container:hover .flipper, .flip-container.hover .flipper {
  transform: rotateY(180deg);
}
.flip-container, .front, .back {
  width: 100%;
  height: 280px;
}
/* flip speed goes here */
.flipper {
  transition: 0.6s;
  transform-style: preserve-3d;

  position: relative;
}
/* hide back of pane during swap */
.front, .back {
  backface-visibility: hidden;
  position: absolute;
  top: 0;
  left: 0;
  background-image: url('../imgs/Agropecuaria.jpg');
}
/* front pane, placed above back */
.front {
  z-index: 2;
  /* for firefox 31 */
  transform: rotateY(0deg);
}
/* back, initially hidden pane */
.back {
  transform: rotateY(180deg);
}
.card-small img{
  height: 100%;
  width: 100%;
}
.-white{
  background-color: #FFFFC4;
  color: black;
}
.-green{
  background-color: #8FB259;
  color: #FFFFC4;
}
.-lightgreen{
  background-color: #CCCC52;
  color: #FFFFC4;
}
.-blue{
  background-color: #192B33;
  color: #FFFFC4;
}
.-yellow{
  background-color: #FFD933;
  color: #FFFFC4;
}
.-black{
  background-color: #212121;
  color: #FFFFC4;
}
div.valores{
  content: url(http://www.ipacoop.gob.pa/new/images/about/IPACOOP/2016/JUNIO_2016/valores.png);
  max-width: 22%;
  max-height: 22%;
  position: relative;
  left: 5%;
}
#virtudes {
  padding-top: 2%;
  font-size: 30px;
}
#trees{
  background-image: url('../dist/fondo.JPG');
  background-position: bottom;
  height: 600px;
  min-height: 80%;
  color: #FFFFC4;
  font-family: 'Montserrat', sans-serif !important;
  font-weight: 600 !important;
  font-size: 3.1vw;
  line-height: 1.2em;
  padding-top: 10%;
  padding-left: 3%;
  padding-right: 3%;
  line-height: 115%;
  overflow: hidden;
  width: auto;
  -webkit-filter: saturate(150%); /* Safari */
  filter: saturate(150%);
}
@-webkit-keyframes filter-animation {
  0% {
    -webkit-filter: sepia(0) saturate(2);
  }
  50% {
    -webkit-filter: sepia(1) saturate(8);
  }
  100% {
    -webkit-filter: sepia(0) saturate(2);
  }
}
#valores h1{
  font-family: 'Montserrat Subrayada', sans-serif;
  font-size: 70px;
  color: #CCCC52!important;
}
#beneficios1 h1{
  padding-top: 50px;
  font-family: 'Montserrat Subrayada', sans-serif;
  font-size: 70px;
  color: #CCCC52!important;
}
#valores{
  padding-top: 2%;
}
#contenedorValor{
  -webkit-clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
  clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
  font-family: 'Montez', cursive;
  font-size: 40px;
  color: #192B33!important;
}
#leaves{
  background-image: url('../dist/elotes.JPG');
  -webkit-animation: filter-animation 5s infinite;
  color: #212121 !important;
}
#frase3{
  color: black!important;
  font-weight: bold;
  font-family: 'Montserrat', sans-serif;
  font-size: 30px;
  color: #FFFFC4 !important;
  /*background-color: #212121 !important;*/

}
.color2{
  background: yellow;
  position: relative;
}
.color2{
  background: blue;
  position: relative;
  -webkit-filter: grayscale(100%);
  filter: grayscale(100%);
  opacity: 0.5;
}
#blacky{
  height: auto;
  background-image: url('../dist/background.jpg');
}
#beneficios{
  font-family: 'Montserrat', sans-serif;
}
#beneficios h3{
  color: #CCCC52;
}
#requisitos ul{
  position: relative;
  color: black;
  height: 100%;
  font-weight: bold;
  font-size: 20px;
}
#requisitos h1{
  padding-top: 50px;
}

.-transicion1{
  background-color: #FFD933;
  color: #FFFFC4;
  -webkit-transition: background-color 0.5s ease;
  transition: background-color 0.5s ease;
  font-size: 30px;
}
.-transicion1:hover {
  background-color: #192B33;
  color: #FFFFC4;

}

.-center{
  display: -webkit-box;
  -webkit-box-pack: center;
  -webkit-box-align: center;
  text-align: center;
}
.-right{
  display: -webkit-box;
  -webkit-box-pack: end;
  -webkit-box-align: center;
  text-align: center;
  justify-items: end;
  justify-content: end;
}
.-left{
  display: -webkit-box;
  -webkit-box-pack: start;
  -webkit-box-align: center;
  text-align: center;
  justify-items: start;
}


.-frase1{
  font-family: 'Bungee', cursive;
  line-height: 1.2em;
  font-size: 40px;
}

#pattern{
  background-image: url('../imgs/image2.jpg');
  min-height: 500px;
}

.fixed-bg {
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.-long1{
  height: 300px;
}
.-long2{
  height: 600px;
}
.-long3{
  height: 200px;
}
.-long4{
  height: 800px;
}
.-long5{
  height: 400px;
}
.-long6{
  height: 120px;
}
#contenedor-principal {
  font-family: 'Roboto', sans-serif;
  font-size: 1.4em;
  align-items: flex-start;
  text-align: left;
  display: -webkit-box;
  -webkit-box-align: center;
  padding-top: 15px;
}
.row{
  overflow: hidden;
}
#contenedorVMision {
  font-size: 1.4em;
  color: #192B33;
  padding: 90px;
  align-items: center;
  text-align: center;
  justify-items: center !important;
  overflow: hidden;
  height: 100%;
  padding-bottom: 100%;
  margin-bottom: -100%;
}
#MVision{
  align-items: center;
  text-align: center;
}
#beneficios{
  height: 200px;
  font-size: 30px;
  padding-left: 70px;
  padding-right: 50px;
}
#beneficios1 h3{
  font-size: 45px;
}
.typewriter h1 {
  font-size: 50px;
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  border-right: .15em solid orange; /* The typwriter cursor */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Gives that scrolling effect as the typing happens */
  letter-spacing: .15em; /* Adjust as needed */
  animation:
  typing 3.5s steps(40, end),
  blink-caret .75s step-end infinite;
}
.collapsible-body{
  color: #FFFFC4 !important;
  text-align: left;
  padding-left: 25%;

}

/* The typing effect */
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: orange; }
}
.-white{
  background-color: #FFFFC4;
  color: black;
}
.-green{
  background-color: #8FB259;
  color: #FFFFC4;
}
.-lightgreen{
  background-color: #CCCC52;
  color: #FFFFC4;
}
.-blue{
  background-color: #192B33;
  color: #FFFFC4;
}
.-yellow{
  background-color: #FFD933;
  color: #FFFFC4;
}
.-black{
  background-color: #212121;
  color: #FFFFC4;
}
.dropdown-button{
  -moz-box-shadow: inset 0px 0px 45px 3px rgba(0,0,0,0.67);
  box-shadow: inset 0px 0px 45px 3px rgba(0,0,0,0.67);
}
#footText{
  font-size: 20px;
}
#foots{
  -webkit-transition: background-color 2s ease-out;
  -moz-transition: background-color 2s ease-out;
  -o-transition: background-color 2s ease-out;
  transition: background-color 2s ease-out;
}
#foots img:hover{
  background: #black;
  filter: alpha(opacity=60);
  -moz-opacity: 0.6;
  opacity: .5;
  transition: opacity .3s ease-out;
  -moz-transition: opacity .3s ease-out;
  -webkit-transition: opacity .3s ease-out;
  -o-transition: opacity .3s ease-out;
}
.navbar-fixed{

}
#app{
  background-color: #262626;
  color: #F4F0EA;
}
#elementos{
  font-family: 'Roboto', sans-serif;

}
a {
  color: #F4F0EA;
  font-family: 'Roboto', sans-serif;
  font-size: 18px;
  text-transform: uppercase;

}

#elementos{
  color: #06152F;
  background: #F4F0EA;
  padding: 0px 50px;
  -webkit-box-shadow: inset 0px 0px 45px 3px rgba(0,0,0,0.67);
  -moz-box-shadow: inset 0px 0px 45px 3px rgba(0,0,0,0.67);
  box-shadow: inset 0px 0px 45px 3px rgba(0,0,0,0.67);
}
#nav-mobile{
  color: #FFFFC4 !important;
}
#busqueda{
  box-shadow: inset 0 -10px 20px -5px rgba(0,0,0,0.67);
  box-shadow: inset 0 10px 20px -5px rgba(0,0,0,0.67);
  color: #F4F0EA;
}
#search:focus {
  -webkit-box-shadow: inset 0px 0px 45px 3px rgba(0,0,0,0.67);
  -moz-box-shadow: inset 0px 0px 45px 3px rgba(0,0,0,0.67);
  box-shadow: inset 0px 0px 45px 3px rgba(0,0,0,0.67);
  background-color: #FF0B00;
  color: #F4F0EA;
}
.page-footer{
  color: #06152F;
  background: black;
}
a :hover{
  opacity: .6;
  transition: opacity .2s ease-out;
  -moz-transition: opacity .2s ease-out;
  -webkit-transition: opacity .2s ease-out;
  -o-transition: opacity .2s ease-out;
}

.footer-copyright{
  color: #06152F;
  background: #262626;
  font-size: 11px !important;
  -webkit-box-shadow: inset 0px 0px 45px 3px rgba(0,0,0,0.67);
  -moz-box-shadow: inset 0px 0px 45px 3px rgba(0,0,0,0.67);
  box-shadow: inset 0px 0px 45px 3px rgba(0,0,0,0.67);
  font-family: 'Roboto', sans-serif;
  font-size: 15px !important;
}
#nav ul { text-align: center; }
@media(max-width: 1080px){
  #frase3{
    font-size: 25px;
  }
  #beneficios{
    font-size: 16px;
    width: 240px;
    padding-left: 45px;
    padding-right: 32px;
  }
  #beneficios1 h1{
    font-size: 60px;
  }
  #beneficios h3{
    font-size: 36px;
  }
  #trees{
    height: 400px;
  }
  .typewriter h1{
    font-size: 4vw;
  }
  #AH{
    padding-left: 30px;
  }
  #CR{
    padding-left: 80px;
    margin: 0;
  }
  #CR h5{
    font-weight: bold;
    text-decoration: underline;
    padding-left: 35px;
  }
  #AH h5{
    font-weight: bold;
    text-decoration: underline;
    padding-left: 70px;
  }
  #ahorros li{
    width: auto;
    margin-left: 160px;
    text-align: left;
    font-weight: bold;
  }
  #credito li{
    text-align: left;
    font-weight: bold;
    width: 310px;
    overflow: hidden;
  }
  #clogo{
    width: 120px;
    height: auto;
  }
  .card-image {
    height: 100%;
    width: 100%;
    overflow: hidden;
    position: relative;
  }
  .card-title{
    font-size: 8px;
    overflow-x: hidden;
    height: 80px;
    margin: auto;
  }
  .card-image img {
    height: 300px;
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
  }
}
@media(max-width: 768px){
  #blacky{
    padding-bottom: 80px;
    padding-left: 50px;
    width: auto;
    height: auto;
    background-size: auto;
  }
  #beneficios1 h1{
    font-size: 55px;
  }
  #beneficios{
    font-size: 16px;
  }
  h1{
      font-size: 35px;
  }
  #STEC{
    font-size: 35px;
  }
  #clogo{
    width: 120px;
    height: auto;
  }
  #frase3{
    font-size: 20px;
  }
  #AH{
    padding-left: 30px;
  }
  #CR{
    padding-left: 80px;
    margin: 0;
  }
  #credito li{
    text-align: left;
    font-weight: bold;
    width: 280px;
    overflow: hidden;
  }
  #CR h5{
    padding-left: 15px;
  }
  #AH h5{
    padding-right: 55px;
  }
  #ahorros li{
    text-align: left;
    margin-left: 25%;
    font-weight: bold;
  }
  .container.row{
    padding-top: 50px;
    padding-left: 50px;
    width: 100%;
    height: auto;
  }
  .-long4.center.-blue{
    height: 650px;
  }
  #valores h1{
    font-family: 'Montserrat Subrayada', sans-serif;
    font-size: 50px;
    color: #CCCC52!important;
  }
  #contenedorValor{
    -webkit-clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
    clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
    font-family: 'Montez', cursive;
    font-size: 40px;
    color: #192B33!important;
  }
  #inicio{
    width: 100%;
    height: 100%;
    margin: 0px;
    padding: 0px;
    overflow-x: hidden;
    left: calc(50% - 75px);
  }
  #trees{
    font-size: 3.1vw;
    width: 100%;
    height: 300px;
    overflow-x: hidden;
  }
  #leaves{
    width: 100%;
    height: 100%;
    margin: 0px;
    padding: 0px;
    overflow-x: hidden;
  }
  #contenedor-principal{
    font-size: 3.0vw;
  }
  #contenedorVMision{
    font-size: 2vw;
  }
  #contenedorValor{
    height: 210px;
    width: 210px;
  }
  #cvalores{
    font-size: 5px;
  }

  .material-icons{
    font-size: 50px;
  }
  .-frase1{
    font-size: 6vw;
  }
  .typewriter h1{
    font-size: 4vw;
  }
  .h1{
    font-size: 300px;
  }
  #virtudes{
    font-size: 2.5vw;
    height: 100px;
  }
  #MVision{
    font-size: 4.9vw;
  }
  .collapsible-body{
    padding-left: 180px;
  }
  #beneficios h3{
    font-size: 4.5vw;
  }
}

</style>
