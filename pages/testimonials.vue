<template>
  <div>
    <Nav />
    <PageHeader title="Testimonials" />
    <TestimonialPage />
    <Footer />
  </div>
</template>
<script>
import Nav from "../components/Nav";
import PageHeader from "../components/PageHeader";
import Footer from "../components/Footer";
import TestimonialPage from "../components/TestimonialPage";
export default {
  components: {
    TestimonialPage,
    Footer,
    PageHeader,
    Nav
  },
  head() {
    return {
      title: "mediaara | Testimonials"
    };
  }
};
</script>
