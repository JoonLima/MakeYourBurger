<template>
  <banner/>
  <div class="main-container">
    <h1>Monte seu burger</h1>
    <burger-form/>
  </div>
</template>

<script>
import Banner from '@/components/Banner.vue';
import BurgerForm from '@/components/BuegerForm.vue'

export default {
  name: "HomeView",
  components: {
    Banner,
    BurgerForm
  },
};
</script>

<style scoped>

</style>
