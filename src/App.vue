<template>
  <!--<div id="app">-->
    <!--<img src="./assets/logo.png">-->
    <!--<router-view/>-->
  <!--</div>-->
  <div>
    <todo-list></todo-list>
  </div>
</template>

<script>
  // eslint-disable-next-line
  /* eslint-disable */
  import TodoList from './components/TodoList';

export default {
  name: 'app',
  components: {
    TodoList,
  },
};
</script>

<style>
/*#app {*/
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
  /*-webkit-font-smoothing: antialiased;*/
  /*-moz-osx-font-smoothing: grayscale;*/
  /*text-align: center;*/
  /*color: #2c3e50;*/
  /*margin-top: 60px;*/
/*}*/
</style>
