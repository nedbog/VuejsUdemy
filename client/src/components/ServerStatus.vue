<template>
  <div>
    <h1>Status: {{ status }}</h1>
    <hr />
    <button @click="changeStatus">Change Status</button>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      status: "Critical",
    };
  },
  methods: {
    changeStatus: function () {
      this.status = "Normal";
    },
  },
};
</script>

<style>
</style>