<template>
  <section class="intro">
      <div class="intro-details">
          <h5 class="intro__subtitle">
              <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6 12C9.31371 12 12 9.31371 12 6C12 2.68629 9.31371 0 6 0C2.68629 0 0 2.68629 0 6C0 9.31371 2.68629 12 6 12Z" fill="#F07566"/>
                </svg> COMPANY
          </h5>
          <h1 class="intro__title">
              Creative <br>
              <span class="intro__span">Marketing</span>
              <img src="../img/Bitmap.png" alt="Bitmap" class="intro__line">
          </h1>
          <p class="intro__text text text_big">The sky was cloudless and of a deep dark blue the spectacle before us was indeed sublime.</p>
          <button class="intro__btn btn btn_primary">Explore</button>
      </div>
      <div class="intro-img">
          <img src="../img/intro1.png" alt="Intro Image" class="intro__img">
      </div>
      <img src="../img/introbg1.png" alt="Background" class="intro__bg">
  </section>
</template>

<script>
export default {
    name: 'Intro'
}
</script>

<style lang="scss">
    .intro{
        display: flex;
        margin-top: 74px;
        justify-content: space-between;
        align-items: center;
        &-details{
            max-width: 470px;
        }
        &-img{
            max-width: 550px;
        }
        &__subtitle{
            display: flex;
            align-items: center;
            gap: 12px;
            font-weight: bold;
            font-size: 16px;
            line-height: 32px;
            letter-spacing: 1px;
            text-transform: uppercase;
        }
        &__title{
            font-weight: bold;
            font-size: 72px;
            line-height: 80px;
            letter-spacing: -1px;
            color: #333333;
            position: relative;
            margin-bottom: 38px;

        }
        &__text{
            margin-bottom: 35px;
        }
        &__span{
            color: #4DB282;
        }
        &__img{
            width: 100%;
        }
        &__line{
            position: absolute;
            left: 0;
            bottom: -18px;
        }
        &__bg{
            position: absolute;
            z-index: -1;
            top: 0;
            right: 0;
        }
    }
    @media only screen and (max-width: 992px) {
        .intro{
            flex-wrap: wrap-reverse;
        }
    }
    @media only screen and (max-width: 476px) {
        .intro{
            &__title{
                font-size: 56px;
                line-height: 64px;
            }
            &__subtitle{
                margin-top: 9px;
            }
            &__line{
                max-width: 240px;
            }
        }
    }
</style>