<template>
    <div class="foot-front-top">
        <div class="container">
            <div class="footer-flex-box">
                <img class="footer-img-slogan" src="../assets/slogan.gif" alt="第三大道公益服 - 公益 认真 负责">
            </div>
        </div>    
    </div>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.foot-front-top {
    height: 120px;
    background: #637599;
    /*! autoprefixer: off */
    background: -webkit-linear-gradient(left bottom,rgb(221,161,150),#637599);
    /*! autoprefixer: on */
    background: -mos-linear-gradient(left bottom,rgb(221,161,150),#637599);
    background: linear-gradient(left bottom,rgb(221,161,150),#637599);
    user-select: none;
}
.footer-flex-box {
    width: auto;
    display: flex;
    height: 120px;
    justify-content: center;
    align-items: center;
    margin: 0 20px;
}
.foot-front-top .container {
    padding: 0px!important;
}
img.footer-img-slogan {
    width: auto;
    height: auto;
    max-width: 100%;
    max-height: 100%;
}
</style>