# lm-bootstrap-trabajo

INTRODUCCIÓN

El tema escogido para esta página web es "Canaima Tierra Mágica". He querido poner en valor un territorio de mi querido país, el cual es uno de los lugares
más antiguos del planeta con una belleza y energía indescriptible, únicas la verdad. En ella hay una sección inicial con imágenes del salto Ángel y río Jaspe
(piedra sagrada de la tribu Pemóm, guardianes de Canaima). Luego hay un pequeño apartado de la historia, tomada de https://en.wikipedia.org/wiki/Canaima_National_Park
y otro de la Leyenda de Canaima, tomada de http://narradoresdelmisterio.net/la-leyenda-de-canaima/. Le sigue la sección de galería de imágenes donde se
muestran la fauna y el paisaje expectacular de  esta zona. Le continua una sección con un vídeo de Canaima y su localización en Google Maps. Seguidamente, 
hay un formulario de Registro, que pretende que los visitantes se registren para recibir más información (visitas, historias, posadas, actividades, etc...). 
Finalmente, el Footer en el que se muestran los datos de contacto y las redes sociales.

CODIGOS DE BOOTSTRAP 4

Se ha usado el IDE Visual Studio Code. Además, se ha utilizado las herramientas de Bootstrap 4 como: 
-Navbar, para la barra de navegación:

 <!--Barra de navegación
  <nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">
        <img src="images/choza.jpeg" alt="" style="width: 20%">
      </a>
      Botón hamburguesa
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#hero">Inicio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#historia">Historia</a> 
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#leyenda">Leyenda</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#galeria">Galería de imágenes</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#localizacion">Localización</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#registro">Registro</a>
          </li>
        </ul>
      </div>
    </div>
  </nav> -->

-Cards para la galería de imágenes, las imágenes de la sección de registro y del Footer:

<!-- <div class="card border-dark">
            <div class="card-body">
              <img src="images/card-1.jpeg" class="d-block w-100" alt="..." class="img-fluid">
            </div>
          </div> -->

-Carousel en la hero section:

<!-- <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
              <ol class="carousel-indicators">
                <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
              </ol>
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img src="images/salto-del-angel.jpg" class="d-block w-100" alt="..." class="img-fluid">
                </div>
                <div class="carousel-item">
                  <img src="images/jaspe.jpeg" class="d-block w-100" alt="..." class="img-fluid">
                </div>
                <div class="carousel-item">
                  <img src="images/salto.jpg" class="d-block w-100" alt="..." class="img-fluid">
                </div>
              </div>
              <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
              </a>
            </div> -->

Collapse (Acordion) para las condiciones de uso y política de privacidad:

 <!--Politica de privacidad
            <div class="accordion" id="accordion">
              <div class="card">
                <div class="card-header" id="headingOne">
                  <h2 class="mb-0">
                    <button class="btn btn-link btn-block text-left" type="button" data-toggle="collapse"
                      data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                      Condiciones de uso y política de privacidad
                    </button>
                  </h2>
                </div> 

                <div id="collapseOne" class="collapse show" aria-labelledby="headingOne"
                  data-parent="#accordionExample">
                  <div class="card-body">
                 
                  </div>
                </div>
              </div> -->

-Form para el formulario de registro y la casilla de selección. 

<!-- <form action="">
            <div class="input-group mb-3">
              <div class="input-group-prepend">
                <i class="fas fa-user input-group-text fa-lg"></i>
              </div>
              <input type="text" name="" id="" class="form-control" placeholder="Nombre">
            </div>
            <div class="input-group mb-3">
              <div class="input-group-prepend">
                <i class="fas fa-envelope input-group-text fa-lg"></i>
              </div>
              <input type="email" name="" id="" class="form-control" placeholder="email">
            </div>
            <div class="input-group mb-3">
              <div class="input-group-prepend">
                <i class="fas fa-key input-group-text fa-lg"></i>
              </div>
              <input type="password" name="" id="" class="form-control" placeholder="Contraseña">
            </div>
            <div class="input-group mb-3">
              <div class="input-group-prepend">
                <i class="fas fa-key input-group-text fa-lg"></i>
              </div>
              <input type="password" name="" id="" class="form-control" placeholder="Repetir contraseña">
            </div>
  
            <!--Politica de privacidad-->
           
            <div class="input-group mb-3">
              <div class="form-group form-check">
                <input type="checkbox" class="form-check-input" id="exampleCheck1">
                <label class="form-check-label" for="exampleCheck1">Acepto las condiciones de uso y la política de
                  privacidad</label>
              </div>
            </div>
            <button type="submit" class="btn btn-primary">Registrar</button>
          </form> -->

Estas herramientas son de la sección de Components. También se usaron las herramientas del Layout de Bootstrap 4, como: container, grid y fluid que están por todo el código.

HEAD DEL HTML

En la cabecera del html se colocarón los enlaces del favicon, Bootstrap 4 CSS, enlace al CCS del estilo y el enlace a Fontawesome. 

  <!--Favicon-->
  <link rel="shortcut icon" href="images/favicon.ico" type="image/x-icon" />
  <!--Bootstrap CSS-->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css"
    integrity="sha384-B0vP5xmATw1+K9KRQjQERJvTumQW0nPEzvF6L/Z6nronJ3oUOFUFpCjEUQouq2+l" crossorigin="anonymous" />
  <!--Enlace al CSS-->
  <link rel="stylesheet" href="styles/style.css">
  <!--Enlace a Fontawesome-->
  <script src="https://kit.fontawesome.com/ddf51cda3b.js" crossorigin="anonymous"></script>
  
 JAVA SCRIPT
 
 <!--Bootstrap js-->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
    integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
    crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
    integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
    crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.min.js"
    integrity="sha384-+YQ4JLhjyBLPDQt//I+STsc9iw4uQqACwlvpslubQzn4u2UU2UFM80nGisd026JF"
    crossorigin="anonymous"></script>
    
CSS

.navbar {
  box-shadow: 2px 2px 5px #000;
}

.navbar .nav-item .nav-link {
  color: #fff;
}

.hero {
  position: relative;
  background-color: rgba(83, 92, 104, 1);
}

NOTA

Por otra parte, para los colores, la página https://flatuicolors.com/palette/au está muy bien. Los íconos se sacaron de la página https://fontawesome.com/. 
Finalmente, el favicon se hizo desde https://www.favicon.cc/.



