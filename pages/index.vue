<template>
  <div>
    <div class="h-14 shadow flex jstify-center items-center>
      <p class="body">
    <TodoButton />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import TodoButton from '../components/TodoButton.vue'

export default Vue.extend({
  name: 'IndexPage',
  components: {
    TodoButton,
  },
  data(){
  }
  
})
</script>
