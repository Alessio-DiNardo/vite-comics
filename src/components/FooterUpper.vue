<template>
    <div class="background">
        <div class="container">
            <nav>
                <ul>
                    <h2>DC COMICS</h2>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    <h2>SHOP</h2>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
                <ul>
                    <h2>DC</h2>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
                <ul>
                    <h2>SITES</h2>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </nav>
            <img src="../assets/dc-logo-bg.png" alt="logo-background">
        </div>
    </div>
</template>


<script>
export default {
    name: 'FooterUpper',
    data(){
        return{

        }
    }
}
</script>


<style lang="scss" scoped>
    @use '../styles/partials/mixins' as*;
    @use '../styles/partials/variables' as*;

    div.background{
        background-image: url('../assets/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        width: 100%;
    }

    nav{
        display: flex;

        ul h2{
            color: $thirdColor;
            padding-top: 3rem;
            padding-bottom: 1rem;
            padding-left: 2rem;
            
        }
    }
    li{
        color: $fourColor;
    }


</style>