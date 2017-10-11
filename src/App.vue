<template>
  <div>
   <acerca></acerca>
   <menu_caffe></menu_caffe>
   <ubicacion></ubicacion>
  </div>
</template>

<script>
import acerca from  './components/acerca.vue';
import menu_caffe from  './components/menu_caffe.vue';
import ubicacion from  './components/ubicacion.vue';

export default {
  components: { acerca, menu_caffe, ubicacion },
  data () {
    return {}
  }
}
</script>

<style>
</style>
