<template>
<div>
    <section class="section section-shaped section-sm my-0" style="padding-top: 0px">
            <div class="shape" style="background-color: #186F6C; border-radius: 20px 0 0 0;">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container">
                <div class="row justify-content-md-between">
                     <div class="col-md-3">
                        <a slot="title" href="#" class="nav-link">
                            <span class="footer-link-inner-title">SERVICES</span>
                        </a>
                        <a slot="title" href="#" class="nav-link">
                            <p class="footer-link-inner">Interior Design</p>
                        </a>
                        <a slot="title" href="#" class="nav-link">
                            <p class="footer-link-inner">Architecture</p>
                        </a>
                        <a slot="title" href="#" class="nav-link">
                            <p class="footer-link-inner">Furniture and Decor</p>
                        </a>
                    </div>
                    <div class="col-md-3">
                        <a slot="title" href="#" class="nav-link">
                            <span class="footer-link-inner-title">ABOUT</span>
                        </a>
                        <a slot="title" href="#" class="nav-link">
                            <p class="footer-link-inner">Philosophy</p>
                        </a>
                        <a slot="title" href="#" class="nav-link">
                            <p class="footer-link-inner">Our Strengths</p>
                        </a>
                        <a slot="title" href="#" class="nav-link">
                            <p class="footer-link-inner">Our Team</p>
                        </a>
                    </div>
                    <div class="col-md-3">
                        <a slot="title" href="#" class="nav-link">
                            <span class="footer-link-inner-title">PORTFOLIO</span>
                        </a>
                        <a slot="title" href="#" class="nav-link">
                            <p class="footer-link-inner">Residental</p>
                        </a>
                        <a slot="title" href="#" class="nav-link">
                            <p class="footer-link-inner">Commercial</p>
                        </a>
                    </div>
                    <div class="col-md-3">
                        <a slot="title" href="#" class="nav-link">
                            <span class="footer-link-inner-title">CONTACT US</span>
                        </a>
                        <a slot="title" class="nav-link">
                            <p class="footer-link-inner">Level 10, 4 Elizabeth St，Melbourne, Victoria 3000</p>
                        </a>
                        <a slot="title" href="#" class="nav-link">
                            <base-button class="btn-1 btn-email" style="margin-top: 30px;">interior_studio@gmail.com<img class="ml-3" style="width: 20px; height: 20px; padding-left: 2px" src="img/icons/common/icon-5.png" alt="send"></base-button>
                        </a>
                    </div>
                </div>
            </div>
    </section>
</div>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
