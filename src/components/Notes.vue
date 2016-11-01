<template>
  <div class="notes">
    <p>Notes Component:</p>
    <p> task : {{task}}</p>
  </div>
</template>

<script>
export default {
  name: 'notes',
  data() {
    return {
      task: 'Super task to do this afternoon',
    };
  },
};
</script>

<style lang="css" scoped>
</style>
