<script setup>
import {
  TheHero,
  PopularProducts,
  SuperQuality,
  TheServices,
  SpecialOffer,
  CustomerReviews,
  TheSubscribe,
  TheFooter,
} from "@/sections";

import TheNav from "@/components/TheNav.vue";
</script>

<template>
  <main class="relative overflow-hidden">
    <TheNav />
    <section id="home" class="padding-b">
      <TheHero />
    </section>
    <section id="products" class="padding max-sm:mt-12">
      <PopularProducts />
    </section>
    <section id="about-us" class="padding">
      <SuperQuality />
    </section>
    <section class="padding-x py-10">
      <TheServices />
    </section>
    <section class="padding">
      <SpecialOffer />
    </section>
    <section class="padding bg-pale-blue">
      <CustomerReviews />
    </section>
    <section id="contact-us" class="padding-x w-full py-16 sm:py-32">
      <TheSubscribe />
    </section>
    <footer class="padding-x padding-t bg-black pb-8">
      <TheFooter />
    </footer>
  </main>
</template>
