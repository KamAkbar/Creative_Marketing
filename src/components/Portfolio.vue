<template>
  <section class="portfolio">
      <div class="portfolio-details">
          <h5 class="portfolio__subtitle">
              <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6 12C9.31371 12 12 9.31371 12 6C12 2.68629 9.31371 0 6 0C2.68629 0 0 2.68629 0 6C0 9.31371 2.68629 12 6 12Z" fill="#F07566"/>
                </svg> COMPANY
          </h5>
          <h1 class="portfolio__title">Company Cases</h1>
          <p class="portfolio__text">Apparently we had reached a great height in the atmosphere, for the sky was a dead black, and the stars had ceased to twinkle the same illusion which lifts the horizon of the sea.</p>
      </div>
      <div class="projects">
          <div class="project">
              <div class="project-img">
                <img src="https://picsum.photos/500/384" alt="Project" class="project__img">
                <h1 class="project__number">01</h1>
              </div>
              <div class="project-details">
                  <h4 class="project__title">Face of Mars</h4>
                  <p class="project__info">Will be a rare experience</p>
              </div>
          </div>
          <div class="project">
              <div class="project-img">
                <img src="https://picsum.photos/500/384" alt="Project" class="project__img">
                <h1 class="project__number">02</h1>
              </div>
              <div class="project-details">
                  <h4 class="project__title">Heavenly Bodies</h4>
                  <p class="project__info">Tour round the world should form</p>
              </div>
          </div>
          <div class="project">
              <div class="project-img">
                <img src="https://picsum.photos/500/384" alt="Project" class="project__img">
                <h1 class="project__number">03</h1>
              </div>
              <div class="project-details">
                  <h4 class="project__title">FLiberal Education</h4>
                  <p class="project__info">Truly it was a great journey</p>
              </div>
          </div>
          <div class="project">
              <div class="project-img">
                <img src="https://picsum.photos/500/384" alt="Project" class="project__img">
                <h1 class="project__number">04</h1>
              </div>
              <div class="project-details">
                  <h4 class="project__title">Though the Gravity</h4>
                  <p class="project__info">Daily classes he no longer collapsed</p>
              </div>
          </div>
          
      </div>
      <div class="portfolio-btn">
        <button class="portfolio__button btn btn_secondary">BROWSE ALL</button>
      </div>
  </section>
</template>

<script>
export default {
    name: 'Portfolio'
}
</script>

<style lang="scss">
    .portfolio{
        &__subtitle{
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            font-weight: bold;
            font-size: 16px;
            line-height: 32px;
            letter-spacing: 1px;
            text-transform: uppercase;
        }
        &__title{
            font-weight: bold;
            font-size: 56px;
            line-height: 64px;
            text-align: center;
            letter-spacing: -1px;
            color: #333333;
            margin: 20px 0 28px;
        }
        &__text{
            font-family: 'Work Sans';
            font-size: 16px;
            line-height: 32px;
            text-align: center;
            color: rgba(51, 51, 51, 0.496405);
        }
        &-btn{
            display: flex!important;
            justify-content: center!important;;
            margin-top: 70px;
        }
    }
    .projects{
        margin-top: 60px;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        gap: 30px;
    }
    .project{
        &__img{
            opacity: 0.7;
            object-fit: contain;
            border-radius: 8px;
            width: 100%;
        }
        &-img{
            position: relative;
            max-width: 570px;
        }
        &__number{
            position: absolute;
            bottom: 0;
            left: 0;
            font-weight: bold;
            width: 96px;
            height: 96px;
            font-size: 40px;
            line-height: 48px;
            text-align: center;
            letter-spacing: -1px;
            color: #FFFFFF;
            padding: 28px 30px;
            border-radius: 0 20px 0 0;
            background-color: #4DB282;
            margin-bottom: 0;
        }
        &-details{
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        &__title{
            margin-top: 25px;
            font-weight: bold;
            font-size: 24px;
            line-height: 32px;
            text-align: center;
            color: #333333;
        }
        &__info{
            margin-top: 2px;
            font-size: 16px;
            line-height: 32px;
            text-align: center;
            color: rgba(51, 51, 51, 0.496405);
        }
    }
    @media only screen and (max-width: 476px) {
        .portfolio{
            margin-top: 110px;
            &__title{
                font-size: 40px;
                line-height: 48px;
            }
        }
    }
</style>