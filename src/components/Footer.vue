<template lang="">
    <footer id="contact">
        <div class="container text-center">
            <div class="contact">
                Contact Me
            </div>
            <div class="d-flex justify-content-center gap-2 my-3">
                <a class="btn btn-outline-light m-1" href="https://www.facebook.com/thanakorn.korn.theeye" target="_blank" role="button" data-bs-toggle="tooltip" data-bs-placement="top" data-bs-title="Korn ThanaKorn">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a class="btn btn-outline-light m-1" href="https://line.me/ti/p/v_afm5tLTF" target="_blank" role="button" data-bs-toggle="tooltip" data-bs-placement="top" data-bs-title="thanakorn.kung">
                    <i class="fa-brands fa-line"></i>
                </a>
                <a class="btn btn-outline-light m-1" href="https://github.com/theeye62" target="_blank" role="button" data-bs-toggle="tooltip" data-bs-placement="top" data-bs-title="github.com/theeye62">
                    <i class="fa-brands fa-github"></i>
                </a>
            </div>
            <div class="d-flex justify-content-center gap-2">
                <div class="-contact">
                    <i class="fa-solid fa-mobile-screen-button"></i>
                    096-8181604
                </div>
                <div class="-contact">
                    <i class="fa-regular fa-envelope"></i>
                    thanakorn.life@gmail.com
                </div>
            </div>
        </div>
    </footer>
</template>
<script>

const tooltipTriggerList = document.querySelectorAll('[data-bs-toggle="tooltip"]')
const tooltipList = [...tooltipTriggerList].map(tooltipTriggerEl => new bootstrap.Tooltip(tooltipTriggerEl))

export default {
    
}
</script>
<style scoped>
    footer{
        margin-top: auto;
        background-color: #1C1C1C;
        padding: 56px 0px;
        color: #ffffff;
    }
    .contact{
        font-size: 28px;
        font-weight: 700;
        color: #ffffff;
    }
    .-contact{
        text-shadow: 0px 2px 3px rgba(0, 0, 0, 0.40);
        font-size: 20px;
        font-weight: 500;
        margin: 10px 10px 10px 10px;
    }
</style>