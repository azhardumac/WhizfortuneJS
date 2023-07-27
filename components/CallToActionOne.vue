<template>
    <div class="section-padding-t90-b100 overflow-hidden">
        <div class="container shape-animate">
            <!-- Section Title Start -->
            <SectionTitle title="We are a full-service creative agency" sub-title="Our team of designers, developers and creatives are perfectionists who love what they do and love where they work" add-class-name="mb-30" />
            <!-- Section Title End -->

            <div class="row row-cols-lg-3 row-cols-md-2 row-cols-sm-2 row-cols-1 mtn-30">
                <div class="col mt-30" data-aos="fade-up">
                    <div class="contact-info">
                        <div class="icon">
                            <img class="svgInject" src="/images/svg/linea/linea-basic-map.svg" alt="Icon">
                        </div>
                        <div class="info">
                            <h4 class="title">Our Location</h4>
                            <span class="info-text"> Konark Business Hub. <br> Pune, India.</span>
                        </div>
                    </div>
                </div>

                <div class="col mt-30" data-aos="fade-up">
                    <div class="contact-info">
                        <div class="icon">
                            <img class="svgInject" src="/images/svg/linea/linea-basic-message-txt.svg" alt="Icon">
                        </div>
                        <div class="info">
                            <h4 class="title">Give Us A Call</h4>
                            <a class="info-text" href="tel:08956786421"> +91-8956786421 <br> </a>
                            <a class="info-text" href="tel:08956786421"> <br> </a>

                        </div>
                    </div>
                </div>

                <div class="col mt-30" data-aos="fade-up">
                    <div class="contact-info">
                        <div class="icon">
                            <img class="svgInject" src="/images/svg/linea/linea-basic-mail-open-text.svg" alt="Icon">
                        </div>
                        <div class="info">
                            <h4 class="title">Help Desk</h4>
                            <span class="info-text">
                                <a href="mailto:info@whizfortune.com">info@whizfortune.com</a>
                                <br>
                                <a href="mailto:support@whizfortune.com">support@whizfortune.com</a>
                            </span>
                        </div>
                    </div>
                </div>
            </div>

            <shape-with-animation add-class-name="shape-1" data-depth="4" img-src="/images/shape-animation/video-shape-1.png" />

        </div>
    </div>
</template>

<script>

    export default {
        components: {
            SectionTitle: () => import("@/components/SectionTitle"),
            ShapeWithAnimation: () => import("@/components/ShapeWithAnimation"),
        },
    };
</script>
