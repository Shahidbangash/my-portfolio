<template>
<div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <service-card />
</div>
</template>

<script>
// @ is an alias to /src
import ServiceCard from "@/components/service-card.vue";

export default {

    components: {
        ServiceCard
    }
};
</script>
