<template>
    <div>
        <Navbar />
        <section class="home">
            <div class="image">
                <img src="images/profile.png" alt="">
            </div>
            <div class="content">
                <h3>hi, i am Panusbodee Pisutsuwimon</h3>
                <span>Belive the Impossible is Possible.</span>
                <p>I have exprerise from new job harbert and lerning in Bangkok University and find something to learn anything</p>
                <router-link to="/about" class="btn"> about me <i class="fas fa-user"></i> </router-link>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar }
}
</script>

<style>

</style>