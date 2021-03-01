<template>
  <div class="about-container">
    <van-cell icon="success" v-for="item in list" :key="item" :title="item" />
  </div>
</template>

<script>
// 请求接口
import { mapGetters } from 'vuex'
export default {
  data() {
    return {
      list: [
        'Vue-cli4',
        '配置多环境变量',
        'VantUI 组件按需加载',
        'Less 全局样式',
        'VantUI - Less样式覆盖',
        'Webpack 4',
        'Vuex 状态管理',
        'Axios 封装及接口管理',
        'Vue-router',
        'Webpack 4 vue.config.js 基础配置',
        '配置 proxy 跨域',
        '配置 alias 别名',
        '配置 打包分析',
        '配置 externals 引入 cdn 资源',
        '去掉 console.log',
        'splitChunks 单独打包第三方模块',
        'Eslint+Pettier 统一开发规范'
      ]
    }
  },
  computed: {
    ...mapGetters(['userName'])
  },
  mounted() {
  },
  methods: {
  }
}
</script>
<style lang="less">
.about-container {
  /* 你的命名空间 */
  background: #fff;
  height: 100vh;
  overflow: auto;
  box-sizing: border-box;
}
</style>
