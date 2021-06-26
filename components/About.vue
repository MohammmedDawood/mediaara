<template>
  <section class="about-section">
    <div class="auto-container">
      <div class="row clearfix">
        <!--Image Column-->
        <div class="image-column col-xl-6 col-lg-12 col-md-12 col-sm-12">
          <div class="inner">
            <div
              class="image-block wow fadeInLeft"
              data-wow-delay="0ms"
              data-wow-duration="1500ms"
            >
              <img src="/images/resource/featured-image-1.jpg" alt="" />
            </div>

            <div
              class="image-block wow fadeInUp"
              data-wow-delay="300ms"
              data-wow-duration="1500ms"
            >
              <img src="/images/resource/featured-image-2.jpg" alt="" />
            </div>
          </div>
        </div>
        <!--Text Column-->
        <div class="text-column col-xl-6 col-lg-12 col-md-12 col-sm-12">
          <div class="inner">
            <div class="sec-title">
              <h2>
                We’re the best agency <br />in middle east
                <span class="dot">.</span>
              </h2>
              <div class="lower-text">
                Mediaara is an Egyptian limited liability company (LLC).
                enriching the digital transformation process and supporting
                e-commerce systems in Egypt and the Arab Gulf States
              </div>
            </div>
            <div class="text">
              <p>
                Our team has passion, confidence, and sufficient experience.
              </p>
            </div>
            <div class="text clearfix">
              <ul>
                <li>branding solutions.</li>
                <li>Digital Marketing & Ads campaign.</li>
                <li>Integrated Solutions & eCommerce.</li>
                <li>Media Production services.</li>
                <li>PR & Media Events management.</li>
              </ul>
              <div class="since">
                <span class="txt">Since <br />2020</span>
              </div>
            </div>
            <div class="link-box">
              <NuxtLink class="theme-btn btn-style-one" to="/about">
                <i class="btn-curve"></i>
                <span class="btn-title">Discover More</span>
              </NuxtLink>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'About',
}
</script>

<style scoped></style>
