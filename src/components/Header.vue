<template>
    <div id="nav">
        <router-link to="/">Home Page</router-link> |
        <router-link to="/about">About Page</router-link>
    </div>
</template>

<style>
#nav {
    padding: 30px;
}

#nav a {
    font-weight: bold;
    color: #2c3e50;
}

#nav a.router-link-exact-active {
    color: #42b983;
}
</style>