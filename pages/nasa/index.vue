<template>
    <div>
        <h1>Nasa {{ message }}</h1>
        <input v-model="message" placeholder="search..." />
        <button @click="find()">Search</button>
        
        <div class="Cards">
            <Thumbs :img_src="value.links[0].href" v-for="(value, index) in dataArray" :key="index"/>
        </div>
        
    </div>
</template>

<script>
import Thumbs from "~/components/gallery/Thumbs.vue";
import axios from "axios";
    export default {
        name: "index",
        components: {Thumbs},
    
    data() {
        return {
            dataArray: [],
            message: ""
        }
    },

    created() {
        this.fetchData("sun");
    },
    methods: {
        find() {
            this.fetchData(this.message);
            this.message = ""
        },
        async fetchData(search) {
            await axios.get("https://images-api.nasa.gov/search?q="+ search).then(response => {
                this.dataArray = response.data.collection.items
            }).catch(error => {
                console.log(error)
                })
            
            }
        }

    }
</script>

<style scoped>
    .Cards {
        justify-content: center;
        display: flex;
        flex-wrap: wrap;
    }
</style>