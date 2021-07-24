<template>
    <div class="md:mx-6 mx-4 md:px-6" style="margin-top: 120px !important;">
        <div class="has-text-black has-text-centered">
            <h2 class="has-text-weight-bold is-size-3">Have an enquiry?</h2>
            <p>We'd love to here from you!</p>
        </div>
        <div class="columns py-6">
            <div class="column mx-2">
                <div class="field">
                    <label class="label">Which of these best describe you? *</label>
                    <div class="control">
                        <div class="select is-primary is-fullwidth">
                            <select class="adjust-outline">
                                <option>Select one</option>
                                <option>Resident</option>
                                <option>Investor</option>
                                <option>Care Provider</option>
                                <option>Support Staff</option>
                                <option>Local Authority</option>
                                <option>Land Lord</option>
                                <option>Neighbour</option>
                                <option>Other</option>
                            </select>
                        </div>
                    </div>
                </div>
            </div>
            <div class="column mx-2">
                <div class="field">
                    <label class="label">Reason for contact? *</label>
                    <div class="control">
                        <div class="select is-primary is-fullwidth">
                            <select class="adjust-outline">
                                <option>Select one</option>
                                <option>Request Maintenance</option>
                                <option>Submit Complaint</option>
                                <option>Submit Compliment</option>
                                <option>Volunteer</option>
                                <option>General Enquiry</option>
                                <option>Referral</option>
                                <option>Other</option>
                            </select>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="columns">
            <div class="column mx-2">
                <div class="field">
                    <div class="control">
                        <input class="input adjust-outline" type="text" placeholder="Your Name *">
                    </div>
                </div>
            </div>
            <div class="column mx-2">
                <div class="field">
                    <div class="control">
                        <input class="input adjust-outline" type="email" placeholder="Email Address *">
                    </div>
                </div>
            </div>
        </div>
        <div class="columns">
            <div class="column mx-2">
                <div class="field">
                    <div class="control">
                        <textarea class="textarea adjust-outline" placeholder="Type your message here... *"></textarea>
                    </div>
                </div>
            </div>
        </div>
        <div class="columns">
            <div class="column mx-2">
                <div class="has-text-right">
                    <button class="button is-primary" style="border-radius: .75rem;" >Send</button>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .adjust-outline {
        border: none;
        border-bottom: 3px solid #666666 !important;
        border-radius: 0;
        box-shadow: none;
    }

    .adjust-outline:focus {
        border-color: #003B56 !important;
    }
</style>