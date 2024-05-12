<template>
    <nav class="flex w-100 flex-auto">
        <div class="flex flex-row align-center space-between ph3 w-100">
            <div class="w-70">
                <p><NuxtLink class="midblue-text no-text-dec" to="/">DAMIANCITY</NuxtLink></p>
            </div>
            <div class="w-30">
                <div class="mobile-nav flex flex-row flex-start align-center pl4">
                    <p><NuxtLink class="black-text no-text-dec" to="/work">WORK</NuxtLink></p>
                    <p><NuxtLink class="black-text no-text-dec" to="/art">ART</NuxtLink></p>
                    <p><NuxtLink class="black-text no-text-dec" to="/about">INFORMATION</NuxtLink></p>
                </div>
            </div>
        </div>
    </nav>
</template>

<style>
h3{
    margin: 0;
}
nav {
    height: 7%;
}
</style>