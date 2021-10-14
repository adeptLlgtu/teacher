<template>
    <div class="footer">
        <div class="content">
            <div class="footer-title">
                <img :src="logo" alt="">
                <div class="footer-title__text">
                    <h2>Сайт учителя начальных классов</h2>
                    <h3>Спесивцевой Инны Анатольвены</h3>
                </div>
            </div>
            <div class="footer-links">
                <a href="#about">Об учителе</a>
                <a href="#class">Наш класс</a>
                <a href="#portfolio">Портфолио</a>
            </div>
        </div>
        <p class="footer-year">с. Становое, 2021 год</p>
    </div>
</template>

<script>
    import logo from '../assets/logo.svg'
    export default {
        name: "Footer",
        data(){
            return{
                logo
            }
        }
    }
</script>

