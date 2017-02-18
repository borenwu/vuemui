<template>
  <aside id="left-sidebar-nav">
    <ul id="slide-out" class="side-nav fixed leftside-navigation">
      <li class="user-details cyan darken-2">
        <div class="row">
          <div class="col col s4 m4 l4">
            <img src="static/images/avatar.jpg" alt="" class="circle responsive-img valign profile-image">
          </div>
          <div class="col col s8 m8 18">
            <ul id="profile-dropdown" class="dropdown-content">
              <li><a href="#"><i class="mdi-action-face-unlock"></i> Profile</a>
              </li>
              <li><a href="#"><i class="mdi-action-settings"></i> Settings</a>
              </li>
              <li><a href="#"><i class="mdi-communication-live-help"></i> Help</a>
              </li>
              <li class="divider"></li>
              <li><a href="#"><i class="mdi-action-lock-outline"></i> Lock</a>
              </li>
              <li><a href="#"><i class="mdi-hardware-keyboard-tab"></i> Logout</a>
              </li>
            </ul>
            <a class="btn-flat dropdown-button waves-effect waves-light white-text profile-btn" href="#"
               data-activates="profile-dropdown">John Doe<i class="mdi-navigation-arrow-drop-down right"></i></a>
            <p class="user-roal">Administrator</p>
          </div>
        </div>
      </li>
      <li class="bold"><a href="index.html" class="waves-effect waves-cyan">
        <i class="material-icons">dashboard</i>主页</a>
      </li>

      <li class="bold"><a href="app-calendar.html" class="waves-effect waves-cyan">
        <i class="material-icons">today</i>日历</a>
      </li>

      <li class="no-padding">
        <ul class="collapsible collapsible-accordion">
          <li class="bold"><a class="collapsible-header waves-effect waves-cyan">
            <i class="material-icons">assignment</i> 订单</a>
          </li>

          <li class="bold"><a class="collapsible-header  waves-effect waves-cyan"><i class="material-icons">schedule</i>生产</a>
            <div class="collapsible-body">
              <ul>
                <li><a href="ui-buttons.html">Buttons</a>
                </li>
                <li><a href="ui-badges.html">Badges</a>
                </li>
                <li><a href="ui-cards.html">Cards</a>
                </li>
                <li><a href="ui-collections.html">Collections</a>
                </li>
                <li><a href="ui-accordions.html">Accordian</a>
                </li>
                <li><a href="ui-navbar.html">Navbar</a>
                </li>
                <li><a href="ui-pagination.html">Pagination</a>
                </li>
                <li><a href="ui-preloader.html">Preloader</a>
                </li>
                <li><a href="ui-modals.html">Modals</a>
                </li>
                <li><a href="ui-media.html">Media</a>
                </li>
                <li><a href="ui-toasts.html">Toasts</a>
                </li>
                <li><a href="ui-tooltip.html">Tooltip</a>
                </li>
              </ul>
            </div>
          </li>

          <li class="bold"><a class="collapsible-header  waves-effect waves-cyan"><i class="material-icons">store</i>
            仓库</a>
            <div class="collapsible-body">
              <ul>
                <li><a href="table-basic.html">Basic Tables</a>
                </li>
                <li><a href="table-data.html">Data Tables</a>
                </li>
              </ul>
            </div>
          </li>

          <li class="bold"><a class="collapsible-header  waves-effect waves-cyan">
            <i class="material-icons">equalizer</i> 财务</a>
            <div class="collapsible-body">
              <ul>
                <li><a href="form-elements.html">Form Elements</a>
                </li>
                <li><a href="form-layouts.html">Form Layouts</a>
                </li>
              </ul>
            </div>
          </li>
        </ul>
      </li>

      <li class="li-hover">
        <div class="divider"></div>
      </li>
      <li class="li-hover"><p class="ultra-small margin more-text">更多</p></li>
      <li><a href="css-grid.html"><i class="material-icons">av_timer</i> 天气</a>
      </li>
      <li><a href="css-helpers.html"><i class="mdi-communication-live-help"></i> 帮助</a>
      </li>
      <li><a href="changelogs.html"><i class="mdi-action-swap-vert-circle"></i> 管理员入口</a>
      </li>
      <li class="li-hover">
        <div class="divider"></div>
      </li>
      <!--<li class="li-hover"><p class="ultra-small margin more-text">Daily Sales</p></li>-->
      <!--<li class="li-hover">-->
        <!--<div class="row">-->
          <!--<div class="col s12 m12 l12">-->
            <!--<div class="sample-chart-wrapper">-->
              <!--<div class="ct-chart ct-golden-section" id="ct2-chart"></div>-->
            <!--</div>-->
          <!--</div>-->
        <!--</div>-->
      <!--</li>-->
    </ul>
    <a href="#" data-activates="slide-out"
       class="sidebar-collapse btn-floating btn-medium waves-effect waves-light hide-on-large-only darken-2"><i
      class="mdi-navigation-menu"></i></a>
  </aside>
</template>

<style>
  ul.side-nav.fixed {
    top: 64px;
  }

  @media only screen and (max-width: 992px) {
    ul.side-nav.fixed {
      top: 56px;
    }
  }

  ul.side-nav.fixed hr {
    display: block;
    height: 1px;
    border: 0;
    border-top: 1px solid #e0e0e0;
    margin: 1em 0;
    padding: 0;
  }

  .side-nav a {
    line-height: 42px;
    height: 42px;
  }

  #left-sidebar-nav {
    position: fixed;
    width: 100px;
    left: 180px;
    z-index: 999;
    height: auto;
  }

  #slide-out li a i {
    line-height: inherit;
    width: 2rem;
    font-size: 1.6rem;
    display: block;
    float: left;
    text-align: center;
    margin-right: 1rem;
  }

  #slide-out ul.side-nav li {
    padding: 0px !important;
  }

  ul.side-nav li {
    padding: 0;
  }

  ul.side-nav .collapsible-header {
    margin: 0;
  }

  .caption {
    font-size: 1.25rem;
    font-weight: 300;
    margin-bottom: 30px;
  }

  .caption-uppercase {
    font-size: 1.25rem;
    font-weight: 300;
    margin-bottom: 30px;
    text-transform: uppercase;
  }

  .sidebar-collapse {
    position: absolute;
    left: -170px;
    top: -45px;
  }

  ul.side-nav.fixed {
    overflow: hidden;
  }

  ul.side-nav.fixed li {
    line-height: 44px;
  }

  ul.side-nav.fixed li:hover,
  ul.side-nav.fixed li.active {
    background-color: rgba(0, 0, 0, 0.05);
  }

  ul.side-nav.fixed li a {
    /*font-family: "Microsoft YaHei";*/
    font-size: 17px;
    font-weight: 400;
  }
  ul.side-nav.fixed .dropdown-content li a{
    font-size: 14px;
  }
  .side-nav .collapsible-body li a {
    margin: 0 1rem 0 3rem;
  }

  ul.side-nav.fixed ul.collapsible-accordion {
    background-color: #FFF;
  }

  ul.side-nav.fixed:hover {
    /*overflow-y:hidden;*/
  }

  ul.side-nav.fixed li.user-details {
    background: url('/static/images/user-bg.jpg') no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    /*overflow: hidden;*/

    margin-bottom: 15px;
    padding: 15px 0px 0px 15px;
  }

  .user-details .row {
    margin: 0;
  }

  .user-task,
  .user-time {
    margin: 0;
    font-size: 13px;
    color: #fff;
  }

  ul.side-nav.fixed .profile-image {
    /*height: 50px;*/
  }

  ul.side-nav.fixed .profile-btn {
    margin: 0;
    text-transform: capitalize;
    padding: 0;
    text-shadow: 1px 1px 1px #444;
    font-size: 15px;
  }

  .user-roal {
    color: #fff;
    margin-top: -16px;
    font-size: 13px;
    text-shadow: 1px 1px 1px #444;
  }

  .bold > a {
    font-weight: bold;
  }

  nav.top-nav {
    height: 122px;
    -webkit-box-shadow: none;
    -moz-box-shadow: none;
    box-shadow: none;
  }

  nav.top-nav a.page-title {
    line-height: 122px;
    font-size: 48px;
  }
</style>


<script>

  export default{
    name: 'side-bar',
    data(){
      return {
        msg: 'hello side bar'
      }
    },
    components: {}
  }
</script>
