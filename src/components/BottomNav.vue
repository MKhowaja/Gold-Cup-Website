<template>
    <!--Footer-->
    <footer class="page-footer pt-4 mt-4">
        <b-container class="text-center text-md-left">
            <b-row>
                <b-col>
                    <ul class="list-unstyled list-inline">
                        <li class="list-inline-item social-media-icons">
                            <a class="btn-floating btn-sm btn-fb mx-1">
                                <i class="fa fa-facebook"> </i>
                            </a>
                        </li>
                        <li class="list-inline-item social-media-icons">
                            <a class="btn-floating btn-sm btn-tw mx-1">
                                <i class="fa fa-twitter"> </i>
                            </a>
                        </li>
                        <li class="list-inline-item social-media-icons">
                            <a class="btn-floating btn-sm btn-gplus mx-1">
                                <i class="fa fa-instagram"> </i>
                            </a>
                        </li>
                    </ul>
                </b-col>
                <b-col>
                    <b-input-group>
                        <b-input-group-text slot="append">
                            <strong class="text"><icon name="search"></icon></strong>
                        </b-input-group-text>
                        <b-form-input></b-form-input>
                    </b-input-group>
                    <br>
                </b-col>
            </b-row>
            <b-row>
                <b-col cols="6">
                    <h5 class="footer-heading text-gold mb-4 mt-3">Sponsors</h5>
                    <p class="footer-text text-white">If you would be interested in sponsoring the Gold Cup Tournament, in any capacity, 
                        please email us at info@gold-cup.ca -- we'd be happy to hear from you!</p>
                    <br>
                    <h5 class="footer-heading text-white mb-4 mt-3">Quest Logo</h5>
                </b-col>
                <b-col cols="3">
                    <h5 class="footer-heading text-gold mb-4 mt-3">Schedule</h5>
                    <b-row>
                        <b-col>
                            <ul class="list-unstyled">
                                <li class="footer-text text-white">
                                    B-07
                                </li>
                                <li class="footer-text text-white">
                                    B-05
                                </li>
                                <li class="footer-text text-white">
                                    B-03
                                </li>
                                <li class="footer-text text-white">
                                    B-00
                                </li>
                                <li class="footer-text text-white">
                                    B-97
                                </li>
                                <li class="footer-text text-white">
                                    B-94
                                </li>
                            </ul>
                        </b-col>
                        <b-col>
                            <ul class="list-unstyled">
                                <li class="footer-text text-white">
                                    G-06
                                </li>
                                <li class="footer-text text-white">
                                    G-03
                                </li>
                                <li class="footer-text text-white">
                                    G-00
                                </li>
                                <li class="footer-text text-white">
                                    G-97
                                </li>
                                <li class="footer-text text-white">
                                    G-96
                                </li>
                            </ul>
                        </b-col>
                        <b-col>
                            <ul class="list-unstyled">
                                <li class="footer-text text-white">
                                    M-93
                                </li>
                                <li class="footer-text text-white">
                                    M-79
                                </li>
                                <li class="footer-text text-white">
                                    M-64
                                </li>
                            </ul>
                        </b-col>
                    </b-row>
                </b-col>
                <b-col>
                    <h5 class="footer-heading text-gold mb-4 mt-3">Site Map</h5>
                    <ul class="list-unstyled">
                        <li class="footer-text text-white">
                            Announcements
                        </li>
                        <li class="footer-text text-white">
                            Blog
                        </li>
                        <li class="footer-text text-white">
                            Coaches Corner
                        </li>
                        <li class="footer-text text-white">
                            Active Living
                        </li>
                        <li class="footer-text text-white">
                            Documents
                        </li>
                        <li class="footer-text text-white">
                            Facilities
                        </li>
                        <li class="footer-text text-white">
                            Calendar
                        </li>
                        <li class="footer-text text-white">
                            Affiliated Programs
                        </li>
                        <li class="footer-text text-white">
                            Contact
                        </li>
                        <li class="footer-text text-white">
                            FAQs
                        </li>
                        <li class="footer-text text-white">
                            Login
                        </li>
                    </ul>
                </b-col>
            </b-row>
        </b-container>

        <div class="text-white text-center py-3">
            <h5 class="mb-1">AKYSB Logo</h5>
        </div>

        <!--Copyright-->
        <div class="text-white footer-text py-3 text-center">
            The Fair Play Code of Conduct encapsulates all the sporting principles for which the game has always 
            stood for. Its purpose is to promote fair play, respect, sportsmanship & team spirit.
            <br>
            Fair Play extends beyond simply the Player, these principles extend to include Coaches, Parents, 
            Referees, Officials & Spectators.
            <br>
        </div>
        <div class="text-gold footer-text py-3 text-center">
            Fair Play Policy | Privacy Policy | Rules & Regulations | Team Conduct Policy | Anti-bullying policy | 
            Terms and Conditions
            <br>
        </div>
        <div class="text-white footer-text py-3 text-center">
            AKYSB Gold Cup 2017. All rights reserved. 
        </div>
        
        <!--/.Copyright-->

    </footer>
</template>

<script>
  import Icon from 'vue-awesome/components/Icon'
  export default {
    components: {
      Icon
    }
  }
</script>

<style scoped>
.social-media-icons:not(:last-child) {
    margin-right: -1rem;
}
/* Style all font awesome icons */
.fa {
    padding: 5px;
    font-size: 11px;
    width: 24px;
    text-align: center;
    text-decoration: none;
    background: #800505;
    color: white;
}

.fa-twitter {
    background: #CAA83F;
}

/* Add a hover effect if you want */
.fa:hover {
    opacity: 0.7;
}

/* Set a specific color for each brand */

.page-footer {
    background-color: #212121;
}

.text-gold {
    color:#CAA83F;
}

.footer-heading {
    font-weight: 400;
    font-size: 1.1rem;
}

.footer-text {
    font-size:0.8rem;
    font-weight:300;
}
</style>