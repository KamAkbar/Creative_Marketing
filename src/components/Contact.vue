<template>
    <section class="contact">
        <div class="container contact-section">
            <div class="contact-details">
            <h1 class="contact__title">Kickstart <br> Your Next <br> Project</h1>
            <button class="btn btn_darkp contact__button">CONTACT US</button>
            </div>
            <p class="contact__text">I shall see the face of Mars, anyhow, and that will be a rare experience. It seems to me that a view of the heavenly bodies through a fine telescope, as well as a tour round the world, should form a part of a liberal education.</p>
            <img src="../img/contactbg.png" alt="Background Image" class="contact__bg">
        </div>
    </section>
</template>

<script>
export default {
    name: 'Contact'
}
</script>

<style lang="scss">
    .contact{
        background-color: #F07566;
        border-radius: 8px;
        padding: 80px 0 90px;
        margin-top: 240px;
        position: relative;
        &-section{
            display: flex;
            justify-content: space-around;
        }
        &__title{
            font-weight: bold;
            font-size: 56px;
            line-height: 64px;
            letter-spacing: -1px;
            color: #FFFFFF;
        }
        &__button{
            font-weight: bold!important;
            font-size: 16px;
            line-height: 26px;
            text-align: center;
            letter-spacing: 1px;
            text-transform: uppercase;
            color: #333333;
            border-radius: 8px!important;
            padding: 11px 33px;
            margin-top: 33px;
        }
        &__text{
            max-width: 470px;
            font-family: 'Work Sans';
            font-size: 16px;
            line-height: 32px;
            color: #FFFFFF;
        }
        &__bg{
            position: absolute;
            bottom: -23px;
        }
    }
    @media (max-width: 992px) {
        .contact{
            &-section{
                flex-direction: column!important;
            }
            &__text{
                margin-top: 60px;
                margin-bottom: 60px;
            }
        }
    }
</style>