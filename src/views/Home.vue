<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <SimpleForm  />
  </div>
</template>

<script>
// @ is an alias to /src
import SimpleForm from "./SimpleForm.vue";

export default {
  name: "Home",
  components: {
    SimpleForm,
  },
};
</script>
