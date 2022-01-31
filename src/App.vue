<template>
<div class="flex-row">
   
  <!-- <img alt="Vue logo" src="./assets/logo.svg" class="img">  -->
  
  <svg  width="600" height="100" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
      <rect class="linea" x="260" y="4" width="80" height="60" rx="15" ry="15"></rect>
      <line class="linea" x1="285" y1="85" x2="315" y2="85"></line>
      <ellipse class="rojo circulo2" cx="300" cy="50" rx="1" ry="1"></ellipse>
      <line  class="rojo circulo1" x1="300" y1="20" x2="300" y2="40" ></line>
  </svg>
</div>


</template>

<script>

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
.linea{
  stroke-width: 9;
}

.circulo2{
  fill:black;
}
.circulo1{
  stroke-width: 5;
}
.rojo{
  stroke:red;
}

svg {
  stroke: #000;
  stroke-width: 5;
  stroke-linecap: round;
  stroke-linejoin: round;
  fill: none;
}

.flex-row{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 0;
}


img {
  width: 100px;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
