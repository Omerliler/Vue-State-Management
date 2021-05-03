<template>
  <div id="app">
    
    <div class="container">
      <div class="image">
        <img
        src="WhatsApp Image 2021-05-01 at 01.37.26.jpeg" 
        height="120px"
        width="150px">
      </div>
      
      <AddTodo/>
      <FilterTodo/>
      <Todos />
    </div>
    
  </div>
</template>

<script>
import Todos from './components/Todo.vue'
import AddTodo from './components/AddTodo.vue'
import FilterTodo from './components/FilterTodo.vue'

export default {
  name: 'App',
  components: {
    Todos,
    AddTodo,
    FilterTodo
  }
}
</script>

<style>
body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #fff;
}
.container {
  max-width: 1100px;
  min-width: 400px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
.image {
  text-align: center;
}
</style>
