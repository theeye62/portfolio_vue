<template lang="">
    <nav id="navbar" class="navbar navbar-expand-lg">
        <div class="container">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <a class="navbar-brand navbar-scroll" href="/">
                Portfolio
            </a>
            <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
                <ul class="navbar-nav mb-2 mb-lg-0 gap-3 pe-3">
                    <li class="nav-item">
                        <a href="#about_me" class="nav-link navbar-scroll">About Me</a>
                    </li>
                    <li class="nav-item">
                        <a href="#experience" class="nav-link navbar-scroll">Experience</a>
                    </li>
                    <li class="nav-item">
                        <a href="#project" class="nav-link navbar-scroll">My Project</a>
                    </li>
                    <li class="nav-item">
                        <a href="#contact" class="nav-link navbar-scroll">Contact Me</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>
<script>
    window.onscroll = function() {
        var currentScrollPos = window.pageYOffset;

        if(currentScrollPos === 0) {
            document.getElementById("navbar").style.backgroundColor = 'transparent';

            let nav_color = document.getElementsByClassName("navbar-scroll");
            for(let i = 0; i<nav_color.length; i++){
                nav_color[i].style.color = '#808080';
            }
        } else {
            document.getElementById("navbar").style.backgroundColor = '#ffffff';

            let nav_color = document.getElementsByClassName("navbar-scroll");
            for(let i = 0; i<nav_color.length; i++){
                nav_color[i].style.color = '#424242';
            }
        }
    }

    export default {
        
    }
</script>
<style scoped>
    .navbar{
        position: fixed;
        padding: 8px 16px;
        background: none;
        width: 100%;
        z-index: 999;
        top: 0;
        transition: .3s;
    }

    .navbar-brand{
        font-size: 22px;
        color: #808080;
        text-shadow: #e0e0e0 1px 1px 0;
    }

    .navbar-nav .nav-link{
        font-size: 18px;
        color: #808080;
        text-shadow: #e0e0e0 1px 1px 0;
    }

    .navbar-nav .nav-link:hover{
        background-color: #FFFFFF40;
        color: #5bbee3 !important;
    }

    .space-nav{
        margin-top: 3rem;
    }
</style>