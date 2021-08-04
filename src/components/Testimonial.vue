<template>
  <section class="testimonial">
      <div class="testimonial-details">
          <h5 class="testimonial__subtitle">
              <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6 12C9.31371 12 12 9.31371 12 6C12 2.68629 9.31371 0 6 0C2.68629 0 0 2.68629 0 6C0 9.31371 2.68629 12 6 12Z" fill="#F07566"/>
                </svg> TESTIMONIAL
          </h5>
          <h1 class="testimonial__title">
              Reviews
          </h1>
          <div class="testimonial-card t-card">
              <p class="testimonial__text">"The sky was cloudless and of a deep dark blue the spectacle before us was indeed sublime sky was cloudless and of a deep dark."</p>
              <h4 class="testimonial__name">Jaroslav Brabec</h4>
              <div class="testimonial__company">Microsoft</div>
              <svg class="testimonial__icon" width="48" height="36" viewBox="0 0 48 36" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M20 0C7.784 2.412 0 13.168 0 23.45C0 31.39 5.572 36 11.602 36C16.832 36 22 32.406 22 26.042C22 20.838 18.19 16.528 13.208 15.744C13.642 11.736 17.538 5.922 21.968 4.252L20 0ZM46 0C33.784 2.412 26 13.168 26 23.45C26 31.39 31.572 36 37.602 36C42.832 36 48 32.406 48 26.042C48 20.838 44.19 16.528 39.208 15.744C39.642 11.736 43.538 5.922 47.968 4.252L46 0Z" fill="#4DB282"/>
                </svg>
          </div>
          <svg class="testimonial__arrows" width="104" height="48" viewBox="0 0 104 48" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect width="48" height="48" rx="24" fill="#F07566"/>
            <path fill-rule="evenodd" clip-rule="evenodd" d="M16.3258 23.2196L25.4156 14.3195C25.6258 14.1135 25.9065 14 26.2057 14C26.5049 14 26.7856 14.1135 26.9958 14.3195L27.6652 14.9748C28.1008 15.4018 28.1008 16.0958 27.6652 16.5221L20.0323 23.9959L27.6737 31.4779C27.8839 31.6839 28 31.9586 28 32.2514C28 32.5446 27.8839 32.8192 27.6737 33.0254L27.0043 33.6805C26.7939 33.8865 26.5134 34 26.2142 34C25.9149 34 25.6343 33.8865 25.424 33.6805L16.3258 24.7723C16.1151 24.5656 15.9993 24.2897 16 23.9963C15.9993 23.7019 16.1151 23.4261 16.3258 23.2196Z" fill="white"/>
            <rect x="56" width="48" height="48" rx="24" fill="#F07566"/>
            <path fill-rule="evenodd" clip-rule="evenodd" d="M87.6742 23.2196L78.5844 14.3195C78.3742 14.1135 78.0935 14 77.7943 14C77.4951 14 77.2144 14.1135 77.0042 14.3195L76.3348 14.9748C75.8992 15.4018 75.8992 16.0958 76.3348 16.5221L83.9677 23.9959L76.3263 31.4779C76.1161 31.6839 76 31.9586 76 32.2514C76 32.5446 76.1161 32.8192 76.3263 33.0254L76.9957 33.6805C77.2061 33.8865 77.4866 34 77.7858 34C78.0851 34 78.3657 33.8865 78.576 33.6805L87.6742 24.7723C87.8849 24.5656 88.0007 24.2897 88 23.9963C88.0007 23.7019 87.8849 23.4261 87.6742 23.2196Z" fill="white"/>
            </svg>
      </div>
      <div class="testimonial-img">
          <img src="../img/testimonial.png" alt="testimonial Image" class="testimonial__img">
      </div>
      <!-- <img src="../img/testimonialbg1.png" alt="Background" class="testimonial__bg"> -->
  </section>
</template>

<script>
export default {
    name: 'Testimonial'
}
</script>

<style lang="scss">
    .testimonial{
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
        &__arrows{
            margin-top: 48px;
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
        &-card{
            padding: 27px 32px;
            background: #FFFFFF;
            box-shadow: 0px 24px 48px rgba(0, 17, 86, 0.0799083);
            border-radius: 8px;
            position: relative;
        }
        &__icon{
            position: absolute;
            top: -20px;
            right: 40px;
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
            font-family: 'Work Sans';
            font-size: 16px;
            line-height: 32px;
            color: rgba(51, 51, 51, 0.496405);
        }
        &__name{
            font-family: 'Hind Siliguri';
            font-style: normal;
            font-weight: bold;
            font-size: 24px;
            line-height: 32px;
            color: #333333;
        }
        &__company{
            font-family: 'Work Sans';
            font-size: 14px;
            line-height: 24px;
            color: rgba(51, 51, 51, 0.496405);
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
        .testimonial{
            flex-wrap: wrap-reverse;
            justify-content: center;
        }
    }
    @media only screen and (max-width: 476px) {
        .testimonial{
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