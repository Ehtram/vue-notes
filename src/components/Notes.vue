<template>
  <div class="notes">
    <h1>{{listName}}</h1>
    <ul>
      <li v-for="todo in tasks" class="mdl-list__item">
        <span class="mdl-list__item-primary-content">
          <i class="material-icons mdl-list__item-avatar">person</i>
          {{todo.name}}
        </span>
      </li>
    </ul>
    <button class="mdl-button mdl-js-button mdl-js-ripple-effect" v-on:click="add">
      Add a tdodo
    </button>
  </div>
</template>

<script>
export default {
  name: 'notes',
  data() {
    return {
      tasks: [
        { name: 'Super task to do this afternoon' },
        { name: 'Super task to do tomorrow' },
      ],
      listName: 'Todos',
    };
  },
  methods: {
    add() {
      console.log('Add Event sent from the button to the notes component');
    },
  },
};
</script>

<style lang="css" scoped>

</style>
