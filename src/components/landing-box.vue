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

.landing-box .landing {
    margin-top: 30vh;
}
.landing-box .landing h1 {
    font-size: 30px;
    margin: 20px 0;
    color: #333;
    letter-spacing: 2px;
    text-transform: uppercase;
    max-width: 80%;
}

.landing-box .landing p {
    color: #666;
    font-size: 16px;
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