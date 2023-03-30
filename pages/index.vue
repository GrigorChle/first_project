<template>
  <div>
    <TopNav/>
    <Gallery/>
  </div>
</template>

<script>
import TopNav from '~/components/nav/TopNav.vue';
import Gallery from '~/components/gallery/Gallery.vue';

export default {
    name: "IndexPage",
    components: {TopNav, Gallery}
}
</script>
