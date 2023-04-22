<template>
  <div id="app">
    <toast-notification></toast-notification>
    <delete-button></delete-button>
  </div>
</template>

<script>
import ToastNotification from "@/components/ToastNotification.vue";
import DeleteButton from "@/components/DeleteButton.vue";

export default {
  name: "App",
  components: {
    ToastNotification,
    DeleteButton,
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
