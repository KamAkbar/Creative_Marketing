<template>
  <section class="article">
      <div class="article-details">
          <h5 class="article__subtitle">
              <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6 12C9.31371 12 12 9.31371 12 6C12 2.68629 9.31371 0 6 0C2.68629 0 0 2.68629 0 6C0 9.31371 2.68629 12 6 12Z" fill="#F07566"/>
                </svg> LATEST ARTICLES
          </h5>
          <h1 class="article__title">Check Our Insights</h1>
          <p class="article__text">See the face of Mars, anyhow, and that will be a rare experience seems to me that a view of the heavenly bodies through a fine telescope, as well as a tour round the world.</p>
          <article class="article-l">
              <div class="article-img">
                  <img src="https://picsum.photos/554/336" alt="Article" class="article__img">
              </div>
              <div>
                <h2 class="article-l__title">What looked like a small patch of purple grass</h2>
                <p class="article-l__text">Truly it was a great journey, and in it I met with many, whom to know was to love.</p>
              </div>
          </article>
          <article class="articles">
            <div class="article-s">
              <div class="article-s-img">
                <img src="https://picsum.photos/338/224" alt="article-s" class="article-s__img">
              </div>
              <div class="article-s-details">
                  <h4 class="article-s__title">Above five feet square, was moving across</h4>
              </div>
            </div>
            <div class="article-s">
              <div class="article-s-img">
                <img src="https://picsum.photos/338/224" alt="article-s" class="article-s__img">
              </div>
              <div class="article-s-details">
                  <h4 class="article-s__title">Enough he perceived that it was not grasss</h4>
              </div>
            </div>
            <div class="article-s">
              <div class="article-s-img">
                <img src="https://picsum.photos/338/224" alt="article-s" class="article-s__img">
              </div>
              <div class="article-s-details">
                  <h4 class="article-s__title">There were no blades, but only purple roots</h4>
              </div>
            </div>
          </article>
                <div class="article-btn">
        <button class="article__button btn btn_secondary">BROWSE ALL</button>
      </div>
      </div>
     

  </section>
</template>

<script>
export default {
    name: 'Articles'
}
</script>

<style lang="scss">
    .article{
        margin-top: 140px;
        &__subtitle{
            display: flex;
            gap: 66px;
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
        &-img{
            max-width: 554px;
        }
        &__img{
            width: 100%;
            background: #D8D8D8;
            border-radius: 8px 8px 50px 8px;
        }
        &-btn{
            display: flex!important;
            justify-content: center!important;;
            margin-top: 70px;
        }
        &-l{
            display: flex;
            gap: 66px;
            background: #FFFFFF;
            border: 1px solid #E6EDF5;
            box-sizing: border-box;
            border-radius: 8px;
            padding: 16px 40px 16px 16px;
                &__title{
                    margin-top: 40px;
                    font-weight: bold;
                    font-size: 40px;
                    line-height: 48px;
                    letter-spacing: -1px;
                    color: #333333;
                    max-width: 429px;
                }
                &__text{
                    font-family: 'Work Sans';
                    font-style: normal;
                    font-weight: normal;
                    font-size: 20px;
                    line-height: 32px;
                    color: #333333;
                }
        }
        &-s{
            padding: 16px;
            background: #FFFFFF;
            border: 1px solid #E6EDF5;
            box-sizing: border-box;
            border-radius: 8px;
            &__img{
                opacity: 0.7;
                object-fit: contain;
                background: #E7F3ED;
                border-radius: 8px 8px 50px 8px;
                width: 100%;
            }
            &-img{
                max-width: 338px;
            }
            &-details{
                display: flex;
                flex-direction: column;
                align-items: start;
            }
            &__title{
                font-weight: bold;
                font-size: 24px;
                line-height: 32px;
                color: #333333;
                margin-top: 25px;
            }
        }
    }
    .articles{
        margin-top: 30px;
        display: flex;
        gap: 46px;
    }
    @media (max-width: 992px) {
        .article{
            &-l{
                flex-direction: column;
                gap: 0;
                justify-content: center;
                &__title{
                    margin-top: 25px;
                }
            }
        }
        .articles{
            flex-wrap: wrap;
            justify-content: center;
        }
    }
    @media only screen and (max-width: 476px) {
        .article{
            margin-top: 110px;
            &__title{
                font-size: 40px;
                line-height: 48px;
            }
        }
    }
</style>