<template>
    <div class="background">
        <h1>ciao</h1>
    </div>
</template>


<script>

export default {
    name: 'HeaderUpper',
    data(){
        return{

        }
    }
}
</script>


<style lang="scss" scoped>
    @use '../styles/partials/mixins';
    @use '../styles/partials/variables';
    
    h1{
        color: $primaryColor;
    }
</style>