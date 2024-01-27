<template>
    <div class="wrapper">
        <div class="title">
            <h1 class="logo">KATRINACITY</h1>
        </div>
        <div class="menu">
            <p><Nuxtlink to="~/pages/art">art</Nuxtlink></p>
            <p><Nuxtlink to="~/pages/about">about</Nuxtlink></p>
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
    flex-direction: row;
    align-items: center;
}
.title {
    margin-left: 2em;
}
.menu{
    display: flex;
    flex-direction: row;
    text-decoration: none;
}
.menu p {
    padding-left: 2em;
}
.menu p:hover {
    color: white;
}
</style>