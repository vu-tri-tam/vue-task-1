<template>
<div class="home-container">
    <div class="home-box ">
        <headerVue/>
        <Banner/>
       
    </div>
    <Globe/>
        <Advantages/>
        <Team/>
        <Blog/>
        <ContactForm/>
        <Advice/>
        <Footer/>
</div>

 
</template>
<script setup>
import headerVue from './headerComponent/header.vue';
import Banner from './bannerComponent/banner.vue';
import Advantages from './advantagesComponent/advantages.vue';
import Team from './teamComponent/team.vue';
import Blog from './blogComponent/blog.vue';
import ContactForm from './contactFormComponent/contactForm.vue';
import Advice from './adviceComponent/advice.vue';
import Footer from './footerComponent/footer.vue';
import Globe from './globeComponent/globe.vue';


</script>
<script>

export default {

  data(){
      return {
          image: '/images/image 11.png'
      }
  }

}
</script>
<style lang="scss" scoped>
.home-container{
    position: relative;
    // max-width: 1902px;
    width: 100%;
    // height: 6747px;

    /* Dark Pri */

    background: #020A12;
    .home-box{
        
        width: 100%;
        height: auto;
        background:  url('/images/image 11.png');
        background-repeat: no-repeat;
        background-size: 100% 100%;
    }
    .banner-main{
        .banner-main-images{
            position: absolute;
            background-repeat: no-repeat!important;
            // background-size: 100%!important;
            width: 100%;
            max-width: 1920px;
            height: 815px;
            left: 0px;
            top: 986px;
            background:  url('/images/bg 5.png');
            // opacity: 0.6;
        }
         .banner-main-images::after{
            background: #020A12;
            // opacity: 0.6;
        }
    }
}
@media  (max-width: 992px){
    
    .home-container{
   
    .home-box{
        
        width: 100%;
        height: auto;
        background:  url('/images/image 11.png');
        background-repeat: no-repeat;
        background-size: 100% 36%!important;
    }
}
}
</style>