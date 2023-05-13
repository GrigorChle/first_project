<template>
    <div>
        <h1>{{ $route.params.id }}</h1>
        <BigImage image="https://www.gardeningknowhow.com/wp-content/uploads/2017/07/hardwood-tree.jpg"/>
    </div>
</template>

<script setup>
    import BigImage from '~/components/gallery/BigImage.vue';
</script>