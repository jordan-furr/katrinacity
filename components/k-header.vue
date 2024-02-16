<template>
    <nav class="flex w-100 flex-auto">
        <div class="flex flex-row align-center space-between ph3 w-100">
            <div class="">
                <h3><NuxtLink class="purple-text no-text-dec" to="/">KATRINACITY</NuxtLink></h3>
            </div>
            <div class="flex flex-row flex-end align-center">
                <p><NuxtLink class="purple-text under-hov" to="/art">art</NuxtLink></p>
                <p><NuxtLink class="purple-text under-hov" to="/work">work</NuxtLink></p>
                <p><NuxtLink class="purple-text under-hov" to="/about">about</NuxtLink></p>
            </div>
        </div>
    </nav>
</template>

<style>
h3{
    margin: 0;
}
nav {
    height: 8%;
}
</style>