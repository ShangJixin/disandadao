<template>
    <div class="landing-box">
        <div class="container">
            <div class="landing">
                <h1>时光荏苒，初心未改</h1>
                <p>第三大道公益服 公益 认真 负责</p>
            </div>
            <div class="guide">向下翻动，查看更多&nbsp;&darr;</div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.landing-box {
    user-select: none;
    height: 100vh;
    background: #f8f8f8;
    background: url(../assets/landing.jpg) center;
    background-size: cover;
}

.landing-box .nav {
    height: 50px;
    line-height: 50px;
    letter-spacing: 1px;
}

.landing-box .nav img {
    height: 100%;
}
.landing-box .nav .drop-nav {
    display: inline-block;
    vertical-align: top;
    float: right;
    position: relative;
}
.landing-box .nav .drop-nav svg.icon {
    vertical-align: text-top;
    cursor: pointer;
}
.landing-box .nav .drop-nav .drop-list {
    position: absolute;
    background: #fff;
    border: 1px solid #cdcdcd;
    border-radius: 3px;
    width: 80px;
    right: 0;
    padding: 10px 0;
    display: none;
}
.landing-box .nav .drop-nav:hover .drop-list {
    display: block;
}
.landing-box .nav .drop-nav .drop-list a {
    display: block;
    text-align: center;
    font-size: 14px;
    line-height: 35px;
}
.landing-box .nav .drop-nav .drop-list a:hover {
    background: #fafafa;
}
.landing-box .nav a {
    color: #637599;
    text-decoration: none;
    font-weight: 500;
    font-size: 16px;
}

.landing-box .landing {
    margin-top: 30vh;
}
.landing-box .landing h1 {
    font-size: 30px;
    margin: 20px 0;
    color: #333;
    font-weight: 500;
    letter-spacing: 2px;
    text-transform: uppercase;
    max-width: 80%;
}

.landing-box .landing p {
    color: #666;
    font-size: 16px;
    font-weight: 500;
    letter-spacing: 2px;
    text-transform: capitalize;
}

.guide {
    position: absolute;
    bottom: 0;
    margin: 30px 0;
    font-size: 14px;
    color: #999;
    text-transform: capitalize;
}
</style>