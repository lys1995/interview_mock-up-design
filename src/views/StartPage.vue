<template>
    <div>
        <section class="section section-shaped section-lg my-0">
            <div class="shape" style="background-color: #186F6C ">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container shape-container d-flex">
                <div class="col px-0">
                    <div class="row">
                        <div class="col-lg-6">
                            <h1 class="display-1  text-white">Our Design
                                <span class="text-customized">Your Passion</span>
                            </h1>
                            <p class="lead  text-white">Lorem ipsum dolor ait amet, consectetur adipiscing elit, 
                                sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse
                                ultrices geavida. Risus commodo viverra maecenas accumsan lacus vel facilisis.</p>
                            <div class="btn-wrapper">
                                <base-button href="#"
                                            class="btn btn-warning btn-warning-addStyle">
                                    Get A Free Consultation
                                </base-button>
                            </div>
                        </div>
                        <div class="col-lg-6">
                            <img class="rounded-circle-customized img-center img-fluid shadow shadow-lg--hover" src="img/brand/interior.jpg" alt="logo">
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Interior Design -->
        <section>
        <div class="section-redesign-interiorDesign">
            <div class="container">
                <!-- Inputs (alternative) -->
                <div class="row">
                    <div class="col-lg-12 mb-5">
                        <h2 class="mb-0 text-black" style="font-weight: 700;">Interior design</h2>
                        <h3 class="text-black"> is for everyone</h3>
                    </div>
                </div>
                <div class="row mt-5">
                    <div class="col-lg-2">
                        <div class="row mt-5">
                            <p class="text-black ml-3" style="letter-spacing: -2px; font-weight: 600;">&mdash;&mdash;</p>
                            <h6 class="mt-1 text-black" style="font-weight: 600; font-style: italic;">&nbsp;&nbsp;&nbsp;Good for You</h6>
                        </div>
                    </div>
                    <div class="col-lg-5">
                        <img v-lazy="'img/icons/common/icon-1.svg'" class="img-center img-fluid text-center justify-content-center" style="width: 150px;">
                        <h3 class="text-black mt-3 display-4">Find your happy place</h3>
                        <p class="text-black mt-3">Nam pharetre auctor nibh, a aliquet urna imperdiet vitae.
                        Sed bibendum purus eget vehicula consequat. Nam efficitur molestie ligula in sodeales.
                        Nullam fringilla accumsan quam, vitae varius.</p>
                    </div>
                    <div class="col-lg-5">
                        <img v-lazy="'img/icons/common/icon-2.svg'" class="img-center img-fluid text-center justify-content-center" style="width: 150px;">
                        <h3 class="text-black mt-3 display-4">Delightfully affordable</h3>
                        <p class="text-black mt-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed 
                        do eiuusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse 
                        ultrices gravida.</p>
                    </div>
                </div>
                <div class="row mt-5">
                    <div class="col-lg-2">
                        <div class="row mt-5">
                            <p class="text-black ml-3" style="letter-spacing: -2px;font-weight: 600;">&mdash;&mdash;</p>
                            <h6 class="mt-1 text-black" style="font-weight: 600; font-style: italic;">&nbsp;&nbsp;&nbsp;Good for Us</h6>
                        </div>
                    </div>
                    <div class="col-lg-5">
                        <img v-lazy="'img/icons/common/icon-3.svg'" class="img-center img-fluid text-center justify-content-center" style="width: 150px;">
                        <h3 class="text-black mt-3 display-4">Create a lasting relationship</h3>
                        <p class="text-black mt-3">Nullam lobortis id nulla id feugiat. Sed lobortis 
                        molestie faucibus. Pellentesque magna eros, finibus ac volutpat et, cursus ut 
                        nisi. Suspendisse net tellus turpis.</p>
                    </div>
                    <div class="col-lg-5">
                        <img v-lazy="'img/icons/common/icon-4.svg'" class="img-center img-fluid text-center justify-content-center" style="width: 150px;">
                        <h3 class="text-black mt-3 display-4">We work with 200 vendors</h3>
                        <p class="text-black mt-3">Vestibulum feugiat dapibus risus, in venenatis justo finibus 
                        quis. Vestiibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae aenean nec
                        maximus elit.</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="container section-redesign-contactUs">
            <div class="col-lg-12">
                <div class="row">
                    <h2 class="mb-0 text-black" style="font-weight: 700;">Contact</h2>
                    <h2 class="ml-2 text-black">us</h2>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-6">
                    <base-input class="mt-3 mb-4"
                                placeholder="Name"
                                style="width: 80%;">
                    </base-input>
                    <base-input class="mb-4" placeholder="Email" style="width: 80%;">
                    </base-input>
                    <base-input class="mb-4">
                            <textarea class="form-control" rows="7" cols="80" placeholder="Message" style="width: 80%;"></textarea>
                    </base-input>
                    <base-button href="#"
                                class="btn btn-warning btn-submit-addStyle" 
                                size="lg">
                        Submit
                    </base-button>
                </div>
                <div class="col-lg-6">
                     <img class="rounded-circle-customized2 img-center img-fluid shadow shadow-lg--hover" src="img/brand/melbourne.png" alt="logo">
                </div>
            </div>
        </div>
    </section>
    </div>
</template>
<script>
import Inputs from "./components/Inputs";
export default {
    name: "components",
    components: {
    Inputs
    }
};
</script>
<style>
</style>
