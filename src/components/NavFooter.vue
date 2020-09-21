<template>
  <div>
    <div class="footer">
      <div class="footer-logo">
        <img src="/imgs/logo-footer.png" alt />
        <p>小米商城</p>
      </div>

      <div class="footer-link">
        <a href="javascript:;">河畔一角主页</a>
        <span>|</span>
        <a href="javascript:;">Vue全栈课程</a>
        <span>|</span>
        <a href="javascript:;">React全家桶课程</a>
        <span>|</span>
        <a href="javascript:;">微信支付专项课程</a>
        <span>|</span>
        <a href="javascript:;">配套课程：Java通用型支付+电商平台双系统实战</a>
      </div>
      <div class="copyright">
        Copyright ©2020
        <span class="domain">mi.futurefe.com</span> All Rights Reserved.
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "nav-footer"
};
</script>
<style lang="scss">
@import "./../assets/scss/config.scss";
.footer {
  height: 234px;
  border-top: 4px solid $colorA;
  background-color: #333;
  color: #999;
  font-size: 16px;
  text-align: center;
  .footer-logo {
    margin-top: 46px;
    margin-bottom: 31px;
    .img {
      width: 53px;
      height: 36px;
      margin-bottom: 13px;
    }
  }
  .footer-link {
      margin-bottom: 10px;
    a {
      color: #999;
      display: inline-block;
    }
    span {
      margin: 0 10px;
    }
  }
  .copyright {

    .domain {
      color: $colorA;
    }
  }
}
</style>