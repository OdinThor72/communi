<template>
<nav id="mainNav" class="flex items-center justify-between flex-wrap bg-transparent p-6">
  <div class="flex items-center flex-shrink-0 text-white mr-6">
    <Logo class="text-white opacity-5" /><span class="font-semibold font-uppercase text-xl tracking-tight ml-3">Communi</span>
  </div>
  <div class="block lg:hidden">
    <button class="flex items-center px-3 py-2 border rounded text-pink-200 border-pink-400 hover:text-white hover:border-white">
      <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
    </button>
  </div>
  <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
    <div class="text-sm lg:flex-grow">
      <a href="#CaMangeQuoiEnHiver" class="block mt-4 lg:inline-block lg:mt-0 text-pink-200 hover:text-white mr-4">
        Ça mange quoi en hiver?
      </a>
      <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-pink-200 hover:text-white mr-4">
        Examples
      </a>
      <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-pink-200 hover:text-white">
        Blog
      </a>
    </div>
    <div class="align-right">
      <a href="#" class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-pink-500 hover:bg-white mt-4 lg:mt-0">Download</a>
    </div>
  </div>
</nav>
</template>

<style>
#mainNav {
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>