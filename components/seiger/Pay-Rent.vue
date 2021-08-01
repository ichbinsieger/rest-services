<template>
    <div class="mt-40">
       <div class="pay rent">



            <div class=" w-full mt-20 py-4 md:pl-16 pl-4" style="background-color: #eeeeee;">
                <div class="mx-6 px-6 py-4">
                    <div class="contactDirectry text-lg  no-underline">
                        <nuxt-link class="has-text-primary pr-2 text-black focus:text-gray-800 md:pr-0 no-underline" to="/">Home</nuxt-link> /  
                        <nuxt-link class=" pl-2 md:pl-0 focus:text-gray-800 no-underline text-black" to="/">
                            Pay-Rent
                        </nuxt-link>
                    </div>
                    <h2 class="text-4xl font-bold mt-2 has-text-black ">Pay Rent</h2>
                </div>
            </div>


                <div class="md:w-11/12 w-full m-auto">
                <p class=" md:px-16 px-5 py-10" >You are responsible for paying your rent and service charges to Creating Change, whether this is via Housing Benefit or from other funds. Non-payment of rent is a breach of tenancy and if not resolved can result in the loss of your home. A reference should be given for any payments into Creating Change's bank account, so we can quickly allocate the payment to you. </p>


                <div class="md:grid gap-5 md:px-16 px-5  flex flex-col  md:grid-cols-3">
                      <a href="#StandingOrder"> <div id="OrderImg"  class=" gridSocial w-full shadow-lg    relative"> <div class=" h-48 w-full bg-blue flex justify-center align-middle ">  <p class="text-white text-center  my-auto  mx-0 font-bold text-2xl"> Standing Order </p> </div> </div> </a> 
                       <a href="#cash">  <div id="CashImg"  class=" gridSocial w-full shadow-lg    relative"> <div class=" h-48 w-full bg-blue flex justify-center align-middle ">  <p class="text-white text-center  my-auto  mx-0 font-bold text-2xl"> Cash </p> </div> </div> </a>
                      <a href="#HousingBenefit">      <div id="BenefitImg"  class=" gridSocial w-full shadow-lg    relative"> <div class=" h-48 w-full bg-blue flex justify-center align-middle ">  <p class="text-white text-center  my-auto  mx-0 font-bold text-2xl"> Housing Benefit </p> </div> </div>      </a> 

                       
                  </div>


                
                <div id="sectionStand" class="mt-20 pt-12 pb-20 px-5 md:px-16">



                      <div id="StandingOrder"  class=" pt-12 flex md:flex-row flex-col  md:m-auto  w-full">
                        <div class="md:w-2/4 ">
                         <img src="https://www.cchousing.co.uk/images/bank-banking-blue-50987.jpg" alt="" srcset="">
                          </div>
                        <div class="md:w-2/4 md:m-auto">
                            <h6 class="text-3xl md:mt-0 mt-5 md:pl-5"> Standing order and Bank Transfer </h6>
                            <p class="md:pr-10 md:mt-0 mt-5 md:pl-5"> A standing order to Creating Change is an instruction to your bank to send us a fixed amount of money at set intervals.
                                 </p>

                                     <div class="mt-7">  <a href="" class="md:mr-10 md:mt-5 mt-5 md:ml-5 p-2 pl-2 text-white rounded  text-center bg-gray-700  hover:text-white focus:bg-gray-800  ">  <span class="  p-2 "> <ion-icon name="cloud-download"></ion-icon> </span> Download our standard order form</a> </div>  
                        </div>

                    </div>

                    <div id="cash" class="pt-3 flex md:flex-row flex-col-reverse  md:m-auto  w-full">

                          <div class="md:w-2/4 md:m-auto">
                            <h6 class="text-3xl md:mt-0 mt-5 md:pl-5"> Cash </h6>
                            <p class="md:pr-10 md:mt-0 mt-5 md:pl-5"> Creating Change accepts cheques posted to the office. You can pay cash into our bank account at any HSBC branch, via online banking, or via the Post Office.
                                 </p>

                                     <div class="mt-7">  <a href="" class="md:mr-10 md:mt-5 mt-5 md:ml-5 p-2 pl-2 text-white rounded  text-center bg-gray-700  hover:text-white focus:bg-gray-800  ">  <span class="  p-2 "> <ion-icon name="location"></ion-icon>  </span> Find Your Closest Branch</a> </div>  
                        </div>

                        <div class="md:w-2/4 ">
                         <img src="https://www.cchousing.co.uk/images/account-a-bank-account-34204.jpg" alt="" srcset="">
                          </div>


                    </div>



                     <div id="HousingBenefit"  class=" pt-12 flex md:flex-row flex-col  md:m-auto  w-full">
                        <div class="md:w-2/4 ">
                         <img src="https://www.cchousing.co.uk/images/account-bank-cashbook-870902.jpg" alt="" srcset="">
                          </div>
                        <div class="md:w-2/4 md:m-auto">
                            <h6 class="text-3xl md:mt-0 mt-5 md:pl-5"> Housing Benefits </h6>
                            <p class="md:pr-10 md:mt-0 mt-5 md:pl-5">Creating Change can help you claim housing benefit which will assist you to pay some or all of your rent.
                                 </p>

                                 
                        </div>

                    </div>


                    <p class="pt-1"> Housing Benefit (HB) is a welfare benefit administered by lower tier and single tier authorities, and is designed to help people to meet their housing costs. Creating Change can help you apply for housing benefit to pay for part, or all of your rent. The amount of Housing Benefit you are eligible to receive can vary, depending upon your income, savings and other circumstances. </p>
                    
                    <p class="my-2"> Housing Benefit payments will cover rent and other property related charges but will not cover heating, hot water, energy or support costs. This means that there may be some elements that you will have to pay for yourself. We may refer to these as service charges, or rent contributions. </p>
                    <p class="my-2"> If you wish for assistance to claim Housing Benefit, please call us on 0333 366 1159 or use our contact form. Please remember that regardless of the decision on your HB claim, you are responsible for paying your rent to Creating Change., in full and when it is due.  </p>


                     <span class="font-bold text-lg"> Find out more </span>
                     <div class="pb-40 flex flex-col">
                         <a class="no-underline hover:underline text-black" href="">Housing Benefit page on GOV.uk – The UK Government’s website.</a>
                         <a class="no-underline hover:underline text-black" href="">Housing Benefit page on shelter.org.uk – The website of the national housing charity</a>
                         <a class="no-underline hover:underline text-black" href="">Find your local council (the council you can claim benefit from)</a>
                     </div>


                </div>

                  

              

            </div>

       </div>
        <Enquiry  />
    </div>
</template>
    

<script>
    import Enquiry from '~/components/Enquiry'

    export default {
        name: "PayRent",
        components: {
            Enquiry,
        },
    }
</script>

<style scoped>
.gridSocial{
    
    background-size: cover;
    background-repeat: no-repeat;
    background-color: rgba(114,22,60,.49);
    background-position: 50%;
    position: relative;
    
}
#OrderImg{
    background-image: url(https://www.cchousing.co.uk/images/account-accounting-balance-164686.jpg);
}
#CashImg{
    background-image: url(	https://www.cchousing.co.uk/images/account-a-bank-account-34204.jpg);
}
#BenefitImg{
    background-image: url(https://www.cchousing.co.uk/images/account-bank-cashbook-870902.jpg);
}
#sectionStand{
         background-color: #eeeeee;
    
 clip-path: polygon(0 5%, 100% 0, 100% 91%, 0 96%);
}
</style>