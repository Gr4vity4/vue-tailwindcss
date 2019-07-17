<template>
  <div class="container max-w-full">
    <nav class="flex items-center justify-between flex-wrap bg-indigo-600 p-6">
      <div class="flex items-center flex-shrink-0 text-white mr-6">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1024px-Vue.js_Logo_2.svg.png" alt="Logo" class="h-8 mr-4">
        <span class="font-semibold text-xl tracking-tight">Tailwind CSS</span>
      </div>
      <div class="block lg:hidden">
        <button class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white">
          <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <title>Menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
        </button>
      </div>
      <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
        <div class="text-sm lg:flex-grow">
            <router-link to="/" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4" active-class="text-white">Home</router-link>
            <router-link to="/navbar" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">Navbar</router-link>
        </div>
      </div>
    </nav>
    <router-view class="pt-8"/>
  </div>
</template>
