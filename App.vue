<script>
export default {
  onLaunch: function() {
    console.log('App Launch');
    setTimeout(() => {
      uni.hideTabBar(); // 隐藏tabBar
    }, 1000);
  },
  onShow: function() {
    console.log('App Show');
  },
  onHide: function() {
    console.log('App Hide');
  }
};
</script>
<style></style>
