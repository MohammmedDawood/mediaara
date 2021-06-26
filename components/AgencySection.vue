<template>
  <section class="agency-section">
    <div class="auto-container">
      <div class="row clearfix">
        <!--Left Column-->
        <div class="left-col col-xl-6 col-lg-12 col-md-12 col-sm-12">
          <div class="inner">
            <div class="sec-title">
              <h2>
                Best Marketing Agency <br />solutions <span class="dot">.</span>
              </h2>
            </div>

            <!--Default Tabs-->
            <div class="default-tabs tabs-box">
              <div class="agency-tabs">
                <!--Tab-->
                <input
                  type="radio"
                  name="tabs"
                  id="tab-two"
                  checked="checked"
                />
                <label for="tab-two" class="tab-btn">Vision</label>
                <div class="tab">
                  <div class="active-tab">
                    <div class="content">
                      <div class="text">
                        From its very first moment, Mediaara was established to
                        become a key player in the process of digital
                        transformation, which has become a national trend in
                        Egypt after the state confirmed its entry into the
                        e-governance space by laying the foundations of
                        electronic connectivity, financial inclusion, and modern
                        trade; According to the Egypt 2030 plan, with the launch
                        of the first phase of the digital transformation system
                        in Port-Said in August 2019.
                      </div>
                    </div>
                  </div>
                </div>

                <!--Tab-->
                <input
                  type="radio"
                  name="tabs"
                  id="tab-one"
                  checked="checked"
                />
                <label for="tab-one" class="tab-btn">Mission</label>
                <div class="tab">
                  <div class="active-tab">
                    <div class="content">
                      <div class="text">
                        A “green cloud” is man’s hope for the near future.
                        Mediaara pledges to make every effort to achieve the
                        goals of digital transformation policies in our Arab
                        world. We are committed to our role in creating
                        opportunities and enhancing the capabilities necessary
                        to create a work environment that adopts the concepts of
                        “green technology” in the highly developed world of
                        economies.
                      </div>
                    </div>
                  </div>
                </div>

                <!--Tab-->
                <input
                  type="radio"
                  name="tabs"
                  id="tab-three"
                  checked="checked"
                />
                <label for="tab-three" class="tab-btn">Philosophy</label>
                <div class="tab">
                  <div class="active-tab">
                    <div class="content">
                      <div class="text">
                        Indeed, according to developments, it will not be long
                        until other stages of this giant transformation project
                        are completed, entering city after city into the world
                        of modern economics. This augurs well for the opening of
                        new markets throughout Egypt and the Arab world that
                        deserve good institutional, technical, and creative
                        preparedness. So, we established mediaara.
                      </div>
                    </div>
                  </div>
                </div>

                <!--Tab-->
                <input
                  type="radio"
                  name="tabs"
                  id="tab-four"
                  checked="checked"
                />
                <label for="tab-four" class="tab-btn">Passion</label>
                <div class="tab">
                  <div class="active-tab">
                    <div class="content">
                      <div class="text">
                        Mediaara looking for lead and actively contribute to
                        supporting new emerging markets that are based on
                        digital transformation and green technology policies. In
                        addition to our aspiration to play a serious role in
                        developing our environments and societies, which need
                        creative energies that have the responsibility,
                        credibility, and experience necessary to produce
                        integrated solutions for entrepreneurs and investors.
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!--Right Column-->
        <div class="right-col col-xl-6 col-lg-12 col-md-12 col-sm-12">
          <div class="inner">
            <div class="text">
              In every service we provide, we are carefully planning, set up,
              stick with good schedules, and adapt all the possibilities for
              accurate results; we build on them new plans for new steps in an
              ongoing creative process.
            </div>
            <div class="featured-block-two clearfix">
              <div class="image">
                <img src="/images/resource/featured-image-6.jpg" alt="" />
              </div>
              <div class="text">
                <ul>
                  <li>Integrated branding solutions.</li>
                  <li>
                    Digital Marketing Services and Ads campaign management.
                  </li>
                  <li>
                    Design, developing, and technical support services for
                    websites and applications.
                  </li>
                  <li>Artistic Production, Video, and Animation Services.</li>
                  <li>Photography and album production services.</li>
                  <li>Public Relations and Media Events management.</li>
                </ul>
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
  name: "AgencySection"
};
</script>

<style>
.agency-tabs {
  display: flex;
  flex-wrap: wrap;
}
.agency-tabs label {
  order: 1;
  display: block;
  padding: 4px 31px;
  margin-right: 0.2rem;
  cursor: pointer;
  background: #ffaa17;
  font-weight: 500;
  transition: background ease 0.2s;
  font-size: 18px;
  text-transform: uppercase;
  color: #222;
}
.agency-tabs .tab {
  order: 99;
  flex-grow: 1;
  width: 100%;
  display: none;
  padding: 1rem;
  background: #f4f5f8;
}
.default-tabs .agency-tabs .text {
  position: relative;
  font-size: 20px;
  font-weight: 300;
  color: var(--thm-text);
  line-height: 1.7em;
  letter-spacing: 2px;
}
.agency-tabs input[type="radio"] {
  display: none;
}
.agency-tabs input[type="radio"]:checked + label {
  background: #f4f5f8;
}
.agency-tabs input[type="radio"]:checked + label + .tab {
  display: block;
}

@media (max-width: 45em) {
  .agency-tabs .tab,
  .agency-tabs label {
    order: initial;
  }
  .agency-tabs label {
    width: 100%;
    margin-right: 0;
    margin-top: 0.2rem;
  }
}
</style>
