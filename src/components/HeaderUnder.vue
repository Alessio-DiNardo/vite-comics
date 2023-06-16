<template>
    <div class="bg-black">
        <div class="container">
            <SingleMovie/>
        </div>
    </div>
</template>


<script>
import SingleMovie from './SingleMovie.vue';

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