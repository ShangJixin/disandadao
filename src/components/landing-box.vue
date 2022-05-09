<template>
    <div class="landing-box">
        <div class="container cover">
            <div class="landing">
                <h1>时光荏苒，初心未改</h1>
                <p>第三大道公益服 公益 认真 负责</p>
            </div>
        </div>
        <div class="container foobar">
            <div class="guide">向下翻动，查看更多&nbsp;&darr;</div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.landing-box .container.cover {
    height: 80vh;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.landing-box .container.foobar {
    height: 20vh;
    line-height: 20vh;
}
.landing-box {
    background: url(../assets/landing.jpg) center bottom no-repeat;
    background-size: cover;
}

.landing-box .landing h1 {
    font-size: 32px;
    margin: 20px 0;
}
.landing-box .landing p {
    font-size: 16px;
    margin: 20px 0;
}

.landing-box .guide {
    font-size: 16px;
    color: #999;
    user-select: none;
}

@media screen and (max-width: 500px) {
    /* 手机端展示 限高，不能用100vh，不美观 */
    /* 约定 60vh */
    .landing-box .container.cover {
        height: 60vh;
    }
    .landing-box .container.foobar {
        /*
        height: 20vh;
        line-height: 20vh;
        */
        display: none;
    }
    .landing-box .container.cover {
        justify-content: center;
        text-align: center;
    }
    .landing-box {
        background-size: contain;
    }
}
/*
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
*/
</style>