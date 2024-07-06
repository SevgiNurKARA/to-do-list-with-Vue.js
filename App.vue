<template>
 <div id="app">
   
    <Todo />
  </div>
</template>

<script>
import './components/style.css';
import Todo from './components/Todo.vue';

export default{
name: 'AnotherComponent',
components: {
    Todo
  },
}

</script>

<style>

</style>