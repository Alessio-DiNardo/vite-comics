<template>
    <div class="background">
        <div class="container">
            <h2>SIGN-UP NOW!</h2>
            <nav>
                <ul>
                    <li class="active">FOLLOW US</li>
                    <li><img src="../assets/footer-facebook.png" alt="Facebook"></li>
                    <li><img src="../assets/footer-twitter.png" alt="Twitter"></li>
                    <li><img src="../assets/footer-youtube.png" alt="Youtube"></li>
                    <li><img src="../assets/footer-pinterest.png" alt="Pinterest"></li>
                    <li><img src="../assets/footer-periscope.png" alt="periscope"></li>
                </ul>
            </nav>
        </div>
        
    </div>
    
</template>
<script>
export default {
    name: 'FooterUnder',
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
        background-color: $thirdbgColor;
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 140px;
    }

    ul{
        display: flex;

        li.active{
            font-size: 1.7rem;
            color: $primaryColor;
        }
    }

    h2{
        border: 1px $primaryColor solid;
        padding: 1rem;
        font-size: 1.3rem;
        color: $thirdColor;
        margin-left: 1rem;
        
    }
</style>