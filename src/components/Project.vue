<template lang="">
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
                        <img src="../assets/indexgame/logo-indexgame.png" class="w-100" alt="Project Image">
                        </a>
                    </div>
                </div>
            </div>
            <button class="view-more-btn" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
                View Image
            </button>
            <div class="collapse mt-4" id="collapseExample">
                <!-- <carousel :autoplay="true" :nav="false">
                    <img src="../assets/indexgame/image1.png" alt="Image Project">
                    <img src="../assets/indexgame/image2.png" alt="Image Project">
                    <img src="../assets/indexgame/image3.png" alt="Image Project">
                </carousel> -->
                <div class="owl-carousel owl-theme">
                    <div class="item">
                        <a href="" target="_blank">
                            <img src="http://via.placeholder.com/640x360" alt="Image Project">
                        </a>
                    </div>
                    <div class="item">
                        <a href="" target="_blank">
                            <img src="http://via.placeholder.com/640x360" alt="Image Project">
                        </a>
                    </div>
                    <div class="item">
                        <a href="" target="_blank">
                            <img src="http://via.placeholder.com/640x360" alt="Image Project">
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
$('.owl-carousel-slide').owlCarousel({
    loop:true,
    margin:30,
    nav:true,
    autoplay:true,
    autoplayTimeout:3000,
    autoplayHoverPause:true,
    responsive:{
        0:{
            items:2
        },
        600:{
            items:3
        },
        1000:{
            items:5
        }
    }
})

export default {
    
}
</script>
<style scoped>
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
</style>