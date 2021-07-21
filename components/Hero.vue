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
                            <div class="hero-body has-text-centered" style="padding-right: 0;">
                                <figure class="image">
                                    <img :src="carousel.image"
                                        style="border-radius: 10px 0 0 10px;"
                                     />
                                </figure>
                            </div>
                        </section>
                    </b-carousel-item>
                </b-carousel>
            </div>
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

    .hero-title {
        margin: 400px 0 0 20px;
    }
</style>