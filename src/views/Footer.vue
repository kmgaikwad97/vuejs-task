<template>
<footer style="background: #284948">
    <div class="container py-5 px-lg-3 px-5">
        <div class="row">
            <div class="col-12 col-sm-6 col-md-4 col-lg">
                <strong class="text-white">Reach Out to us</strong> <br />
                <span class="text-white">Lorem epsum Ptv Ltd.</span> <br />

                <div class="pt-4 footer-icon">
                    <ul class="list-unstyled where-data text-start">
                        <li class="location">
                            <a style="text-decoration: none; color: white">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                Exercitationem, quo saepe velit libero ea tempora odio.</a>
                        </li>
                        <li class="phone">
                            <a style="text-decoration: none; color: white" href="tel:91452547452">+91452547452</a>
                        </li>
                        <li class="mail">
                            <a style="text-decoration: none; color: white" href="loremepsum@gmail.com">loremepsum@gmail.com</a>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="col-12 col-sm-6 col-md-4 col-lg pt-5 text-white">
                <h5>About</h5>
                <ul class="list-unstyled about-data text-start">
                    <li><a>Contact Us</a></li>
                    <li><a>About Us</a></li>
                    <li><a>Careers</a></li>
                    <li><a>Blogs</a></li>
                    <li><a>Sitemap</a></li>
                    <li><a>Map Account</a></li>
                </ul>
            </div>

            <div class="col-12 col-sm-6 col-md-4 col-lg pt-5 text-white">
                <h5>Policy Info</h5>
                <ul class="list-unstyled about-data text-start">
                    <li><a>Privacy Policy</a></li>
                    <li><a>Terms of Use</a></li>
                    <li><a>Return Policy</a></li>
                </ul>
            </div>

            <div class="col-12 col-sm-6 col-md-4 col-lg pt-5 text-white">
                <h5>Need Help?</h5>
                <ul class="list-unstyled about-data text-start">
                    <li><a>FAQs</a></li>
                    <li><a>Online Support</a></li>
                    <li><a>Customer Support</a></li>
                </ul>
                <button class="btn btn-warning reqbtn">REQUEST DEMO</button>
            </div>

            <div class="col-12 col-sm-6 col-md-4 col-lg pt-5 text-white">
                <h5>Subscribe Our Newsletter</h5>
                <div class="input-group mb-3">
                    <input type="text" class="form-control" placeholder="Enter Your Email" aria-label="Recipient's username" aria-describedby="button-addon2" />
                    <button class="btn newsletter-btn btn-warning" type="button" id="button-addon2">
                        <i class="fa-solid text-white fa-arrow-right-long"></i>
                    </button>
                </div>
                <p class="small appletter">
                    Register now to get updates on promotions and coupons or Download
                    App
                </p>
            </div>
        </div>

        <div class="row py-lg-2 py-5">
            <div class="col text-lg-end text-white fw-light">
                <small>@ Copyright 2021 UniteCloud</small>
            </div>
        </div>
    </div>
</footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer-icon {
    color: #f28737;
}

.reqbtn {
    background: #f28737 !important;
    color: white !important;
    border: #f28737 !important;
    font-size: 11px !important;
    font-weight: 400 !important;
}

.about-data li a {
    font-weight: 300;
    cursor: pointer;
    text-decoration: none;
    color: white;
}
.about-data li {
padding-bottom: 5px;
}

.newsletter-btn {
    background: #f28737 !important;
    color: white;
    border: #f28737 !important;
}

.location::marker,
.phone::marker,
.email::marker {
    /* position: absolute; */
    font-family: FontAwesome;
    content: "\f3c5";
    color: #f28737;
}

.where-data li {
    padding-left: 7px;
    padding-bottom:10px;
}
.where-data li a{
    padding-left: 7px;
    font-weight: 300;
}

.phone::marker {
    content: "\f095";
}

.mail::marker {
    content: "\f0e0";
    font-family: FontAwesome;
}
.appletter{
    font-weight: 300;
}
</style>
