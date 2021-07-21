<template>
    <div>
        <div class="columns">
            <div class="column carousel-container">
                <b-carousel
                    animated="fade"
                    :repeat="true"
                    indicator-style="is-lines"
                    indicator-position="is-bottom"
                    :autoplay="true"
                    :interval="3000"
                    :pause-info="false">
                    <b-carousel-item v-for="(carousel, i) in carousels" :key="i">
                        <section :class="`hero is-medium `">
                            <div class="hero-body has-text-centered" style="padding-right: 0; padding-left: 0; padding-bottom: 0;">
                                <figure class="image">
                                    <img :src="carousel.image"
                                        style="border-radius: 100px 0 0 0;"
                                     />
                                </figure>
                            </div>
                        </section>
                    </b-carousel-item>
                </b-carousel>
            </div>
        </div>
        <div class="hero-text-container ml-6 pl-6">
            <h1 class="has-text-weight-bold is-size-1 has-background-black has-text-white hero-text px-3">We offer a safe and secure</h1>
            <h1 class="has-text-weight-bold is-size-1 has-background-black has-text-white hero-text px-3 my-2">environment for people in need</h1>
            <button class="button is-primary has-text-weight-bold is-size-4" style="border-radius: .75rem;">Learn More</button>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Hero",
        data() {
            return {
                carousels: [
                    {
                        image: "http://themepure.net/template/sycho-prv/sycho/assets/img/slider/slider-humb-2.jpg",
                    },
                    {
                        image: "http://themepure.net/template/sycho-prv/sycho/assets/img/slider/slider-humb-2.jpg",
                    },
                    {
                        image: "http://themepure.net/template/sycho-prv/sycho/assets/img/slider/slider-humb-2.jpg",
                    },
                    {
                        image: "http://themepure.net/template/sycho-prv/sycho/assets/img/slider/slider-humb-2.jpg",
                    },
                    {
                        image: "http://themepure.net/template/sycho-prv/sycho/assets/img/slider/slider-humb-2.jpg",
                    },
                ],
            }
        },  
    }
</script>

<style scoped>
    .carousel-container {
        padding: 0 !important;
    }

    .button-white {
        color: #056c5f;
    }

    .button-white:hover {
        border-color: white !important;
        background-color: transparent !important;
    }

    .hero-text {
        width: fit-content;
    }

    .hero-text-container {
        margin-top: -200px;
        z-index: 1;
        position: absolute;
        top: 800px;
    }
</style>