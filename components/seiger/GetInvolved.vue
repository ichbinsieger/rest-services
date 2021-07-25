<template>
    <div class="">
        <div class=" w-full mt-20 py-4 md:pl-16 pl-0" style="background-color: #eeeeee;">
                <div class="mx-6 md:px-6 px-0 py-4">
                    <div class="contactDirectry text-lg  no-underline">
                        <nuxt-link class="has-text-primary pr-2 text-black focus:text-gray-800 md:pr-0 no-underline" to="/">Home</nuxt-link> /  
                        <nuxt-link class=" pl-2 md:pl-0 focus:text-gray-800 no-underline text-black" to="/">
                            Get-involved
                        </nuxt-link>
                    </div>
                    <h2 class="text-3xl font-bold mt-2 has-text-black ">Get-involved</h2>
                </div>
            </div>
        <div class="md:mx-6 md:px-6 px-4 mt-6 pt-6">
              
            <div class="columns md:px-0 px-4 mb-5">
                <div class="column"> <img src="https://www.cchousing.co.uk/images/friends.png" alt=""> </div>
                <div class="column mt-2">
                        <h4 class=" font-bold text-2xl mb-2 "> Work for us</h4>
                        <p class=" md:leading-10 leading-8">Each member of staff contributes their skills and experience to help us provide a high quality, innovative accommodation based service that seeks to meet the needs of the men and women we support. We also believe it is important to continue the improvement of not only our services but our staff. We are dedicated to providing the appropriate training and support for each employee and volunteer, which will enable them to develop professionally and also gain job satisfaction from their role.</p>
                         <a class="w-full mt-4 rounded text-white flex justify-center p-2 bg-gray-800 hover:bg-gray-900 hover:text-white  focus:bg-gray-900" href="http://"> find a vacancy</a>
                </div>
            </div>

            <div class="columns md:px-0 px-4  flex flex-col-reverse md:flex-row mb-5">
                <div class="column mt-4"> 
                     <h4 class=" font-bold text-2xl mb-2 "> Volunteer with us </h4>
                        <p class="md:leading-10 leading-8 ">There are many reasons why people volunteer. For some, volunteering can be a route to employment, or a chance to try something new, which may lead to a career change. Our dedicated pool of volunteers regularly give a considerable amount of their time, energy, ideas and enthusiasm, free of charge, providing invaluable support to our clients.

                                If you are interested in volunteering please use the enquiry form below or contact us to discuss further</p>
                </div>
                <div class="column">
                     <img src="https://www.cchousing.co.uk/images/volunteer.png" alt="" srcset="">
                </div>
            </div>


         

        </div>
        <div class="ReasonToVolunteer px-4  md:mt-10 mt-4 md:pt-16 pt-10 pb-24  " style="background-color:  #eeeeee;">
              <h4 class=" font-bold text-2xl md:mx-6 px-4 md:px-6 mt-2 pt-6  "> Reasons to Volunteer</h4>
             <div class="columns  md:mx-6 md:px-6 px-4 mt-2 pt-4 ">
                 
                 <div class="column">
                      
                        <p class=" md:leading-10 ">Gaining new skills, knowledge and experience
                                Developing existing skills and knowledge
                                    Enhancing your CV
                                    Improving one’s employment prospects
                                    Using one’s professional skills and knowledge to benefit others</p>

                </div>
                <div class="column">
                      
                        <p class="md:leading-10 leading-8">Getting to know the local community <br> Making new friends
                                A chance to socialise <br> Meeting new people</p>

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