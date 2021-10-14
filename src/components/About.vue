<template>
    <div id="about" class="about">
        <div class="content">
            <div class="about-top">
                <img :src="teacher" alt="">
                <div class="about-top__text">
                    <h4>Спесивцева Инна Анатольевна</h4>
                    <p class="sub-title">Учитель начальных классов</p>
                    <p class="sub-school">МБОУ СШ с. Становое</p>
                </div>
            </div>
            <div class="life-style">
                <p>"За весь свой немалый стаж работы - 33 года, я обучила большое количество детей, которые выросли замечтаельными людьми: работниками культуры, спорта, программистами, педагогами, историками, юристами и многими-многими другими. Все они получили мою безмерную любовь, заботу, знания."</p>
            </div>
        </div>
    </div>
</template>

<script>
    import teacher from '../assets/teacher.png'
    export default {
        name: "About",
        data(){
            return{
                teacher
            }
        }
    }
</script>

