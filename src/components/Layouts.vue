<template>
  <div class="container">
    <section class="menu">
      <MenuBar></MenuBar>
    </section>
    <section class="content-container">

    </section>
  </div>
</template>
<script>
  import MenuBar from "./Menu"
  export default{
    components:{
      MenuBar
    }
  }
</script>
<style lang="less">
  @import '../common/style/layout.less';
</style>
