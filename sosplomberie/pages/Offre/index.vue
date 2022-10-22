<template>
    <div>
        <Navbar/>
<Offre/>
<Footer/>
    </div>

    
</template>

<script>
import Offre from "./offre.vue";
import Navbar from "../../components/navbar.vue";
import Footer from "../../components/Footer.vue";
export default {
    components: { Offre, Navbar, Footer }
}
</script>

<style>

</style>
