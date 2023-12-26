<template>
  <section class="py-24" id="Contact">
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
      <CardContact :icon="icon[1]" />
      <CardContact :icon="icon[0]" />
      <CardContact :icon="icon[2]" />
    </div>
  </section>
</template>
<script>
import CardContact from "./Card/CardContact.vue";
import C1 from "@/assets/icon/contact/contact1.svg";
import C2 from "@/assets/icon/contact/contact2.svg";
import C3 from "../assets/icon/contact/contact3.svg";

export default {
  data() {
    return {
      icon: [C1, C2, C3],
    };
  },
  components: {
    CardContact,
  },
};
</script>
