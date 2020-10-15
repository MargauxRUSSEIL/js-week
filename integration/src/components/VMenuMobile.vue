<template>
    <div class="MenuMobile absolute w-full bg-white">
        <nav class="flex flex-col justify-around items-center h-full">
            <router-link class="link" to="/">Accueil</router-link>
            <a class="link" href="#">Articles</a>
            <a class="link" href="#">Portfolio</a>
            <router-link class="link" to="/about">À propos</router-link>
        </nav>
    </div>
</template>

<style lang="postcss" scoped>
.MenuMobile {
    top: 72px;
    height: calc(100vh - 72px) ;
    padding-top: 10vh ;
    padding-bottom: 20vh ;
}

.link {
    @apply mr-0 ml-0 font-bold ;
    text-transform: uppercase ;
    font-size: 20px ;
}
</style>