<template>
    <section v-if="category == 'Caricatures'">
        <caricature-component></caricature-component>
    </section>
    <section v-else-if="category == 'Portraits'">
        <portraits-component></portraits-component>
    </section>
    <section v-else-if="category == 'Comics'">
        <comics-component></comics-component>
    </section>
    <section v-else>
        <cards-component></cards-component>
    </section>
</template>

<script lang="ts">
import Vue from 'vue'
import CaricatureComponent from '@/components/CaricatureComponent.vue'
import CardsComponent from '@/components/CardsComponent.vue'
import PortraitComponent from '@/components/PortraitsComponent.vue'
import ComicsComponent from '@/components/ComicsComponent.vue'

export default Vue.extend({
    components: {
        CaricatureComponent,
        CardsComponent,
        PortraitComponent,
        ComicsComponent 
    },
    props: {
        category: {
            required: true,
            type: String
        }
    }
})
</script>