<template>
    <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel class="hero-items" :items="1" :nav="false" :dots="false" :autoplay="true">

            <div class="single-hero-items set-bg" style="background-image: url('/img/cloth1.jpg');">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Cloth, Boys</span>
                            <h1>Black friday</h1>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
                                incididunt ut labore
                                et dolore
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="single-hero-items set-bg" style="background-image: url('/img/cloth1.jpg');">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Cloth, Boys</span>
                            <h1>Black friday</h1>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
                                incididunt ut labore
                                et dolore
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>

        </carousel>
    </section>
    <!-- Hero Section End -->
</template>

<script>
import carousel from 'vue-owl-carousel';

export default {
    name : 'HeroDomn',
    components : {
        carousel
    }
}
</script>