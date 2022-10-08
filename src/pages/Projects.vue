<template>
    <div>
        <Navbar />
        <section class="projects">
            <h1 class="heading"> <span>my</span> projects </h1>
            <h3>Song I mosty like in this time</h3>
            <p>เพลงที่ชอบตอนนี้นะคับ</p>
            <div class="box-container">
                <iframe width="950" height="534" src="https://www.youtube.com/embed/ZGUBRuztbBo" title="mindfreakkk ft. Tanskul - Navy Blue (Official Video)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
                    title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; 
                    gyroscope; picture-in-picture" allowfullscreen> 
                </iframe>
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