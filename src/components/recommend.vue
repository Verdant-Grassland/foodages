<template>
  <div class="main">
    <div class="ps">
        <span>—</span><h3>&nbsp;店长推荐&nbsp;</h3><span>—</span>
    </div>
    <hr>
    <ul>
        <li>
            <img src="@/assets/images/1_13.jpg" title="美式咖啡"><br>
            
            <p>
                <span>美式咖啡</span><br>
                <input type="button" value="立即预约" class="btn">
            </p>
        </li>
        <li>
            <img src="@/assets/images/1_14.jpg" title="卡布奇诺"><br>
            <p>
                <span>卡布奇诺</span><br>
                <input type="button" value="立即预约" class="btn">
            </p>
        </li>
        <li>
            <img src="@/assets/images/1_16.jpg" title="摩卡"><br>
            <p>
                <span>摩卡</span><br>
                <input type="button" value="立即预约" class="btn">
            </p>
        </li>
        <li>
            <img src="@/assets/images/1_17.jpg" title="白咖啡"><br>
            <p>
                <span>白咖啡</span><br>
                <input type="button" value="立即预约" class="btn">
            </p>
        </li>
    </ul>
    <p class="more">
        <input type="button" value="查看更多" class="btns">
    </p>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.main {
    width: 483px;
    border-bottom: 5px solid #F8F8F8;
    margin: 0px auto;
}
.ps {
    margin: 0px;
    line-height: 32px;
    text-align: center;
}
.ps span {
    color: #9B9B9B;
}
.ps h3 {
    margin: 0px;
    display: inline-block;
}
.main hr {
    width: 483px;
    margin-bottom: 2px;
}
.main ul {
    list-style: none;
    margin: 0px;
    padding-left: 0px;
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: center;
}
.main ul li p {
    margin: 0px;
    padding-left: 7px;
}
.main ul li p .btn {
    background-color: #F3302E;
    color: white;
    border-radius: 15px;
    border: 0px;
    padding: 4px 14px;
    margin: 4px 4px 4px 0px;
}
.main ul li p .btn:hover {
    background-color: white;
    color: #F3302E;
    border: 1px solid #F3302E;
}
.main .more {
    text-align: center;
    margin-bottom: 4px;
}
.main .more .btns {
    background-color: white;
    color: #F3302E;
    border-radius: 15px;
    width: 112px;
    height: 30px;
    border: 1px solid #F3302E;
}
.main .more .btns:hover {
    background-color: #F3302E;
    color: white;
}
</style>