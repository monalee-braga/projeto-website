<template>
  <div class="relative bg-white">
    <div class="max-w-full mx-auto px-4 sm:px-6">
      <div
        class="flex justify-between items-center border-gray-100 py-6 md:justify-start md:space-x-10"
      >
        <div class="flex justify-start lg:w-0 lg:flex-1">
          <a href="#">
            <span class="sr-only">Landing Page</span>

            <img class="h-8 w-auto sm:h-10" src="../assets/logo.png" alt="" />
          </a>
        </div>
        <div class="-mr-2 -my-2 md:hidden">
          <button
            type="button"
            class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-blush"
            @click="isMenuOpen = !isMenuOpen"
          >
            <span class="sr-only">Open menu</span>
            <img class="h-6 w-6" src="../assets/menu.svg" alt="" />
          </button>
        </div>
        <nav class="hidden md:flex space-x-10">
          <a
            href="#"
            class="text-base font-medium text-gray-500 hover:text-gray-900"
          >
            Home
          </a>
          <a
            href="#"
            class="text-base font-medium text-gray-500 hover:text-gray-900"
          >
            About Us
          </a>
          <a
            href="#"
            class="text-base font-medium text-gray-500 hover:text-gray-900"
          >
            Products
          </a>
          <a
            href="#"
            class="text-base font-medium text-gray-500 hover:text-gray-900"
          >
            Contact
          </a>
        </nav>
      </div>
    </div>

    <div
      v-bind:class="{
        'opacity-100 scale-100 transition ease-out duration-200 absolute top-0 inset-x-0 p-2 transition transform origin-top-right md:hidden':
          isMenuOpen,

        'opacity-0 scale-95 absolute top-0 inset-x-0 p-2 transition transform origin-top-right md:hidden':
          !isMenuOpen,
      }"
    >
      <div
        class="rounded-lg shadow-lg ring-1 ring-black ring-opacity-5 bg-white divide-y-2 divide-gray-50"
      >
        <div class="pt-5 pb-6 px-5">
          <div class="flex items-center justify-between">
            <div>
              <img class="h-8 w-auto" src="../assets/logo.png" alt="" />
            </div>
            <div class="-mr-2">
              <button
                type="button"
                class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-400 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-blush-500"
                @click="isMenuOpen = !isMenuOpen"
              >
                <span class="sr-only">Close menu</span>
                <img
                  class="h-6 w-6 text-gray-100"
                  src="../assets/close.svg"
                  alt=""
                />
              </button>
            </div>
          </div>
        </div>

        <div className="py-6 px-5 space-y-6">
          <div className="grid grid-cols-2 gap-y-4 gap-x-8">
            <a
              href="#"
              className="text-base font-medium text-gray-900 hover:text-gray-700"
            >
              Home
            </a>
            <a
              href="#"
              className="text-base font-medium text-gray-900 hover:text-gray-700"
            >
              About Us
            </a>
            <a
              href="#"
              className="text-base font-medium text-gray-900 hover:text-gray-700"
            >
              Products
            </a>
            <a
              href="#"
              className="text-base font-medium text-gray-900 hover:text-gray-700"
            >
              Contact
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data() {
    return {
      isMenuOpen: false,
    };
  },
  methods: {},
};
</script>
