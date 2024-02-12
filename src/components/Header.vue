<template lang="">
    <div class="header-banner">
        <div id="about_me" class="row h-100 w-100">
            <div class="col-lg-6 col-sm-12 col-12 d-flex justify-content-center align-items-center">
                <div class="image-profile">
                    <img src="../assets/avatar.jpg" alt="Avatar">
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
</template>
<script>
export default {
    
}
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