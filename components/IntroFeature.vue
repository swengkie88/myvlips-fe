<!-- Please remove this file from your project -->
<template>
  <section
    class="bg-[#EBF5FF] py-20"
  >
    <div class="main-container">
      <div class="flex flex-row py-2">
        <div class="basis-[40%]">
          <div class="pr-32">
            <h2 class="text-3xl font-bold text-gray-600 w-72">
              Fitur spesial v-lips hanya untuk anda
            </h2>
            <p class="mt-2 text-lg">
              Kami menyediakan fitur spesial yang disiapkan hanya untuk anda
            </p>
          </div>
        </div>
        <div class="basis-[60%] grid grid-cols-2 grid-rows-2 gap-4">
          <CardFeature title="Ruang Karya">
            Wadah yang tepat untuk anda menunjukkan
            hasil kerja keras yang telah anda lakukan.
          </CardFeature>
          <CardFeature title="Ruang Baca">
            Temukan bacaan seputar IPS hanya disini,
            baca sepuasnya!
          </CardFeature>
          <CardFeature title="Ruang Diskusi">
            Keluarkan isi pikiran anda dan mari diskusikan
            bersama untuk mencari sudut pandang baru!
          </CardFeature>
          <CardFeature title="Ruang Aspirasi">
            Suarakan aspirasi anda di ruang ini.
            Ruang Aspirasi sahabat aspirasi anda
          </CardFeature>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'IntroFeature'
}
</script>
