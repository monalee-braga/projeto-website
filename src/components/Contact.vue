<template>
  <section class="py-16 px-4 bg-white">
    <div class="container mx-auto">
      <h2 class="text-2xl font-bold mb-4">Contato</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Opção 1: E-mail -->
        <div class="bg-white rounded-lg shadow-md p-4 flex items-center">
          <img src="" alt="E-mail" class="w-12 h-12 inline-block mr-4" />
          <div>
            <p class="text-gray-600 mb-4">Entre em contato via E-mail:</p>
            <a
              href="mailto:seuemail@example.com"
              class="text-blue-500 font-bold"
              >seuemail@example.com</a
            >
          </div>
        </div>
        <!-- Opção 2: WhatsApp -->
        <div class="bg-white rounded-lg shadow-md p-4 flex items-center">
          <img src="" alt="WhatsApp" class="w-12 h-12 inline-block mr-4" />
          <div>
            <p class="text-gray-600 mb-4">Entre em contato via WhatsApp:</p>
            <a
              href="https://wa.me/seunumerodetelefone"
              class="text-green-500 font-bold"
              >Seu número de WhatsApp</a
            >
          </div>
        </div>
        <!-- Opção 3: Instagram -->
        <div class="bg-white rounded-lg shadow-md p-4 flex items-center">
          <img src="" alt="Instagram" class="w-12 h-12 inline-block mr-4" />
          <div>
            <p class="text-gray-600 mb-4">Siga-nos no Instagram:</p>
            <a
              href="https://www.instagram.com/seuinstagram"
              class="text-pink-500 font-bold"
              >@seuinstagram</a
            >
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Contact',
};
</script>

<style scoped>
.bg-white {
  background-color: #fff;
}
.text-gray-600 {
  color: #6c757d;
}
.text-3xl {
  font-size: 3rem;
}
.font-bold {
  font-weight: 700;
}
.border-b-4 {
  border-bottom-width: 4px;
}
</style>
