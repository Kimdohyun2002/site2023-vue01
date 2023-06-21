<template>
  <main>
    <SliderSection attr="slider_wrap gamrket5" />
    <IntroSection attr="intro__wrap section bg-blue gmarket5" />
    <PortSection attr="port__wrap section center bg-blue gmarket5" />
    <YoutubeSection attr="youtube__wrap section gmarket5" />
    <UnsplashSection attr="unsplash__wrap section gmarket5" />
    <MovieSection attr="movie__wrap section gmarket5" />
  </main>
</template>

<script>
import SliderSection from "@/components/section/SliderSection.vue";
import IntroSection from "@/components/section/IntroSection.vue";
import PortSection from "@/components/section/PortSection.vue";
import MovieSection from "@/components/section/MovieSection.vue";
import YoutubeSection from "@/components/section/YoutubeSection.vue";
import UnsplashSection from "@/components/section/UnsplashSection.vue";

export default {
  components: {
    IntroSection,
    SliderSection,
    PortSection,
    MovieSection,
    YoutubeSection,
    UnsplashSection,
  },
};
</script>
