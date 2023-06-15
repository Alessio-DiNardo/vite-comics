<template>
    <div class="background">
        <div class="container">
            <section class="flex">
                <div class="card" v-for="shop in shopBar">
                    <img src={{shop.img}} alt="">
                    <h2>{{shop.text}}</h2>
                </div>
                
            </section>
        </div>
    </div>
</template>


<script>

export default {
    name: 'AppMain',
    data(){
        return{
            shopBar :[
                {
                    img: '../assets/buy-comics-digital-comics.png',
                    text: 'DIGITAL COMICS' 
                },
                {
                    img: '../assets/buy-comics-merchandise.png',
                    text: 'DC MERCHANDISE' 
                },
                {
                    img: '../assets/buy-comics-subscriptions.png',
                    text: 'SUBSCRIPTION' 
                },
                {
                    img: '../assets/buy-comics-shop-locator.png',
                    text: 'COMIC SHOP LOCATOR' 
                },
                {
                    img: '../assets/buy-dc-power-visa.png',
                    text: 'DC POWER VISA' 
                },
                
            ]
        }
    }
}
</script>


<style lang="scss" scoped>
    @use '../styles/partials/mixins' as*;
    @use '../styles/partials/variables' as*;
    
    div.background{
        background-color: $primaryColor;
        height: 120px;
    }

    div.card{
        display: flex;
        justify-content: center;
        align-items: center;
        padding-top: 1.6rem;

        img{
            width: 40px;
            
        }
    }

    h2{
        color: $thirdColor;
        font-size: 1rem;
        padding-left: 1rem;
        
    }
</style>