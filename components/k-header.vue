<template>
    <nav>
        <div class="wrapper">
            <div class="title">
                <h1 class="logo"><NuxtLink to="/">KATRINACITY</NuxtLink></h1>
            </div>
            <div class="menu">
                <p class="menu-item"><NuxtLink to="/art">art</NuxtLink></p>
                <p class="menu-item"><NuxtLink to="/about">about</NuxtLink></p>
                <p class="menu-item"><NuxtLink to="/work">work</NuxtLink></p>
                <p class="menu-item"><NuxtLink to="/art">art</NuxtLink></p>
            </div>
        </div>
    </nav>
</template>

<style>
    .title{
        margin-top: -3.6em;
    }
    .logo {
        font-size: 4.6em;
    }
    .wrapper{ 
        background-color: #ff2830;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 0;
    }
    .menu{
        display: flex;
        flex-direction: row;
        margin-top: -2em;
        height: 3.2em;
        gap: 2em;
    }
    .menu-item{
        text-decoration: none;
    }
    .menu-item:hover{
        color: white;
    }
</style>
