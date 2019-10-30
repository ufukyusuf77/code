<template>
  <div id="app">
    <MainHeader></MainHeader>
  </div>
</template>

<script>
  import MainHeader from "./components/MainHeader";


export default {
  name: 'app',
  components: {
    MainHeader,
  }
}


</script>

<style>
#app {
  padding: 0 30px 0 30px;
}
</style>
