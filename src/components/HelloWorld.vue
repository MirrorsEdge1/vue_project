<template>
  <section class="el-container is-vertical">
    <header class="el-header menu-title" style="height: 60px;">
      <el-button>Menu</el-button>
    </header>
    <section class="el-container">
      <aside class="el-aside" style="width: 200px;">
        <el-button>Section-1</el-button>
        <el-button>Section-2</el-button>
        <el-button>Section-3</el-button>
      </aside>
      <main class="el-main">
        {{msg}}
      </main>
    </section>
  </section>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    },
    methods: {
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .menu-section{
    float: left;
    display: grid;
  }
  .router{
    background: red;
  }
  .menu-title{
    position: fixed;
    height: 42px;
    width: 100%;
    left: 0;
    top: 0;
    background: black;
  }

</style>
