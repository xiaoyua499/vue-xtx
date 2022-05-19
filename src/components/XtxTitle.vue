<template>
  <div class="title">
    <ul class="box">
      <li>
        <a href="#" v-for="title in title" :key="title.index">{{ title }}</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "XtxTitle",
  data() {
    return {
      title: [
        "请先登录",
        "免费注册",
        "我的订单",
        "会员中心",
        "帮助中心",
        "在线客服",
        "手机版",
      ],
    };
  },
};
</script>

<style scoped>
/* 头部 */
.title {
  width: 100%;
  height: 52px;
  background-color: #333;
}

.title ul li {
  float: right;
}

.title ul li a {
  padding: 0 16px;
  border-right: 1px solid #666;
  color: #dcdcdc;
  line-height: 52px;
  font-size: 14px;
}
</style>