<template>
        <div class="Card">
            <div class="movie">
                <img :src="img" alt="">
            </div>
        </div>
</template>

<script>
export default {
    name:'SingleMovie',
    props: [
        'img',
        'price',
        'series',
        'type',
        
    ]
}
</script>

<style lang="scss" scoped>

    div.movie{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
    }
    div.card{
        display: flex;

        img{
            width: 200px;
        }
    }

    div.container{
        display: flex;
    }
</style>