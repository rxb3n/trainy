<template>

<NavView/>
<HeroView/>
<ClientView/>
<DescriptionView/>
<ServicesView/>
<ReviewView/>
<BannerView/>
<LocationView/>
<FooterView/>

</template>

<script>
import NavView from './components/NavView.vue'
import HeroView from './components/HeroView.vue'
import DescriptionView from './components/DescriptionView.vue'
import ServicesView from './components/ServicesView.vue'
import ReviewView from './components/ReviewView.vue'
import ClientView from './components/ClientView.vue'
import FooterView from './components/FooterView.vue'
import BannerView from './components/BannerView.vue'
import LocationView from './components/LocationView.vue'

export default {
  name: 'App',
  components: {
    NavView,
    HeroView,
    DescriptionView,
    ServicesView,
    ReviewView,
    ClientView,
    FooterView,
    BannerView,
    LocationView,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Bitter:wght@400;500&display=swap');

:root {
  --bg-primary: #880D1E;
  --bg-secondary: #DD2D4A;
  --bg-tertiary: #151E3F;
}

body, h1, h2, h3, h4, h5, h6{
  margin: 0;
  padding: 0;
  font-family: 'Bitter', serif;
  overflow-x: hidden;
}

</style>
