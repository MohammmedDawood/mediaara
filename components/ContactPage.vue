<template>
  <section class="contact-section">
    <div class="auto-container">
      <div class="sec-title centered">
        <h2>Offices near you<span class="dot">.</span></h2>
      </div>

      <div class="upper-info">
        <div class="row clearfix">
          <div
            class="info-block col-xl-12 col-lg-12 col-md-12 col-sm-12 wow fadeInUp"
            data-wow-delay="0ms"
            data-wow-duration="1500ms"
          >
            <div class="inner-box">
              <h5>Giza</h5>
              <div class="text">
                <ul class="info">
                  <li>3 Dokki St.</li>
                  <li>
                    <a href="mailto:info@mediaara.com">info@mediaara.com</a>
                  </li>
                  <li><a href="tel:+20 10 5053 0010">+20 10 5053 0010</a></li>
                </ul>
              </div>
            </div>
          </div>

          <!-- <div
            class="info-block col-xl-3 col-lg-6 col-md-6 col-sm-12 wow fadeInUp"
            data-wow-delay="300ms"
            data-wow-duration="1500ms"
          >
            <div class="inner-box">
              <h5>Boston</h5>
              <div class="text">
                <ul class="info">
                  <li>5 Federal Street Boston</li>
                  <li>
                    <a href="mailto:needhelp@mediaara.com"
                      >needhelp@mediaara.com</a
                    >
                  </li>
                  <li><a href="tel:666888000">666 888 000</a></li>
                </ul>
              </div>
            </div>
          </div> -->

          <!-- <div
            class="info-block col-xl-3 col-lg-6 col-md-6 col-sm-12 wow fadeInUp"
            data-wow-delay="600ms"
            data-wow-duration="1500ms"
          >
            <div class="inner-box">
              <h5>New york</h5>
              <div class="text">
                <ul class="info">
                  <li>8th Broklyn New York</li>
                  <li>
                    <a href="mailto:needhelp@mediaara.com"
                      >needhelp@mediaara.com</a
                    >
                  </li>
                  <li><a href="tel:666888000">666 888 000</a></li>
                </ul>
              </div>
            </div>
          </div> -->

          <!-- <div
            class="info-block col-xl-3 col-lg-6 col-md-6 col-sm-12 wow fadeInUp"
            data-wow-delay="900ms"
            data-wow-duration="1500ms"
          >
            <div class="inner-box">
              <h5>baltimore</h5>
              <div class="text">
                <ul class="info">
                  <li>3 Lombabr 50 Baltimore</li>
                  <li>
                    <a href="mailto:needhelp@mediaara.com"
                      >needhelp@mediaara.com</a
                    >
                  </li>
                  <li><a href="tel:666888000">666 888 000</a></li>
                </ul>
              </div>
            </div>
          </div> -->
        </div>
      </div>

      <div class="map-box">
        <iframe
          class="map-iframe"
          src="https://maps.google.com/maps?q=mediaara&t=&z=13&ie=UTF8&iwloc=&output=embed"
          style="border:0;"
          aria-hidden="false"
          tabindex="0"
        ></iframe>
      </div>
      <div class="form-box">
        <div class="sec-title">
          <h2>Write Us a Message<span class="dot">.</span></h2>
        </div>
        <div class="default-form">
          <form method="post" action="#" id="contact-form">
            <div class="row clearfix">
              <div class="form-group col-lg-6 col-md-6 col-sm-12">
                <div class="field-inner">
                  <input
                    type="text"
                    name="username"
                    value=""
                    placeholder="Your Name"
                    required=""
                  />
                </div>
              </div>
              <div class="form-group col-lg-6 col-md-6 col-sm-12">
                <div class="field-inner">
                  <input
                    type="email"
                    name="email"
                    value=""
                    placeholder="Email Address"
                    required=""
                  />
                </div>
              </div>
              <div class="form-group col-lg-6 col-md-6 col-sm-12">
                <div class="field-inner">
                  <input
                    type="text"
                    name="phone"
                    value=""
                    placeholder="Phone Number"
                    required=""
                  />
                </div>
              </div>
              <div class="form-group col-lg-6 col-md-6 col-sm-12">
                <div class="field-inner">
                  <input
                    type="text"
                    name="subject"
                    value=""
                    placeholder="Subject"
                    required=""
                  />
                </div>
              </div>
              <div class="form-group col-lg-12 col-md-12 col-sm-12">
                <div class="field-inner">
                  <textarea
                    name="message"
                    placeholder="Write Message"
                    required=""
                  ></textarea>
                </div>
              </div>
              <div class="form-group col-lg-12 col-md-12 col-sm-12">
                <button class="theme-btn btn-style-one">
                  <i class="btn-curve"></i>
                  <span class="btn-title">Send message</span>
                </button>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContactPage"
};
</script>

<style scoped></style>
