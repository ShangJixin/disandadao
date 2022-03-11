<template>
    <div class="players-say">
        <div class="container">
            <h2 class="title">还有我们的小伙伴们</h2>
            <div class="subtitle">Players' Comments</div>
            <div class="say-container">
                <div class="players-say-cell">
                    <img src="../assets/players/bossxk.jpg" class="avatar"/>
                    <p><a href="https://www.mcbbs.net/home.php?mod=space&uid=1075907" target="_blank" rel="nofollow" class="name">boss_xk</a>非常不错的服务器 如果你刚入正没服务器玩的话 我推荐这个<br>基本上我整个初中的时间都砸进去了 为了这服存了一个暑假的钱入正 还拉了几位班里的同学 不过因为从来没正经地玩过游戏 到后期基本就不玩了 开启新周目后很快就没目标 但是更期待六周目的子服 希望有空岛</p>
                </div>
                <div class="players-say-cell">
                    <img src="https://bbs.disandadao.org/uc_server/data/avatar/000/00/01/75_avatar_middle.jpg" class="avatar"/>
                    <p><a href="https://bbs.disandadao.org/home.php?mod=space&uid=175" target="_blank" class="name">F1yVerse</a>5周目玩到现在, 蛮喜欢这个服务器的, 至今没有哪个服务器能让我玩这么久, 在三道认识了很多朋友, 也很高兴服务器重启</p>
                </div>
                <div class="players-say-cell">
                    <img src="../assets/players/a1941256657.jpg" class="avatar"/>
                    <p><a href="https://www.mcbbs.net/home.php?mod=space&uid=334478" target="_blank" rel="nofollow" class="name">a1941256657</a>以后就玩这服了，我以前的那个服，僵尸强化【普通僵尸都250血】，还得买神器，创一个箱子卖东西要100。总之各种坑。圈地坑死人。</p>
                </div>
                <div class="players-say-cell">
                    <img src="https://bbs.disandadao.org/uc_server/data/avatar/000/00/02/20_avatar_middle.jpg" class="avatar"/>
                    <p><a href="https://bbs.disandadao.org/home.php?mod=space&uid=220" target="_blank" class="name">xiaofan7520</a>这是一个能找到归属的地方，唯有共同建设和维护才能使其越办越好。</p>
                </div>
                <div class="players-say-cell">
                    <img src="../assets/players/soer69bb.jpg" class="avatar"/>
                    <p><a href="" target="_blank" class="name">soer69bb</a>快点开服 我们等了好几年了 千言万语都不及这一句话能表面我对三道的怀念 三道简直就是我的童年 我最快乐的暑假是在三道度过的</p>
                </div>
                <div class="players-say-cell">
                    <img src="../assets/players/1575612126.jpg" class="avatar"/>
                    <p><a href="https://www.mcbbs.net/home.php?mod=space&uid=310309" target="_blank" rel="nofollow" class="name">1575612126</a>顶一下，在盗版也就是几周目的时候就非常好了</p>
                </div>
                <div class="players-say-cell">
                    <img src="../assets/players/MC635096016.jpg" class="avatar"/>
                    <p><a href="https://www.mcbbs.net/home.php?mod=space&uid=590346" target="_blank" rel="nofollow" class="name">MC635096016</a>不错，在现在大多数服很难做到完全免费。这是MC忠实爱好者的最佳之选！</p>
                </div>
            </div>
            <div class="tip">向右滑动查看更多</div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.players-say {
    background: #f6f6f6;
}
.players-say-cell {
    display: inline-block;
    background: #fff;
    padding: 20px;
    border-radius: 3px;
    color: #666;
    margin: 0 10px 10px 0;
    max-width: 270px;
    /* height: 80px; */
    white-space: normal;
    vertical-align: top;
}
.players-say-cell p {
    font-size: 14px;
    letter-spacing: 1px;
    margin-left: 40px;
    overflow-y: scroll;
    height: 110px;
    padding: 0 5px;
}
.players-say-cell .avatar {
    height: 32px;
    border-radius: 50%;
    padding: 1px;
    border: 1px solid #637599;
    box-sizing: border-box;
    float: left;
}
.players-say-cell a.name {
    display: block;
    font-size: 16px;
    letter-spacing: normal;
    text-decoration: none;
    color: #555;
    font-weight: 600;
    margin-bottom: 3px;
}
.say-container {
    width: 100%;
    /* margin-left: auto; */
    /* margin-right: auto; */
    overflow-x: scroll;
    overflow-y: hidden;
    /* justify-content: space-between; */
    white-space: nowrap;
}
.players-say .tip {
    text-align: right;
    margin: 15px 0;
    font-size: 12px;
    color: #666;
    letter-spacing: 1px;
    text-transform: capitalize;
}
.players-say .tip::before {
    content: "* ";
    color: red;
    font-size: 12px;
}
</style>