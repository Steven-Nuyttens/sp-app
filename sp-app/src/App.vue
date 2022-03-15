<template>
  <div>
    <InputForm />
  </div>
  <div>
    <InputList />
  </div>
</template>

<script>
import InputForm from "./components/InputForm.vue";
import InputList from "./components/InputList.vue";

export default {
  name: "App",
  components: {
    InputForm,
    InputList,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
