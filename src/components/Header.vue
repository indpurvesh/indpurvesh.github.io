<template>
  <a-layout-header class="avored-navbar">
    <div class="logo">
      <img src="../assets/logo.svg" alt="AvoRed E commerce" />voRed
    </div>
    <a-menu
      theme="light"
      mode="horizontal"
      class="avored-nav"
      :default-selectedkeys="['2']"
      :style="{ lineHeight: '64px' }">
      <a-menu-item key="1">nav 1</a-menu-item>
      <a-menu-item key="2">nav 2</a-menu-item>
      <a-menu-item key="3">nav 3</a-menu-item>
    </a-menu>
  </a-layout-header>
</template>

<script>
export default {
  name: 'Header',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.logo {
    float: left;
    font-weight: bold;
    font-size: 1rem;
    line-height: 55px;
    padding: 5px 20px;
}
.logo img {
  height: 40px;
  
}
#app .avored-navbar {
  background-color: #fff;
  -webkit-box-shadow: 0px 5px 5px 0px rgba(221,221,221,1);
  -moz-box-shadow: 0px 5px 5px 0px rgba(221,221,221,1);
  box-shadow: 0px 5px 5px 0px rgba(221,221,221,1);
}
#app .avored-nav {
  float:right;
  border: 0px solid #fff;
  line-height: 63px !important;
}
</style>
