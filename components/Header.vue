<template>
    <header class="header">
        <ul class="navbar-items">
            <li>
                <nuxt-link to="/">home</nuxt-link>
            </li>
            <li>
                 <nuxt-link to="/users">users</nuxt-link>
            </li>
        </ul>
        </header>
</template>
<style scoped>
    .header{
        width: 100%;
        height: 60px;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #c3c3c3;
        padding:0;
    }
    .navbar-items{
        list-style: none;
        font-size: 18px;
        padding: 0;
        margin: 0;
        display: flex;
        justify-content: space-around;
        align-items: center;
        width: 20%;
    }
    .navbar-items a{
        text-decoration: none;
        font-size:20px;
    }
</style>
