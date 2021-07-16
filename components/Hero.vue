<template>
    <div>
        <div class="columns">
            <div class="column"></div>
            <div class="column is-8">
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
                            <div class="hero-body has-text-centered">
                                <figure class="image">
                                    <img :src="carousel.image" />
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