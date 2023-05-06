<!DOCTYPE html>
<html>
  <head>
    <title>W3.CSS Template</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Inconsolata">
    <style>
    body, html {
      height: 100%;
      font-family: "Inconsolata", sans-serif;
    }

    .bgimg {
      background-position: center;
      background-size: cover;
      background-image: url("https://cdn0.bodas.com.mx/vendor/2170/3_2/960/jpg/img-2075_5_112170.jpeg");
      min-height: 75%;
    }

    .menu {
      display: none;
    }
    </style>
  </head>
<body>

<!-- Links (sit on top) -->
<div class="w3-top">
  <div class="w3-row w3-padding w3-black">
    <div class="w3-col s3">
      <a href="#" class="w3-button w3-block w3-black">INICIO</a>
    </div>
    <div class="w3-col s3">
      <a href="#about" class="w3-button w3-block w3-black">CONOCENOS</a>
    </div>
    <div class="w3-col s3">
      <a href="#menu" class="w3-button w3-block w3-black">MENÚ</a>
    </div>
    <div class="w3-col s3">
      <a href="#where" class="w3-button w3-block w3-black">DIRECCIÓN</a>
    </div>
  </div>
</div>

<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-center w3-padding-large w3-hide-small">
    <span class="w3-tag">Abierto de 8:00 am a 6:00 pm</span>
  </div>
  <div class="w3-display-middle w3-center">
    <span class="w3-text-white" style="font-size:90px">PASTELERIA<br>PALADAR</span>
  </div>
  <div class="w3-display-bottomright w3-center w3-padding-large">
    <span class="w3-text-white">Nebaj, Quiche. Desde 2021</span>
  </div>
</header>

<!-- Add a background color and large text to the whole page -->
<div class="w3-sand w3-grayscale w3-large">

<!-- About Container -->
<div class="w3-container" id="about">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">LOS MEJORES EN REPOSTERIA ARTESANAL</span></h5>
    <p>Iniciamos nuestras actividades el 10 de enero de 2021, desde entonces nuestros clientes han disfrutado la excelente calidad de nuestros productos.

Comenzamos instalandonos en un local tomado en arriendo en el barrio del Centro en Nebaj ofreciendo productos de panadería tales como: galletería, bizcochería, pastelería y los rosquetes cocidos y plumeros.

Intentando salir adelante con nuestro negocio, tomando determinadas estrategias de ventas tomamos la decisión de impulsar y dedicarnos únicamente a la producción de Postres Artesanales especial mente Pasteles, así Pasteleria Paladar logro mejorar nuestra maquinaria y empezamos la comercialización y distribución en los diferentes municipios del departamento.

Actualmente nuestra fábrica se encuentra ubicada en el Centro de Nebaj en donde buscamos el mejoramiento continuó en nuestros procesos productivos y la expansión de nuestros productos en todo el territorio nacional.
</p>
    <p>Emprendimiento por Catarina Brito.</p>
    <div class="w3-panel w3-leftbar w3-light-grey">
      <p><i>"Nuestros productos estan echos con productos 100% naturales y de la más alta calidad, visita nuestra tienda fisica y conoce mas de nosotros".</i></p>
      <p>¡Conoce nuestra gran variedad de Adornos para cumpleaños asi puedan pasarla bien en esas fechas tan especiales!</p>
    </div>
    <img src="https://www.w3schools.com/w3images/coffeeshop.jpg" style="width:100%;max-width:1000px" class="w3-margin-top">
    <p><strong>Horarios de Atención:</strong> Lunes a Domingo de 8:00 am a 6:00 pm.</p>
    <p><strong>Dirrección:</strong> Nebaj, Quiche desde 2021 calle pricipal, NY</p>
  </div>
</div>

<!-- Menu Container -->
<div class="w3-container" id="menu">
  <div class="w3-content" style="max-width:700px">
 
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">NUESTRO MENÚ</span></h5>
  
    <div class="w3-row w3-center w3-card w3-padding">
      <a href="javascript:void(0)" onclick="openMenu(event, 'POSTRES');" id="myLink">
        <div class="w3-col s6 tablink">POSTRES</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Drink');">
        <div class="w3-col s6 tablink">BEBIDAS</div>
      </a>
    </div>

    <div id="POSTRES" class="w3-container menu w3-padding-48 w3-card">
      <h5>Pastel Tres Leches</h5>
      <p class="w3-text-grey"> Mediano (Q 150.00), Grande (Q 225.00)</p><br>
    
      <h5>Pastel de Chocolate con Vainilla</h5>
      <p class="w3-text-grey"> Mediano (Q 150.00), Grande (Q 225.00)</p><br>
    
      <h5>Pastel de Chocolate y Crema</h5>
      <p class="w3-text-grey"> Mediano (Q 150.00), Grande (Q 225.00)</p><br>
    
      <h5>Pastel de Fresa con Crema</h5>
      <p class="w3-text-grey"> Porcion (Q 5.00), Grande (Q 100.00)</p><br>
    
      <h5>Pastel de Vainilla</h5>
      <p class="w3-text-grey"> Porcion (Q 5.00), Grande (Q 100.00)</p>
    </div>

    <div id="Drink" class="w3-container menu w3-padding-48 w3-card">
      <h5>Café</h5>
      <p class="w3-text-grey">Cafe Negro (Q 8.50)</p><br>
    
      <h5>Chocolate</h5>
      <p class="w3-text-grey">Chocolate espresso con leche (Q 15.00)</p><br>
    
      <h5>Capuchino</h5>
      <p class="w3-text-grey">Capuchino Mediano (Q 10.00)</p><br>
    
      <h5>Te Frio</h5>
      <p class="w3-text-grey">TE SABORES (Q 10.00)</p><br>
    
      <h5>Sodas</h5>
      <p class="w3-text-grey">Coke, Sprite, Fanta, etc. (Q 8.50)</p>
    </div>  
    <img src="https://www.w3schools.com/w3images/coffeehouse2.jpg" style="width:100%;max-width:1000px;margin-top:32px;">
  </div>
</div>

<!-- Contact/Area Container -->
<div class="w3-container" id="where" style="padding-bottom:32px;">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">Donde Encontrarnos</span></h5>
    <p>Visita nuestra tienda fisica.</p>
    <img src="https://www.w3schools.com/w3images/map.jpg" class="w3-image" style="width:100%">
    <p><span class="w3-tag">Apresurate!</span> Encuentranos en Nebaj en la 3 Av 1-23 zona 1.</p>
    <p><strong>Pedidos:</strong> Solicita aqui lo que gustes:</p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Nombre" required name="Name"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="numero" placeholder="Para cuantas personas" required name="Persona"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2023-04-16T20:00"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Ecribe aqui lo que necesitas" required name="Message"></p>
      <p><button class="w3-button w3-black" type="submit">ENVIAR MENSAJE</button></p>
    </form>
  </div>
</div>

<!-- End page content -->
</div>

<!-- Footer. This section contains an ad for W3Schools Spaces. You can leave it to support us. -->
<footer class="w3-center w3-light-grey w3-padding-48 w3-large">
  <p></p>
  
 <!-- Footer end. -->
 </footer>

<script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-dark-grey", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-dark-grey";
}
document.getElementById("myLink").click();
</script>

</body>
</html>
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
