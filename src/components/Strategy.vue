<template>
    <section class="strategy">
        <div class="container strategy-section">
            <div class="strategy-img">
             <img src="../img/strategy.png" alt="" class="strategy__img">
            </div>
            <div class="strategy-details">
                <h1 class="strategy__title">Strategy, Technology <br> and Design</h1>
                <p class="strategy__text">Apparently we had reached a great height in the atmosphere, for the sky was a dead black.</p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Strategy'
}
</script>

<style lang="scss">
    .strategy{
        background-color: #F07566;
        border-radius: 8px;
        padding: 80px 0 90px;
        margin-top: 240px;
        position: relative;
        &-section{
            display: flex;
            justify-content: flex-end;
        }
        &__title{
            font-weight: bold;
            font-size: 56px;
            line-height: 64px;
            letter-spacing: -1px;
            color: #FFFFFF;
        }
        &__text{
            max-width: 470px;
            font-family: 'Work Sans';
            font-size: 16px;
            line-height: 32px;
            color: #FFFFFF;
        }
        &__img{
            position: absolute;
            left: 120px;
            top: -60px;
        }

    }
    @media (max-width: 1110px) {
        .strategy{
            &-details{
                justify-content: center;
                margin-top: 410px;
            }
        }
    }
    @media (max-width: 992px) {
        .strategy{
            &-section{
                flex-direction: column!important;
            }
            &__text{
                margin-top: 60px;
                margin-bottom: 60px;
            }
            &__img{
                top: -130px;
                left: 25%;
            }
        }
    }
    @media only screen and (max-width: 476px) {
        .strategy{
            &__title{
                font-size: 40px;
                line-height: 48px
            }
            &__img{
                left: 20px;
            }
        }
     }
     @media (max-width: 390px) {
         .strategy{
             &__img{
                 max-width: 300px;
             }
             &-details{
                 margin-top: 250px;
             }
         }
     }

</style>