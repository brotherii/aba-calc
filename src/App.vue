<template>
  <div id="app">
    <TodoList /> <!--не кебаб стиль, разрешено для однофайловых компонент-->
  </div>
</template>

<script>
import TodoList from "./components/TodoList.vue";

export default {
  name: 'App',
  data(){
    return {
      todos: []
    }
  },
  components: {
    TodoList
  }
}
</script>

<style>

</style>