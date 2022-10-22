<template>
    <div>

    <Navbar/>
    <Service/>
    <Footer/>
</div>
</template>

<script>
import Service from "./service.vue";
import Navbar from "../../components/navbar.vue";
export default {
    components: { Service, Navbar }
}
</script>

<style>

</style>
