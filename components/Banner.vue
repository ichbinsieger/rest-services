<template>
    <div class="has-background-primary" style="margin-top: 120px !important;">
        <div class="columns mx-6 px-6 my-6">
            <div class="column py-6">
                <h4 class="has-text-white is-size-4 has-text-weight-semibold">{{ title }}</h4>
                <p class="has-text-white">{{ description }}</p>
            </div>
            <div class="column has-text-right py-6 pr-6">
                <button class="button is-white is-outlined" style="border-radius: .75rem;" @click="$router.push(`${buttonLink}`)">{{ buttonText }}</button>
            </div>
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