<template lang="html">
  <div class="todo-item">
    <p>{{todo.title}}</p>
  </div>
</template>

<script>
  export default {
    name: 'TodoItem',
    props: ['todo']
  }
</script>

<style lang="css" scoped>
  .todo-item {
    background: #f4f4f4;
    padding: 10px;
    border-bottom: 1px dotted #ccc;
  }

  .is-complete {
    text-decoration: line-through;
  }

  .del {
    background: #ff0000;
    color: #fff;
    border: none;
    padding: 5px 9px;
    cursor: pointer;
    float: right;
  }
</style>
