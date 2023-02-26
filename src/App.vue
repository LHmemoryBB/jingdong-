<template>
    <div class="wrapper">
        <div class="position">
            <span class="iconfont position__icon">&#xe7f1;</span>
            浙江省宁波市鄞州区潘火路和荣大厦A座
            <span class="iconfont position__notice">&#xe60b;</span>
        </div>
    </div>
    <div class="docker">
        <span class="docker__item docker__item--active">
            <div class="iconfont">&#xe625;</div>
            <div class="docker__title">首页</div>
        </span>
        <span class="docker__item">
            <div class="iconfont">&#xe63f;</div>
            <div class="docker__title">购物车</div>
        </span>
        <span class="docker__item">
            <div class="iconfont">&#xe897;</div>
            <div class="docker__title">订单</div>
        </span>
        <span class="docker__item">
            <div class="iconfont">&#xe62f;</div>
            <div class="docker__title">我的</div>
        </span>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.wrapper{
    position: absolute;
    // width: 100%;
    left: 0;
    top: 0;
    right: 0;
    bottom: 0.5rem;
    padding: 0 .18rem;
}
.position{
    padding: .16rem 0;
    line-height: .22rem;
    font-size: .16rem;
    overflow: hidden;
    white-space: nowrap;
    text-overflow: ellipsis;
    .position__icon{
        font-size: .2rem;
    }
    .position__notice{
        position: absolute;
        right: .16rem;
        top: .17rem;
        font-size: .2rem;
    }
}
.docker {
    position: absolute;
    left: 0;
    bottom: 0;
    box-sizing: border-box;
    padding: 0 .18rem;
    display: flex;
    width: 100%;
    height: 0.49rem;
    border-top: .01rem solid #f1f1f1;

    // background-color: aqua;
    &__item {
        flex: 1;
        text-align: center;

        .iconfont {
            margin: .07rem 0 .02rem 0;
            font-size: .18rem;
        }

        &--active {
            color: #1FA4FC
        }
    }

    &__title {
        font-size: .12rem;
    }
}
</style>
