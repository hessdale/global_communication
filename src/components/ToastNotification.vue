<template>
  <div></div>
</template>

<script>
export default {
  data() {
    return {
      message: undefined,
    };
  },
  methods: {
    toast_listen(toast) {
      this.message = toast;
    },
  },
  mounted() {
    this.$root.$on(`toast_notify`, this.toast_listen);
  },
};
</script>

<style scoped>
</style>