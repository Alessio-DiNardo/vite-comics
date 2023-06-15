<template>
    <div class="container">
        <img src="../assets/dc-logo.png" alt="">
        <nav>
            <ul class="flex">
                <li v-for="link in navbarLinks" :class="link.active ? active : ''">
                    {{link.text}}
                </li>
            </ul>
        </nav>
    </div>
</template>


<script>

export default {
    name: 'HeaderUpper',
    data(){
        return{
            navbarLinks :[
                {
                    text: 'characters',
                    active: false
                },
                {
                    text: 'comics',
                    active: true
                },
                {
                    text: 'movies',
                    active: false
                },
                {
                    text: 'tv',
                    active: false
                },
                {
                    text: 'games',
                    active: false
                },
                {
                    text: 'collectibles',
                    active: false
                },
                {
                    text: 'videos',
                    active: false
                },
                {
                    text: 'fans',
                    active: false
                },
                {
                    text: 'news',
                    active: false
                },
                {
                    text: 'shop',
                    active: false
                },
            ]
        }
    }
}
</script>


<style lang="scss" scoped>
    @use '../styles/partials/mixins' as*;
    @use '../styles/partials/variables' as*;
    
    nav{
        padding-top: 2.5rem;

    }

    li{
        padding: 0 2rem 0 2rem;

        &.active,
        &:hover{
            color: $primaryColor;
        }
    }

    img{
        padding: 0.75rem 0;
        width: 90px;

    }
</style>