<script setup>
import Summit from './components/Summit.vue';
import Hero from './components/Hero.vue';
import Overview from './components/Overview.vue';
import Sessions from './components/Sessions.vue';
import Session from './components/Session.vue';
</script>

<template>
  <Summit id="AppVue" class="container [ max-w-5xl mx-auto ] p-4 pt-0">

    <Hero></Hero>
    <Overview></Overview>

    <Sessions>
      <Session name="Greg Lewis" title="Everything I thought I knew was wrong" time="9 AM" short-name="glewis" />
      <Session name="Jeff Gibby" title="My revolutionary motto: buy low and sell high" time="11 AM"
        short-name="jgibby" />
      <Session name="Daryl Guppy" title="What I think I will do now with MetaStock" time="12 PM" short-name="dguppy" />
    </Sessions>

  </Summit>
</template>

<style>

</style>
