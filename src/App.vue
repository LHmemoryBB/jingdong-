<template>
    <div class="docker">
        <span class="docker_item">
            <div class="iconfont">&#xe625;</div>
            首页
        </span>
        <span class="docker_item">
            <div class="iconfont">&#xe63f;</div>
            购物车
        </span>
        <span class="docker_item">
            <div class="iconfont">&#xe897;</div>
            订单
        </span>
        <span class="docker_item">
            <div class="iconfont">&#xe62f;</div>
            我的
        </span>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.docker {
    position: absolute;
    left: 0;
    bottom: 0;
    box-sizing: border-box;
    padding:0 .18rem;
    display: flex;
    width: 100%;
    height: 0.49rem;
    border-top: 1px solid #f1f1f1;
    // background-color: aqua;

}
.docker_item{
    flex: 1;
    text-align: center;
    .iconfont{
        margin: .07rem 0 .02rem 0;
        font-size: .18rem;
    }
}
</style>
