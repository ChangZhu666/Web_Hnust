<script setup>
import HomeHeader from "./components/HomeHeader.vue"
import HomeClearFix from "./components/HomeClearFix.vue"
const list = [
  "https://www.hnust.edu.cn/images/2023-09/gp_th_11dbedee63b9498bb6327f804452543b.jpg",
  "https://www.hnust.edu.cn/images/2023-07/9c8a40be5a3b4ed5b1362c5e048cffdd.jpg",
  "https://www.hnust.edu.cn/images/2023-05/004361d985dd4a0b83128fb8a02aaad4.png",
  "https://www.hnust.edu.cn/images/2023-04/31efc76eaf1b4e53b89f421f6358de27.jpg",
  "https://www.hnust.edu.cn/images/2023-04/e1e3fc66832342238894e9a7d91f467b.jpg"
]
</script>

<template>
  <el-carousel :interval="3000" arrow="always" height="750px">
    <el-carousel-item v-for="item in list" :key="item">
     <img :src="item" alt="" class="img">
    </el-carousel-item>
  </el-carousel>
  <HomeHeader class="HomeHeader"></HomeHeader>
  <HomeClearFix class="HomeClearFix"></HomeClearFix>
</template>

<style >
.carousel { 
  position: relative; 
}
.HomeHeader{
  position: absolute; 
  top: 0; 
  left: 0; 
  background-color: rgba(0, 0, 0, 0); 
  padding: 10px; 
  color: #ffffff; 
}
.HomeClearFix{
  position: absolute;
  top:70px;
  left: 50%;
  margin-left:-605px ;
  
}
.img{
  height: 750px;
  width: 100%;
}

.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #d3dce6;
}

</style>

