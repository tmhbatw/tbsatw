<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <div>
    {{msg}}
  </div>

  <div id = "tmhbatw">
    {{msgg}}
  </div>

  <button @click="register">登录</button>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
document.write("fuck you! world!")


export default {
  name: 'App',
  data(){
    return {
      msg : "hello world",
      msgg : "tmhbatw"
    }
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
