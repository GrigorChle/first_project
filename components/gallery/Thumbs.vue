<template>
    <a :href="this.href"><img :src="this.img_src"></a>
</template>

<script>

export default {
    name: "Thumbs",
    props: {
        img_src: {
            type: String,
            default: () => 'pusty'
        },
        href: {
            type: String,
            default: () => "#"
        }
    },
}
</script>

<style scoped>
    img {
        width: 100px;
        height: 100px;
        padding: 2px;
    }
    img:hover {
        border: 1px black solid;
    }
</style>
