<script setup>
const list = [
    ["https://www.hnust.edu.cn/images/2023-04/0a014a4ccd2141a0b1bc261a69db80a1.png",
    "https://www.hnust.edu.cn/images/2023-03/62bf3c753f30451eab59cbfaa74998cf.png",
    "https://www.hnust.edu.cn/images/2022-10/125ff644010a4dd4904006b81a21fe2c.jpg",
    "https://www.hnust.edu.cn/images/2022-10/ef2fb7fcfa8f495193a3007469a5bfcc.jpg",
    "https://www.hnust.edu.cn/images/2022-04/33456aea988845fa9e2b0ae5079037b7.jpg",],
    [ "https://www.hnust.edu.cn/images/2021-05/01b35b276370472caa1dfaec0d9576e9.jpg",
    "https://www.hnust.edu.cn/images/2022-03/8a794f3d68164e4bb577fc562685ad7f.jpg",
    "https://www.hnust.edu.cn/images/2019-05/9e88ccee989046b3b3f10fe3ade1789a.png",
    "https://www.hnust.edu.cn/images/2021-11/4dea644b6f3e4c88a23e279becc9eb68.jpg",
    "https://www.hnust.edu.cn/images/2019-05/fff509676787492e91eebf70c935f46f.png"]
  
]




</script>
<template>
    <div class="main">
        <el-carousel :interval="4000" arrow="always" height="120px">
            <el-carousel-item v-for="item in list " :key="item.id"  >
                <img :src="item[0]" >
                <img :src="item[1]" >
                <img :src="item[2]" >
                <img :src="item[3]" >
                <img :src="item[4]" >
            </el-carousel-item>
        </el-carousel>
    </div>
</template>

<style scoped>
.main{
    position: relative;
    background-color: rgb(255, 255, 255);
    height: 120px;
    width: 1100px;
    margin: 0 auto;
}
img{
  height: 105px;
  width: 195px;
  margin: 0 12px;
}
.el-carousel__item:nth-child(2n) {
  background-color: #ffffff00;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #ffffff00;
}
.el-carousel__indicators el-carousel__indicators--horizontal{
    height: 120px;
}
.el-carousel__container{
  height:200px !important;
}
</style>
<style>
.el-carousel__arrow {
top: 45%;
right: 20px;
background-color: rgb(31 45 61 / 66%);
}

</style>