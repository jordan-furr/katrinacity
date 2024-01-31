<template>
    <nav>
        <div class="wrapper">
            <div class="title">
                <h1 class = "logo"><NuxtLink class="logo-text" to="/">KATRINACITY</NuxtLink></h1>
            </div>
            <div class="menu">
                <p class="menu-item"><NuxtLink class="menu-text" to="/art">art</NuxtLink></p>
                <p class="menu-item"><NuxtLink class="menu-text" to="/about">about</NuxtLink></p>
                <p class="menu-item"><NuxtLink class="menu-text" to="/work">work</NuxtLink></p>
                <p class="menu-item"><NuxtLink class="menu-text" to="/art">art</NuxtLink></p>
            </div>
        </div>
    </nav>
</template>

<style>
    .title{
        margin-top: -2.6em;
    }
    .logo {
        font-size: 3em;
    }
    .logo-text {
        color: #ff2830;
        text-decoration: none;
    }
    .logo-text:hover {
        color: #ff282fbb;
    }
    .wrapper{ 
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 0;
        background: white;
        width: 25vw;
    }
    .menu{
        display: flex;
        flex-direction: row;
        margin-top: -3.4em;
        height: 3.2em;
        gap: 2em;
    }
    .menu-text{
        color: #ff2830;
        text-decoration: none;
    }
    .menu-text:hover {
        text-decoration: underline;
    }
    nav {
        position: fixed;
        background: white;
        height: 100vh;
    }
</style>
