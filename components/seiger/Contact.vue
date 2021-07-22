<template>
    <div>
        <div class="contactPage">
            <div class="contactInfo w-full mt-20 py-4 md:pl-16 pl-4" style="background-color: #eeeeee;">
                <div class="mx-6 px-6 py-4">
                    <div class="contactDirectry text-lg  no-underline">
                        <nuxt-link class="has-text-primary pr-2 text-black focus:text-gray-800 md:pr-0 no-underline" to="/">Home</nuxt-link> /  
                        <nuxt-link class=" pl-2 md:pl-0 focus:text-gray-800 no-underline text-black" to="/">
                            Contact
                        </nuxt-link>
                    </div>
                    <h2 class="text-4xl font-bold mt-2 has-text-black ">Contact Us</h2>
                </div>
            </div>

            <div class="mainContact bg-white w-full " v-if="true === false">
                <div class="contactLinks w-full md:mt-24 mt-12  md:flex mx-6 px-6">
                    <div class="link1 m-10 md:m-0  md:w-2/6 bord er-gray-100 border rounded   p-20 flex flex-col justify-center  h-96 shadow mx-3">
                        <p class="text-base flex justify-center p-5"> 1, rest service avenue, rest city</p>
                        <a class="flex justify-center p-5 hover:no-underline no-underline text-black "  href="tel:+44 1234 567890">  
                            <span class="ml-2" >
                                <ion-icon name="call-outline"></ion-icon>
                            </span> 
                            +44 1234 567890
                        </a>
                        <a class="border-2 flex justify-center w-full p-2 focus:ring cursor-pointer focus:border-gray-100 border-gray-200 outline-none hover:bg-gray-800 hover:text-white block rounded" href="mailto:admin@restservices.com">
                            Email us
                        </a>
                    </div>
                    <div class="link2 m-10 md:m-0 md:w-2/6 border-gray-100 border rounded  p-20 flex flex-col justify-center h-96 shadow mx-6">
                        <p class="text-base flex justify-center p-5" > 1, rest service avenue, rest city</p>
                        <a class="flex justify-center p-5 hover:no-underline no-underline text-black" href="tel:+44 1234 567890"> 
                            <span class="ml-2" >
                                <ion-icon name="call-outline"></ion-icon>
                            </span>  
                            +44 1234 567890
                        </a>
                        <a class="border-2 flex justify-center w-full p-2 focus:ring cursor-pointer focus:border-gray-100 border-gray-200 outline-none hover:bg-gray-800 hover:text-white block rounded" href="mailto:admin@restservices.com">
                            Email us
                        </a>
                    </div>
                </div>
            </div>

            <div class="columns mx-6 px-6 py-6 my-4">
                <div class="column">
                    <div class="card">
                        <div class="card-content has-text-centered">
                            <h4 class="has-text-primary is-size-4">Blackpool</h4>
                            <p class="has-text-black my-4">
                                92a topping Street<br />
                                Blackpool<br />
                                Lanchasire<br />
                                FY1 3AD
                            </p>
                            <p class="has-text-black">
                                <span class="">
                                    <ion-icon name="call-sharp"></ion-icon>
                                </span> 
                                <span>0333 366 1159</span>
                            </p>
                            <button class="button is-dark is-outlined mt-6">Email us</button>
                        </div>
                    </div>
                </div>
                <div class="column">
                    <div class="card">
                        <div class="card-content has-text-centered">
                            <h4 class="has-text-primary is-size-4">Liverpool</h4>
                            <p class="has-text-black my-4">
                                L6 Community Centre<br />
                                99 Queens Road<br />
                                Liverpool<br />
                                L6 2NG
                            </p>
                            <p class="has-text-black">
                                <span class="">
                                    <ion-icon name="call-sharp"></ion-icon>
                                </span> 
                                <span>0333 366 1159</span>
                            </p>
                            <button class="button is-dark is-outlined mt-6">Email us</button>
                        </div>
                    </div>
                </div>
            </div>

            <Enquiry />
        </div>
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

<style scoped>
    ion-icon {
        font-size: 24px;
        -webkit-transform: scaleX(-1);
        transform: scaleX(-1);
    }
</style>