<template>
    <div class="bg-black">
        <div class="container">
            <h1>
            ->> Content goes here 
            </h1>
        </div>
        <SingleMovie/>
    </div>
</template>


<script>
import SingleMovie from './components/SingleMovie.vue';

export default {
    name: "HeaderUnder",
    data() {
        return {};
    },
    components: {
        SingleMovie
    }
}
</script>


<style lang="scss" scoped>
    @use '../styles/partials/mixins' as*;
    @use '../styles/partials/variables' as*;

    div.bg-black{
        background-color: $secondbgColor;
        height: 115px;
    }

    h1{
        color: $thirdColor;
        font-size: 2rem;
        padding-top: 2rem;
    }
</style>