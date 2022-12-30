<template>
  <div class="main">
    <div class="ps">
        <div></div>
        <div></div>
        <div></div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
  .main {
    text-align: -webkit-center;
  }
  .main .ps {
    width: 483px;
    text-align: center;
    display: flex;
    justify-content: space-around;
    margin: 6px 0px;
  }
  .main .ps div:nth-of-type(1) {
    width: 52px;
    height: 41px;
    background: url(@/assets/images/11.png) no-repeat;
  }
  .main .ps div:nth-of-type(2) {
    width: 52px;
    height: 41px;
    background: url(@/assets/images/44.jpg) no-repeat;
  }
  .main .ps div:nth-of-type(3) {
    width: 52px;
    height: 41px;
    background: url(@/assets/images/3.png) no-repeat;
  }
</style>