<template>
    <div>
        <Navbar />
        <section class="home">
            <div class="image">
                <img src="images/profile.jpg" alt="">
            </div>
            <div class="content">
                <h3>hi, i am {{name}}</h3>
                <span>{{motto}}</span>
                <p>{{content}}</p>
                <router-link to="/about" class="btn"> about me <i class="fas fa-user"></i> </router-link>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar },
    data() {
        return {
            name: 'Natthaphol lapchai',
            motto: 'Live for Tomorrow',
            content: ' I am a student of the Faculty of Engineering. Multimedia and Entertainment 2nd year with skills in graphics, drawing, photography and music.',
        }
}
}
</script>

<style>

</style>