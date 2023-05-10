<template>
    <div class="pricing-area ptb-75">
        <div class="container">
            <div class="section-title">
                <h2>Let’s get started?</h2>
                <p>Choose a plan that works best for your team and boost <br> your sales with DealDocx.</p>
            </div>
            <div class="row align-items-center justify-content-center">
                <div class="col-lg-4 col-md-6 col-sm-6">
                    <div class="single-pricing-box">
                        <div class="title">
                            <h3>FREE</h3>
                        </div>
                        <!-- <div class="price">
                            $39 <span>/Month</span>
                        </div> -->
                        
                        <ul class="features-list">
                            <li><i class="ri-check-line"></i> All free Features</li>
                            <li><i class="ri-check-line"></i> Personalized Document</li>
                            <li><i class="ri-check-line"></i> Templates Sales Dashboard</li>
                            <li><i class="ri-check-line"></i> API</li>
                            <li><i class="ri-check-line"></i> SSO Support</li>
                            <li><i class="ri-check-line"></i> Online forms</li>
                        </ul>
                        <br>
                        <router-link to="/contact" class="default-btn">Start Using for Free</router-link>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-6">
                    <div class="single-pricing-box active">
                        <div class="title">
                            <h3>Premium</h3>
                        </div>
                        <span class="popular">Most Popular</span>
                        <!-- <div class="price">
                            $49 <span>/Month</span>
                        </div> -->
                        <ul class="features-list">
                            <li><i class="ri-check-line"></i> All free Features</li>
                            <li><i class="ri-check-line"></i> Personalized Document</li>
                            <li><i class="ri-check-line"></i> Templates Sales Dashboard</li>
                            <li><i class="ri-check-line"></i> API</li>
                            <li><i class="ri-check-line"></i> SSO Support</li>
                            <li><i class="ri-check-line"></i> Online forms</li>
                            <li><i class="ri-check-line"></i> All free Features</li>

                        </ul>
                        <br>
                        <router-link to="/contact" class="default-btn">Request a Quote</router-link>

                    </div>
                </div>
                <!-- <div class="col-lg-12 col-md-12 col-sm-12">
                    <div class="see-more-pricing color-black">
                        <router-link to="/pricing" class="link-btn">See All Pricing Plan</router-link>
                    </div>
                </div> -->
            </div>
        </div>
        <!-- <div class="shape12"><img src="../../assets/images/shape/shape11.png" alt="shape"></div>
        <div class="shape13"><img src="../../assets/images/shape/shape15.png" alt="shape"></div> -->
    </div>
</template>

<script>
export default {
    name: 'Pricing'
}
</script>