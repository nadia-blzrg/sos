<template>
    <div>
    
    <nav class=" bg-red-700  relative">
<div class="container flex justify-between font-semibold items-center mx-auto py-4">
<NuxtLink 
to="/"
class="flex items-center font-semibold text-black text-m uppercase italic">
<img 
src="/logo.jpg"
alt="logo sos"
class="h-10 nr-4"
/>SOS PLOMBERIE
</NuxtLink>

<ul class="md:flex items-center space-x-3 hidden">
    <li >
        <NuxtLink to="/" class="inline-block px-3 py-2 text-sm text-black rounded-full
   hover:bg-slate-200 transition-all duration-300 font-semibold">
   ACCUEIL
</NuxtLink>
    </li>
    <li >
        <NuxtLink to="/Service"  class="inline-block px-3 py-2 text-sm text-black rounded-full
   hover:bg-slate-200 transition-all duration-300 font-semibold">
   SERVICE
   </NuxtLink>
    </li>
    <li >
        <NuxtLink to="/Offre" class="inline-block px-3 py-2 text-sm text-black rounded-full
   hover:bg-slate-200 transition-all duration-300 font-semibold">   OFFRE
   </NuxtLink>
    </li>
    <li >
        <NuxtLink to="/" class="inline-block px-3 py-2 text-sm text-black rounded-full
   hover:bg-slate-200 transition-all duration-300 font-semibold">   APPLICATION
   </NuxtLink>
    </li>


       <!-- Login Button App -->
<Nuxt-Link to="/Login" class="px-5 py-2 text-sm bg-blue-700 text-white rounded-full hover:bg-blue-600 transition-all 
duration-300 ">
LOGIN
</Nuxt-Link>
</ul>
</div>
    </nav>


    </div>

</template>

<script>

</script>

<style >

</style>
