<template>
    <div class="footer-wrap-area pt-100">
        <div class="container">
            <div class="row">
                <div class="col-lg-2 col-md-6 col-sm-6">
                    <div class="single-footer-widget">
                        <router-link to="/" class="logo">
                            <img src="../../assets/images/footer-logo.svg" alt="logo">
                        </router-link>
                        <p>DealDocx, a unique cost-effective, CRM and AI enabled quote management software specially
                            designed for IT services.</p>
                        <ul class="social-links">
                            <li>
                                <a href="#" target="_blank"><i class="ri-facebook-fill"></i></a>
                            </li>
                            <li>
                                <a href="#" target="_blank"><i class="ri-instagram-fill"></i></a>
                            </li>
                            <li>
                                <a href="#" target="_blank"><i class="ri-linkedin-fill"></i></a>
                            </li>
                            <li>
                                <a href="#" target="_blank"><i class="ri-twitter-fill"></i></a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-lg-2 col-md-6 col-sm-6">
                    <div class="single-footer-widget pl-2">
                        <h3>Features</h3>
                        <ul class="links-list">
                            <li>
                                <router-link to="/about-simple">CPQ</router-link>
                            </li>
                            <li>
                                <router-link to="/features-two">Integrations</router-link>
                            </li>
                            <li>
                                <router-link to="/privacy-policy">Swift Quotes</router-link>
                            </li>
                            <li>
                                <router-link to="/privacy-policy">Simplified Deals</router-link>
                            </li>
                            <li>
                                <router-link to="/feedback">Quick Approvals</router-link>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-lg-2 col-md-3 col-sm-6">
                    <div class="single-footer-widget">
                        <h3>Integrations</h3>
                        <ul class="links-list">
                            <li>
                                <router-link to="/services">Salesforce</router-link>
                            </li>
                            <li>
                                <router-link to="/contact">Hubspot</router-link>
                            </li>
                            <li>
                                <router-link to="/privacy-policy">Freshworks</router-link>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-lg-2 col-md-3 col-sm-6">
                    <div class="single-footer-widget">
                        <h3>Company</h3>
                        <ul class="links-list">
                            <li>
                                <router-link to="/privacy-policy">About Us</router-link>
                            </li>
                            <li>
                                <router-link to="/privacy-policy">Collaborators</router-link>
                            </li>
                            <li>
                                <router-link to="/terms-conditions">Contact us</router-link>
                            </li>
                            <li>
                                <router-link to="/how-it-works">Glossary</router-link>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-lg-2 col-md-3 col-sm-6">
                    <div class="single-footer-widget">
                        <h3>Resources</h3>
                        <ul class="links-list">
                            <li>
                                <router-link to="/privacy-policy">Blog</router-link>
                            </li>
                            <li>
                                <router-link to="/privacy-policy">Success</router-link>
                            </li>
                            <li>
                                <router-link to="/terms-conditions">Stories</router-link>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-lg-2 col-md-6 col-sm-6">
                    <div class="single-footer-widget">
                        <h3>Get in touch</h3>
                        <ul class="links-list">
                            <li>
                                <router-link to="/">Locate us on map</router-link>
                            </li>
                            <li>
                                <router-link to="/">Mail us - Info@dealdocx.io</router-link>
                            </li>
                            <li>
                                <router-link to="/">Call us - 999999999</router-link>
                            </li>
                        </ul>
                        <!-- <p>Best solution for your it startup business, consecteturadipiscing elit.</p>
                        <form class="newsletter-form" data-toggle="validator">
                            <input type="text" class="input-newsletter" placeholder="Your Email" name="EMAIL">
                            <button type="submit">
                                <i class="ri-send-plane-2-line"></i>
                            </button>
                        </form> -->
                    </div>
                </div>
            </div>
            <div class="copyright-area">
                <div class="row col-lg-12 col-md-6 col-sm-6">
                    <div className="col-lg-6 col-md-6">
                        <p>Copyright {{ currentYear }} <strong>All right reserved @2023, </strong><a
                                href="https://dealdox.io/" target="_blank">DealDocx</a></p>
                    </div>

                    <div className="col-lg-6 col-md-6">
                        <p><router-link to="/terms-conditions">Terms & conditions</router-link> | <router-link to="/privacy-policy">Privacy Policy</router-link></p>
                    </div>
                </div>
            </div>
        </div>

        <div class="footer-wrap-shape">
            <img src="../../assets/images/more-home/footer/footer-shape-2.png" alt="image">
        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterStyleFour',
    data() {
        return {
            currentYear: new Date().getFullYear(),
        };
    }
}
</script>