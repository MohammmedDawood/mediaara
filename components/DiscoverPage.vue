<template>
  <section class="discover-section">
    <div class="auto-container">
      <div class="row clearfix">
        <!--Discover Block-->
        <div class="discover-block col-lg-6 col-md-12 col-sm-12">
          <div class="inner-box">
            <div class="image-box">
              <img src="/images/resource/featured-image-11.jpg" alt="" />
            </div>
            <div
              class="cap-box wow fadeInUp"
              data-wow-delay="0ms"
              data-wow-duration="1500ms"
            >
              <div class="cap-inner">
                <h5>All-in-One Web Solution for Your Business</h5>
                <div class="more-link">
                  <NuxtLink to="/about"
                    ><span class="fa fa-angle-right"></span
                  ></NuxtLink>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!--Discover Block-->
        <div class="discover-block col-lg-6 col-md-12 col-sm-12">
          <div class="inner-box">
            <div class="image-box">
              <img src="/images/resource/featured-image-12.jpg" alt="" />
            </div>
            <div
              class="cap-box wow fadeInUp"
              data-wow-delay="300ms"
              data-wow-duration="1500ms"
            >
              <div class="cap-inner">
                <h5>The best digital agency you’ll ever need</h5>
                <div class="more-link">
                  <NuxtLink class="theme-btn" to="/about"
                    ><span class="fa fa-angle-right"></span
                  ></NuxtLink>
                </div>
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
  name: 'DiscoverSection',
}
</script>

<style scoped></style>
