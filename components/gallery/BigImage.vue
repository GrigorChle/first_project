<template>
    <div>
        <img class="img" :src="this.image"/>
        <p>{{ this.title }}</p>
    </div>
</template>

<script>

export default {
    name: "BigImage",
    props: {
        image: {
            type: String,
            default: () => 'pusty'
        },
        title: {
            type: String,
            default: () => "Default Title"
        }
    },

    data() {
        return {}
    },

    created() {
        console.log(this.image)
    }
}
</script>

<style scoped>
    .img {
        width: 100%;
        border: 1px solid red;
    }
</style>