<template>
  <div>
    <section class="banner-section banner-one">
      <div class="left-based-text">
        <div class="base-inner">
          <div class="hours">
            <ul class="clearfix">
              <li><span>sun - thu</span></li>
              <li><span>9am - 7pm</span></li>
            </ul>
          </div>
          <div class="social-links">
            <ul class="clearfix">
              <li>
                <a href="https://twitter.com/"><span>Twitter</span></a>
              </li>
              <li>
                <a href="https://www.facebook.com/"><span>Facebook</span></a>
              </li>
              <li>
                <a href="https://www.youtube.com/"><span>Youtube</span></a>
              </li>
            </ul>
          </div>
        </div>
      </div>

      <div class="banner-carousel">
        <client-only>
          <!-- important to add client-only-->
          <carousel :items="1">
            <!-- Slide Item -->
            <div class="slide-item">
              <div
                class="image-layer"
                style="background-image: url(/images/main-slider/1.jpg)"
              ></div>
              <div class="left-top-line"></div>
              <div class="right-bottom-curve"></div>
              <div class="right-top-curve"></div>
              <div class="auto-container">
                <div class="content-box">
                  <div class="content">
                    <div class="inner">
                      <div class="sub-title">welcome to mediaara agency</div>
                      <h1>Marketing Agency</h1>
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
            </div>

            <!-- Slide Item -->
            <div class="slide-item">
              <div
                class="image-layer"
                style="background-image: url(/images/main-slider/2.jpg)"
              ></div>
              <div class="left-top-line"></div>
              <div class="right-bottom-curve"></div>
              <div class="right-top-curve"></div>
              <div class="auto-container">
                <div class="content-box">
                  <div class="content">
                    <div class="inner">
                      <div class="sub-title">welcome to mediaara agency</div>
                      <h1>Marketing Agency</h1>
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
            </div>
          </carousel>
        </client-only>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Banner',
}
</script>

<style scoped></style>
