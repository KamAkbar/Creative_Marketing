<template>
  <section class="features">
      <div class="features-details">
          <h5 class="features__subtitle">
              <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6 12C9.31371 12 12 9.31371 12 6C12 2.68629 9.31371 0 6 0C2.68629 0 0 2.68629 0 6C0 9.31371 2.68629 12 6 12Z" fill="#F07566"/>
                </svg> FEATURES
          </h5>
          <h1 class="features__title">
              Smart Complex <br> Solutions
          </h1>
          <p class="features__text text text_big">Stars had ceased to twinkle the same illusion which lifts the horizon of the sea to the level of the spectator on a hillside, the sable cloud beneath was dished out.</p>
          <div class="features-board1 board1">
              <h2 class="board1__title"><svg width="24" height="23" viewBox="0 0 24 23" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M8.332 7.62569L12 0L15.668 7.6267L24 8.78546L17.936 14.6569L19.416 22.999L12 19.0028L4.584 23L6.064 14.6579L0 8.78546L8.332 7.62569ZM14.335 9.47468L12 4.62096L9.665 9.47468L4.36 10.2133L8.221 13.9515L7.279 19.2617L12 16.7175L16.721 19.2607L15.779 13.9505L19.64 10.2123L14.335 9.47468Z" fill="#4DB282"/>
                </svg> Modern Technology
                </h2>
              <p class="board1__text">The sky was cloudless and of a deep dark blue the spectacle before us was indeed sublime.</p>
          </div>
      </div>
      <div class="features-img">
          <img src="../img/features.png" alt="features Image" class="features__img">
      </div>
  </section>
</template>

<script>
export default {
    name: 'Features'
}
</script>

<style lang="scss">
    .features{
        display: flex;
        margin-top: 360px;
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
            margin-bottom: 20px;
        }
        &__title{
            font-weight: bold;
            font-size: 56px;
            line-height: 64px;
            letter-spacing: -1px;
            color: #333333;
            position: relative;
            margin-bottom: 28px;

        }
        &__text{
            margin-bottom: 20px;
            font-family: 'Work Sans';
            font-size: 16px;
            line-height: 32px;
        }
        &__img{
            width: 100%;
            margin-top: 70px;
        }
    }
    .board1{
        padding: 25px 32px;
        background: #FFFFFF;
        box-shadow: 0px 24px 48px rgba(0, 17, 86, 0.0799083);
        border-radius: 8px;
        border: 1px solid #FFFFFF;
        &:hover{
            border: 1px solid #f076666b;
            transition: .6s;
        }
        &__title{
            display: flex;
            align-items: center;
            gap: 16px;
            font-weight: bold;
            font-size: 24px;
            line-height: 32px;
            color: #333333;
        }
        &__text{
            margin-top: 6px;
            font-family: 'Work Sans';
            font-size: 14px;
            line-height: 24px;
            color: rgba(51, 51, 51, 0.496405);
        }
    }
    @media only screen and (max-width: 992px) {
        .features{
            flex-wrap: wrap;
        }
    }
    @media only screen and (max-width: 476px) {
        .features{
            margin-top: 155px;
            display: flex;
            justify-content: center;
            &__title{
                font-size: 40px;
                line-height: 48px;
            }
        }
    }
</style>