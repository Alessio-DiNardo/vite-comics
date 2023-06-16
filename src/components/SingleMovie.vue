<template>
    <div class="Card">
        <img :src="img" alt="">
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
    
</style>