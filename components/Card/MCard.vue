<template>
  <div
    class="w-[230px] h-[233px] px-10 py-[30px] bg-white flex-col justify-start items-center gap-2.5 inline-flex"
  >
    <div class="w-12 h-12 relative">
      <div class="w-12 h-[44.21px] left-[0.50px] top-[2px] absolute">
        <img :src="icon" alt="" />
      </div>
    </div>
    <div
      class="text-slate-800 text-[40px] font-bold leading-[57px] tracking-tight"
    >
      {{ name }}
    </div>
    <div
      class="text-center text-neutral-500 text-base font-bold leading-normal tracking-tight"
    >
      {{ sub }}
    </div>
  </div>
</template>
<script>
export default {
  props: {
    name: String,
    icon: null,
    sub: String,
  },
};
</script>
