<script setup>

</script>

<template>
    <div class="main">
        <div class="logo">
            <img src="https://www.hnust.edu.cn/images/logo.svg" alt="">
        </div>
        
            <el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal" @select="handleSelect"  text-color="#fff" background-color="rgba(0,0,0,0)" >
                <el-sub-menu index="1">
                    <template #title><strong><a href="https://www.hnust.edu.cn/xxgk/xxjj/index.htm">学校概况</a></strong></template>
                    <el-menu-item index="1-1"><a href="https://www.hnust.edu.cn/xxgk/xxjj/index.htm">学校简介</a></el-menu-item>
                    <el-menu-item index="1-2"><a href="https://www.hnust.edu.cn/xxgk/xxbs/xh/index.htm">学校标识</a></el-menu-item>
                    <el-menu-item index="1-3"><a href="https://www.hnust.edu.cn/xxgk/xxzc/index.htm">学校章程</a></el-menu-item>
                    <el-menu-item index="1-4"><a href="https://www.hnust.edu.cn/xxgk/xrld/index.htm">现任领导</a></el-menu-item>
                    <el-menu-item index="1-5"><a href="https://www.hnust.edu.cn/xxgk/zzjg/index.htm">组织机构</a></el-menu-item>
                    <el-menu-item index="1-6"><a href="https://www.hnust.edu.cn/xxgk/xksz/index.htm">学科设置</a></el-menu-item>
                    <el-menu-item index="1-7"><a href="https://www.hnust.edu.cn/xxgk/xyfg/index.htm">学校风光</a></el-menu-item>
                </el-sub-menu>
                <el-sub-menu index="2">
                    <template #title><strong><a href="https://djgz.hnust.edu.cn/">工作领域</a></strong></template>
                    <el-menu-item index="2-1"><a href="https://djgz.hnust.edu.cn/">党建工作</a></el-menu-item>
                    <el-menu-item index="2-2"><a href="https://www.hnust.edu.cn/gzly/glfwgz/index.htm">管理服务</a></el-menu-item>
                </el-sub-menu>
                <el-sub-menu index="3">
                    <template #title><strong><a href="https://www.hnust.edu.cn/zsjy/index.htm">招生网</a></strong></template>
                    <el-menu-item index="3-1"><a href="https://zs.hnust.edu.cn/">本科生招生</a></el-menu-item>
                    <el-menu-item index="3-2"><a href="https://graduate.hnust.edu.cn/">研究生招生</a></el-menu-item>
                    <el-menu-item index="3-3"><a href="https://jxjyxy.hnust.edu.cn/">继续教育招生</a></el-menu-item>
                </el-sub-menu>
                <el-sub-menu index="4">
                    <template #title><strong><a href="https://www.hnust.edu.cn/jyw/index.htm">就业网</a></strong></template>
                    <el-menu-item index="4-1"><a href="https://jy.hnust.edu.cn/">就业服务</a></el-menu-item>
                    <el-menu-item index="4-2"><a href="http://cxcy.hnust.edu.cn/">创新创业</a></el-menu-item>
                </el-sub-menu>
                <el-sub-menu index="5">
                    <template #title><strong><a href="https://www.hnust.edu.cn/hzjl/index.html">合作交流</a></strong></template>
                    <el-menu-item index="5-1"><a href="https://dwll.hnust.edu.cn/">国际交流</a></el-menu-item>
                    <el-menu-item index="5-2"><a href="https://dwll.hnust.edu.cn/">港澳台交流</a></el-menu-item>
                    <el-menu-item index="5-3"><a href="http://xyh.hnust.edu.cn/">校友会</a></el-menu-item>
                </el-sub-menu>
                <a href="https://www.hnust.edu.cn/xysh/index.html"><strong style="padding-left:20px;padding-right: 40px; color:rgb(255, 255, 255); line-height: 60px;">校园生活</strong></a>
                <a href="https://www.hnust.edu.cn/ztwz/index.htm"><strong style="padding-left:20px;padding-right: 40px; color:rgb(255, 255, 255); line-height: 60px;">专题网站</strong></a>
            </el-menu>
        </div>
    
</template>

<style >
.logo{
    width: 260px;
    height: 60px;
    margin-right: 100px;
}
.el-menu-demo{
    width: 1000px;
    font-size: 18px ;
}
.main div{
    float: left;
}
.el-menu--horizontal>.el-sub-menu .el-sub-menu__title{
    font-size: 18px;
}

.el-menu--horizontal>.el-sub-menu .el-sub-menu__title{
    border-bottom: 0px;
}
.el-menu--horizontal.el-menu{
    border-bottom: 0px;
}
a{
    color: #ffffff;
    text-decoration: none;
}
.el-popper.is-light{
    background: #ffffff00;
    border: 1px solid #e4e7ed00;
}
.el-menu--horizontal .el-menu .el-menu-item, .el-menu--horizontal .el-menu .el-sub-menu__title {
    background-color: rgb(0 0 0 / 55%);
}
.el-menu-item:hover {
    --el-menu-hover-bg-color: rgb(0 0 0 / 43%);
}
.el-menu--popup {
    min-width: 175px;
}
.el-menu--horizontal>.el-sub-menu .el-sub-menu__title{
    padding-left: 10px;
}
</style>

