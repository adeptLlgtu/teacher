<template>
    <div id="class" class="class">
        <h2>Наш класс</h2>
        <div class="content">
            <Hooper :wheelControl="false" :autoPlay="true" :playSpeed="5000" :itemsToShow="1" :centerMode="true" pagination="true" :vertical="false">
                <Slide>
                    <img class="slide-img" :src="class1" alt="">
                </Slide>
                <Slide>
                    <img class="slide-img" :src="class2" alt="">
                </Slide>
                <Slide>
                    <img class="slide-img" :src="class3" alt="">
                </Slide>
                <hooper-navigation slot="hooper-addons"></hooper-navigation>
                <hooper-pagination slot="hooper-addons"></hooper-pagination>
                <hooper-progress slot="hooper-addons"></hooper-progress>
            </Hooper>
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
    import class1 from '../assets/class1.png'
    import class2 from '../assets/class2.png'
    import class3 from '../assets/class3.png'

    export default {
        name: "Class",
        components:{
            Hooper,
            Slide,
            HooperProgress,
            HooperPagination,
            HooperNavigation
        },
        data() {
            return {
                class1, class2, class3
            }
        }
    }
</script>

