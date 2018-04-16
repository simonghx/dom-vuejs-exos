<template>
  <button class="btn" :class="{'btn-primary' : !change, 'btn-danger' : change}" @click.prevent="changeButton">Click on me</button>
</template>

<script>
export default {
  name: "exo2",
  props: [],
  mounted() {},
  data() {
    return {
      change: true
    };
  },
  methods: {
    changeButton() {
      if (this.change == true) {
        this.change = false;
      } else {
        this.change = true;
      }
    }
  }
};
</script>

<style lang="sass">

</style>
