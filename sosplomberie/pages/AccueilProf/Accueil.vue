<template>
        <div class=" bg-gradient-to-r from-blue-900 to-blue-400">
        <!-- Header -->
        <div class=" w-full flex items-center justify-between h-14 text-white z-10">
        <div class="flex items-center justify-start md:justify-center pl-3 w-14 md:w-64 h-14 bg-red-800 dark:bg-gray-800 border-none">
          <img class="w-7 h-7 md:w-10 md:h-10 mr-2 rounded-md overflow-hidden" src="/logo.jpg" />
          <span class="hidden md:block">SOS PLOMBERIE</span>
        </div>
        <div class="flex justify-between items-center h-14 bg-red-800 dark:bg-gray-800 header-right">
          <ul class="flex items-center">
            <li>

                <button
  type="button"
  role="switch"
  aria-checked="false"
  class="relative inline-flex h-5 w-8 shrink-0 cursor-pointer appearance-none rounded-full border-2 border-transparent bg-gray-200 transition focus:outline-none focus:ring focus:ring-blue-200">
  <span
    aria-hidden="true"
    class="pointer-events-none inline-block h-4 w-4 translate-x-0 rounded-full bg-white transition will-change-transform"></span>
</button>


            </li>
           
            <li>
              <a href="#" class="flex items-center mr-4 hover:text-blue-100">
                <span class="inline-flex mr-1">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 16l4-4m0 0l-4-4m4 4H7m6 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h4a3 3 0 013 3v1"></path></svg>
                </span>
                Déconnexion
              </a>
            </li>
          </ul>
        </div>
      </div>
      <!-- ./Header -->
    
      <!-- Sidebar -->
      <div class= "fixed flex flex-col top-14 left-0 w-14 hover:w-64 md:w-64 bg-red-900 dark:bg-gray-900 h-full
       text-white transition-all duration-300 border-none z-10 sidebar">
        <div class="overflow-y-auto overflow-x-hidden flex flex-col justify-between flex-grow">
          <ul class="flex flex-col py-4 space-y-1">
            <li class="px-5 hidden md:block">
              <div class="flex flex-row items-center h-8">
                <div class="text-sm font-light tracking-wide text-gray-400 uppercase">Main</div>
              </div>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-red-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-red-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path></svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Fournisseurss</span>
              </a>
            </li>
            
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-red-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-red-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path></svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Professionnels</span>
              </a>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-blue-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-red-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 13V6a2 2 0 00-2-2H6a2 2 0 00-2 2v7m16 0v5a2 2 0 01-2 2H6a2 2 0 01-2-2v-5m16 0h-2.586a1 1 0 00-.707.293l-2.414 2.414a1 1 0 01-.707.293h-3.172a1 1 0 01-.707-.293l-2.414-2.414A1 1 0 006.586 13H4"></path></svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Annonces</span>
                <span class="hidden md:block px-2 py-0.5 ml-auto text-xs font-medium tracking-wide text-blue-500 bg-indigo-50 rounded-full">New</span>
              </a>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-red-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-red-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"></path></svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Forum</span>
              </a>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-red-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-red-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"></path></svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Codes d'erreurs</span>
                <span class="hidden md:block px-2 py-0.5 ml-auto text-xs font-medium tracking-wide text-red-500 bg-red-50 rounded-full">1.2k</span>
              </a>
            </li>
            <li class="px-5 hidden md:block">
              <div class="flex flex-row items-center mt-5 h-8">
                <div class="text-sm font-light tracking-wide text-gray-400 uppercase">Settings</div>
              </div>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-red-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-red-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path></svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Profile</span>
              </a>
            </li>

          </ul>
          <p class="mb-14 px-5 py-3 hidden md:block text-center text-xs">Copyright @2021</p>
        </div>
      </div>
      <!-- ./Sidebar -->


      <div class=" relative mt-10 lg:mt-0 lg:col-start-1 lg:row-start-1 items-right ">
        <div class="grid grid-cols-1 gap-6 mx-auto lg:grid-cols-2">
            <div class="p-6">
                <NuxtLink to="#">
                <img class=" object-cover object-center w-full mb-8 lg:h-48 md:h-36 rounded-xl" src="/fournisseurs.jfif" alt="blog">
                <div class="inline-flex justify-between w-full">
                    <h1 class="mb-8 text-xl font-semibold leading-none tracking-tighter text-neutral-600">Fournisseurs</h1>
                </div>
                </NuxtLink>
            </div>
            <div class="p-6">
                <NuxtLink to="#">
                <img class="object-cover object-center w-full mb-8 lg:h-48 md:h-36 rounded-xl" src="/professionnels.jpg" alt="blog">
                <div class="inline-flex justify-between w-full">
                    <h1 class="mb-8 text-xl font-semibold leading-none tracking-tighter text-neutral-600">Professionnels</h1>
                    
                </div>
                </NuxtLink>
            </div>
            <div class="p-6">
                <NuxtLink to="#">
                <img class="object-cover object-center w-full mb-8 lg:h-48 md:h-36 rounded-xl" src="/annones.jpg" alt="blog">
                <div class="inline-flex justify-between w-full">
                    <h1 class="mb-8 text-xl font-semibold leading-none tracking-tighter text-neutral-600">Annonces</h1>
                </div>
                </NuxtLink>
            </div>
            <div class="p-6">
                <NuxtLink to="#">
                <img class="object-cover object-center w-full mb-8 lg:h-48 md:h-36 rounded-xl" src="/code-err.jfif" alt="blog">
                <div class="inline-flex justify-between w-full">
                    <h1 class="mb-8 text-xl font-semibold leading-none tracking-tighter text-neutral-600">Codes d'erreurs</h1>
                </div>
                </NuxtLink>
            </div>
        </div>
    </div>
     </div>

      <!-- ./Sidebar -->
</template>

<script>
export default {

}
</script>

<style>

</style>




