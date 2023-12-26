<template>
  <div class="card px-10 py-12 space-y-4 text-center bg-white">
    <div class="flex justify-center">
      <img :src="icon" alt="" />
    </div>
    <div class="">
      <h1>georgia.young@example.com</h1>
      <h1>georgia.young@example.com</h1>
    </div>
    <div class="">
      <h1>Get Support</h1>
    </div>
    <button class="px-5 py-3 border border-amber-400 text-amber-400">
      Submit Request
    </button>
  </div>
</template>
<script>
export default {
  props: {
    icon: null,
  },
};
</script>
