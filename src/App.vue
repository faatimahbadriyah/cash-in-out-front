<template>
  <navbar />
  <div class="mt-10"></div>
  <router-view />
</template>

<script>
import Navbar from "@/components/Navbar";
export default {
  components: { Navbar },
};
</script>

<style>
</style>