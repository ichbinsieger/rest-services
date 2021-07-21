<template>
    <div class="bg-black" style="margin: 0 !important;">
        <div class="columns px-6">
            <div class="column"></div>
            <div class="column has-text-right py-6"></div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Banner",
        props: {
            title: {
                type: String,
                default: "Hello World!",
            },
            description: {
                type: String,
                default: "This is Rest Services",
            },
            buttonText: {
                type: String,
                default: "Visit us",
            },
            buttonLink: {
                type: String,
                default: "/",
            },
        },
    }
</script>