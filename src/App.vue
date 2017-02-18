<template>
  <div id="app">
    <app-bar></app-bar>
    <side-bar></side-bar>
  </div>
</template>

<script>
  import AppBar from './components/AppBar'
  import SideBar from './components/SideBar'
  export default {
    name: 'app',
    components: {
      AppBar,
      SideBar
    }
  }
</script>

<style>

</style>
