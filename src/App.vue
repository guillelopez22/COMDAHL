<template>
  <div id="app">


    <router-view></router-view>
    <div class="tap-target" data-activates="menu">
      <div class="tap-target-content">
        <p>Al crearte una cuenta recibirás promociones especiales y podras ordenar desde tu móvil</p>
      </div>
    </div>
    <footer class="page-footer">
      <div class="container" id="foot">
        <div class="row">
          <div class="col l6 s6">
            <h5 class="white-text">Ubicación</h5>
            <p class="grey-text text-lighten-4" id="footText">
              Colonia Alameda 2da Ave. Sendero Subirana/ Tegucigalpa M.D.C., a tres casas del CINAH, frente al kínder Belén Star, casa #547.</p>
            </div>
            <div class="col l4 offset-l2 s6">
              <h5 class="white-text">Conéctate con nosotros</h5>
              <ul>
                <li>
                  <div class="col s3 center" id="foots">
                    <a href="https://www.facebook.com/COMDAHL/?ref=br_rs" target="_blank">
                      <img  src="https://www.iconfinder.com/data/icons/free-social-icons/67/facebook_circle_gray-64.png"></img>
                    </a>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="container" id="foot">
          <div class="row">
            <div class="col s8">
              <p class="grey-text text-lighten-4" id="footText">
                <i class="Small material-icons left">call</i> Teléfonos (+504)<br>  2235 - 9384  /  2262 - 8660 <br> 9430-723 / 9892-5851
              </p>
            </div>
            <div class="col s4 ">
              <p class="grey-text text-lighten-4" id="footText">
                <i class="small material-icons left">email</i>Correos<br> Comdahl.hn@gmail.com / administracion@comdahl.hn
              </p>
            </div>
            <div class="col s12">
              <p class="grey-text text-lighten-4" id="footText">
                <i class="small material-icons left">face</i>Horarios de Atencion<br> Lunes: 9:00 A.M - 5:00 P.M. <br> Sábado 9:00 A.M - 12:00 P.M.
              </p>
            </div>
          </div>
        </div>
        <div class="footer-copyright">
          <div class="container white-text">
            © 2017 Copyright COMDAHL
          </div>
        </div>
      </footer>

    </div>
  </template>

  <script>
  import Home from './components/Home.vue'
  export default {
    name: 'app',
    methods:{
      // $('.tap-target').tapTarget('open'),
      // $('.tap-target').tapTarget('close')
    }
  }
  </script>

  <style scoped>

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

  </style>
