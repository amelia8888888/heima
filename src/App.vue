<template>
  <div id="app">
    <h1>黑马头条</h1>
    <router-view/>
    <van-button type="primary">主要按钮</van-button>
<van-button type="info">信息按钮</van-button>
<van-button type="default">默认按钮</van-button>
<van-button type="warning">警告按钮</van-button>
<van-button type="danger">危险按钮</van-button>

<div class="box"></div>
  </div>
</template>

<script>

export default {
  name: 'App',

  data () {
    return {
      show: false
    }
  },

  methods: {
    showPopup () {
      this.show = true
    }
  }
}
</script>

<style lang="less">
.box{
  width: 200px;
  height: 200px;
  background-color: pink;
}
</style>
