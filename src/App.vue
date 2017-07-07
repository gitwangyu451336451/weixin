<template>
  <div id="app">
    <router-view></router-view>
    <div class="menus">
        <router-link to="/home">
            <span class="home_img"></span>
            <span>首页</span>
        </router-link>
        <router-link to="/my">
            <span class="my_img"></span>
            <span>我的</span>
        </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-bottom: 3em ;
}
.menus{
  font-size: 12px;
  bottom:0;
  position: fixed;
  height: 4em;
  width: 100%;
  background: white;
  border-top: 1px solid #f2f2f2;
  color: #666666;
}
.menus a{
  display:block;
  text-decoration: none;
  width:calc(50% - 1px);
  margin-left:1px;
  float:left;
  padding-top:.5em; 
  color:#999999;
}
.menus a span{
  display: block;
  width:2em;
  height: 2em;
  line-height: 1.5em;
  margin: auto;
}
.menus a span.home_img{
  width:2em;
  height: 2em;
  display: block;
}
a:active{  
  background-color: #f2f2f2;
}
a.active{
  color:#008fff;
}
.home_img{
  background: url('assets/home_img.png');
  background-size: 1.8em; 
  background-repeat:no-repeat;
  background-position:center;
}
.my_img{
  background: url('assets/my_img.png');
  background-size: 1.6em; 
  background-repeat:no-repeat;
  background-position:center;
}
.active .my_img{
  background: url('assets/my_img_active.png');
  background-size: 1.6em; 
  background-repeat:no-repeat;
  background-position:center;
}
</style>
