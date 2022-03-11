<template>
    <div class="whychoose">
        <div class="container">
            <h2 class="title">为什么选择我们</h2>
            <div class="subtitle">Why Choose Us</div>
            <div class="advantage-row">
                <div class="advantage l">
                    <img src="../assets/whychoose/tiezhen.png" />
                    <h3>绝对公平</h3>
                    <p class="text">绝不出售可买到的权限。捐助者可以在服务器里的捐助名单留名，除此之外无任何特权。无老玩家，跟管理脸熟特权。</p>
                </div>
                <div class="advantage r">
                    <img src="../assets/whychoose/fumotai.gif" />
                    <h3>绝对自由</h3>
                    <p class="text">管理不干涉玩家生活。无规定刷怪场，无规定矿物的官方价。无白名单。不禁红石。不规定建筑区域。</p>
                </div>
                <div>&nbsp;</div>
                <div class="advantage l">
                    <img src="../assets/whychoose/minglingfangkuai.gif" />
                    <h3>绝对稳定</h3>
                    <p class="text">服务器在我们自己的实体物理机上运行。不会因为同机器的其它腐竹在下电影而影响性能。</p>
                </div>
                <div class="advantage r">
                    <img src="../assets/whychoose/tiekuai.png" />
                    <h3>绝对口碑</h3>
                    <p class="text">服务器管理组凭借自己的努力给服务器赢得了良好的名声。以前 4 周目还是盗版服的时候累计有超过 4 万名玩家加入。</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.whychoose .advantage-row{
    margin: 60px 0 30px 0;
    letter-spacing: 0;
    font-size: 0;
}
.whychoose .advantage-row .advantage{
    display: inline-block;
    width: 50%;
    /*float: left;*/
    text-align: center;
    vertical-align: top;
}
.whychoose .advantage-row .advantage.l{
    padding-right: 20px;
}
.whychoose .advantage-row .advantage.r{
    padding-left: 20px;
}
.whychoose .advantage-row .advantage p{
    margin: 20px 0 40px 0;
    font-size: 14px;
    letter-spacing: 1px;
    font-weight: 300;
    color: #666;
}
.whychoose .advantage-row .advantage h3{
    margin: 20px 0;
    font-size: 20px;
    letter-spacing: 2px;
    font-weight: 400;
    color: #333;
    text-transform: uppercase;
}
.whychoose .advantage-row .advantage img {
    height: 100px;
    width: 100px;
}
</style>