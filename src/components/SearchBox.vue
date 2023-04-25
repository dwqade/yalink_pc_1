<!--  -->
<template>
    <div class=''>
        <div id="BackImage">
    我是背景
    <div class="searchBox">
      <div class="searchEngin">
        <div>一堆搜索引擎按钮</div>
      </div>
      <div class="search">
        输入框
        <input type="button" value="点的">
      </div>
    </div>
  </div>
    </div>
</template>

<script>
export default {
    name:'SearchBox',
    components: {},
    data() {
        
        return {
            
        };
    },
    //监听属性 类似于data概念
    computed: {},
    //监控data中的数据变化
    watch: {},
    
    methods: {
        
    },
    //生命周期 - 挂载完成（可以访问DOM元素）
    mounted() {
        
    },
    }
</script>
<style scoped>
*{
    padding: 0;
    margin: 0;
  }
  body{
    background-color: black;
  }
  #BackImage{
    position: relative;
    height: 500px;
    background-color: pink;
  }
  .searchEngin{
    width: 80%;
    height: 50%;
    background-color: white;
    border:1px black solid;
  }
  .search{
    height: 50%;
    background-color: white;
  }
  .searchBox{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    width: 60%;
    height: 100px;
  }
  .search input{
    float: right;
    background-color: red;
    width: 50px;
    height: 80%;
    margin-top: 5px;
  }
</style>