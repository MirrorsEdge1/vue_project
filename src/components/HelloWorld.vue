<template>
  <div>
    <div class="menu-title">
      <button>Menu</button>
    </div>
    <div>
      <div class="menu-section">
        <button>Section-1</button>
        <button>Section-2</button>
        <button>Section-3</button>
      </div>
      <div class="router">
        {{msg}}
      </div>
    </div>
  </div>
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
