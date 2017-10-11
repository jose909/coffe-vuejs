<template>
  <div>
    <section class="ubicacion" id="ubicacion">
      <div class="contenedor">
        <h3 class="titulo">Ubicacion</h3>
        <div class="direccion">
          <p class="calle">3ra. Av 8-56 Plaza Santa Elena<br/> 503 Antiguo Cuscatlán</p>
          <p class="telefono">(503) 2246-0009</p>
          <p class="correo">rosaleayal19@hotmail.com</p>
        </div>
        <div class="horarios">
          <h4>Horarios</h4>
          <p class="entre-semana">Lunes a Viernes <br> 6:00am - 23:00pm</p>
          <p class="fin-semana">Sabados a Domingos <br> 8:00am - 23:00pm</p>
        </div>
      </div>
    </section>
    <section class="mapa">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3876.780713982556!2d-89.25724268561586!3d13.67109389039973!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x67c415e6189cebbd!2sPlaza+Madero!5e0!3m2!1ses-419!2ssv!4v1507684694669" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
    </section>
    <footer>
      <div class="contenedor">
        <div class="copyright">
          <p>Copyright Jose Rosales @ 2017</p>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: 'ubicacion',
  data () {
    return {
    }
  }
}
</script>

<style>

/* ----- ----- UBICACION ----- ----- */
.ubicacion{
  background: #ffffff;
  padding: 60px 0;
  overflow: hidden;
}

.ubicacion .titulo{
  text-align: center;
  font-size: 40px;
  line-height: 40px;
  font-weight: 300;
  margin-bottom: 40px;

}

.ubicacion .direccion{
  float: left;
  width: 50%;
  text-align: left;
}

.ubicacion .horarios{
  float: right;
  width: 50%;
  text-align: right;
  overflow: hidden;
}

.ubicacion .direccion .calle{
  margin-bottom: 15px;
}
.ubicacion .horarios h4{
  text-align: center;
  margin-bottom: 20px;
}

.ubicacion .horarios .entre-semana,
.ubicacion .horarios .fin-semana{
  width: 50%;
  float: left;
  text-align: center;
}

.mapa{
  width: 100%;
  overflow: hidden;
}

.mapa iframe{
  width: 100%;
  max-height: 600px;
}

/* ----- ----- FOOTER ----- ----- */
footer{
  background: #000000;
}

footer .copyright{
  text-align: center;
  padding: 15px 0;
  color: #ffffff;
}
</style>
