<template>
  <Navbar></Navbar>
  <div class="container py-3">
    <router-view />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
export default {
  components: {
    Navbar
  }
}
</script>
