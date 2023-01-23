<template>
  <q-page class="row items-center justify-evenly">
    <TodoItem></TodoItem>
    <TodoList></TodoList>
  </q-page>
</template>

<script setup lang="ts">
import TodoList from 'src/components/TodoList.vue';
import TodoItem from 'src/components/TodoItem.vue';
</script>
