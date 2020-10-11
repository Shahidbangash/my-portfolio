<template>
<div class="container-fluid container-wrapper">

</div>
<navbar />
<router-view />
</template>

<script>
import Navbar from "@/components/Navbar.vue";
export default {
    components: {
        Navbar
    }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap.scss";

#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    // text-align: center;
    color: #2c3e50;
}

.container-wrapper {

    background-color: #F3F3F3;
}

#nav {
    // padding: 30px;

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
        border-left: 2px solid #9c9292;
        width: 140px;
        text-align: center;

        &:last-child {

            border-right: 1px solid #a59b9b;
        }

    }
}
</style>
