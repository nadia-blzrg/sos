
<template>
<div class="bg-white dark:bg-gray-900">
    <div class="flex justify-center h-screen">
        <div class="hidden bg-cover lg:block lg:w-2/3" style="background-image: url(/login.jpg)">
            <div class="flex items-center h-full px-20 bg-gray-900 bg-opacity-40">
                <div>
                    <h2 class="text-4xl font-bold text-white">SOS PLOMBERIE</h2>

                    <p class="max-w-xl mt-3 text-gray-300">
                        Là ou vos problèmes de plomberie seront réglés par une simple application
                        Disponible 24h/24 7j/7
				    </p>
                </div>
            </div>
        </div>

        <div class="flex items-center w-full max-w-md px-6 mx-auto lg:w-2/6">
            <div class="flex-1">
                <div class="text-center">
                    <h2 class="text-4xl font-bold text-center text-gray-700 dark:text-white">Se connecter</h2>

                    <p class="mt-3 text-gray-500 dark:text-gray-300">Connectez-vous pour acceder à votre compte</p>
                </div>

                <div class="mt-8">
                    <form>
                        <div>
                            <label for="email" class="block mb-2 text-sm text-gray-600 dark:text-gray-200">Adresse mail</label>
                            <input type="email" name="email" id="email" placeholder="*****@example.com" class="block w-full px-4 py-2 mt-2 text-gray-700 placeholder-gray-400 bg-white border border-gray-200 rounded-md dark:placeholder-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-700 focus:border-blue-400 dark:focus:border-blue-400 focus:ring-blue-400 focus:outline-none focus:ring focus:ring-opacity-40" />
                        </div>

                        <div class="mt-6">
                            <div class="flex justify-between mb-2">
                                <label for="password" class="text-sm text-gray-600 dark:text-gray-200">Mot de passe</label>
                                <NuxtLink to="/signup" class="text-sm text-gray-400 focus:text-blue-500 hover:text-blue-500 hover:underline">Mot de passe oublié?</NuxtLink>
                            </div>

                            <input type="password" name="password" id="password" placeholder="*****" class="block w-full px-4 py-2 mt-2 text-gray-700 placeholder-gray-400 bg-white border border-gray-200 rounded-md dark:placeholder-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-700 focus:border-blue-400 dark:focus:border-blue-400 focus:ring-blue-400 focus:outline-none focus:ring focus:ring-opacity-40" />
                        </div>

                        <div class="mt-6">
                            <button class="w-full px-4 py-2 tracking-wide text-white transition-colors duration-300 transform bg-blue-500 rounded-md hover:bg-blue-400 focus:outline-none focus:bg-blue-400 focus:ring focus:ring-blue-300 focus:ring-opacity-50">
                                Connexion
                            </button>
                        </div>

                    </form>

                    <p class="mt-6 text-sm text-center text-gray-400">Vous n'avez pas encore de compte? <NuxtLink to="/Signup" class="text-blue-500 focus:outline-none focus:underline hover:underline">Créer votre compte.</NuxtLink>.</p>
                </div>
            </div>
        </div>
    </div>
</div>
</template>