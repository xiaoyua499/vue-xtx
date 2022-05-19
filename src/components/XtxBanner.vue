<template>
  <div class="banner">
    <div class="box">
      <img src="../assets/uploads/banner_1.png" alt="" />
      <h2>
        <ul>
          <li>
            <a href="javascript:;" v-for="freshObj in fresh" :key="freshObj.id"
              >{{ freshObj.sort}}<span>{{freshObj.datails}}</span>></a>
          </li>
          
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
</template>

<script>
export default {
  name: "XtxBanner",
  data() {
    return {
      fresh:[
        {id:'001',sort:'生鲜',datails:'水果 蔬菜'},
        {id:'002',sort:'美食',datails:'面点 干果'},
        {id:'003',sort:'餐厨',datails:'数码产品'},
        {id:'004',sort:'电器',datails:'床品 四件套'},
        {id:'005',sort:'居家',datails:'奶粉 玩具'},
        {id:'006',sort:'洗护',datails:'洗发 洗护'},
        {id:'007',sort:'孕婴',datails:'奶粉 玩具'},
        {id:'008',sort:'服饰',datails:'女装 男装'},
        {id:'009',sort:'杂货',datails:'户外 图书'},
        {id:'010',sort:'品牌',datails:'品牌制造'},
      ],
    };
  },
};
</script>

<style scoped>
/* 轮播图 */
.banner {
  position: relative;
  height: 500px;
  background-color: #f5f5f5;
}

.banner .box {
  position: relative;
}

.banner h2 {
  position: absolute;
  top: 0;
  left: 0;
  width: 251px;
  height: 500px;
  background-color: #000;
  opacity: 0.8;
}

.banner h2 a:hover {
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
  background-image: url(../assets/images/sprites.png);
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
  background-image: url(../assets/images/sprites.png);
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

.banner .point .round {
  background-color: #fff;
  opacity: 1;
}
</style>