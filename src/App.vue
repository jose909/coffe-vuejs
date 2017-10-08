<template>
  <div id="app">
    <header>
        <div class="contenedor">
          <nav class="menu">
            <a href="#" id="btn-acerca-de">Acerca de </a>
            <a href="#" id="btn-menu">Menu </a>
            <a href="#" id="btn-galeria">Galeria</a>
            <a href="#" id="btn-ubicacion">Ubicacion</a>
          </nav>
    
          <div class="textos">
            <h1 class="nombre">Cofe <span>Vue</span></h1>
            <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</h3>
          </div>
        </div>
    </header>

    <section class="main">
      <div class="contenedor">
        <div class="foto">
              <img src= "./assets/foto10.jpg">
        </div>
          <article>
            <h3>Acerca de</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            <p>Nam a convallis libero. Morbi bibendum, tortor ut placerat ornare, dui ligula pellentesque risus, sed tincidunt metus arcu a dui.</p>

            <p> Nam a convallis libero. Morbi bibendum, tortor ut placerat ornare, dui ligula pellentesque risus, sed tincidunt metus arcu a dui. Suspendisse imperdiet suscipit blandit. Pellentesque eget metus sed odio fringilla varius a vitae risus. Donec ac lobortis urna</p>
          </article>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      //src: './assets/foto10.jpg',
    }
  }
}
</script>

<style >


*{
  margin: 0;
  padding: 0;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}

body {
  font-family: "Open Sans", Arial, Sans-serif;
  font-size: 16;
}

.contenedor {
  width: 90%;
  max-width: 1000px;
  margin: auto;
  overflow: hidden;
}

/*----- ----- HEADER ----- -----*/
header {
  width: 100%;
  background: url(./assets/foto14.jpg) #281a0c;
  background-size:cover;
  background-attachment: fixed;
  background-position: center 0;

}
header .contenedor{
  position: relative;
  height: 700px;
}

header .menu {
  width: 100%;
  text-align: right;
}

header .menu a {
  color: #ffffff;
  font-size: 20px;
  font-weight: 300;
  display: inline-block;
  margin: 40px 20px;
  text-decoration: none;
  position: relative;

}

header .menu a:hover{
  text-decoration: underline;
}

header .textos{
  widows: 100%;
  color: #fff;
  position: absolute;
  top: 50%;
  margin-top:-52px;

}
header .textos .nombre{
  font-size: 50px;
  font-weight: 600;
}

header .textos .nombre span{
  font-weight: 300;
}

header .textos {
  font-size: 25px;
  font-weight: 300;
  font-style: italic;
}
</style>
