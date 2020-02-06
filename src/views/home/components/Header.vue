<template>
  <div class="header">
    <div class="header-left">
      <i class="iconfont back-icon">&#xe658;</i>
    </div>
    <div class="header-center">
      <i class="iconfont">&#xe63c;</i>
      <input type="text" placeholder="输入城市/景点/游玩主题">
      <!-- 输入城市/景点/游玩主题 -->
    </div>
    <div class="header-right">
      <span>城市</span>
      <i class="iconfont">&#xe65c;</i>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~@/assets/styles/variables.styl'
.header {
  display: flex;
  line-height: .86rem;
  background: $bgColor;
  color: #fff;
  .header-left {
    width: .64rem;
    text-align: center;
    .back-icon {
      font-size: .4rem
    }
  }
  .header-center {
    flex: 1;
    height: .64rem;
    line-height: .64rem;
    margin-top: .12rem;
    // margin-left: .2rem;
    border-radius: .1rem;
    background: #fff;
    color: #ccc;
  }
  .header-right {
    width: 1.24rem;
    text-align: center;
  }
}
</style>
