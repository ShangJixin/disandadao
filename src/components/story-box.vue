<template>
    <div class="story-box">
        <div class="container">
            <h2 class="title">这里，是我们的故事</h2>
            <div class="subtitle">Our Story, Why Us</div>
            <p class="text">第三大道公益服建立于 2013 年 7 月 29 日，到现在已经有 {{ passbyYear }} 年多的历史。从 1.5.2 版本到现在，一直保持公益模式，并且今后会继续坚持下去，只为提供高质量的纯净 Minecraft 游戏平台。</p>
            <p class="text">我们仅支持无偿捐助，本着精益求精的原则，资金全用于服务器维护，捐助者可以在服务器便捷菜单上留名纪念，不会给予权限，物品等实质性奖励。游戏内玩家人人平等，劳动创造财富，让你享受公平的 Minecraft 游戏</p>

            <div class="zhoumu">
                <div class="zhoumu-tag">一周目<span class="date">2013-07-29</span></div>
                <div class="zhoumu-tag">二周目<span class="date">2013</span></div>
                <div class="zhoumu-tag">三周目<span class="date">2013</span></div>
                <div class="zhoumu-tag">创造服<span class="date">2014</span></div>
                <div class="zhoumu-tag">四周目<span class="date">2014-06</span></div>
                <div class="zhoumu-tag">五周目<span class="date">2015-02-19</span></div>
                <div class="zhoumu-tag">六周目<span class="date">2016-05-20</span></div>
                <div class="zhoumu-tag">势力战争分服<span class="date">2017-07-25</span></div>
                <div class="zhoumu-tag">七周目<span class="date">2018-07-13</span></div>
                <div class="zhoumu-tag">重启 · 势力战争分服<span class="date">Coming s∞n</span></div>
                <div class="zhoumu-tag">八周目<span class="date">征集点子中...</span></div>
            </div>
            <div class="img-row">
                <img src="../assets/zuchuan.jpg" />
                <img src="../assets/wuzhoumumax.jpg" />
            </div>
            <div class="passby">
                <div class="before">2013</div>
                <div class="cha">距 {{ passbyDay }} 天</div>
                <div class="now">{{ nowYear }}</div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            created: 1375056000000
        }
    },
    computed: {
        nowYear() {
            let date = new Date()
            return date.getFullYear()
        },
        passbyYear() {
            let now = new Date()
            //console.log(now.valueOf())
            return parseInt((now.valueOf() - this.created) / 86400 / 365 / 1000)
        },
        passbyDay() {
            let now = new Date()
            //console.log(now.valueOf())
            return parseInt((now.valueOf() - this.created) / 86400 / 1000)
        }
    }
}
</script>

<style lang="less" scoped>
.story-box {
    background: #F6F6F6;
}
.zhoumu .zhoumu-tag {
    margin: 5px 0;
    padding: 15px;
    background: #637599;
    color: #fff;
    font-size: 15px;
    border-radius: 3px;
    text-transform: uppercase;
}
.zhoumu .zhoumu-tag span.date {
    float: right;
    text-transform: lowercase;
}
.passby {
    text-align: center;
    margin: 40px 0;
    color: #333;
}
.passby .before,
.passby .cha,
.passby .now {
    display: inline-block;
}
.passby .before,
.passby .now {
    font-size: 35px;
}
.passby .cha {
    font-size: 16px;
    border: 2px solid #637599;
    color: #637599;
    padding: 3px 5px;
    vertical-align: super;
    margin: 0 10px;
}

.story-box .img-row img{
    display: inline-block;
    width: 50%;
    box-sizing: border-box;
    padding: 5px;
    border-radius: 10px;
}
.story-box .img-row {
    letter-spacing: 0;
    font-size: 0;
    width: 80%;
    margin-left: auto;
    margin-right: auto;
    margin-top: 40px;
}
</style>