<template>
  <section class="px-10 md:px-0 bg-neutral-50">
    <div class="container mx-auto py-20">
      <div class="flex justify-center">
        <div class="text-center font-sans w-[600px]">
          <h1 class="font-bold text-4xl">WHY CHOOSE US</h1>
          <p class="text-xl my-10">
            Problems trying to resolve the conflict between the two major realms
            of Classical physics: Newtonian mechanics
          </p>
        </div>
      </div>
      <div class="flex md:justify-between flex-wrap gap-7 justify-center my-20">
        <MCard :name="nama[0]" :icon="icon[0]" :sub="sub[0]" />
        <MCard :name="nama[1]" :icon="icon[1]" :sub="sub[1]" />
        <MCard :name="nama[2]" :icon="icon[2]" :sub="sub[2]" />
        <MCard :name="nama[3]" :icon="icon[3]" :sub="sub[3]" />
      </div>
    </div>
  </section>
  <section>
    <div class="container mx-auto py-20">
      <div class="flex justify-center">
        <div class="text-center font-sans w-[600px]">
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
<script>
import MCard from "./Card/MCard.vue";
import LCard from "./Card/LCard.vue";
import award from "@/assets/icon/features/award-app.svg";
import box from "@/assets/icon/features/bx-stats-app.svg";
import users from "@/assets/icon/features/users-line.svg";
import tool from "@/assets/icon/catalog/tool-box.svg";

export default {
  data() {
    return {
      nama: ["3K", "45", "12+", "1.5K"],
      icon: [award, box, users, tool],
      sub: ["CASES DONE", "HAPPY CUSTOMERS", "AWARD WINNING", "CASES DONE"],
    };
  },
  components: {
    MCard,
    LCard,
  },
};
</script>
