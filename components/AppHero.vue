<template>
  <section class="h-[500px]">
    <div class="main-container">
      <div class="flex items-center flex-row">
        <div class="flex-1">
          <h2 class="text-5xl font-bold text-gray-700">
            Virtual Laboratorium IPS Pertama di Indonesia
          </h2>
          <p class="text-xl mt-4 w-[26rem] text-gray-500">
            Tempat menyenangkan untuk eksplorasi apapun mengenai Ilmu Pengetahuan Sosial
          </p>
          <div class="mt-4">
            <PrimaryButton>Get Started</PrimaryButton>
            <SecondaryButton>Read Guidebook</SecondaryButton>
          </div>
        </div>
        <div class="flex-1">
          <img class="h-[450px] mx-auto" src="/img-hero.svg" alt="Gambar Hero">
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'AppHero'
}
</script>
