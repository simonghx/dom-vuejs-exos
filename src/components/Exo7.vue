<template>
  <section id="exo7" class="panel my-4 bg-light">
    <h1 class="text-center">Todo List en VueJS</h1>
    <div class="input-part text-center my-2">
      <input type="text" class="mr-1">
      <button class="btn btn-primary ml-1">Add a task</button>
    </div>
    <div class="tags">
      <h3 class="d-inline mr-4">List Filter</h3>
      <button class="btn btn-success mx-1">All</button>
      <button class="btn btn-success mx-1">Done</button>
      <button class="btn btn-success mx-1">To do</button>
    </div>
    <div class="group-list">

    </div>
  </section>
</template>

<script>
export default {
  name: "exo7",
  props: [],
  mounted() {},
  data() {
    return {};
  },
  methods: {}
};
</script>

<style lang="sass">

</style>