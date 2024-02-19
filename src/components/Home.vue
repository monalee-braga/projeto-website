<template>
  <section class="py-16 px-4 bg-blush-900">
    <div class="container mx-auto flex flex-col lg:flex-row items-center">
      <!-- Texto e botão -->
      <div class="lg:w-1/2 lg:mr-8">
        <h2 class="text-3xl font-bold mb-4">Seja bem-vindo!</h2>
        <p class="text-lg mb-6">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
          auctor quam sit amet magna dignissim, et aliquet enim mattis.
        </p>
        <button
          class="bg-blush-500 hover:bg-blush-600 text-white font-bold py-2 px-4 rounded"
        >
          Saiba mais
        </button>
      </div>
      <!-- Imagem -->
      <div class="lg:w-1/2 mt-8 lg:mt-0 flex items-center justify-center">
        <img src="../assets/makeup.png" alt="Imagem" class="w-9/12 mx-auto" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Home',
};
</script>
