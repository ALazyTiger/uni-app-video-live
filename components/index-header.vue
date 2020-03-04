<template>
    <view class="index-header"><!--固定定位到首页顶部-->
       
        <view class="middle"> <!--搜索图标绝对定位后，middle将会上移动到顶部，在搜索图标下面，里面内容居中显示即可-->
            <text class="text">推荐</text>
            <text class="bor">|</text>
            <text class="text">同城</text><!--变成行内元素-->
            <!-- <view class="text">同城</view> 设置颜色无效 -->
        </view>
    </view>
</template>

<style scoped>
.index-header {
    position: fixed;
    top: 25px;
    left: 0;
    z-index: 20;
   width: 750upx;
   height: 70upx;
   padding: 10upx 0;
   flex-direction: column;
   /* #ifndef APP-PLUS */
   white-space: nowrap;
   /* #endif */
}
.icon {
    position: absolute;
    left: 0;
    top: 0;
    color: white;
}
.middle {
    text-align: center;
    color: white;
    display:flex;
    font-size: 24upx;
    line-height: 50upx;
    flex-direction: row;
    justify-content: center;
}
.bor{
  height: 48upx;
 margin-top: -5upx;
  color: white;
  }
.text {
    display: inline;
    margin: 0 10px;
    text-align: center;
    color: white;
}

</style>