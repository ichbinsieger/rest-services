<template>
    <div>
        <div class="referral">

            <div class=" w-full mt-20 py-4 md:pl-16 pl-0" style="background-color: #eeeeee;">
                <div class="mx-6 md:px-6 px-0 py-4">
                    <div class="contactDirectry text-lg  no-underline">
                        <nuxt-link class="has-text-primary pr-2 text-black focus:text-gray-800 md:pr-0 no-underline" to="/">Home</nuxt-link> /  
                        <nuxt-link class=" pl-2 md:pl-0 focus:text-gray-800 no-underline text-black" to="/">
                           Referral
                        </nuxt-link>
                    </div>
                    <h2 class="text-3xl font-bold mt-2 has-text-black ">Referrals</h2>
                </div>
            </div>


        <div class="mx-5">
                <p class="flex justify-center text-lg flex-wrap md:mx-10 mt-10"> We can accept clients, male and female, aged 18 years and over with or without a local connection, in the area of accommodation </p>
               
               
                <div class="flex justify-center " >
                          <div class=" md:flex  md:flex-row gap-0 flex flex-col md:w-4/5  w-full ">

                    <div class="column mt-12  ">
                        <div class="flex  md:px-4 md:pb-8 px-5 md:py-4 rounded border shadow-xl  w-full ">
                            <span class="flex justify-center mt-7  md:mt-0"> <ion-icon class= "md:text-9xl text-9xl" name="person"> </ion-icon>  </span>
                            <div class="selfRefer md:w-4/5 w-3/4  ">
                                <h5 class="font-bold md:text-2xl mt-1 text-xl">Self-Referral</h5>
                                <p class="mt-2 md:leading-6 flex flex-wrap pl-1" >  Contact us or visit your local office  <br> and an  appointment for an  assessment will be offered.  <br>  <a class=" no-underline text-gray-800 pointer hover:underline hover:text-gray-900 " href="./contact">Details can be found in contact us</a>   </p>
                            </div> 
                        </div>
                    </div>




                      <div class="column  md:mt-12">
                        <div class="flex md:px-4 pb-8 md:pb-2 px-5  md:py-4 rounded border shadow-xl w-full ">
                            <span class="flex justify-center mt-7 md:mt-0"> <ion-icon class= "text-9xl" name="people"></ion-icon>  </span>
                            <div class="selfRefer md:w-4/5 w-3/4  ">
                                <h5 class="font-bold md:text-2xl mt-1 text-xl">3rd Party Referral</h5>
                                <p class="mt-2 md:leading-6 pl-1  flex flex-wrap" >  We accept referrals from agencies and <br> organisations who wish to refer on behalf  of  their clients.   You can refer  <br> using our  online  form  or contact   us directly. </p>
                            </div> 
                        </div>
                    </div>


                  
                </div>

                </div>


                <div class="mt-8 mb-5">
                    <p class="my-16 leading-8 text-lg md:mx-24 "> When a referral is received, if appropriate, an appointment will be offered for
                         a comprehensive assessment. Once assessed, if the client meets our criteria and a vacancy exists, a unit of accommodation will be offered.
                         If a vacancy does not exist, the client will be put on a waiting list for consideration 
                         for when a vacancy becomes available.
                     </p>
                </div>
              


                
        </div>
        <div style="background-color: #eeeeee;" class="w-full h-36 mt-10 flex justify-center">
            <a href="http://" class="bg-gray-700 hover:bg-gray-900 hover:text-white focus:bg-gray-900 w-48 p-2 m-auto text-center inline-block align-middle text-white border h-10  rounded "> Use our online form </a>

        </div>
        </div>

    </div>
</template>

<script>

export default {
  name: 'Referral',
}
</script>
