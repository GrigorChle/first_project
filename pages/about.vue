<template>
    <div>
        <h1 class="colorRed">About</h1>
        <button @click="showInfo">Klikaj</button>
        <BigImage image="https://img.freepik.com/darmowe-zdjecie/zolty-zonkil-narcyz-kwitnacy-w-ogrodzie_127675-2729.jpg?w=1380&t=st=1679759626~exp=1679760226~hmac=af080a04badfa3d9513ada3e22e1dc1e841ca19a9d57407f9b5f5342cadbf6a1"/>
    </div>
</template>

<script>
import BigImage from '~/components/gallery/BigImage.vue';

export default {
    name: "AboutPage",
    components: {BigImage},

    methods: {
        showInfo: () =>console.log("Witaj")
    }
}

</script>