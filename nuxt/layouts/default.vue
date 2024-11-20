<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="conatainr mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">Nuxt</NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/products" class="btn">Products</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <!-- Output the page content -->

        <div class="container mx-auto p-4">
            <slot/>
        </div>
    </div>
</template>

<style scoped>
.router-link-exact-active {
    color: #12b488;
}
</style>
