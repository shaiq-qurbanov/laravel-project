<template>
    <div id="nav">
        <router-link to="/">Home</router-link>
        |
        <router-link to="/Test">Test</router-link>
    </div>

    <router-view></router-view>
</template>

<script>
export default {
    name: "Welcome"
}
</script>

<style scoped>
#nav {
    padding: 20px;
}
#nav a{
    font-weight: bold;
    color: wheat;
    text-decoration: none;
    padding: 4px;
    border-radius: 4px;
    background: crimson;
}
#nav a.router-link-exact--active {
    color: #718096;


}


</style>
