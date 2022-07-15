<template>
  <div class="main-header">
    <div class="search-header">
      <div class="img-logo">
        <img src="../../assets/jtp_logo.png">
      </div>
      <div>
        <input type="text">
      </div>

    </div>
    <div class="menu-header">menu</div>
  </div>
</template>

<script>
export default {
  name: "header"
}
</script>

<style scoped>
  .main-header{
    height: 130px;
  }
  .search-header{
    height: 60px;
  }
  .menu-header{
    height: 50px;
    background-color: #42b983;
  }
  .img-logo{
    float: left;
  }
</style>