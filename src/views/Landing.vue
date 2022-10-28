<template>
    <div>

        <div class="position-relative">
            <!-- shape Hero -->
            <section class="section-shaped my-0">
                <div class="shape shape-style-1 shape-default shape-skew bc-blue">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <div class="container shape-container d-flex">
                    <div class="col px-0">
                        <div class="row">
                            <div class="col-lg-6">
                                <h1 class="display-3  text-white">[title]
                                    <span></span>
                                </h1>
                                <p class="lead  text-white">[description]</p>
                                <div class="btn-wrapper">
                                    <base-button tag="a"
                                                 href="/services"
                                                 class="mb-3 mb-sm-0"
                                                 type="warning"
                                                 icon="fa fa-info">
                                        [button]
                                    </base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <section class="section section-lg pt-lg-0 mt--200">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-primary text-uppercase">Construction</h6>
                                    <p class="description mt-3">[description]</p>
                                    <div>
                                        <badge type="primary" rounded>experienced</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="primary" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-check-bold" type="success" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-success text-uppercase">Capentry</h6>
                                    <p class="description mt-3">[description]</p>
                                    <div>
                                        <badge type="success" rounded>reliable</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="success" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-check-bold" type="warning" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-warning text-uppercase">Coating</h6>
                                    <p class="description mt-3">[description]</p>
                                    <div>
                                        <badge type="warning" rounded>stunning</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="warning" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-md-2">
                        <img src="img/theme/promo-1.png" class="img-fluid floating">
                    </div>
                    <div class="col-md-6 order-md-1">
                        <div class="pr-md-5">
                            <icon name="ni ni-settings-gear-65" class="mb-5" size="lg" type="success" shadow
                                  rounded></icon>
                            <h3>[title]</h3>
                            <p>[description]</p>
                            <ul class="list-unstyled mt-5">
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-settings-gear-65"></badge>
                                        <h6 class="mb-0">[bullet point 1]</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-html5"></badge>
                                        <h6 class="mb-0">[bullet point 2]</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-satisfied"></badge>
                                        <h6 class="mb-0">[bullet point 3]</h6>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section bg-secondary">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6">
                        <div class="card bg-default shadow border-0">
                            <img v-lazy="'img/theme/img-1-1200x1000.jpg'" class="card-img-top">
                            <blockquote class="card-blockquote">
                                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                                     class="svg-bg">
                                    <polygon points="0,52 583,95 0,95" class="fill-default"></polygon>
                                    <polygon points="0,42 583,95 683,0 0,95" opacity=".2" class="fill-default"></polygon>
                                </svg>
                                <h4 class="display-3 font-weight-bold text-white">[title]</h4>
                                <p class="lead text-italic text-white">[description]</p>
                            </blockquote>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="pl-md-5">
                            <icon name="ni ni-settings" class="mb-5" size="lg" type="warning" shadow rounded></icon>

                            <h3>[title]</h3>
                            <p class="lead">[description]</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-1 bg-gradient-warning shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container py-0">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-lg-2 ml-lg-auto">
                        <div class="position-relative pl-md-5">
                            <img src="img/ill/ill-2.svg" class="img-center img-fluid">
                        </div>
                    </div>
                    <div class="col-lg-6 order-lg-1">
                        <div class="d-flex px-3">
                            <div>
                                <icon name="ni ni-building" size="lg" class="bg-gradient-white" color="primary" shadow
                                      rounded></icon>
                            </div>
                            <div class="pl-4">
                                <h4 class="display-3 text-white">[title]</h4>
                                <p class="text-white">[description]</p>
                            </div>
                        </div>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-satisfied" gradient="success" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-success">[bullet point]</h5>
                                    <p>[description]</p>
                                    <a href="#" class="text-success">Learn more</a>
                                </div>
                            </div>
                        </card>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-active-40" gradient="warning" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-warning">[bullet point]</h5>
                                    <p>[description]</p>
                                    <a href="#" class="text-warning">Learn more</a>
                                </div>
                            </div>
                        </card>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg">
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">Our Team</h2>
                        <p class="lead text-muted">[description]</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy=""
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Kelly Hebert</span>
                                    <small class="h6 text-muted">CEO</small>
                                </h5>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy=""
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Al Hebert</span>
                                    <small class="h6 text-muted">President</small>
                                </h5>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy=""
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Dusty Martin</span>
                                    <small class="h6 text-muted">COO</small>
                                </h5>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy=""
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">John Doe</span>
                                    <small class="h6 text-muted">Random</small>
                                </h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt-lg pb-300">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h2 class="display-3 text-white">[title]</h2>
                        <p class="lead text-white">[description]</p>
                    </div>
                </div>
                <div class="row row-grid mt-5">
                    <div class="col-lg-4">
                        <icon name="ni ni-settings" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">[blurb 1]</h5>
                        <p class="text-white mt-3">[description]</p>
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-ruler-pencil" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">[blurb 2]</h5>
                        <p class="text-white mt-3">[description]</p>
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-atom" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">[blurb 3]</h5>
                        <p class="text-white mt-3">[description]</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-lg-0 section-contact-us">
            <div class="container">
                <div class="row justify-content-center mt--300">
                    <div class="col-lg-8">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Questions or Comments?</h4>
                            <p class="mt-0">Your feedback is very important to us.</p>
                            <base-input class="mt-5"
                                        alternative
                                        placeholder="Your name"
                                        addon-left-icon="ni ni-user-run">
                            </base-input>
                            <base-input alternative
                                        placeholder="Email address"
                                        addon-left-icon="ni ni-email-83">
                            </base-input>
                            <base-input class="mb-4">
                                    <textarea class="form-control form-control-alternative" name="name" rows="4"
                                              cols="80" placeholder="Type a message..."></textarea>
                            </base-input>
                            <base-button type="default" round block size="lg">
                                Send Message
                            </base-button>
                        </card>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
  name: "home",
  components: {}
};
</script>
