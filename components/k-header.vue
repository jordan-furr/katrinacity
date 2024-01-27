<template>
    <div class="wrapper">
        <div class="title">
            <h1 class="logo">KATRINACITY</h1>
        </div>
        <div class="nav">
            <div class="menu">
                <Nuxtlink to="/art">art</Nuxtlink>
                <Nuxtlink to="/about">about</Nuxtlink>
            </div>
        </div>
    </div>
</template>


<style>
.logo:hover {
    color: white;
}
.wrapper{ 
    background-color: #ff2830;
    display: flex;
    align-items: center;
}
.menu{
    color: white;
    text-decoration: none;
}
</style>