<template>
    <div>
        <h1>{{ $route.params.id }}</h1>
        <BigImage image="https://plantacjalawendy.pl/109-thickbox_default/lawenda-blue-scent-duza.jpg"/>
    </div>
</template>

<script setup>
    import BigImage from '~/components/gallery/BigImage.vue';
</script>