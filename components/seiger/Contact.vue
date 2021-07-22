<template>
    <div>
        <div class="contactPage">
            <div class="contactInfo w-full mt-24 h-28 pt-4 md:pl-16 pl-4 bg-gray-200">
                <div class="contactDirectry text-lg  no-underline"> <a class=" pr-2 text-black focus:text-gray-800 md:pr-0 no-underline" href="http://">Home</a> /  <a  class=" pl-2 md:pl-0 focus:text-gray-800 no-underline text-black" href="">Contact</a> </div>
                <h2 class="text-3xl font-semibold mt-2 tracking-widest ">Contact Us</h2>
            </div>

        <div class="mainContact bg-white w-full ">
                <div class="contactLinks w-full md:mt-24 mt-16  md:flex md:justify-center">
                <div class="link1 m-10 md:m-0  md:w-2/6 border-gray-100 border rounded   p-20 flex flex-col justify-center  h-96 shadow  md:mr-20">
                    <p class="text-base flex justify-center p-5"> 1, rest service avenue, rest city</p>
                    <a class="flex justify-center p-5 hover:no-underline no-underline text-black "  href="tel:+44 1234 567890">  <span class="ml-2" ><ion-icon name="call-outline"></ion-icon></span>  +44 1234 567890</a>
                    <a class="border-2 flex justify-center w-full p-2 focus:ring cursor-pointer focus:border-gray-100 border-gray-200 outline-none hover:bg-gray-800 hover:text-white block rounded" href="mailto:admin@restservices.com">Email us</a>
                </div>
                 <div class="link2 m-10 md:m-0 md:w-2/6 border-gray-100 border rounded  p-20 flex flex-col justify-center h-96 shadow md:ml-20 ">
                    <p class="text-base flex justify-center p-5" > 1, rest service avenue, rest city</p>
                    <a class="flex justify-center p-5 hover:no-underline no-underline text-black" href="tel:+44 1234 567890"> <span class="ml-2" ><ion-icon name="call-outline"></ion-icon></span>  +44 1234 567890</a>
                    <a class="border-2 flex justify-center w-full p-2 focus:ring cursor-pointer focus:border-gray-100 border-gray-200 outline-none hover:bg-gray-800 hover:text-white block rounded" href="mailto:admin@restservices.com">Email us</a>
                </div>
            </div>
        </div>



        <div class="enquiry  flex-col flex text-center mt-16 mb-16">
            <h1 class="text-3xl font-bold ">Have any enquiry?</h1>
            <p class="text-base mt-4 " >we'd love to hear from you!</p>
        </div>
        <div class="enquiryForm m-10 mt-16">
         <form action="" class="relative">
             <div class="desRes flex flex-col md:flex-row md:w-4/5 md:ml-20 md:flex md:justify-between  ">


                 <div class="describeDiv mt-5 md:w-5/12 flex flex-col">
                      <label class="text-xl " for="describe">What best describe you?*</label>
                <select class=" border-b-4  text-base p-3 border-gray-700"   name="describe" id="describe" required>
                    <option value="0">Select one</option>
                    <option value="1">Resident</option>
                    <option value="2">Investor</option>
                    <option value="3">Care Provider</option>
                    <option value="4">Business man/woman</option>
                    <option value="5">Local Authority</option>
                    <option value="6">Other</option>

                </select>
                 </div>
                 <div class="res mt-5  flex flex-col md:w-5/12">
                     <label for="reason" class="text-xl " >Reason for contact?*</label>
                     <select name="reason" class=" border-b-4 text-base p-3 border-gray-700"  required id="reason">
                           <option value="0">Select one</option>
                          <option value="1">General enquiry</option>
                        <option value="2">Request maintanance</option>
                          <option value="3">Referral</option>
                         <option value="4">Other</option>
                </select>
             </div>

             </div>


             <div class=" md:flex flex flex-col  md:ml-20 md:w-4/5 md:justify-between md:flex-row">
                  <input type="text" class="mt-5 md:w-5/12 outline-none border-b-4 border-gray-700 p-4"  placeholder="Your name*" required>
                <input type="email" class="mt-5 md:w-5/12 outline-none border-b-4 border-gray-700 p-4"  placeholder="Email Address*" required name="mail"  id="email">

             </div>
              <div class="md:flex flex flex-col  md:ml-20 md:w-4/5 md:justify-between md:flex-row ">
                            <textarea name="message"  id="message" placeholder="Type your message here*" required cols="30" rows="4" class="  mt-5  w-full p-0 outline-none resize-none border-b-4 border-gray-700 mb-10"></textarea>                                                               </div>   

                <input type="button" class="w-16 md:w-24 h-10  md:h-12 rounded bg-gray-900  absolute md:right-64 right-8 mb-10 text-gray-500 focus:bg-gray-400" value="Send">
           

         </form>
        </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Contact",
    }
</script>