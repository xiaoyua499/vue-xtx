<template>
  <div class="footer">
    <div class="box">
      <ul>
        <li>
          <div>客户服务</div>
          <h5>
            <div><span></span>在线客服</div>
            <div><span></span>问题反馈</div>
          </h5>
        </li>
        <li>
          <div>客户服务</div>
          <h5>
            <div><span></span>在线客服</div>
            <div><span></span>问题反馈</div>
          </h5>
        </li>
        <li>
          <div>客户服务</div>
          <h5>
            <div><span></span>在线客服</div>
            <div><span></span>问题反馈</div>
          </h5>
        </li>
        <li>
          <div>客户服务</div>
          <h5>
            <div><span></span>在线客服</div>
            <div><span></span>问题反馈</div>
          </h5>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name:'XtxFooter'
};
</script>

<style scoped>
/* 底部 */
.footer {
  height: 300px;
  /* background-color: pink; */
}

.footer ul {
  display: flex;
  justify-content: space-around;
  align-items: center;
  margin-top: 79px;
}

.footer ul li {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.footer ul li h5 {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 35px;
}

.footer ul li h5 div:nth-child(1) {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  width: 93px;
  height: 93px;
  background-color: #fff;
  border: solid 1px #eeeeee;
}

.footer ul li h5 div:nth-child(1) span {
  display: block;
  width: 30px;
  height: 30px;
  /* background-color: skyblue; */
  background-image: url(../assets/images/sprites.png);
  background-position: -250px -70px;
}

.footer ul li h5 div:nth-child(2) {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  width: 93px;
  height: 93px;
  background-color: #fff;
  border: solid 1px #eeeeee;
}

.footer ul li h5 div:nth-child(2) span {
  display: block;
  width: 30px;
  height: 30px;
  /* background-color: skyblue; */
  background-image: url(../assets/images/sprites.png);
  background-position: -350px -70px;
}
</style>