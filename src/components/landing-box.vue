<template>
    <div class="landing-box">
        <div class="container cover">
            <div class="landing">
                <h1>时光荏苒，初心未改</h1>
                <p>第三大道公益服 公益 认真 负责</p>
            </div>
        </div>
        <div class="container foobar">
            <a class="next" href="https://bbs.disandadao.org/" title="三道社区"><span>三道社区&nbsp;</span>&raquo;</a>
            <a class="guide" href="https://bbs.disandadao.org/thread-86-1-1.html">战服、8周目、三道的未来，来提意见吧</a>
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
    display: flex;
    justify-content: space-between;
    align-items: center;
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

.landing-box .next {
    font-size: 16px;
    height: 30px;
    width: 30px;
    text-align: center;
    line-height: 30px;
    box-sizing: content-box;
    border: 2px solid #9AA8C5;
    color: #9AA8C5;
    font-weight: 600;
    text-decoration: none;
    transition: all 0.3s;
}
.landing-box .next span {
    display: none;
    font-weight: 500;
    font-size: 14px;
}
.landing-box .next:hover {
    width: auto;
    padding: 0 10px;
    transition: all 0.3s;
}
.landing-box .next:hover span {
    display: inline-block;
}
.landing-box .guide {
    font-size: 14px;
    color: #9AA8C5;
    /* 兼容性保底 */
    background: #fff;
    background: #ffffffdd;
    padding: 6px 10px;
    text-decoration: none;
}

@media screen and (max-width: 500px) {
    /* 手机端展示 限高，不能用100vh，不美观 */
    /* 约定 70vh */
    .landing-box .container.cover {
        height: 50vh;
    }
    .landing-box .container.foobar {
        justify-content: center;
    }
    .landing-box .next {
        display: none;
    }
    .landing-box .container.cover {
        justify-content: center;
        text-align: center;
    }

    .landing-box {
        background-size: contain;
        border-bottom: 3px solid #eee;
    }
}

</style>