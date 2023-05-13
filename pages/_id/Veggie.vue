<template>
    <div>
        <h1>{{ $route.params.id }}</h1>
        <BigImage image="https://cdn.shopify.com/s/files/1/0451/1101/7626/products/carrotseeds.jpg?v=1604032858"/>
    </div>
</template>

<script setup>
    import BigImage from '~/components/gallery/BigImage.vue';
</script>