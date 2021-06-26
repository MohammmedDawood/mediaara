<template>
  <section class="banner-section banner-three">
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

    <div
      class="bg-image"
      style="background-image: url(/images/main-slider/banner-bg-shape-3.png)"
    ></div>
    <div class="banner-carousel">
      <client-only>
        <carousel :items="1">
          <!-- Slide Item -->
          <div class="slide-item">
            <div class="round-shape-1"></div>
            <div class="round-image">
              <div
                class="image"
                style="background-image: url(/images/main-slider/image-1.jpg)"
              ></div>
            </div>
            <div class="auto-container">
              <div class="content-box">
                <div class="content">
                  <div class="inner">
                    <h1>Marketing Agency</h1>
                    <div class="text">
                      We are committed to providing our customers with
                      exceptional service while offering our employees the best
                      training.
                    </div>
                    <div class="link-box">
                      <NuxtLink class="theme-btn btn-style-two" to="/about">
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
            <div class="round-shape-1"></div>
            <div class="round-image">
              <div
                class="image"
                style="background-image: url(/images/main-slider/image-1.jpg)"
              ></div>
            </div>
            <div class="auto-container">
              <div class="content-box">
                <div class="content">
                  <div class="inner">
                    <h1>Marketing Agency</h1>
                    <div class="text">
                      We are committed to providing our customers with
                      exceptional service while offering our employees the best
                      training.
                    </div>
                    <div class="link-box">
                      <NuxtLink class="theme-btn btn-style-two" to="/about">
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
            <div class="round-shape-1"></div>
            <div class="round-image">
              <div
                class="image"
                style="background-image: url(/images/main-slider/image-1.jpg)"
              ></div>
            </div>
            <div class="auto-container">
              <div class="content-box">
                <div class="content">
                  <div class="inner">
                    <h1>Marketing Agency</h1>
                    <div class="text">
                      We are committed to providing our customers with
                      exceptional service while offering our employees the best
                      training.
                    </div>
                    <div class="link-box">
                      <NuxtLink class="theme-btn btn-style-two" to="/about">
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
</template>

<script>
export default {
  name: 'BannerThree',
}
</script>

<style scoped></style>
