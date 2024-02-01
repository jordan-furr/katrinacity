<template>
    <head>
        <title>KATRINACITY | Home</title>
        <meta property="og:image" content="/public/flowers.png">
    </head>
    <nav>
        <div class="wrapper">
            <div class="title">
                <h1 class = "logo"><NuxtLink class="logo-text" to="/">KATRINACITY</NuxtLink></h1>
            </div>
            <div class="menu">
                <p class="menu-item"><NuxtLink class="menu-text" to="/art">art</NuxtLink></p>
                <p class="menu-item"><NuxtLink class="menu-text" to="/about">about</NuxtLink></p>
                <p class="menu-item"><NuxtLink class="menu-text" to="/work">work</NuxtLink></p>
            </div>
        </div>
    </nav>
</template>

<style>
    .title{
        height: 2.8vw;
    }
    .logo-text {
        color: #2877ff;
        text-decoration: none;
    }
    .logo-text:hover {
        text-decoration: wavy;
    }
    .wrapper{ 
        padding-left: 1.4vw;
    }
    .menu{
        display: flex;
        flex-direction: column;
    }
    .menu-item {
        margin: 0;
    }
    .menu-text{
        color: #2877ff;
        text-decoration: none;
    }
    .menu-text:hover {
        text-decoration: underline;
    }
    nav {
        width: 22vw;
        position: fixed;
        background: white;
        height: 120vh;
        background-size: 1.4vw 1.4vw;
        background-image:
            linear-gradient(to right, grey 1px, transparent 1px),
            linear-gradient(to bottom, grey 1px, transparent 1px);
    }
</style>
