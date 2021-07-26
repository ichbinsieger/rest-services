<template>
    <div class="">
        <div class="partner">
             <div class="contactInfo w-full mt-20 py-4 md:pl-16 pl-4" style="background-color: #eeeeee;">
                        <div class="mx-6 px-6 py-4">
                           <div class="contactDirectry text-lg  no-underline">
                               <nuxt-link class="has-text-primary pr-2 text-black focus:text-gray-800 md:pr-0 no-underline" to="/">Home</nuxt-link> /  
                               <nuxt-link class=" pl-2 md:pl-0 focus:text-gray-800 no-underline text-black" to="/partners">
                            partners
                                </nuxt-link>
                            </div>
                    <h2 class="text-4xl font-bold mt-2 has-text-black "> Partners</h2>
                </div> 


             
                </div>

                <div class="md:w-4/5  m-5  md:m-auto"> 
                    <p class="my-10 md:mx-24"> 
                        Supported Housing is a multi-agency provision which requires housing providers, local authorities and care providers to work together to ensure that all aspects of the service meet the needs of the residents. Also involved in the provision of supported housing are funders, property owners and service providers. Creating Change brings these parties together to deliver housing related services that meet the needs of the market.
                    </p>
                </div>

              
                    <h5 class="text-center font-bold md:text-4xl text-4xl mb-10 mt-5" id="associations">Housing Associations</h5>
              
                

               <div class="w-full mt-2 " >
                    <div class="flex justify-between flex-col md:flex-row w-4/5 m-auto">
                        <div class="md:w-2/4 w-full  "> <img src="https://www.cchousing.co.uk/images/adults-business-people-businessmen-1586525.jpg" alt="" srcset="">  </div>
                        <div class="md:w-2/4  w-full md:p-10  md:mt-0 mt-5 "> 
                            <p> Creating Change offers services to housing associations to enable them to effectively manage their specialised supported housing stock. Services include tenancy sign- ups, property sourcing, rent setting, rent collection, management of repairs, communal services and safety certification, liaison with care providers and stakeholders, inspections, provision of bespoke easy-read materials, 24/7 contact centre services, and other associated services as required. Whether you want us to handle a single project for a transitionary period, or manage a larger portfolio on an ongoing basis, we have the skills and experience to help. </p>
                        </div>
                    </div>
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


