<template>
  <div class="index-container">
    <div class="warpper">
      <h1 class="home__title"><span> VUE H5开发模板</span></h1>
      <h2 class="home__desc">
        A vue h5 template with Vant UI
      </h2>
    </div>
    <div class="content">
      welcome
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
<style lang="scss" scoped>
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
    .home__desc {
      color: rgba(69, 90, 100, 0.6);
      font-size: 14px;
    }
  }

  .content {
    padding: 12px;
    font-size: 14px;
  }
}
</style>
