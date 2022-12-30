<template>
  <div class="main">
    <p><img src="@/assets/images/1_23.jpg"></p>
    <div class="footer">
        <p class="foots">&copy;2019版权所有</p>
        <p>电脑版&nbsp;|&nbsp;本站使用&nbsp;&nbsp;凡科建站&nbsp;搭建</p>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
    .main {
        width: 483px;
        margin: 0px auto;
        border-top: 5px solid #F8F8F8;
    }
    .main p {
        margin: 0px;
        line-height: 32px;
        text-align: center;
    }
    .main p img {
        width: 483px;
    }
    .main .footer {
        background-color: #F5F5F5;
        height: 102px;
    }
    .main .footer .foots {
        padding-top: 16px;
    }
    .main .footer p {
        color: #C0BFC4;
        font-size: 14px;
    }
</style>