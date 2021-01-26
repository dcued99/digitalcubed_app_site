<template>
  <div id="app"><br/><br/>
    <img alt="Digital Cubed logo" src="./assets/Digital-Cubed-logo.png" width="200">
    <HelloWorld msg=" "/>
  <br/><br/>
<center>1000 N Division St Unit 2A, Peekskill, New York, 10566, United States<br>
<a href="https://www.google.com/maps/place/Digital+Cubed/@41.3013957,-73.9183462,15z/data=!4m5!3m4!1s0x0:0x696bf981be2cb663!8m2!3d41.3048983!4d-73.9148703">Map</a>
                    <br><br>&copy; 2005 - 2021 Digital Cubed L.L.C.</center><br><br>

  </div>



</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
html, body {
                width: 100%;
                height: 100%;
                margin: 0;
                padding: 0;
                background-image: url("./assets/d3_sitebackground.jpg");
  background-repeat: no-repeat;
  background-size: cover;background-position: center;

            }
#app {
              
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color:white;
  opacity: 80%;

}
</style>
