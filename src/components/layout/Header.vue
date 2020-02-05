<template>
    <header class="header">
        <h1>TodoList</h1>
        <div>
            <router-link to="/">Home</router-link>
            <router-link to='/about'><a>About</a></router-link>
        </div>
        <div class="theme-button">Change Theme</div>
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>
    .header {
        background: #333;
        color: #fff;
        text-align: center;
        padding: 10px;
    }
    .header a {
        color: #fff;
        padding-right: 5px;
        text-decoration: none;
    }
    .theme-button {
        color: rgb(140,140,140);
        font-size: 12px;
    }
</style>