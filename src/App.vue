<template>
  <div>
    <!-- 头部 -->
    <XtxTitle />

    <!-- 导航 -->
    <XtxNav />

    <!-- 轮播图 -->
    <XtxBanner />

    <!-- 新鲜好物 -->
    <XtxArticle />

    <!-- 底部 -->
    <XtxFooter />

    <!-- 版权部分 -->
    <XtxDrm />
  </div>
</template>

<script>
import XtxTitle from "./components/XtxTitle.vue";
import XtxNav from "./components/XtxNav.vue";
import XtxBanner from "./components/XtxBanner.vue";
import XtxArticle from "./components/XtxArticle.vue";
import XtxFooter from "./components/XtxFooter.vue";
import XtxDrm from "./components/XtxDrm.vue";
export default {
  name: "App",
  components: { XtxTitle, XtxNav, XtxBanner, XtxArticle, XtxFooter, XtxDrm },
};
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

.box {
  width: 1240px;
  margin: 0 auto;
}
</style>
