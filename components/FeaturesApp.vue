<template>
  <section class="px-10 md:px-0 bg-neutral-50">
    <div class="container mx-auto py-20">
      <div class="flex justify-center">
        <div class="text-center font-sans w-[511px]">
          <h1 class="font-bold text-4xl">WHY CHOOSE US</h1>
          <p class="text-xl my-10">
            Problems trying to resolve the conflict between the two major realms
            of Classical physics: Newtonian mechanics
          </p>
        </div>
      </div>
      <div class="flex md:justify-between flex-wrap gap-7 justify-center my-20">
        <MCard />
        <MCard />
        <MCard />
        <MCard />
      </div>
    </div>
  </section>
  <section>
    <div class="container mx-auto py-20">
      <div class="flex justify-center">
        <div class="text-center font-sans w-[511px]">
          <h1 class="font-bold text-4xl">Practice Advice</h1>
          <p class="text-xl my-10">
            Problems trying to resolve the conflict between the two major realms
            of Classical physics: Newtonian mechanics
          </p>
        </div>
      </div>
      <div class="flex md:justify-between flex-wrap gap-7 justify-center my-20">
        <LCard />
        <LCard />
        <LCard />
        <LCard />
      </div>
    </div>
  </section>
</template>
<script setup>
import MCard from "./Card/MCard.vue";
import LCard from "./Card/LCard.vue";
</script>
