<template>
<div>
    <Navbar/>
<Signup/>
<Footer/>
</div>
    
</template>


<script>
import Signup from "./signup.vue";
import Navbar from "../../components/navbar.vue";
export default {
    components: { Signup, Navbar }
}
</script>

<style>

</style>
