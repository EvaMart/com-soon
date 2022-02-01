<template>
  <div class="container" id="index-main">
    <header class="row first">
        <span class="logo"><img src="../assets/FAIRplus_logo.svg" width="20px"></span>
        <span class='brand-name'>FAIRification  <br>Tool Discoverer</span>
    </header>
    <div class="row">
      <img src="../assets/coming_soon.svg" width="25%">
    </div>
    <div class="row text">
      <h2>Coming soon</h2>
    </div>
  </div>
</template>
<style scoped>
#index-main{
  text-align: center;
}
.first{
  margin-bottom: 6em;
  height: 30px;
  margin-top: 4em
}
.brand-name{
    font-weight: bolder;
    color: grey;
    text-align: left;
    padding-left: .9em;
    padding-top: .4em;
    font-size: 1rem;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
  }
  .text{
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    color: #f99768
  }
.logo{
  margin-left: .7em
}
</style>
<script>
export default {
  name: 'ComingSoon'
}
</script>
