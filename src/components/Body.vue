<!--  -->
<template>
  <div class="">
    <div id="big">
      <div class="small">复用</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Body",
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
  #big{
    position: relative;
    width: 60%;
    height: 200px;
    border: 1px black solid;
  }
  .small{
    position: absolute;
    float: left;
    top: 50%;
    margin-left: 5%;
    width: 20%;
    height: 50px;
    border: 1px solid black;
  }
</style>