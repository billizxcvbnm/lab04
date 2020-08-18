<template>
  <div>

  </div>
</template>

<script>
export default {
  name: "CsButton",
  props: {
    label1: String,
  },
  data: function () {
    return {
      counter1: 0,
      classObject: {
        active: true,
        "text-danger": false,
        weight: 20,
      },
    };
  },
};
</script>



<style>
</style>