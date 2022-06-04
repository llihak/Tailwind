<script setup>
import Summit from './components/Summit.vue';
import Hero from './components/Hero.vue';
import Overview from './components/Overview.vue';
import Sessions from './components/Sessions.vue';
import Session from './components/Session.vue';
</script>

<template>
  <Summit class="container mx-auto">

    <Hero></Hero>
    <Overview></Overview>

    <Sessions>
      <Session name="Greg Lewis" title="Everything I thought I knew was wrong" time="9 AM" />
      <Session name="Jeff Gibby" title="My revolutionary motto: buy low and sell high" time="11 AM" />
      <Session name="Scott Brown" title="What I think I will do now with MetaStock" time="12 PM" />
    </Sessions>

  </Summit>
</template>

<style>

</style>
