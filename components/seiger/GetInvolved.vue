<template>
    <div class="">
        <div class="mx-6 px-6 mt-6 pt-6">
            <div class="columns">
                <div class="column">Evenly spaced col-1</div>
                <div class="column">Evenly spaced col-2</div>
            </div>
        </div>
        <Enquiry />
    </div>
</template>

<script>
    import Enquiry from '~/components/Enquiry'

    export default {
        name: "Contact",
        components: {
            Enquiry,
        },
    }
</script>