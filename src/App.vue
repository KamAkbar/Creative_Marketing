<template>
  <div id="app">
    <div class="container">
      <Header />
      <Intro />
      <About />
      <Cards />
      <Features />
      <Portfolio />
      <Sponsors />
      <Service />
    </div>
      <Strategy />
    <div class="container">
      <Team />
      <Testimonial />
      <Contact />
      <Subscribe />
      <Articles />
    </div>
      <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Intro from './components/Intro.vue'
import About from './components/About.vue'
import Cards from './components/Cards.vue'
import Features from './components/Features.vue'
import Portfolio from './components/Portfolio.vue'
import Sponsors from './components/Sponsors.vue'
import Service from './components/Service.vue'
import Contact from './components/Contact.vue'
import Strategy from './components/Strategy.vue'
import Team from './components/Team.vue'
import Testimonial from './components/Testimonial.vue'
import Subscribe from './components/Subscribe.vue'
import Articles from './components/Articles.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header, Intro, About, Cards, Features, Portfolio, Sponsors, Service, Contact, Strategy, Team, Testimonial,
    Subscribe, Articles, Footer
  }
}
</script>

<style lang="scss">
//Variables
$primary-color: #f07566;
$secondary-color: #ffffff;
$dark-primary-color: #fbd34b;
$dark-secondary-color: #ffffff;
*, #app{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Hind Siliguri', 'Work Sans', sans-serif;
}
.text {
    font-family: 'Work Sans';
    font-size: 16px;
    line-height: 32px;
    color: #333333;
    &_big {
        font-family: 'Work Sans';
        font-size: 20px;
        line-height: 32px;
        color: #333333;
    }
    &_grey {
        font-family: 'Work Sans';
        font-size: 16px;
        line-height: 32px;
        color: rgba(51, 51, 51, 0.496405);
    }
    &_small {
        font-family: 'Work Sans';
        font-size: 14px;
        line-height: 24px;
        color: rgba(51, 51, 51, 0.496405);
    }
}
//Default Styling
h1 {
    font-family: 'Hind Siliguri';
    font-weight: bold;
    font-size: 72px;
    line-height: 80px;
    letter-spacing: -1px;
    color: #333333;
}
h2 {
    font-family: 'Hind Siliguri';
    font-weight: bold;
    font-size: 56px;
    line-height: 64px;
    letter-spacing: -1px;
    color: #333333;
}
h3 {
    font-family: 'Hind Siliguri';
    font-weight: bold;
    font-size: 40px;
    line-height: 48px;
    letter-spacing: -1px;
    color: #333333;
}
h4 {
    font-family: 'Hind Siliguri';
    font-weight: bold;
    font-size: 24px;
    line-height: 32px;
    color: #333333;
}
h5 {
    font-family: 'Hind Siliguri';
    font-weight: bold;
    font-size: 16px;
    line-height: 32px;
    letter-spacing: 1px;
    text-transform: uppercase;
    color: #f07566;
}
label {
    font-family: 'Arimo';
    font-weight: bold;
    font-size: 12px;
    line-height: 14px;
    text-transform: uppercase;
    color: #333333;
}

//Buttons
.btn{
    padding: 11px 40px!important;
    font-weight: bold;
    font-size: 16px;
    line-height: 26px;
    text-align: center;
    letter-spacing: 1px;
    text-transform: uppercase;
    border-radius: 6px;
    &_primary{
        color: $secondary-color!important;
        border: 1px solid $primary-color!important;
        background-color: $primary-color!important;
    }
    &_secondary{
        color: $primary-color!important;
        border: 1px solid $primary-color!important;
        background-color: $secondary-color!important;
    }
    &_darkp{
        color: #000000;
        border: 1px solid $primary-color!important;
        background-color: $dark-primary-color!important;
    }
}

//FONTS
@import url('https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;400;500;600;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;400;500;600;700&family=Work+Sans:wght@100;200;300;400;500;600&display=swap');
</style>
