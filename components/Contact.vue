<template>
  <section class="">
    <div class="container mx-auto flex justify-center">
      <div class="text-center font-sans w-[600px]">
        <h1 class="font-bold text-4xl">Get In Touch</h1>
        <p class="text-xl my-10">
          Problems trying to resolve the conflict between the two major realms
          of Classical physics: Newtonian mechanics
        </p>
      </div>
    </div>
    <div class="card-items flex justify-center flex-wrap gap-8 md:gap-0">
      <CardContact />
      <CardContact />
      <CardContact />
    </div>
  </section>
</template>
<script setup>
import CardContact from "./Card/CardContact.vue";
</script>
