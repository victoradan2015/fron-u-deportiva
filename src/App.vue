<template>
  <div id="app">
    <nav-bar/>
    <Registro/>
    <Login/>
    <registro-alumno/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import RegistroAlumno from './components/registro/RegistroAlumno.vue'
import Login from './components/sesion/Login.vue'
import Registro from './components/sesion/Registro.vue'

export default {
  name: 'App',
  components: {
    Registro,
    Login,
    NavBar,
    RegistroAlumno,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
