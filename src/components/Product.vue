<template>
  <div class="mb-2">
    <img src="../assets/myprofile.png" height="200"/>
  </div>
</template>

<script>

export default {
  name: "Product",
  data() {
    return {
      value:"",
      categories: [
        { name: "Lácteos", code: "LA" },
        { name: "Verduras", code: "VE" },
        { name: "Frutas", code: "FR" },
      ],
    };
  }
};
</script>

<style scoped>

</style>