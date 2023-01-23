<template>
  <div>
    <h1>Todo List</h1>
    <q-list bordered separator>
      <q-item clickable v-for="i in 10" :key="i">
        <q-item-section>Todo {{ i }}</q-item-section>
      </q-item>
    </q-list>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({});
</script>
