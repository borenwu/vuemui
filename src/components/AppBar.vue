<template>
  <header id="header" class="page-topbar">
    <!-- start header nav-->
    <div class="navbar-fixed">
      <nav class="cyan">
        <div class="nav-wrapper">
          <h1 class="logo-wrapper"><a href="index.html" class="brand-logo darken-1"><img src="static/images/materialize-logo.png" alt="materialize logo"></a> <span class="logo-text">Materialize</span></h1>
          <ul class="right hide-on-med-and-down">
            <li class="search-out">
              <input type="text" class="search-out-text">
            </li>
            <li>
              <a href="javascript:void(0);" class="waves-effect waves-block waves-light show-search"><i class="mdi-action-search"></i></a>
            </li>
            <li><a href="javascript:void(0);" class="waves-effect waves-block waves-light toggle-fullscreen"><i class="mdi-action-settings-overscan"></i></a>
            </li>
            <li><a href="javascript:void(0);" class="waves-effect waves-block waves-light"><i class="mdi-social-notifications"></i></a>
            </li>
            <!-- Dropdown Trigger -->
            <li><a href="#" data-activates="chat-out" class="waves-effect waves-block waves-light chat-collapse"><i class="mdi-communication-chat"></i></a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
    <!-- end header nav-->
  </header>
</template>

<style>
  h1.logo-wrapper{
    margin: 0px 0px;
  }
  h1 span.logo-text{
    display: none;
  }
  header .brand-logo {
    margin: 5px 0px;
    /*padding: 0 42px;
    padding: 0px 10px 0 75px;*/

    padding: 0 20px;
  }
  @media only screen and (max-width: 992px) {
    nav .nav-wrapper {
      text-align: center;
    }
    nav .nav-wrapper a.page-title {
      font-size: 36px;
    }
  }
  li.search-out:hover{
    background: transparent;
  }
  .search-out{
    display: none;
  }
  .search-out-text{
    border-bottom: 1px solid #fff !important;
  }
  .search-out input[type=text]:focus:not([readonly]){
    border-bottom: 1px solid #fff !important;
    box-shadow:none;
  }
</style>

<script>

  export default{
    data(){
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    },
    components: {}
  }
</script>
