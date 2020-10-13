<template>
    <header class="MainHeader bg-red-500">
        <div class="MainHeader__container max-w-4xl mx-auto py-6 bg-green-300 flex">

            <img src="@/assets/image.svg" alt="Digits logo">

            <nav class="ml-20 text-blue-dark">
                <router-link to="/">Accueil</router-link>
                <router-link to="/about">A propos</router-link>
            </nav>

            <div class="contact ml-auto">
                <a href="#">+00 123 456 789</a>
                <a href="#" class="bg-blue-button">Contact Us</a>
            </div>

        </div>
    </header>
</template>