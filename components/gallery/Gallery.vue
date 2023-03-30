<template>
    <div class="grid-container">
        <div class="grid-item">
            <BigImage image="https://nt.global.ssl.fastly.net/binaries/content/gallery/website/holidays/library/cornwall/durgan-wood-cottage/durgan-wood-cottage-cornwall.jpg"/>
        </div>
        <div class="grid-item">
            <BigImage image="https://nt.global.ssl.fastly.net/binaries/content/gallery/website/holidays/library/cornwall/durgan-wood-cottage/durgan-wood-cottage-cornwall.jpg"/>
        </div>
        <div class="grid-item">
            <BigImage image="https://nt.global.ssl.fastly.net/binaries/content/gallery/website/holidays/library/cornwall/durgan-wood-cottage/durgan-wood-cottage-cornwall.jpg" title="Check Props"/>
        </div>  
        <div class="grid-item">
            <BigImage image="https://nt.global.ssl.fastly.net/binaries/content/gallery/website/holidays/library/cornwall/durgan-wood-cottage/durgan-wood-cottage-cornwall.jpg"/>
        </div>
        <div class="grid-item">
            <BigImage image="https://nt.global.ssl.fastly.net/binaries/content/gallery/website/holidays/library/cornwall/durgan-wood-cottage/durgan-wood-cottage-cornwall.jpg"/>
        </div>
        <div class="grid-item">
            <BigImage image="https://nt.global.ssl.fastly.net/binaries/content/gallery/website/holidays/library/cornwall/durgan-wood-cottage/durgan-wood-cottage-cornwall.jpg"/>
        </div>  
        <div class="grid-item">
            <BigImage image="https://nt.global.ssl.fastly.net/binaries/content/gallery/website/holidays/library/cornwall/durgan-wood-cottage/durgan-wood-cottage-cornwall.jpg"/>
        </div>
        <div class="grid-item">
            <BigImage image="https://nt.global.ssl.fastly.net/binaries/content/gallery/website/holidays/library/cornwall/durgan-wood-cottage/durgan-wood-cottage-cornwall.jpg"/>
        </div>
        <div class="grid-item">
            <BigImage image="https://nt.global.ssl.fastly.net/binaries/content/gallery/website/holidays/library/cornwall/durgan-wood-cottage/durgan-wood-cottage-cornwall.jpg"/>
        </div>  
    </div>
</template>

<script>

import BigImage from './BigImage.vue';
export default {
    name: "Gallery",
    components: {BigImage}
}
</script>

<style scoped>
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto;
  background-color: #a1aeb4;
  padding: 10px;
}
.grid-item {
  background-color: #a1aeb4;
  padding: 20px;
  font-size: 20px;
  text-align: center;
}

.p {
    font-family: serif;
}
</style>