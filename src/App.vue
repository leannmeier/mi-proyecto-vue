<template>
  <div class="contain">
    <div class="jumbo">
      <h1>Bienvenidos a Vue CLI</h1> 
      <h2>Componente principal (App)</h2>
      <br>

      <Binding />
      <Estructura />
      <Atributos />

    </div>
  </div> 
</template> <!-- seccion de vista-->

<script>
import Binding from './componentes/Binding.vue'
import Estructura from './componentes/Estructura.vue'
import Atributos from './componentes/Atributos.vue'

export default {
  name: 'App',
  components: {
    Binding,
    Estructura,
    Atributos, 
  }
}
</script> <!-- seccion de controlador-->

<style>
h1{
  color: crimson;
}
h2{
  color: blue;
}
hr{
  color:black;
}
</style> <!-- seccion de estilos-->
