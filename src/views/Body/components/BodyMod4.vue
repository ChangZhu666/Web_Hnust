<script setup>



</script>
<template>
    <div class="main">
        <div class="main1">
        <div class="left">
            <div class="title">
                <span class="readMore"><a href="https://www.hnust.edu.cn/sylm/xshd/index.htm" target="_blank">MORE</a></span>
                <h2>
                    <a href="https://www.hnust.edu.cn/sylm/xshd/index.htm" target="_blank">通知公告</a>
                </h2>
            </div>
            
        </div>   
        <div class="right">
            <div class="title">
                <span class="readMore"><a href="https://news.hnust.edu.cn/xscg/index.htm" target="_blank">MORE</a></span>
                <h2>
                     <a href="https://news.hnust.edu.cn/xscg/index.htm" target="_blank">服务</a>
                </h2>
        </div>
        
    </div>
</div>
</div>
</template>

<style scoped>
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
    width: 48.3%;
    float: right;
}
.left{
    width:500px;
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
    line-height: 20px;
}
.readMore a{
    color: #999;
}
</style>
