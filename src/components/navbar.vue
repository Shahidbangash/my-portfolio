<template>
<nav class="navbar navbar-expand-lg navbar-light bg-primary justify-content-between">

    <a class="navbar-brand" href="#">Navbar</a>

    <div class="collapse navbar-collapse" id="">
        <ul class="navbar-nav">
            <li class="nav-item active">
                <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    Dropdown
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <a class="dropdown-item" href="#">Action</a>
                    <a class="dropdown-item" href="#">Another action</a>
                    <a class="dropdown-item" href="#">Something else here</a>
                </div>
            </li>
            <li class="nav-item">
                <a class="nav-link disabled" href="#">Disabled</a>
            </li>
        </ul>
    </div>

    <div>
        <form class="collapse navbar-collapse form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
        </form>
    </div>

    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="ml-auto justify-content-end navbar-toggler-icon"></span>
    </button>

</nav>
</template>

<script>
export default {
    name: "Navbar"
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
