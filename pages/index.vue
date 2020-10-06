<template>
  <div class="">
    <Hero />
    <Solutions />
    <Integration />
    <Tooling />
    <CTA />
    <Design />
    <Security />
    <Extensions />
    <Reviews />
    <Testimonial />
    <Pricing />
    <Features />
  </div>
</template>

<script>
import Hero from "~/components/landing/Hero";
import Solutions from "~/components/landing/Solutions";
import Features from "~/components/content/Features";
import Testimonial from "~/components/content/Testimonial";
import Tooling from "~/components/content/Tooling";
import CTA from "~/components/content/CTA";
import Design from "~/components/content/Design";
import Reviews from "~/components/content/Reviews";
import Extensions from "~/components/content/Extensions";
import Integration from "~/components/content/Integration";
import Security from "~/components/content/Security";
import Pricing from "~/components/content/Pricing";
export default {
  components: {
    Hero,
    Solutions,
    Testimonial,
    Features,
    Pricing,
    Tooling,
    Extensions,
    CTA,
    Design,
    Security,
    Reviews
  },
  head() {
    return {
      title: "Jira, by Atlassian | Clone",
      script: [
        {
          src:
            "https://cdn.jsdelivr.net/gh/akhilarjun/tinylibs@latest/themejs/theme.min.js",
          type: "text/javascript",
          onload: 'setupThemeIcon()',
          defer: true,
        },
      ],
    };
  },
};
</script>

<style>
</style>
