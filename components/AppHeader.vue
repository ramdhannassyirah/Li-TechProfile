<template>
  <div class="container mx-auto px-10 md:px-0">
    <nav class="flex items-center justify-between">
      <div class="py-9">
        <h1 class="text-slate-800 text-2xl font-bold">Li-TechProfile</h1>
      </div>
      <div class="hidden space-x-3 md:block" v-if="isCreating">
        <NuxtLink to="/about">Home</NuxtLink>
        <a href="">Product</a>
        <a href="">Pricing</a>
        <a href="">Contact</a>
      </div>
      <div class="">
        <img
          src="../assets/icon/navbar/toggler-icon.svg"
          alt=""
          @click="isCreating = !isCreating"
        />
      </div>
    </nav>
  </div>
  <!-- Mobile Navbar -->
  <div
    class="flex flex-col w-screen text-center py-20 gap-7 absolute md:hidden bg-white"
    v-if="!isCreating"
  >
    <NuxtLink to="/about">Home</NuxtLink>
    <a href="">Product</a>
    <a href="#Pricing">Pricing</a>
    <a href="#Contact">Contact</a>
  </div>
</template>
<script>
export default {
  data() {
    return {
      isCreating: true,
    };
  },
};
</script>
