<template>
  <div class="article">
    <div class="box">
      <h3 class="clearfix">
        <ul>
          <li>
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
            <img src="../assets/uploads/new_goods_1.jpg" alt="" />
            <h4>
              睿米无线吸尘器F8
              <div><span>￥</span>899</div>
            </h4>
          </li>
          <li>
            <img src="../assets/uploads/new_goods_1.jpg" alt="" />
            <h4>
              睿米无线吸尘器F8
              <div><span>￥</span>899</div>
            </h4>
          </li>
          <li>
            <img src="../assets/uploads/new_goods_1.jpg" alt="" />
            <h4>
              睿米无线吸尘器F8
              <div><span>￥</span>899</div>
            </h4>
          </li>
          <li>
            <img src="../assets/uploads/new_goods_1.jpg" alt="" />
            <h4>
              睿米无线吸尘器F8
              <div><span>￥</span>899</div>
            </h4>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name:'XtxArticle'
};
</script>

<style scoped>
/* 新鲜好物 */
.article {
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
.article h3 li span:nth-child(1) {
  padding-right: 863px;
  padding-left: 34px;
}

.article h3 li span:nth-child(2) {
  padding-right: 13px;
}

.nominate ul li {
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