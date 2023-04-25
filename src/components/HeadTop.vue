<!--  -->
<template>
  <div class="">
    <div id="top">
      <div class="logo">这里是logo</div>
      <div class="inclusion"></div>
      <div class="avatar">头像</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Head",
  components: {},
  data() {
    return {};
  },
  //监听属性 类似于data概念
  computed: {},
  //监控data中的数据变化
  watch: {},

  methods: {},
  //生命周期 - 挂载完成（可以访问DOM元素）
  mounted() {},
};
</script>
<style scoped>
*{
        padding: 0;
        margin: 0;
    }
    body{
        background-color: black;
    }
    #top{
        position: relative;
        background-color: white;
        top: 0;
        height: 60px;
    }
    .logo{
        position: absolute;
        left: 20%;
        width: 100px;
        height: 50px;
        line-height: 50px;
        border: black 1px solid;
        margin-top: 5px;
    }
    .avatar{
        position: absolute;
        right: 20%;
        width: 50px;
        height: 50px;
        line-height: 50px;
        border-radius: 50px;
        border: black 1px solid;
        margin-top: 5px;
    }
    .inclusion{
        position: absolute;
        right: 30%;
        width: 50px;
        height: 20px;
        line-height: 50px;
        border: black 1px solid;
        margin-top: 20px;
    }
</style>