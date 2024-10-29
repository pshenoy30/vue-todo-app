<script setup>
import todoForm from './TodoForm.vue';
import todoList from './TodoList.vue'
</script>

<template>
    <div class="todo-app">
        <h1>To Do List</h1>
        <todoForm />
        <todoList />
    </div>
</template>

<style>
.todo-app {
  min-height: 100vh;
  width: 70vw;
}
</style>