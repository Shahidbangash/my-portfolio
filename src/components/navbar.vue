<template>
<div id="nav" class="Navbar">
    <router-link to="/" class=" nav-link">Home</router-link>
    <router-link to="/about" class=" nav-link">About</router-link>
    <router-link to="/contact" class=" nav-link">Contact</router-link>
    <router-link to="/Pricing" class=" nav-link">Pricing</router-link>
    <router-link to="/services" class=" nav-link">Services</router-link>
</div>
</template>

<script>
export default {
    components: {
        Navbar
    }
};
</script>

<style lang="scss">
#nav {
    background-color: #bdcbc4;

    a {
        font-weight: bold;
        color: #000000;

        &.router-link-exact-active {
            color: #ec1111;
        }
    }

    .nav-link {
        display: inline-block;
        padding: 15px 20px;
        border-left: 1px solid;
    }
}
</style>
