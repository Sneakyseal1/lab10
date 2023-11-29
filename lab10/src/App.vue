<script setup>
import Home from './components/Home.vue'
import HelloWorld from './components/HelloWorld.vue'

</script>

<template>
  <header>
    <div class="wrapper">
      <HelloWorld msg="Welcome to my Lab 10 Web Page" />
    </div>
  </header>

  <main>
    <br>
    <br>
    <div style="text-align: center">
      <h1 class="color">After Installing Node.js, I created a folder on my desktop and used windows powershell as well as Vue CLI (Command Line Interface) in order to create a Vue.js project.</h1>
      <br>
      <h1 class="color">After preparing the project, I opened the folder in visual studio and started manipulating the vue files with both html and css.</h1>
      <br>
      <h1 class="color1">The main difficulties I faced was navigating through all the files provided by the default Vue CLI set up as well as understanding the syntax and how each file worked together.</h1>
      <br>
    </div>
  </main>
</template>


<!--
.wrapper {
  text-align: center;
}
.h1{
  display: flex;
}

#app {
  color: white;
  background-color: #722F37;
  height: 100vh;
  width: 100%;
}
.border{
  color: aqua;
  border: 2px solid black;
  border-style: groove;
  display: absolute;
}
-->
<style>
#app {
  color:antiquewhite;
}
body{
  background: rebeccapurple;
}
.color{
  color:aquamarine
}
.color1{
  color:crimson
}
</style>

