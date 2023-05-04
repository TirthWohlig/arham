<template>
  <div>
    <navabar />
    <router-view />
  </div>
</template>

<script>
import navabar from "@/components/navbar.vue";
export default {
  components: {
    navabar,
  },
};
</script>

<style>
</style>