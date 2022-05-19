<template>
  <div class="drm">
    <div class="box">
      <ul>
        <li><span></span>价格亲民</li>
        <li><span></span>价格亲民</li>
        <li><span></span>价格亲民</li>
      </ul>
      <div class="about">
        <ul>
          <li><a href="#">关于我们</a></li>
          <li><a href="#">关于我们</a></li>
          <li><a href="#">关于我们</a></li>
          <li><a href="#">关于我们</a></li>
          <li><a href="#">关于我们</a></li>
          <li><a href="#">关于我们</a></li>
          <li><a href="#">关于我们</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "XtxDrm",
};
</script>

<style scoped>
/* 版权部分 */
.drm {
  height: 345px;
  background-color: #333;
}

.drm ul {
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding-top: 60px;
  padding-bottom: 54px;
  border-bottom: 3px solid #434343;
}

.drm ul li {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 191px;
  height: 58px;
  color: #fff;
  font-size: 28px;
}

.drm ul li span {
  display: block;
  margin-right: 19px;
  width: 60px;
  height: 60px;
  background-image: url(../assets/images/sprites.png);
  background-position: 0 0;
}

.about ul {
  display: flex;
  justify-content: center;
  align-items: center;
}

.about ul li {
  display: flex;
  justify-content: center;
  align-items: center;
}

.about ul li a {
  font-size: 14px;
  color: #999;
}
</style>