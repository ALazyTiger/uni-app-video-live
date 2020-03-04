<template>
    <view class="footer">
      <view class="footer-tab">
        <navigator open-type="switchTab" url="/pages/index/index" class="tab-box">首页</navigator>
        <navigator open-type="switchTab" url="/pages/follow/follow" class="tab-box">关注</navigator>
       <navigator open-type="switchTab" url="/pages/follow/follow" class="tab-box">+</navigator>
        <navigator open-type="switchTab" url="/pages/news/news" class="tab-box">消息</navigator>
        <navigator open-type="switchTab" url="/pages/personal/personal" class="tab-box">我的</navigator>
        </view>
    </view>
</template>

<style>
.footer{
    position:fixed;
    bottom: 0;
    left: 0;
    right: 0;
    z-index: 20;
    width: 750upx;
    height: 100upx;
    /* #ifndef APP-PLUS */
    white-space: nowrap;
    /* #endif */
}
.footer-tab{
  display:flex;
  flex-direction:row;
  justify-content: center;
  height: 100upx;
  text-align: center;
  color: #FFFFFF;
  
}
.tab-box{
 flex: 1;
  text-align: center;
  color: white;
  height: 100upx;
  font-size: 12px;
  line-height:100upx;
  background-color: transparent;
  margin: 0 2upx;
  
}
</style>