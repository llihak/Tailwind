<script setup>
import Summit from './components/Summit.vue';
import Hero from './components/Hero.vue';
import Overview from './components/Overview.vue';
import Sessions from './components/Sessions.vue';
import Session from './components/Session.vue';
</script>

<template>
  <Summit>
    <Hero></Hero>
    <Overview></Overview>
    <Sessions>
      <Session></Session>
      <Session></Session>
      <Session></Session>
    </Sessions>
  </Summit>
</template>

<style>

</style>
