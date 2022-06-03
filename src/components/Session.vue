<script>
export default {
  name: 'Session',
  props: {
    name: String,
    title: String,
    time: String,
  },
}
</script>

<template>
  <div class="Session
      block sm:grid grid-cols-4 gap-4
      mt-6
      border-t-gray-600
      shadow-dark-800
      ">
    <div class="media 
      flex justify-center 
      mb-2 sm:mb-0
    ">
      <img class="w-[240px] h-[240px] mx-auto" src="../assets/avatar-2092113_640.webp" alt="Presenter image">
    </div>
    <div class="session-details col-span-3">
      <div class="meta">
        <h2 class="font-bold text-2xl text-blue-700">
          {{ name }}
        </h2>
        <h3 class="font-bold text-xl">
          {{ time }}
        </h3>
        <h4 class="font-bold text-3xl text-orange-700">
          {{ title }}
        </h4>
      </div>
      <div class="details col-span-3 mt-4 text-left">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Est perferendis itaque assumenda nemo iusto vero,
          illo
          sequi odit. Molestiae voluptas officiis, dolorem temporibus non nisi necessitatibus consectetur reiciendis?
          Quibusdam, repellat!
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Est perferendis itaque assumenda nemo iusto vero,
          illo
          sequi odit. Molestiae voluptas officiis, dolorem temporibus non nisi necessitatibus consectetur reiciendis?
          Quibusdam, repellat!
        </p>
      </div>
    </div>
  </div>
</template>

<style lang="">

</style>
