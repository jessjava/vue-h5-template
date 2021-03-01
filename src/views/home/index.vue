<template>
  <div class="index-container">
    <div class="warpper">
      <h1 class="home__title"><span> VUE H5 工程模板</span></h1>
    </div>
    <div class="content">
      <div class="title">mixin-less</div>
      <div class="desc">
        mixin-less演示，mixin-less演示，mixin-less演示，mixin-less演示，
        mixin-less演示，mixin-less演示，mixin-less演示，mixin-less演示
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
    }
  },

  computed: {},

  mounted() { },

  methods: {}
}
</script>
<style lang="less" scoped>
.index-container {
  .warpper {
    padding: 12px;
    background: #fff;
    .home__title {
      margin: 0 0 4px;
      font-size: 20px;
      .home__title img,
      .home__title span {
        display: inline-block;
        vertical-align: middle;
      }
      span {
        font-weight: 500;
        color: #333;
      }
    }
  }

  .content {
    padding: 12px;
    font-size: 14px;

    .title {
      color: rgba(69, 90, 100, 0.6);
      .textoverflow(1);
      margin: 8px 0;
    }

    .desc {
      .textoverflow(2);
      line-height: 1.6;
    }
  }
}
</style>
