<template>
    <nav>
        <div class="flex flex-row align-center ph3">
            <div class="w-80">
                <h3><NuxtLink class="red-text no-text-dec" to="/">KATRINACITY</NuxtLink></h3>
            </div>
            <div class="flex flex-row flex-end align-center w-20">
                <p><NuxtLink class="red-text under-hov" to="/art">art</NuxtLink></p>
                <p><NuxtLink class="red-text under-hov" to="/about">about</NuxtLink></p>
                <p><NuxtLink class="red-text under-hov" to="/work">work</NuxtLink></p>
            </div>
        </div>
    </nav>
</template>

<style>
.purple-text{
    color: var(--purple);
}
nav {
    height: 8%;
}
</style>