<template>
  <section class="we-do-section">
    <div class="auto-container">
      <div class="row clearfix">
        <!--Left Column-->
        <div class="left-col col-lg-6 col-md-12 col-sm-12">
          <div class="inner">
            <div class="sec-title">
              <h2>
                We do more than ever <br />strategies <span class="dot">.</span>
              </h2>
            </div>
            <div class="featured-block clearfix">
              <div class="image">
                <img src="/images/resource/featured-image-4.jpg" alt="" />
              </div>
              <div class="text">
                Branding content creation, and design of various electronic
                products. As well as creating the best innovative marketing and
                promotional solutions to expand the audience base of its
                customers and achieve the highest return on investment on the
                internet.
              </div>
            </div>
            <div class="progress-box">
              <div class="bar-title">Branding & Digital marketing</div>
              <div class="bar">
                <div class="progress-bar">
                  <span class="progress-bar-fill" style="width: 90%;"></span>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!--Right Column-->
        <div class="right-col col-lg-6 col-md-12 col-sm-12">
          <div class="inner">
            <div class="faq-box">
              <div class="accordion-container-one">
                <!-- Branding  -->
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">
                    Integrated branding solutions
                  </h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">
                      The perfect design, composition, and design of brand
                      fundamentals is the creation and creation process that
                      requires high artistic, professional touches, and a lot of
                      experience. Therefore, the mediaara team helps you to plan
                      well, study competitors, partners, and target audiences,
                      to shape the brand of enterprises and projects, and to
                      build their distinct personality and unique voice.
                    </p>
                  </div>
                </div>
                <!-- Marketing   -->
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">
                    Digital Marketing Services and Ads campaign management
                  </h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">
                      High competitiveness. It requires constant attention and
                      constant follow-up of updates on applications and social
                      media, to reach the target audience and attract them to
                      buy products or try services and talk to them to build a
                      strong and continuous relationship. The mediaara team has
                      sufficient experience to create and update social media
                      platforms, and to manage them to create a wide audience
                      base.
                    </p>
                  </div>
                </div>
                <!-- Digital & e-commerce solutions  -->
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">
                    Digital & E-Commerce Solutions
                  </h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">
                      A creative team of designers and developers is ready to
                      start your journey to launch a premium website that
                      expresses the brand’s message, giving it powerful
                      competitive features, by providing sufficient tools to
                      control all phases and content edits.
                    </p>
                  </div>
                </div>
                <!-- Media services & production  -->
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">
                    Media Services & Production
                  </h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">
                      Artistic Production, Video, and Animation Services.<br />
                      Photography and album production services.
                    </p>
                  </div>
                </div>
                <!-- PR & Event Management  -->
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">
                    PR & Event Management
                  </h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">
                      We have an expert team in organizing events and occasions,
                      which has high efficiency for planning and preparing
                      events for the opening and launching of new projects.
                    </p>
                  </div>
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
  name: "WedoSection",
  mounted() {
    new Accordion(".accordion-container-one");
  }
};
</script>

<style scoped>
.ac {
  margin-top: 10px;
  padding: 10px;
  background: #fff;
  box-sizing: border-box;
}

.ac > .ac-q {
  font: bold 15px Arial, sans-serif;
  font-size: 20px;
  color: #444;
  padding: 10px 30px 10px 10px;
  margin: 0;
  text-decoration: none;
  display: block;
  cursor: pointer;
  position: relative;
  font-weight: 500;
  text-transform: uppercase;
  font-family: Teko;
}

.ac.is-active .ac-q {
  color: #ffaa17 !important;
}
.ac > .ac-q::after {
  content: "+";
  text-align: center;
  width: 15px;
  right: 10px;
  top: 50%;
  -webkit-transform: translate(0, -50%);
  transform: translate(0, -50%);
  position: absolute;
}

.ac > .ac-a {
  overflow: hidden;
  -webkit-transition-property: all;
  transition-property: all;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}

.ac > .ac-a p {
  font: 16px/1.5 Arial, sans-serif;
  color: #444;
  margin: 0;
  padding: 10px;
}

.ac.js-enabled > .ac-a {
  visibility: hidden;
}

.ac.is-active > .ac-a {
  visibility: visible;
}

.ac.is-active > .ac-q::after {
  content: "\2013";
  color: #ffaa17;
}

.progress-bar {
  width: 100%;
  background-color: #e0e0e0;
  padding: 3px;
  border-radius: 3px;
  box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.2);
}

.progress-bar-fill {
  display: block;
  height: 7px;
  background-color: #ffaa17;
  border-radius: 3px;

  transition: width 500ms ease-in-out;
}
</style>
