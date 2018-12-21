<template>
  <div>
    <ul class="menu-container">
      <li class="menu-item" @click="showItemContent">
        <span class="icon-lock" v-if="item.locked"></span>
        <span class="item-title">{{item.title}}</span>
        <span class="list-count">{{item.count}}</span>
      </li>
    </ul>
    <div class="add-item">
      <span class="icon-ios-add-circle-outli"></span>
      <span>新增</span>
    </div>
  </div>
</template>
<script>
  export default{
    data(){
      return{
        item:{
          title:"helloworld",
          locked:true,
          count:10
        }
      }
    },
    methods:{
      showItemContent(){
        this.$router.push()
      }
    }
  }
</script>
<style lang="less">
  @import "../common/style/menu.less";
</style>
