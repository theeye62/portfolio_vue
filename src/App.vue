<script setup>
import Footer from './components/Footer.vue';
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue';
import TimeLine from './components/TimeLine.vue';
import carousel from 'vue-owl-carousel';
</script>

<template>
  <Navbar></Navbar>

  <div class="header-banner">
    <div id="about_me" class="row h-100 w-100">
      <div class="col-lg-6 col-sm-12 col-12 d-flex justify-content-center align-items-center">
        <div class="image-profile">
          <img src="./assets/avatar.jpg" alt="Avatar">
        </div>
      </div>
      <div class="col-lg-6 col-sm-12 col-12 d-flex flex-column justify-content-center align-items-center">
        <div class="first-about">
          <p class="text-mute">About me</p>
          <div class="title-name">
            KORN THANAKORN
          </div>
          <div class="text-position">
            Front End Developer
          </div>
          <span>Hi. My name is Thanakorn Huayyai my nickname is Korn and  I am 26 years old. Professional, currently holds the position of Frontend Web Developer. Creating visually appealing and functional websites that seamlessly blend design and functionality.</span>
        </div>
      </div>
    </div>
  </div>

  <section id="skill" class="white_section">
    <div class="container">
      <div class="title-text">
        My Skill
      </div>
      <div class="row">
        <div class="col-lg-3 col-sm-4 col-6 text-center">
          <div class="skill-box">
            <div class="-image-icon">
              <img src="./assets/icon/html.png" alt="Skill Icon">
            </div>
            <div class="text">
              Html
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-4 col-6 text-center">
          <div class="skill-box">
            <div class="-image-icon">
              <img src="./assets/icon/css.png" alt="Skill Icon">
            </div>
            <div class="text">
              Css
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-4 col-6 text-center">
          <div class="skill-box">
            <div class="-image-icon">
              <img src="./assets/icon/bootstrap.png" alt="Skill Icon">
            </div>
            <div class="text">
              Bootstrap
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-4 col-6 text-center">
          <div class="skill-box">
            <div class="-image-icon">
              <img src="./assets/icon/js.png" alt="Skill Icon">
            </div>
            <div class="text">
              JavaScript
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-4 col-6 text-center">
          <div class="skill-box">
            <div class="-image-icon">
              <img src="./assets/icon/php.png" alt="Skill Icon">
            </div>
            <div class="text">
              Php
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-4 col-6 text-center">
          <div class="skill-box">
            <div class="-image-icon">
              <img src="./assets/icon/laravel.png" alt="Skill Icon">
            </div>
            <div class="text">
              Laravel
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-4 col-6 text-center">
          <div class="skill-box">
            <div class="-image-icon">
              <img src="./assets/icon/git.png" alt="Skill Icon">
            </div>
            <div class="text">
              Git Source Control
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-4 col-6 text-center">
          <div class="skill-box">
            <div class="-image-icon">
              <img src="./assets/icon/figma.png" alt="Skill Icon">
            </div>
            <div class="text">
              Figma (Convert Design to Code)
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-4 col-6 text-center">
          <div class="skill-box">
            <div class="-image-icon">
              <img src="./assets/icon/sql.png" alt="Skill Icon">
            </div>
            <div class="text">
              MySql
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-4 col-6 text-center">
          <div class="skill-box">
            <div class="-image-icon">
              <img src="./assets/icon/vue.png" alt="Skill Icon">
            </div>
            <div class="text">
              Vue.Js (Beginer)
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="experience" class="g_section">
    <div class="container">
      <div class="title-text">
        Experience
      </div>
      <TimeLine></TimeLine>
    </div>
  </section>

  <section id="project" class="white_section">
    <div class="container">
      <div class="title-text">
        My Project
      </div>
      <div class="row">
        <div class="col-lg-6 col-sm-12 col-12">
          <div class="title-project">
            PROJECT 1
          </div>
          <div class="v-name">
            <a href="https://indexgame.in.th/" target="_blank">
              Indexgame Center
            </a>
          </div>
          <span class="v-detail">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Doloremque magni accusantium ducimus blanditiis, vitae repellat totam tenetur ipsam minima nisi provident ea officia magnam. Cum sapiente eos temporibus vel doloribus eius ducimus hic odio reiciendis ipsa sed quia rerum voluptatem, laborum similique facilis ex tempora quaerat esse aut distinctio non.
          </span>
        </div>
        <div class="col-lg-6 col-sm-12 col-12">
          <div class="project-image">
            <a href="https://indexgame.in.th/" target="_blank">
              <img src="./assets/indexgame/logo-indexgame.png" class="w-100" alt="Project Image">
            </a>
          </div>
        </div>
      </div>
      <button class="view-more-btn" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        View Image
      </button>
      <div class="collapse mt-4" id="collapseExample">
        <!-- <carousel :autoplay="true" :nav="false">
          <img src="./assets/indexgame/image1.png" alt="Image Project">
          <img src="./assets/indexgame/image2.png" alt="Image Project">
          <img src="./assets/indexgame/image3.png" alt="Image Project">
        </carousel> -->
        <div class="owl-carousel owl-theme">
          <div class="item">
            <a href="" target="_blank">
              <img src="./assets/indexgame/image1.png" alt="Image Project">
            </a>
          </div>
          <div class="item">
            <a href="" target="_blank">
              <img src="./assets/indexgame/image1.png" alt="Image Project">
            </a>
          </div>
          <div class="item">
            <a href="" target="_blank">
              <img src="./assets/indexgame/image3.png" alt="Image Project">
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <Footer></Footer>
</template>

<script>
  // $('.owl-carousel').owlCarousel({
  //   loop:true,
  //   margin:30,
  //   nav:true,
  //   autoplay:true,
  //   autoplayTimeout:3000,
  //   autoplayHoverPause:true,
  //   responsive:{
  //     0:{
  //         items:2
  //     },
  //     600:{
  //         items:3
  //     },
  //     1000:{
  //         items:5
  //     }
  //   }
  // })
</script>

<style scoped>
  .header-banner{
    background: #F6F8F9;
    background: radial-gradient(circle farthest-corner at right center, #F6F8F9 0%, #E5EBEE 30%, #D7DEE3 57%, #F5F7F9 100%);
    width: 100%;
    height: 100dvh;
  }
  .image-profile{
    width: 500px;
    height: 500px;
    border-radius: 50%;
    overflow: hidden;
  }
  .image-profile img{
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  .first-about{
    width: 100%;
    padding: 20px;
  }
  .first-about .title-name{
    font-size: 3rem;
    font-weight: 700;
    color: #424242;
    text-transform: uppercase;
  }
  .first-about .text-position{
    font-size: 20px;
    font-weight: 700;
    color: #424242;
  }
  .first-about span{
    display: block;
    width: 50%;
    margin: 15px 0px;
    font-size: 14px;
    font-weight: 400;
    color: #808080;
  }
  .title-project{
    font-size: 18px;
    font-weight: 600;
    color: #5bbee3;
    text-transform: uppercase;
  }
  .v-name{
    font-size: 18px;
    font-weight: 600;
    color: #000;
    margin: 10px 0px;
  }
  .v-detail{
    font-size: 16px;
    font-weight: 500;
    color: #424242;
  }
  .skill-box{
    width: 100%;
    height: 140px;
  }
  .skill-box .text{
    font-size: 16px;
    font-weight: 600;
    color: #424242;
  }

  @media (min-width: 340px) and (max-width: 577px){
    .image-profile{
      width: 250px;
      height: 250px;
    }
    .first-about span{
      width: 100%;
    }
  }
</style>
