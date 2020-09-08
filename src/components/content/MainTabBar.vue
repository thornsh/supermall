<template>
	<TabBar>
	  <TabBaritem path="/home">
	    <img slot="item-icon" src="../../assets/img/tabbar/shangcheng.png" alt="">
	    <div slot="item-text">首页</div>
	  </TabBaritem>
	  <TabBaritem path="/category">
	    <img slot="item-icon" src="../../assets/img/tabbar/fenlei.png" alt="">
	    <div slot="item-text">分页</div>
	  </TabBaritem>
	  <TabBaritem path="/cart">
	    <img slot="item-icon" src="../../assets/img/tabbar/gouwuche.png" alt="">
	    <div slot="item-text">购物车</div>
	  </TabBaritem>
	  <TabBaritem path="/profile">
	    <img slot="item-icon" src="../../assets/img/tabbar/gerenzhongxin.png" alt="">
	    <div slot="item-text">我的</div>
	  </TabBaritem>
	  <!-- <div class="tab-bar-item">
	    <img src="../../assets/img/tabbar/shangcheng.png" alt="">
	    <div>首页</div>
	    </div>
	  <div class="tab-bar-item">
	    <img src="../../assets/img/tabbar/fenlei.png" alt="">
	    <div>分页</div>
	    </div>
	  <div class="tab-bar-item">
	    <img src="../../assets/img/tabbar/gouwuche.png" alt="">
	    <div>购物车</div>
	    </div>
	  <div class="tab-bar-item">
	    <img src="../../assets/img/tabbar/gerenzhongxin.png" alt="">
	    <div>我的</div>
	    </div> -->
	</TabBar>
</template>

<script>
	import TabBar from '../common/tabbar/TabBar.vue'
	import TabBaritem from '../common/tabbar/TabBaritem.vue'
	
	export default{
		name:'MainTabBar',
		components:{
			TabBar,
			TabBaritem
		}
	}
</script>

<style>
</style>
