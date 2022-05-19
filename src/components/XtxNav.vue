<template>
  <div class="nav box">
    <div class="logo">
      <img src="../assets/logo.png" alt="" />
    </div>
    <div class="sort">
      <ul>
        <li>
          <a href="#" v-for="sort in sort" :key="sort.index">{{ sort }}</a>
        </li>
      </ul>
    </div>
    <div class="search">
      <input type="text" placeholder="搜一搜" />
      <span></span>
      <div class="car">
        <!-- <span class="red">2</span> -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "XtxNav",
  data() {
    return {
      sort: [
        "首页",
        "生鲜",
        "美食",
        "餐厨",
        "电器",
        "居家",
        "洗护",
        "孕婴",
        "服装",
      ],
    };
  },
};
</script>

<style scoped>
/* 导航 */
.nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 130px;
  /* background-color: pink; */
}

.nav .logo img {
  width: 207px;
  height: 70px;
}

.nav .sort li {
  float: left;
}

.nav .sort li a {
  margin-right: 48px;
}

.nav .sort li a:hover {
  padding-bottom: 8px;
  color: #27ba9b;
  border-bottom: 1px solid #27ba9b;
}

.nav .search {
  position: relative;
  width: 222px;
  height: 33px;
}

.nav .search input {
  padding-left: 30px;
  width: 172px;
  height: 30px;
  border-bottom: 2px solid #e7e7e7;
}

.nav .search span {
  position: absolute;
  top: 5px;
  left: 2px;
  background-image: url(../assets/images/sprites.png);
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
  background-image: url(../assets/images/sprites.png);
  background-position: -120px -69px;
}

.red {
  position: absolute;
  top: 20px;
  left: 0px;
  background-color: red;
}
</style>