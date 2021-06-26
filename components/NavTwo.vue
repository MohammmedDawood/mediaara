<template>
  <header
    :class="`main-header header-style-two ${sticky ? 'fixed-header' : ''}`"
  >
    <!-- Header Upper -->
    <div class="header-upper">
      <div class="inner-container clearfix">
        <!--Logo-->
        <div class="logo-box">
          <div class="logo">
            <a href="/" title="mediaara - DIgital Agency Template"
              ><img
                src="/images/mediaara-logo-whiteo.png"
                id="thm-logo"
                alt="mediaara - Digital Agency HTML Template"
                title="mediaara - DIgital Agency Template"
            /></a>
          </div>
        </div>
        <div class="nav-outer clearfix">
          <!--Mobile Navigation Toggler-->
          <div class="mobile-nav-toggler">
            <span
              @click="mobileToggle = !mobileToggle"
              class="icon flaticon-menu-2"
            ></span
            ><span class="txt">Menu</span>
          </div>

          <!-- Main Menu -->
          <nav class="main-menu navbar-expand-md navbar-light">
            <div class="collapse navbar-collapse show clearfix">
              <ul class="navigation clearfix">
                <li class="current dropdown">
                  <a href="/">Home</a>
                  <ul>
                    <li><NuxtLink to="/">Home Style 01</NuxtLink></li>
                    <li><NuxtLink to="/index-2">Home Style 02</NuxtLink></li>
                    <li><NuxtLink to="/index-3">Home Style 03</NuxtLink></li>
                  </ul>
                </li>
                <li><NuxtLink to="/about">About Us</NuxtLink></li>
                <li class="dropdown">
                  <a href="/team">Pages</a>
                  <ul>
                    <li><NuxtLink to="/team">Our Team</NuxtLink></li>
                    <li>
                      <NuxtLink to="/testimonials">Testimonials</NuxtLink>
                    </li>
                    <li><NuxtLink to="/faqs">FAQs</NuxtLink></li>
                    <li><NuxtLink to="/not-found">404 Page</NuxtLink></li>
                  </ul>
                </li>
                <li class="dropdown">
                  <NuxtLink to="/services">Services</NuxtLink>
                  <ul>
                    <li><NuxtLink to="/services">All Services</NuxtLink></li>
                    <li>
                      <NuxtLink to="/web-development"
                        >Website Development</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/graphic-designing"
                        >Graphic Designing</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/digital-marketing"
                        >Digital Marketing</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/seo">SEO & Content Writting</NuxtLink>
                    </li>
                    <li>
                      <NuxtLink to="/app-development">App Development</NuxtLink>
                    </li>
                    <li>
                      <NuxtLink to="/ui-designing">UI/UX Designing</NuxtLink>
                    </li>
                  </ul>
                </li>
                <li class="dropdown">
                  <NuxtLink to="/portfolio">Portfolio</NuxtLink>
                  <ul>
                    <li><NuxtLink to="/portfolio">Portfolio</NuxtLink></li>
                    <li>
                      <NuxtLink to="/portfolio-single"
                        >Portfolio Single 01</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/portfolio-single-2"
                        >Portfolio Single 02</NuxtLink
                      >
                    </li>
                  </ul>
                </li>
                <li class="dropdown">
                  <NuxtLink to="/blog-grid">Blog</NuxtLink>
                  <ul>
                    <li><NuxtLink to="/blog">Blog Sidebar</NuxtLink></li>
                    <li>
                      <NuxtLink to="/blog-grid">Blog Grid View</NuxtLink>
                    </li>
                    <li>
                      <NuxtLink to="/blog-single">Blog Single</NuxtLink>
                    </li>
                  </ul>
                </li>
                <li><NuxtLink to="/contact">Contact</NuxtLink></li>
              </ul>
            </div>
          </nav>
        </div>

        <div class="other-links clearfix">
          <div class="link-box">
            <div class="call-us">
              <a class="link" href="tel:+20 10 5053 0010">
                <span class="icon"></span>
                <span class="sub-text">Call Anytime</span>
                <span class="number">+20 10 5053 0010</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--End Header Upper-->
    <nav class="mobile-nav__container">
      <!-- content is loading via js -->

      <div
        :class="`collapse navbar-collapse ${
          mobileToggle ? 'show' : ''
        } clearfix`"
      >
        <ul class="navigation clearfix">
          <li class="dropdown">
            <a href="#"
              >Home
              <div class="dropdown-btn">
                <span class="fa fa-angle-right"></span></div
            ></a>
            <ul class="sub-menu">
              <li><NuxtLink to="/">Home Style 01</NuxtLink></li>
              <li><NuxtLink to="/index-2">Home Style 02</NuxtLink></li>
              <li><NuxtLink to="/index-3">Home Style 03</NuxtLink></li>
            </ul>
          </li>
          <li><NuxtLink to="/about">About Us</NuxtLink></li>
          <li class="dropdown">
            <a href="#"
              >Pages
              <div class="dropdown-btn">
                <span class="fa fa-angle-right"></span></div
            ></a>
            <ul class="sub-menu">
              <li><NuxtLink to="/team">Our Team</NuxtLink></li>
              <li><NuxtLink to="/testimonials">Testimonials</NuxtLink></li>
              <li><NuxtLink to="/faqs">FAQs</NuxtLink></li>
              <li><NuxtLink to="/not-found">404 Page</NuxtLink></li>
            </ul>
          </li>
          <li class="dropdown">
            <NuxtLink to="#"
              >Services
              <div class="dropdown-btn">
                <span class="fa fa-angle-right"></span></div
            ></NuxtLink>
            <ul class="sub-menu">
              <li><NuxtLink to="/services">All Services</NuxtLink></li>
              <li>
                <NuxtLink to="/web-development">Website Development</NuxtLink>
              </li>
              <li>
                <NuxtLink to="/graphic-designing">Graphic Designing</NuxtLink>
              </li>
              <li>
                <NuxtLink to="/digital-marketing">Digital Marketing</NuxtLink>
              </li>
              <li><NuxtLink to="/seo">SEO & Content Writting</NuxtLink></li>
              <li>
                <NuxtLink to="/app-development">App Development</NuxtLink>
              </li>
              <li><NuxtLink to="/ui-designing">UI/UX Designing</NuxtLink></li>
            </ul>
          </li>
          <li class="dropdown">
            <NuxtLink to="#"
              >Portfolio
              <div class="dropdown-btn">
                <span class="fa fa-angle-right"></span></div
            ></NuxtLink>
            <ul class="sub-menu">
              <li><NuxtLink to="/portfolio">Portfolio</NuxtLink></li>
              <li>
                <NuxtLink to="/portfolio-single">Portfolio Single 01</NuxtLink>
              </li>
              <li>
                <NuxtLink to="/portfolio-single-2"
                  >Portfolio Single 02</NuxtLink
                >
              </li>
            </ul>
          </li>
          <li class="dropdown">
            <NuxtLink to="#"
              >Blog
              <div class="dropdown-btn">
                <span class="fa fa-angle-right"></span></div
            ></NuxtLink>
            <ul class="sub-menu">
              <li><NuxtLink to="/blog">Blog Sidebar</NuxtLink></li>
              <li><NuxtLink to="/blog-grid">Blog Grid View</NuxtLink></li>
              <li><NuxtLink to="/blog-single">Blog Single</NuxtLink></li>
            </ul>
          </li>
          <li><NuxtLink to="/contact">Contact</NuxtLink></li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Nav',
  data() {
    return {
      sticky: false,
      mobileToggle: false,
    }
  },
  mounted() {
    window.addEventListener('scroll', this.handleScroll)

    const mobileNav = document.querySelector('.mobile-nav__container')
    const dropdownMenu = mobileNav.querySelectorAll('.dropdown')

    for (let i = 0; i < dropdownMenu.length; i++) {
      dropdownMenu[i].addEventListener('click', function () {
        this.classList.toggle('open')
        this.classList.toggle('current')
      })
    }
  },
  methods: {
    handleScroll() {
      if (window.scrollY > 70) {
        this.sticky = true
      } else if (window.scrollY < 70) {
        this.sticky = false
      }
    },
  },
}
</script>

<style scoped></style>
