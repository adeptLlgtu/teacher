<template>
    <div id="portfolio" class="portfolio">
        <div class="content">
            <h2>Портфолио учителя</h2>
            <div class="content">
                <Hooper :wheelControl="false" :autoPlay="true" :playSpeed="5000" :itemsToShow="1" :centerMode="true" pagination="true" :vertical="false">
                    <Slide>
                        <img class="slide-img" :src="portf1" alt="">
                    </Slide>
                    <Slide>
                        <img class="slide-img" :src="portf2" alt="">
                    </Slide>
                    <Slide>
                        <img class="slide-img" :src="portf3" alt="">
                    </Slide>
                    <hooper-navigation slot="hooper-addons"></hooper-navigation>
                    <hooper-pagination slot="hooper-addons"></hooper-pagination>
                    <hooper-progress slot="hooper-addons"></hooper-progress>
                </Hooper>
            </div>
        </div>

    </div>
</template>

<script>
    import {
        Hooper,
        Slide,
        Progress as HooperProgress,
        Pagination as HooperPagination,
        Navigation as HooperNavigation
    } from 'hooper';
    import 'hooper/dist/hooper.css';
    import portf1 from '../assets/portf1.png'
    import portf2 from '../assets/portf2.png'
    import portf3 from '../assets/portf3.png'
    export default {
        name: "Portfolio",
        components:{
            Hooper,
            Slide,
            HooperProgress,
            HooperPagination,
            HooperNavigation
        },
        data() {
            return {
                portf1, portf2, portf3
            }
        }
    }
</script>

<style scoped>

</style>