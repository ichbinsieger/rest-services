<template>
    <div>
        <div class="columns">
            <div class="column">
                REST SERVICES <br />
                Something about rest services
            </div>
            <div class="column has-text-right">
                <MailIcon /> admin@restservices.org <br />
                <PhoneIcon /> +44 1234 567890 <br />
                <LocationMarkerIcon /> 1, rest service avenue, rest city
            </div>
        </div>
        <div class="columns has-text-centered">
            <div class="column is-12">
                All Rights Reserved <br />
                REST SERVICES <br />
                &copy; {{ year }}.
            </div>
        </div>
    </div>
</template>

<script>
    import { MailIcon, PhoneIcon, LocationMarkerIcon } from "@vue-hero-icons/outline"

    export default {
        name: "Footer",
        components: {
            MailIcon,
            PhoneIcon,
            LocationMarkerIcon,
        },
        data() {
            return {
                year: new Date().getFullYear(),
            }
        },
    }
</script>