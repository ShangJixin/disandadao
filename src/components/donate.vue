<template>
    <div class="donate">
        <div class="container">
            <h2 class="title">无偿捐助</h2>
            <div class="subtitle">Donation</div>
            <p class="text">让服务器发展更加好，需要更多的资金。此资金性质为<strong>无偿捐助</strong>。本服为了让更多玩家体会公平游戏的乐趣，因此赞助者不会获得游戏物品、金钱、权限等，只为打造劳动致富的公平世界，希望你能理解这一苦心。感谢你支持第三大道！</p>
            <div class="btn-box">
                <a href="https://bbs.disandadao.org/thread-65-1-1.html" target="_blank" title="向支持三道的筑梦人致敬！在此向大家致以最诚挚的感谢">筑梦人</a>
                <a href="" target="_blank" onclick="alert('新周目尚未开启，暂时未设置捐助通道。\n感谢对第三大道公益服的支持！');event.preventDefault();">无偿捐助</a>
            </div>
            <p class="text" style="color: red;">由于服务器暂时未重新开启，故捐助通道暂不提供</p>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.btn-box {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 20px 0;
}

.btn-box a {
    color: #637599;
    text-decoration: none;
    border: 1px solid #637599;
    padding: 7px 15px;
    letter-spacing: 1px;
    margin: 0 10px;
    text-transform: uppercase;
}
</style>