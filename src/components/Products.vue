<template>
  <section class="py-16 px-4 bg-white">
    <div class="flex justify-center mb-4">
      <h2 class="text-3xl font-bold">Produtos</h2>
    </div>
    <div class="container mx-auto grid grid-cols-1 md:grid-cols-3 gap-8">
      <!-- Card 1 -->
      <div
        class="relative bg-white rounded-lg shadow-md p-6 transform hover:scale-105 transition duration-300"
      >
        <h2 class="text-xl font-bold mb-2">Kit de Maquiagem 1</h2>
        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-800 font-bold">Preço: $XX.XX</p>
      </div>
      <!-- Card 2 -->
      <div
        class="relative bg-white rounded-lg shadow-md p-6 transform hover:scale-105 transition duration-300 z-10"
      >
        <h2 class="text-xl font-bold mb-2">Kit de Maquiagem 2</h2>

        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-800 font-bold">Preço: $XX.XX</p>
      </div>
      <!-- Card 3 -->
      <div
        class="relative bg-white rounded-lg shadow-md p-6 transform hover:scale-105 transition duration-300"
      >
        <h2 class="text-xl font-bold mb-2">Kit de Maquiagem 3</h2>

        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-600 mb-4">Descrição do Kit de Maquiagem 1.</p>
        <p class="text-gray-800 font-bold">Preço: $XX.XX</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Products',
};
</script>
