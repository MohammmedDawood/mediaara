<template>
  <div>
    <Nav />
    <PageHeader title="E-commerce" />
    <ServiceDetails />
    <CallToActionThree />
    <Footer />
  </div>
</template>
<script>
import Nav from "../components/Nav";
import PageHeader from "../components/PageHeader";
import Footer from "../components/Footer";
import CallToActionThree from "../components/CallToActionThree";
import ServiceDetails from "../components/ServiceDetails";
export default {
  components: {
    ServiceDetails,
    CallToActionThree,
    Footer,
    PageHeader,
    Nav
  },
  head() {
    return {
      title: "mediaara | E-commerce"
    };
  }
};
</script>
