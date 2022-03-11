<template>
    <div class="footer">
        <div class="container">
            <div class="content">
                <div class="sub">
                    <strong>SDZJ V3.</strong>build.vue
                    <br>Dev by <a href="https://github.com/ShangJixin/" target="_blank" title="三道水师提督尚寂新">ShangJixin</a>
                </div>
                Copyright &copy; 2013-{{ nowYear }}<br>
                <strong><a href="https://www.disandadao.org/">第三大道公益服</a></strong> | 勿剽窃本服及本站创意
            </div>
        </div>
    </div>
</template>

<script>
export default {
    computed: {
        nowYear() {
            let date = new Date()
            return date.getFullYear()
        }
    }
}
</script>

<style lang="less" scoped>
.footer {
    font-size: 12px;
    font-weight: 400;
    color: #666;
    line-height: 18px;
}
.footer .container {
    padding: 0 20px;
}
.footer .content {
    margin: 15px 0 40px 0;
}
.footer .content .sub {
    float: right;
}
.footer a {
    text-decoration: none;
    color: inherit;
}
</style>