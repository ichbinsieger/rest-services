<template>
    <div class="pt-6" style="margin-top: 120px !important; background-color: #f3f3f3; box-shadow: 0 0 10px #888;">
        <div class="columns mx-6 px-6">
            <div class="column is-6">
                <div class="brand-text has-text-weight-bold">
                    REST SERVICES
                </div>
                <h4 class="has-text-black is-size-5 has-text-weight-semibold">We are Rest Services</h4>
                <p class="has-text-black">We are determined to offer the opportunity and the support necessary to encourage and enable personal growth, self-development</p>
            </div>

            <div class="column">
                <h4 class="has-text-black is-size-5 has-text-weight-semibold">Useful Links</h4>
                <div>
                    <nuxt-link to="/" class="has-text-primary has-text-weight-semibold">Home</nuxt-link>
                </div>
                <div>
                    <nuxt-link to="/" class="has-text-primary has-text-weight-semibold">About us</nuxt-link>
                </div>
                <div>
                    <nuxt-link to="/" class="has-text-primary has-text-weight-semibold">Residents</nuxt-link>
                </div>
                <div>
                    <nuxt-link to="/" class="has-text-primary has-text-weight-semibold">Referrals</nuxt-link>
                </div>
                <div>
                    <nuxt-link to="/" class="has-text-primary has-text-weight-semibold">Partners</nuxt-link>
                </div>
                <div>
                    <nuxt-link to="/" class="has-text-primary has-text-weight-semibold">Contact</nuxt-link>
                </div>
            </div>

            <div class="column is-4">
                <h4 class="has-text-black is-size-5 has-text-weight-semibold">Contact us</h4>
                <div class="has-text-black has-text-weight-bold">Head office</div>
                <p class="has-text-weight-black">
                    92 topping Street,<br />
                    Blackpool,<br />
                    FY1 3AD
                </p>
                <div class="has-text-black">
                    <span class="has-text-weight-bold">Head office</span>
                    <span class="has-text-black">08430 330085</span>
                </div>
                <div class="has-text-black">
                    <span class="has-text-weight-bold">Email</span>
                    <span class="has-text-black">info@restservices.org</span>
                </div>
            </div>
        </div>
        <div class="columns pt-6">
            <div class="column has-text-centered has-text-white has-background-primary">
                Copyright &copy; Rest Services {{ year }}
            </div>
        </div>
    </div>
</template>

<script>

    export default {
        name: "Footer",
        data() {
            return {
                year: new Date().getFullYear(),
            }
        },
    }
</script>

<style scoped>
    .brand-text {
        -webkit-text-fill-color: transparent;
        -webkit-text-stroke: 0.5px #003B56;
    }
</style>