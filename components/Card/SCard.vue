<template>
  <div class="Card bg-white p-10">
    <div class="">
      <img :src="icon" alt="" class="py-4" />
      <h1 class="text-2xl font-bold text-slate-800">{{ name }}</h1>
      <p class="text-neutral-500">
        Just type what's on your mind and we'll get you there.
      </p>
    </div>
  </div>
</template>
<script>
export default {
  props: {
    icon: null,
    name: String,
  },
};
</script>
