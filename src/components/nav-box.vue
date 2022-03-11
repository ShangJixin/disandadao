<template>
    <div class="nav-box">
        <div class="nav-container">
            <a href="https://www.disandadao.org" class="a-attr-logo">
                <img class="logo" src="../assets/logo.png" alt="第三大道公益服" title="第三大道公益服" />
            </a>
            <div class="nav">
                <svg t="1602676023318" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="1169" width="24" height="24"><path d="M374.272 440.832H127.488c-33.792 0-61.44-27.648-61.44-61.44V132.608c0-33.792 27.648-61.44 61.44-61.44h247.296c33.792 0 61.44 27.648 61.44 61.44v247.296c-0.512 33.792-27.648 60.928-61.952 60.928zM127.488 132.608v247.296h247.296V132.608H127.488zM762.88 492.032c-16.384 0-31.744-6.144-43.52-17.92l-174.592-174.592c-11.776-11.776-17.92-27.136-17.92-43.52s6.144-31.744 17.92-43.52l174.592-174.592c11.776-11.776 27.136-17.92 43.52-17.92s31.744 6.144 43.52 17.92l174.592 174.592c11.776 11.776 17.92 27.136 17.92 43.52s-6.144 31.744-17.92 43.52l-174.592 174.592c-11.776 11.776-27.136 17.92-43.52 17.92z m0-410.624L588.288 256 762.88 430.592 937.472 256 762.88 81.408zM374.272 952.832H127.488c-33.792 0-61.44-27.648-61.44-61.44v-247.296c0-33.792 27.648-61.44 61.44-61.44h247.296c33.792 0 61.44 27.648 61.44 61.44v247.296c-0.512 34.304-27.648 61.44-61.952 61.44z m-246.784-308.224v247.296h247.296v-247.296H127.488zM886.272 952.832h-247.296c-33.792 0-61.44-27.648-61.44-61.44v-247.296c0-33.792 27.648-61.44 61.44-61.44h247.296c33.792 0 61.44 27.648 61.44 61.44v247.296c0 34.304-27.136 61.44-61.44 61.44z m-246.784-308.224v247.296h247.296v-247.296h-247.296z" p-id="1170" fill="#637599"></path></svg>
                <div class="nav-cell">
                    <a href="https://bbs.disandadao.org/wiki/" target="_blank">百科</a>
                    <a href="https://bbs.disandadao.org" target="_blank">社区</a>
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
.nav-box {
    height: 50px;
    background-color: #000;
    display: block;
    background-color: #fff;
    background-color: rgba(255,255,255,0.72);
    backdrop-filter: saturate(180%) blur(20px);
    /*border-bottom: 1px solid rgba(128,128,128,0.16);*/
    position: fixed;
    width: 100vw;
    z-index: 1;
}

.nav-box .nav-container {
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;
    padding: 0 20px;
}

.nav-box .logo {
    height: 50px;
    width: auto;
    padding: 10px 0;
    box-sizing: border-box;
    display: inline-block;
}

.nav-box .a-attr-logo{
    text-decoration: none;
}

.nav-box .a-attr-logo::after {
    content: "· 主站";
    vertical-align: text-bottom;
    line-height: 50px;
    display: inline-block;
    font-size: 12px;
    letter-spacing: 2px;
    text-decoration: none;
    color: #637599;
}

.nav-box .nav {
    display: inline-block;
    float: right;
    line-height: 50px;
    position: relative;
}

.nav-box .nav .icon {
    padding: 13px 0;
    display: none;
}

.nav-box .nav .nav-cell {
    display: inline-block;
}

.nav-box .nav .nav-cell a {
    color: #637599;
    text-decoration: none;
    margin-left: 10px;
    text-transform: uppercase;
    background: #f5f5f5;
    padding: 3px 16px;
    border-radius: 3px;
    font-size: 14px;
}
@media screen and (max-width: 370px) {
    .nav-box .nav .icon {
        display: inline-block;
        cursor: pointer;
    }
    .nav-box .nav .nav-cell {
        display: none;
    }
    
    .nav-box .nav:hover .nav-cell{
        display: block;
        position: absolute;
        border: 1px solid rgba(128,128,128,0.16);
        background: #fff;
        padding: 5px 0;
        top: 40px;
        right: 0;
        width: 80px;
        text-align: center;
        border-radius: 3px;
    }
    .nav-box .nav .nav-cell a {
        margin: 5px 0;
        display: block;
        line-height: 35px;
        font-size: 16px;
        background: #FAFAFA;
    }
    .nav-box .nav .nav-cell a:hover {
        background: #E6E9F0;
    }
}

@media screen and (min-width: 2560px) {
    .nav-box .nav-container {
        max-width: 80vw;
    }
}
</style>