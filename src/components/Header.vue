<template>
    <div class="header">
        <div class="content">
            <div class="header-title">
                <img :src="logo" alt="">
                <div class="header-title__text">
                    <h2>Сайт учителя начальных классов</h2>
                    <h3>Спесивцевой Инны Анатольвены</h3>
                </div>
            </div>
            <div class="header-links">
                <a href="#about">Об учителе</a>
                <a href="#class">Наш класс</a>
                <a href="#portfolio">Портфолио</a>
            </div>
        </div>
    </div>
</template>

<script>
    import logo from '../assets/logo.svg'
    export default {
        name: "Header",
        data() {
            return{
                logo
            }
        }
    }
</script>

<style scoped>

</style>