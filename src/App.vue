<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default{
  components: {AppTitle, AppHero}
}
</script>

<template>
<div class="vh-100 vw-100 d-flex justify-content-center align-items-center">
  <div class="container border h-75 shadow rounded-5">
    <AppTitle></AppTitle>
    <AppHero></AppHero>
  </div>
</div>
</template>

<style>

</style>
