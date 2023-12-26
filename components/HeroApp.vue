<template>
  <section>
    <header class="header">
      <AppHeader />
      <div class="container mx-auto mt-28">
        <div class="text-center md:text-left font-sans">
          <h1 class="font-bold text-4xl md:text-6xl md:w-[509px]">
            EMPOWER YOUR BUSINESS
          </h1>
          <p class="text-xl my-10 md:w-[500px]">
            We know how large objects will act, but things on a small scale just
            do not act that way.
          </p>
        </div>
        <div
          class="flex flex-wrap justify-center md:justify-start gap-9 md:gap-2"
        >
          <button
            class="px-9 py-2.5 bg-amber-500 text-white font-bold rounded-full"
          >
            Get Quote Now
          </button>
          <button
            class="box-border px-9 py-2.5 border text-cyan-600 border-cyan-600 rounded-full"
          >
            Learn More
          </button>
        </div>
      </div>
    </header>
    <div class="container mx-auto px-10 md:px-0">
      <div
        class="Card-items flex md:justify-between justify-center gap-7 flex-wrap md:flex-nowrap -mt-20"
      >
        <SCard :name="nama[0]" :icon="Icons[2]" />
        <SCard :name="nama[1]" :icon="Icons[1]" />
        <SCard :name="nama[2]" :icon="Icons[0]" />
      </div>
    </div>
  </section>
</template>
<style scoped>
header {
  background-image: url("../assets/img/cover.png");
  height: 793px;
}
</style>
<script>
import SCard from "./Card/SCard.vue";
import notebook from "@/assets/icon/catalog/notebook.svg";
import shop from "@/assets/icon/catalog/shop-twotone.svg";
import tool from "@/assets/icon/catalog/tool-box.svg";
export default {
  data() {
    return {
      Icons: [notebook, shop, tool],
      nama: ["Digital Marketing", "National top 50 firms", "Digital Marketing"],
    };
  },
  components: {
    SCard,
  },
};
</script>
