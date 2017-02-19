<template>
  <div id="app">
    <app-bar></app-bar>
    <main-content></main-content>
  </div>
</template>

<script>
  import AppBar from './components/AppBar'
  import MainContent from './components/MainContent'
  import SideBar from './components/SideBar'
  import MainPage from './components/MainPage'

  export default {
    name: 'app',
    components: {
      AppBar,
      MainContent
    }
  }
</script>

<style>

</style>
