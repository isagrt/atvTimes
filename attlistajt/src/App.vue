<script setup>
import HeaderComp from '@/components/template/HeaderComp.vue';
import FooterComp from '@/components/template/FooterComp.vue';
import MusicasView from '@/views/MusicasView.vue';
</script>

<template>
  <HeaderComp />
  <RouterView />
  <FooterComp />
  <MusicasView />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: auto;
  margin: 0 auto;
  /* padding: 2rem; */
  height: 100vh;

  font-weight: normal;
}

footer {
  background-color: cornflowerblue;
  height: 15%;
  font-size: 1.3rem;
  padding-left: 2rem;
  color: white;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

main {
  min-height: 70%;
}

a {
  color: inherit;
  text-decoration: none;
}
</style>