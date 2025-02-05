<template>
  <div class="bg-blue-600 h-full md:h-screen rounded-xl ">
    <div class="max-w-2xl text-center mx-auto pt-24">
      <h2 class="block text-2xl font-bold text-white md:text-3xl ">
        Our Offering
      </h2>
      <h3 class="block text-xl font-bold text-gray-50 md:text-2xl">
        Enhance and Pioneer Using Technology Trends
      </h3>
    </div>
    <div class="max-w-7xl grid grid-cols-2 md:grid-cols-6 place-items-center pt-10 mx-auto">
      <div v-for="n in 12" :key="n"
        class="bg-white flex items-center justify-center flex-col w-40 p-5 rounded-xl gap-3 mt-5"
      >
        <img class="object-contain"
          :src="techs[0].logo"
          alt="logo"
        />
        <h3>{{ techs[0].name }}</h3>
      </div>
    </div>
  </div>
</template>

<script setup>
const techs = [
  {
    logo: 'data:image/png;base64,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',
    name: 'Vue js'
  }
]
</script>