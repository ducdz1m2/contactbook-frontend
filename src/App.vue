<script>
import AppHeader from "@/components/AppHeader.vue";

export default {
  components: {
    AppHeader,
  },
};
</script>

<template>
  <div id="app">

    <AppHeader />

    <main class="mt-3">
      <router-view />
    </main>
  </div>
</template>

<style>
.page {
  max-width: 400px;
  margin: auto;
}
</style>
