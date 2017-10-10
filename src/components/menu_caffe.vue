<template>
  <div>
    <section class="menu-platillo">
      <div class="contenedor">
        <h3 class="titulo" id="platillos">Menu</h3>
        <div class="contenedor-menu">
         <div class="contenedor-menu2">
            <article>
              <p class="categoria">De Comer</p>
              <div class="platillo">
                <p class="nombre">Sed sageittis nisl dictum</p>
                <p class="precio">$15</p>
                <p class="descripcion">Praesent gravia, augu sit amet gignissim rutrum, enim telus suscit risus.</p>
              </div>

               <div class="platillo">
                  <p class="nombre">Sed sageittis nisl dictum</p>
                  <p class="precio">$15</p>
                  <p class="descripcion">Praesent gravia, augu sit amet gignissim rutrum, enim telus suscit risus.</p>
              </div>

              <div class="platillo">
                <p class="nombre">Sed sageittis nisl dictum</p>
                <p class="precio">$15</p>
                <p class="descripcion">Praesent gravia, augu sit amet gignissim rutrum, enim telus suscit risus.</p>
              </div>
            </article>
          </div>
        </div>
      </div>
    </section>

    <section class="galeria" id="galeria">
      <div class="foto">
        <img src="../assets/img/foto1.jpg" alt="">
      </div>
      <div class="foto">
        <img src="../assets/img/foto2.jpg" alt="">
      </div>
      <div class="foto">
        <img src="../assets/img/foto3.jpg" alt="">
      </div>
      <div class="foto">
        <img src="../assets/img/foto4.jpg" alt="">
      </div>
      <div class="foto">
        <img src="../assets/img/foto5.jpg" alt="">
      </div>
      <div class="foto">
        <img src="../assets/img/foto6.jpg" alt="">
      </div>
      <div class="foto">
        <img src="../assets/img/foto7.jpg" alt="">
      </div>
      <div class="foto">
        <img src="../assets/img/foto8.jpg" alt="">
      </div>
     
      
     
     

    </section>
  </div>
</template>

<script>
export default {
  name: 'menu_caffe',
  data () {
    return {
    }
  }
}
</script>

<style>
*{
  margin: 0;
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
.menu-platillo {
  padding-top: 570px;
  margin-bottom: 50px;
}

.menu-platillo .titulo{
  font-size: 40px;
  font-weight: 300;
  text-align: center;
  margin-bottom: 40px;
}

.menu-platillo .contenedor-menu,
.menu-platillo .contenedor-menu2 {
  border:1px solid #000;
  background: transparent;
  padding: 10px;
  overflow: hidden;
}
</style>
