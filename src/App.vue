<template>
  <div id="app">
    <Header></Header>
    <About></About>
    <Class></Class>
    <Portfolio></Portfolio>
    <Footer></Footer>
  </div>
</template>

<script>
  import './assets/styles.scss'
  import './assets/Montserrat/Montserrat.css'
  import Header from "./components/Header";
  import About from "./components/About";
  import Class from "./components/Class";
  import Portfolio from "./components/Portfolio";
  import Footer from "./components/Footer";

  export default {
    components: {Header, About, Class, Portfolio, Footer}
  }
</script>


