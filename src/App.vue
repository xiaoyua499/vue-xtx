<template>
  <div>
    <!-- 头部 -->
    <div class="title">
      <ul class="box">
        <li> <a href="#">请先登录</a></li>
        <li> <a href="#">免费注册</a></li>
        <li> <a href="#">我的订单</a></li>
        <li> <a href="#">会员中心</a></li>
        <li> <a href="#">帮助中心</a></li>
        <li> <a href="#">在线客服</a></li>
        <li> <a href="#">手机版</a></li>
      </ul>
    </div>

  <!-- 导航 -->
  <div class="nav box">
    <div class="logo">
      <img src="./assets/logo.png" alt="">
    </div>
    <div class="sort">
      <ul>
        <li><a href="#">首页</a></li>
        <li><a href="#">生鲜</a></li>
        <li><a href="#">美食</a></li>
        <li><a href="#">餐厨</a></li>
        <li><a href="#">电器</a></li>
        <li><a href="#">居家</a></li>
        <li><a href="#">洗护</a></li>
        <li><a href="#">孕婴</a></li>
        <li><a href="#">服装</a></li>
      </ul>
    </div>
    <div class="search">
      <input type="text" placeholder="搜一搜">
      <span></span>
      <div class="car">
        <!-- <span class="red">2</span> -->
      </div>
    </div>
  </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
/* 清除默认样式的代码 */
/* 去除常见标签默认的 margin 和 padding */
body,
h1,
h2,
h3,
h4,
h5,
h6,
p,
ul,
ol,
li,
dl,
dt,
dd,
input {
  margin: 0;
  padding: 0;
}

/* 內减模式 */
* {
    box-sizing: border-box;
}

/* 设置网页统一的字体大小、行高、字体系列相关属性 */
body {
  font: 16px/1.5 "Helvetica Neue", Helvetica, Arial, "Microsoft Yahei",
    "Hiragino Sans GB", "Heiti SC", "WenQuanYi Micro Hei", sans-serif;
  color: #333;
}

/* 去除列表默认样式 */
ul,
ol {
  list-style: none;
}

/* 去除默认的倾斜效果 */
em,
i {
  font-style: normal;
}

/* 去除a标签默认下划线，并设置默认文字颜色 */
a {
  text-decoration: none;
  color: #333;
}

/* 设置img的垂直对齐方式为居中对齐，去除img默认下间隙 */
img {
  vertical-align: middle;
}

/* 去除input默认样式 */
input {
  border: none;
  outline: none;
  color: #333;
}

/* 左浮动 */
.fl {
  float: left;
}

/* 右浮动 */
.fr {
  float: right;
}

/* 双伪元素清除法 */
.clearfix::before,
.clearfix::after {
  content: "";
  display: table;
}
.clearfix::after {
  clear: both;
}

.box{
  width: 1240px;
  margin: 0 auto;
}

/* 头部 */
  .title {
  width: 100%;
  height: 52px;
  background-color: #333;
}

.title ul li{
  float: right;
  
}

.title ul li a{
  padding: 0 16px;
  border-right: 1px solid #666;
  color: #dcdcdc;
  line-height: 52px;
  font-size: 14px;
}

/* 导航 */
.nav{
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 130px;
  /* background-color: pink; */
}

.nav .logo img{
  width: 207px;
  height: 70px;
}

.nav .sort li {
  float: left;
  padding-right: 48px;
}

.nav .sort li a:hover {
  padding-bottom: 8px;
  color: #27ba9b;
  border-bottom: 1px solid #27ba9b;
}

.nav .search{
  position: relative;
  width: 222px;
  height: 33px;
}

.nav .search input{
  padding-left: 30px;
  width: 172px;
  height: 30px;
  border-bottom:2px solid #e7e7e7 ;
}

.nav .search span {
  position: absolute;
  top: 5px;
  left: 2px;
  background-image: url(./assets/images/sprites.png);
  background-position: -79px -69px;
  width: 19px;
  height: 19px;
  /* background-color: blue; */
}

.nav .search .car {
  position: relative;
  float: right;
  width: 24px;
  height: 24px;
  /* background-color: #fff; */
  padding-right: 15px;
  background-image: url(./assets/images/sprites.png);
  background-position: -120px -69px;
}

.red{
  position: absolute;
  top: 20px;
  left: 0px;
}
</style>
