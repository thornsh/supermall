<template>
  <div class="tab-bar-item" @click="itemClick">
    <slot name="item-icon"></slot>
    <slot name="item-text"></slot>
  </div>
</template>

<script>
  export default{
    name:"TabBaritem",
    props:{
      path:String
    },
    methods:{
      itemClick(){
        console.log('ceshi')
        this.$router.replace(this.path)
      }
    }
  }
</script>

<style>
  #tab-bar{
    display: flex;
    background-color: #f6f6f6;

    position: fixed;
    left: 0px;
    right: 0px;
    bottom: 0;

    box-shadow: 0 -1px 1px rgba(100,100,100,.2);
  }
  .tab-bar-item{
    flex: 1;
    text-align: center;
    height: 49px;
  }
  .tab-bar-item img{
    width: 24px;
    height: 24px;
  }
</style>
