<script setup>



</script>
<template>
    <div class="main">
        <div class="main1">
        <div class="left">
            <div class="title">
                <span class="readMore"><a href="https://www.hnust.edu.cn/sylm/xshd/index.htm" target="_blank">MORE</a></span>
                <h2>
                    <a href="https://www.hnust.edu.cn/sylm/xshd/index.htm" target="_blank">学术动态</a>
                </h2>
            </div>
            <a class="toulan" href="https://www.hnust.edu.cn/sylm/xshd/9b5cadeb03ae4f54889240b152731a59.htm"><img  src="../../../assets/上面.png" alt=""></a>
            <a class="toulan" href="https://www.hnust.edu.cn/sylm/xshd/9b5cadeb03ae4f54889240b152731a59.htm"><img  src="../../../assets/下面.png" alt=""></a>
        </div>   
        <div class="right">
            <div class="title">
                <span class="readMore"><a href="https://news.hnust.edu.cn/xscg/index.htm" target="_blank">MORE</a></span>
                <h2>
                     <a href="https://news.hnust.edu.cn/xscg/index.htm" target="_blank">学术讲座</a>
                </h2>
        </div>
        <a href="https://news.hnust.edu.cn/kdyw/436899f5c80c431389e3b90967c19187.htm" class="index_042"><div class="img"><img src="https://news.hnust.edu.cn/images/2023-10/45a8c76e1485451292ab01a335c76891.png"></div></a>
        <div class="index_043 ul-inline">
						<ul class="xscgli">
						<li><a href="https://news.hnust.edu.cn/kdyw/436899f5c80c431389e3b90967c19187.htm"><div class="time"><div class="day fs22">12</div><div class="month fs12">2023.10</div></div><div class="title fs16">我校研究生刘锐在工程技术领域TOP期刊发表研究成果</div></a></li><li><a href="https://news.hnust.edu.cn/kdyw/72db6b25c5314838ac4c5d5107d98553.htm"><div class="time"><div class="day fs22">07</div><div class="month fs12">2023.10</div></div><div class="title fs16">易清风教授课题组在用于ORR/OER的高效稳定非贵金属氧电催化剂上取得重要进展</div></a></li></ul>
					</div>
    </div>
</div>
</div>
</template>

<style scoped>
.toulan img{
    height: 200px;
    width: 750px;
    margin-bottom: 35px;
}
.main{
    background: url("https://www.hnust.edu.cn/images/mode04_bg.png") center no-repeat;
    background-size: cover;
    height: 550px;
    font-size: 14px;
}
.main1{
    width: 1100px;
    margin: 0px auto;
    padding: 30px 0;

}
.right {
    width: 40.3%;
    float: right;
}
.left{
    width:600px;
    float: left;
}
.title{
    border-bottom: 1px solid #eee;
}

.title h2 a{
    color: #003b90;
    padding-left: 10px;
    border-left: 4px solid #003b90;
    height: 20px;
    line-height: 20px;
    font-size: 18px;
}
.readMore{
    height: 20px;
    float: right;
    font-size: 12px;
    font-weight: bold;
    line-height: 65px;
}
.readMore a{
    color: #999;
}
.index_042 .img::before {
    content: '';
    display: block;
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
    padding-bottom: 21.25%;
    background: -webkit-linear-gradient(top, rgba(0, 0, 0, 0), rgba(0, 0, 0, .8));
    background: -o-linear-gradient(bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, .8));
    background: -moz-linear-gradient(bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, .8));
    background: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, .8));
}
.index_042 .img {
    padding-bottom: 56.25%;
    position: relative;
}
.img img:hover {
    transform: scale(1.05);
    -ms-transform: scale(1.05);
    -moz-transform: scale(1.05);
    -webkit-transform: scale(1.05);
    -o-transform: scale(1.05);
}
.img img {
    width: 100%;
    display: block;
    transition: all ease-in 0.2s;
    -ms-transition: all ease-in 0.2s;
    -moz-transition: all ease-in 0.2s;
    -webkit-transition: all ease-in 0.2s;
    -o-transition: all ease-in 0.2s;
}
img, object {
    width: 100%;
    max-width: 100%;
    /* height: auto; */
    width: auto\9;
    -ms-interpolation-mode: bicubic;
}
.img {
    display: block;
    overflow: hidden;
    width: 100%;
    height: 0;
    background: #d6d6d6;
}
.index_042 {
    position: relative;
    display: block;
    padding: 10px 20px 24px;
    background: #2678eb;
}
.index_043 {
    background: #2678eb;
}
.index_043 ul {
    margin: 0 0 0 0;
    padding: 0 20px;
}
.index_043 li {
    width: 100%;
}
.ul-inline li {
    display: inline-block;
    font-size: 14px;
    vertical-align: top;
}
.ul-inline li a {
    display: block;
}
.index_043 a {
    margin: 0 0 24px;
    overflow: hidden;
}
.index_043 .time {
    float: left;
    width: 56px;
    height: 56px;
    background: #fff;
    border: 5px solid #efeef4;
    text-align: center;
}
.index_043 .title {
    margin: 0 0 0 85px;
    padding: 6px 0 0;
    height: 48px;
    line-height: 24px;
    color: #fff;
    font-size:15px;
    border: 0;
}

.index_043 .month {
    color: #757575;
    margin: 0 0 0 0;
    line-height: 20px;
    opacity: .7;
}
.fs12 {
    font-size: 12px;
}
.title {
    display: block;
    overflow: hidden;
    text-overflow: ellipsis;
}
.index_043 .day {
    color: #003c88;
    margin: 9px 0 0 0;
    line-height: 20px;
    font-weight: bold;
}
.fs22 {
    font-size: 22px;
}
</style>
