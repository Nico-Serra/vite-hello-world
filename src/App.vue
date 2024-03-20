<script>
//import HelloWorld from './components/HelloWorld.vue'
export default {
  data() {
    return {
      message: 'Hello World',
    }
  }
}
</script>

<template>
  <!-- <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" /> -->

  <header>
    <h1>{{ message }}</h1>
  </header>
  <main></main>
  <footer></footer>
</template>

<style>
h1{
  background-color: black;
  color: white
}
/* body{
  background-color: black;
} */
</style>
