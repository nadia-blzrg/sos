<template>
<section class="bg-white dark:bg-gray-900">
    <div class="flex justify-center min-h-screen">
        <div class="w-full lg:w-1/2 flex flex-col items-center justify-center p-12 bg-no-repeat bg-cover bg-center" style="background-image: url('/signup.jpg');">
           <div class=" h-full w-full ">
          <h1 class="text-white text-3xl mb-3 ">Bienvenu chez</h1>
          <span class="font-extrabold text-3xl mb-3 bg-clip-text text-transparent bg-gray-200  bg-opacity-50
bg-gradient-to-r from-red-700 via-blue-800 to-gray-800"> SOS PLOMBERIE</span>
          <div>
            <p class="text-white "> Contactez votre plombier où que vous soyez </p>
          
          </div>
        </div>
        </div>

        <div class="flex items-center w-full max-w-3xl p-8 mx-auto lg:px-12 lg:w-3/5">
            <div class="w-full">
                <h1 class="text-2xl font-semibold tracking-wider text-gray-800 capitalize dark:text-white">
                    Créer votre compte
                </h1>

                <p class="mt-4 text-gray-500 dark:text-gray-400">
                  Entrer vos informations personnelles et créer votre nouveau compte
                </p>

                <div class="mt-6">
                    <h1 class="text-gray-500 dark:text-gray-300">Selectionner votre type de compte</h1>

                    <div class="mt-3 md:flex md:items-center md:-mx-2">
                        <button class="flex justify-center w-full px-6 py-3 text-white bg-blue-500 rounded-md md:w-auto md:mx-2 focus:outline-none">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                            </svg>

                            <span class="mx-2">
                               Professionnel
                            </span>
                        </button>

                        <button class="flex justify-center w-full px-6 py-3 mt-4 text-blue-500 border border-blue-500 rounded-md md:mt-0 md:w-auto md:mx-2 dark:border-blue-400 dark:text-blue-400 focus:outline-none">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
                            </svg>

                            <span class="mx-2">
                                Particulier
                            </span>
                        </button>
                    </div>
                </div>

                <form class="grid grid-cols-1 gap-6 mt-8 md:grid-cols-2">
                    <div>
                        <label class="block mb-2 text-sm text-gray-600 dark:text-gray-200">Nom</label>
                        <input type="text" placeholder="John" class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-400 bg-white border border-gray-200 rounded-md dark:placeholder-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-700 focus:border-blue-400 dark:focus:border-blue-400 focus:ring-blue-400 focus:outline-none focus:ring focus:ring-opacity-40" />
                    </div>

                    <div>
                        <label class="block mb-2 text-sm text-gray-600 dark:text-gray-200">Prenom</label>
                        <input type="text" placeholder="Snow" class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-400 bg-white border border-gray-200 rounded-md dark:placeholder-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-700 focus:border-blue-400 dark:focus:border-blue-400 focus:ring-blue-400 focus:outline-none focus:ring focus:ring-opacity-40" />
                    </div>

                    <div>
                        <label class="block mb-2 text-sm text-gray-600 dark:text-gray-200">Numéro de téléphone</label>
                        <input type="text" placeholder="XXX-XX-XXXX-XXX" class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-400 bg-white border border-gray-200 rounded-md dark:placeholder-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-700 focus:border-blue-400 dark:focus:border-blue-400 focus:ring-blue-400 focus:outline-none focus:ring focus:ring-opacity-40" />
                    </div>

                    <div>
                        <label class="block mb-2 text-sm text-gray-600 dark:text-gray-200">Adresse email</label>
                        <input type="email" placeholder="johnsnow@example.com" class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-400 bg-white border border-gray-200 rounded-md dark:placeholder-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-700 focus:border-blue-400 dark:focus:border-blue-400 focus:ring-blue-400 focus:outline-none focus:ring focus:ring-opacity-40" />
                    </div>

                    <div>
                        <label class="block mb-2 text-sm text-gray-600 dark:text-gray-200">Mot de passe</label>
                        <input type="password" placeholder="Enter your password" class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-400 bg-white border border-gray-200 rounded-md dark:placeholder-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-700 focus:border-blue-400 dark:focus:border-blue-400 focus:ring-blue-400 focus:outline-none focus:ring focus:ring-opacity-40" />
                    </div>

                    <div>
                        <label class="block mb-2 text-sm text-gray-600 dark:text-gray-200">Confirmer le mot de passe</label>
                        <input type="password" placeholder="Enter your password" class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-400 bg-white border border-gray-200 rounded-md dark:placeholder-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-700 focus:border-blue-400 dark:focus:border-blue-400 focus:ring-blue-400 focus:outline-none focus:ring focus:ring-opacity-40" />
                    </div>
                    <div >
        <label  class="block mb-2 text-sm text-gray-600 dark:text-gray-200">Wilaya</label>
        <select class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-400 bg-white border border-gray-200 rounded-md dark:placeholder-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-700 focus:border-blue-400 dark:focus:border-blue-400 focus:ring-blue-400 focus:outline-none focus:ring focus:ring-opacity-40">
            <option> Alger</option>
            <option>Sétif</option>
            <option>Annaba</option>
            <option>Blida</option>
        </select>
      </div>


                    <button
                        class="flex items-center justify-between w-full px-6 py-3 text-sm tracking-wide text-white capitalize transition-colors duration-300 transform bg-blue-500 rounded-md hover:bg-blue-400 focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-50">
                        <span> S'inscrire</span>

                        <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 rtl:-scale-x-100" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd"
                                d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                                clip-rule="evenodd" />
                        </svg>
                    </button>
                </form>
            </div>
        </div>
    </div>
</section>
</template>

<!--
<template>
<div class="min-h-screen py-40" style="background-image: linear-gradient(115deg, #9F7AEA, #FEE2FE)">
    <div class="container mx-auto">
      <div class="flex flex-col lg:flex-row w-10/12 lg:w-8/12 bg-white rounded-xl mx-auto shadow-lg overflow-hidden">
        <div class="w-full lg:w-1/2 flex flex-col items-center justify-center p-12 bg-no-repeat bg-cover bg-center" style="background-image: url('/client.jpg');">
          <h1 class="text-white text-3xl mb-3">Bienvenu chez</h1>
          <div>
            <p class="text-white"> Contactez votre plombier où que vous soyez <a href="" class="text-purple-500 font-semibold">Learn more</a></p>
          </div>
        </div>
        <div class="w-full lg:w-1/2 py-16 px-12">
          <h2  class="text-3xl mb-4">S'enregistrer</h2>
          <p class="mb-4">
            Créer votre compte en moin d'une minute
          </p>
          <form action="#">
            <div class="grid grid-cols-2 gap-5">
              <input type="text" placeholder="Firstname" class="border border-gray-400 py-1 px-2">
              <input type="text" placeholder="Surname" class="border border-gray-400 py-1 px-2">
            </div>
            <div class="mt-5">
              <input type="text" placeholder="Email" class="border border-gray-400 py-1 px-2 w-full">
            </div>
            <div class="mt-5">
              <input type="password" placeholder="Password" class="border border-gray-400 py-1 px-2 w-full">
            </div>
            <div class="mt-5">
              <input type="password" placeholder="Confirm Password" class="border border-gray-400 py-1 px-2 w-full">
            </div>
            <div class="mt-5">
              <input type="checkbox" class="border border-gray-400">
              <span>
                I accept the <a href="#" class="text-purple-500 font-semibold">Terms of Use</a> &  <a href="#" class="text-purple-500 font-semibold">Privacy Policy</a> 
              </span>
            </div>
            <div class="mt-5">
              <button class="w-full bg-purple-500 py-3 text-center text-white">Enregistrer</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
  </template>
  --->