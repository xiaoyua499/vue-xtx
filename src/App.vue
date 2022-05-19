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

    <!-- 轮播图 -->
    <div class="banner">
      <div class="box">
        <img src="./assets/uploads/banner_1.png" alt="">
        <h2>
          <ul>
            <li><a href="javascript:;">生鲜<span>水果 蔬菜</span>></a></li>
            <li><a href="javascript:;">生鲜<span>水果 蔬菜</span>></a></li>
            <li><a href="javascript:;">生鲜<span>水果 蔬菜</span>></a></li>
            <li><a href="javascript:;">生鲜<span>水果 蔬菜</span>></a></li>
            <li><a href="javascript:;">生鲜<span>水果 蔬菜</span>></a></li>
            <li><a href="javascript:;">生鲜<span>水果 蔬菜</span>></a></li>
            <li><a href="javascript:;">生鲜<span>水果 蔬菜</span>></a></li>
            <li><a href="javascript:;">生鲜<span>水果 蔬菜</span>></a></li>
            <li><a href="javascript:;">生鲜<span>水果 蔬菜</span>></a></li>
            <li><a href="javascript:;">生鲜<span>水果 蔬菜</span>></a></li>
          </ul>
        </h2>
        <div>
          <span class="forward"></span>
          <span class="back"></span>
        </div>
        <div class="point">
          <ul>
            <li></li>
            <li></li>
            <li class="round"></li>
            <li></li>
            <li></li>
          </ul>
        </div>
      </div>
    </div>

    <!-- 新鲜好物 -->
    <div class="article">
      <div class="box">
        <h3 class="clearfix">
          <ul>
            <li >
              新鲜好物
              <span>新鲜出炉 品质靠谱</span>
              <span>查看全部</span>
              <span>></span>
            </li>
          </ul>
        </h3>
        <div class="nominate">
          <ul>
            <li>
              <img src="./assets/uploads/new_goods_1.jpg" alt="">
              <h4>睿米无线吸尘器F8 <div><span>￥</span>899</div></h4>
            </li>
            <li>
              <img src="./assets/uploads/new_goods_1.jpg" alt="">
              <h4>睿米无线吸尘器F8 <div><span>￥</span>899</div></h4>
            </li>
            <li>
              <img src="./assets/uploads/new_goods_1.jpg" alt="">
              <h4>睿米无线吸尘器F8 <div><span>￥</span>899</div></h4>
            </li>
            <li>
              <img src="./assets/uploads/new_goods_1.jpg" alt="">
              <h4>睿米无线吸尘器F8 <div><span>￥</span>899</div></h4>
            </li>
          </ul>
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
  background-color: red;
}

/* 轮播图 */
.banner{
  position: relative;
  height: 500px;
  background-color: #f5f5f5;
}

.banner .box {
  position: relative;
}

.banner h2{
  position: absolute;
  top: 0;
  left: 0;
  width: 251px;
  height: 500px;
  background-color: #000;
  opacity: 0.8;
}

.banner h2 li:hover {
  background-color: #27ba9b;
}

.banner h2 a {
  display: block;
  padding-left: 36px;
  height: 50px;
  color: #fff;
  font-size: 16px;
  line-height: 50px;
}

.banner h2 a span {
  padding-left: 15px;
  padding-right: 82px;
  font-size: 14px;
}

.banner .forward {
  position: absolute;
  top: 228px;
  left: 260px;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  background-color: #000;
  opacity: 0.2;
  background-image: url(./assets/images/sprites.png);
  background-position: 15px -59px;
}

.banner .back {
  position: absolute;
  top: 228px;
  left: 1160px;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  background-color: #000;
  opacity: 0.2;
  background-image: url(./assets/images/sprites.png);
  background-position: -23px -59px;
}

.banner .point {
  position: absolute;
  top: 459px;
  left: 680px;
}

.banner .point li {
  margin-left: 15px;
  float: left;
  width: 10px;
  height: 10px;
  background-color: #fff;
  opacity: 0.5;
  border-radius: 50%;
}

.banner .point .round{
  background-color: #fff;
  opacity: 1;
}

/* 新鲜好物 */
.article{
  margin: 48px 0;
  height: 471px;
  background-color: #fff;
}
.article h3 li {
  float: left;
  color: #333;
  font-size: 29px;
}

.article h3 li span {
  color: #999;
  font-size: 16px;
}
.article h3 li span:nth-child(1){
  padding-right: 863px;
  padding-left: 34px;
}

.article h3 li span:nth-child(2) {
  padding-right: 13px;
}

.nominate ul li{
  float: left;
  margin: 37px 6px 0 0;
  width: 305px;
  height: 405px;
  background-color: #f0f9f4;
}

.nominate ul li:nth-child(4) {
  margin-right: 0;
}

.nominate ul li img {
  width: 305px;
  height: 305px;
}

.nominate ul li h4 {
  padding-top: 22px;
  text-align: center;
  font-size: 20px;
  color: #333;
}

.nominate ul li h4 div {
  font-size: 23px;
  color: #9a2e1f;
}

.nominate ul li h4 div span {
  font-size: 17px;
}
</style>
