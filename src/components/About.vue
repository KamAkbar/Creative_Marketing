<template>
  <section class="about">
      <div class="about-details">
          <h5 class="about__subtitle">
              <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6 12C9.31371 12 12 9.31371 12 6C12 2.68629 9.31371 0 6 0C2.68629 0 0 2.68629 0 6C0 9.31371 2.68629 12 6 12Z" fill="#F07566"/>
                </svg> ABOUT
          </h5>
          <h1 class="about__title">
              We Build <br> Pro Business

          </h1>
          <h3 class="about__name">Excited to work with customers</h3>
          <p class="about__text">
              <svg width="24" height="22" viewBox="0 0 24 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M22 11C22 10.421 21.942 9.857 21.856 9.303L19.99 11.205C19.879 16.072 15.894 20 11 20C6.038 20 2 15.962 2 11C2 6.038 6.038 2 11 2C12.8 2 14.474 2.537 15.882 3.45L17.304 1.993C15.518 0.741 13.347 0 11 0C4.925 0 0 4.925 0 11C0 17.075 4.925 22 11 22C17.075 22 22 17.075 22 11ZM11.5 10.806L20.904 1.167L24 4.263L11.5 17L4.562 10.29L7.657 7.192L11.5 10.806Z" fill="#4DB282"/>
                </svg> The sky was cloudless and of a deep 
          </p>
          <p class="about__text">
              <svg width="24" height="22" viewBox="0 0 24 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M22 11C22 10.421 21.942 9.857 21.856 9.303L19.99 11.205C19.879 16.072 15.894 20 11 20C6.038 20 2 15.962 2 11C2 6.038 6.038 2 11 2C12.8 2 14.474 2.537 15.882 3.45L17.304 1.993C15.518 0.741 13.347 0 11 0C4.925 0 0 4.925 0 11C0 17.075 4.925 22 11 22C17.075 22 22 17.075 22 11ZM11.5 10.806L20.904 1.167L24 4.263L11.5 17L4.562 10.29L7.657 7.192L11.5 10.806Z" fill="#4DB282"/>
                </svg> Spectacle before us was indeed 
          </p>
          <p class="about__text">
              <svg width="24" height="22" viewBox="0 0 24 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M22 11C22 10.421 21.942 9.857 21.856 9.303L19.99 11.205C19.879 16.072 15.894 20 11 20C6.038 20 2 15.962 2 11C2 6.038 6.038 2 11 2C12.8 2 14.474 2.537 15.882 3.45L17.304 1.993C15.518 0.741 13.347 0 11 0C4.925 0 0 4.925 0 11C0 17.075 4.925 22 11 22C17.075 22 22 17.075 22 11ZM11.5 10.806L20.904 1.167L24 4.263L11.5 17L4.562 10.29L7.657 7.192L11.5 10.806Z" fill="#4DB282"/>
                </svg> Cloudless and of a deep dark 
          </p>
          <button class="about__btn btn btn_primary">LEARN MORE</button>
      </div>
      <div class="about-img">
          <img src="../img/intro2.png" alt="About Image" class="about__img">
      </div>
      <!-- <img src="../img/aboutbg1.png" alt="Background" class="about__bg"> -->
  </section>
</template>

<script>
export default {
    name: 'About'
}
</script>

<style lang="scss">
    .about{
        display: flex;
        margin-top: 192px;
        justify-content: space-between;
        align-items: center;
        flex-direction: row-reverse;
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
            margin-bottom: 26px;

        }
        &__text{
            display: flex;
            align-items: center;
            gap: 8px;
            font-family: 'Work Sans';
            font-style: normal;
            font-weight: normal;
            font-size: 16px;
            line-height: 32px;
            color: #333333;
            margin-bottom: 0;
        }
        &__name{
            margin-bottom: 35px;
            font-weight: bold;
            font-size: 24px;
            line-height: 32px;
            color: #333333;
            mix-blend-mode: normal;
            opacity: 0.9;
            margin-bottom: 34px;
        }
        &__img{
            width: 100%;
            padding-top: 70px;
        }
        &__bg{
            position: absolute;
            z-index: -1;
            top: 0;
            right: 0;
        }
        &__btn{
            margin-top: 37px;
        }
    }
    @media only screen and (max-width: 992px) {
        .about{
            flex-wrap: wrap-reverse;
            justify-content: center;
        }
    }
    @media only screen and (max-width: 476px) {
        .about{
            margin-top: 140px;
            &__title{
                font-size: 40px;
                line-height: 48px;
            }
            &__subtitle{
                margin-top: 9px;
            }
            &__text{
                font-size: 14px;
            }
            &__img{
                padding-top: 0;
            }
        }
    }
</style>