<template>
  <section class="live-section">
    <div class="auto-container">
      <div class="sec-title centered">
        <h2>Experience us live <span class="dot">.</span></h2>
      </div>
      <div class="main-image-box">
        <div
          class="image-layer"
          style="background-image: url(/images/resource/featured-image-3.jpg)"
        ></div>
        <div class="inner clearfix">
          <div
            class="round-box wow fadeInUp"
            data-wow-delay="0ms"
            data-wow-duration="1500ms"
          >
            <div class="round-inner">
              <div class="vid-link">
                <a href="https://youtu.be/_KT4WYCucsA" class="glightbox2">
                  <div class="icon">
                    <span class="flaticon-play-button-1"></span
                    ><i class="ripple"></i>
                  </div>
                </a>
              </div>
              <div class="title">
                <h3>agency that gets <br />excited about</h3>
              </div>
              <div class="more-link">
                <NuxtLink to="/about">Read More</NuxtLink>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'LiveSection',
  mounted() {
    new GLightbox({
      selector: '.glightbox2',
      touchNavigation: true,
      loop: true,
      autoplayVideos: true,
    })
  },
}
</script>

<style scoped></style>
