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
            <button class="button is-primary has-text-weight-bold is-size-5" style="border-radius: .75rem;">Learn More</button>
        </div>
        <div class="columns my-6 mx-6" style="margin-top: 120px !important;">
            <div class="column">
                <div class="hero-img">
                    <figure class="image">
                        <img class="team-image" src="https://www.cchousing.co.uk/images/team.png" />
                    </figure>
                </div>
            </div>
            <div class="column pt-6 pr-6 has-text-black">
                <h3 class="mt-6 has-text-weight-bold is-size-4">We are Creating Change.</h3>
                <p>
                    Creating Change Housing Management provide supported housing accommodation for people who are homeless or at risk of homelessness, who require Intensive support in managing and maintaining a tenancy. Our residents may have complex and additional support needs to include but not limited to those with addictions, mental health issues, learning difficulties and offending behaviour. Creating Change recognises that people who require specialist support may encounter difficulty renting accommodation from the wider housing market.
                </p>
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

    .hero-text {
        width: fit-content;
    }

    .hero-text-container {
        margin-top: -200px;
        z-index: 1;
        position: absolute;
        top: 800px;
    }

    .hero-img {
        position: relative;
        max-width: 300px;
        margin: 30px auto;
    }

    .hero-img::before {
        position: absolute;
        width: 90%;
        height: 92%;
        z-index: -1;
        content: "";
        background-color: #003B56;
        left: -31px;
        top: -30px;
    }

    .hero-img::after {
        position: absolute;
        width: 90%;
        height: 92%;
        z-index: -1;
        content: "";
        background-color: #003B56;
        right: -31px;
        bottom: -30px;
    }

    .team-img {
        width: 100%;
        border: 8px solid #fff;
        position: relative;
    }
</style>