<template>
  <div id="app">
    <h1>By Lens</h1>
    <div class="description">
      <p>By lens is an Android app to introduce interesting trivias of a movie.</p>
      <p>In addition, this is also my final assignment for my Intelligent Mobile Development course</p>
    </div>
    <div>
      <p id="developerInfo">Developed by Zodiac</p>
    </div>
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#developerInfo{
  font-weight: 600;
}

</style>
