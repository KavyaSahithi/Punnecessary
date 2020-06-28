<template>
    <img :src="url"/>
</template>

<style lang="scss">
img {
    display: block;
    width: 100%;
    height: auto;
    border-radius: 10px;
}
</style>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    props: {
        id: {
            required: true,
            type: String
        },
        category: {
            required: true,
            type: String
        }
    },
    computed: {
        url: function() {
            return `https://res.cloudinary.com/punnecessary/image/upload/q_auto:eco,f_auto/${this.category}/${this.id}.png`
        }
    }
})
</script>