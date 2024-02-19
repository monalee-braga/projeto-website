<template>
  <section class="py-16 px-4 bg-teste">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold mb-8 text-center text-gray-100">
        Depoimentos dos Clientes
      </h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Depoimento 1 -->
        <div class="bg-white rounded-lg shadow-md p-6">
          <div class="flex items-center mb-4">
            <img
              src="../assets/makeup.png"
              alt="Cliente 1"
              class="w-16 h-16 rounded-full"
            />
            <h3 class="text-xl font-bold ml-4">Cliente 1</h3>
          </div>
          <p class="text-gray-600 mb-4">
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua."
          </p>
        </div>
        <!-- Depoimento 2 -->
        <div class="bg-white rounded-lg shadow-md p-6">
          <div class="flex items-center mb-4">
            <img
              src="../assets/makeup.png"
              alt="Cliente 2"
              class="w-16 h-16 rounded-full"
            />
            <h3 class="text-xl font-bold ml-4">Cliente 2</h3>
          </div>
          <p class="text-gray-600 mb-4">
            "Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
            nisi ut aliquip ex ea commodo consequat."
          </p>
        </div>
        <!-- Depoimento 3 -->
        <div class="bg-white rounded-lg shadow-md p-6">
          <div class="flex items-center mb-4">
            <img
              src="../assets/makeup.png"
              alt="Cliente 3"
              class="w-16 h-16 rounded-full"
            />
            <h3 class="text-xl font-bold ml-4">Cliente 3</h3>
          </div>
          <p class="text-gray-600 mb-4">
            "Duis aute irure dolor in reprehenderit in voluptate velit esse
            cillum dolore eu fugiat nulla pariatur."
          </p>
        </div>
        <!-- Depoimento 4 -->
        <div class="bg-white rounded-lg shadow-md p-6">
          <div class="flex items-center mb-4">
            <img
              src="../assets/makeup.png"
              alt="Cliente 4"
              class="w-16 h-16 rounded-full"
            />
            <h3 class="text-xl font-bold ml-4">Cliente 4</h3>
          </div>
          <p class="text-gray-600 mb-4">
            "Excepteur sint occaecat cupidatat non proident, sunt in culpa qui
            officia deserunt mollit anim id est laborum."
          </p>
        </div>
        <!-- Depoimento 5 -->
        <div class="bg-white rounded-lg shadow-md p-6">
          <div class="flex items-center mb-4">
            <img
              src="../assets/makeup.png"
              alt="Cliente 4"
              class="w-16 h-16 rounded-full"
            />
            <h3 class="text-xl font-bold ml-4">Cliente 5</h3>
          </div>
          <p class="text-gray-600 mb-4">
            "Excepteur sint occaecat cupidatat non proident, sunt in culpa qui
            officia deserunt mollit anim id est laborum."
          </p>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'Clients',
};
</script>
