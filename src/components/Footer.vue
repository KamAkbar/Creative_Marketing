<template>
  <footer class="footer">
      <div class="container">
          <div class="footer-container">
              <img src="../img/logolight.png" alt="Logo" class="logo footer__logo">
                <div class="footer-column">
                    <h5 class="footer__subtitle">MENU</h5>
                    <ul class="footer-link">
                        <router-link class="footer-link__item">About</router-link>
                        <router-link class="footer-link__item">Portfolio</router-link>
                        <router-link class="footer-link__item">Service</router-link>
                        <router-link class="footer-link__item">Blog</router-link>
                        <router-link class="footer-link__item">Contact</router-link>
                    </ul>
                </div>
                <div class="footer-column">
                    <h5 class="footer__subtitle">SERVICE</h5>
                    <ul class="footer-link">
                        <router-link class="footer-link__item">Consulting</router-link>
                        <router-link class="footer-link__item">Planning</router-link>
                        <router-link class="footer-link__item">Support</router-link>
                        <router-link class="footer-link__item">Cooperation</router-link>
                    </ul>
                </div>
                <div class="footer-column">
                    <h5 class="footer__subtitle">SOCIAL</h5>
                    <div class="footer-social">
                        <router-link to="https://facebook.com"><svg class="footer__social" width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M24 48C37.2548 48 48 37.2548 48 24C48 10.7452 37.2548 0 24 0C10.7452 0 0 10.7452 0 24C0 37.2548 10.7452 48 24 48Z" fill="#F07566"/>
                            <path d="M21.6667 21.3333H19V24H21.6667V32H25.6667V24H28.0933L28.3333 21.3333H25.6667V20.2227C25.6667 19.5853 25.7947 19.3333 26.4107 19.3333H28.3333V16H25.128C22.7307 16 21.6667 17.056 21.6667 19.0773V21.3333Z" fill="white"/>
                            </svg> </router-link>
                        <router-link to="https://twitter.com"><svg width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M24 48C37.2548 48 48 37.2548 48 24C48 10.7452 37.2548 0 24 0C10.7452 0 0 10.7452 0 24C0 37.2548 10.7452 48 24 48Z" fill="#F07566"/>
                            <path d="M32 19.54C31.412 19.8013 30.7787 19.9773 30.1147 20.0573C30.7933 19.6507 31.312 19.008 31.5587 18.2413C30.924 18.6173 30.2213 18.8907 29.4733 19.0373C28.876 18.3987 28.0213 18 27.0787 18C24.9587 18 23.4013 19.9773 23.88 22.0307C21.1533 21.8933 18.7333 20.5867 17.1147 18.6013C16.2547 20.076 16.6693 22.0067 18.1307 22.984C17.5933 22.9667 17.088 22.8187 16.6453 22.5733C16.6093 24.0933 17.7 25.516 19.2787 25.8333C18.8173 25.9587 18.3107 25.988 17.796 25.8893C18.2133 27.1933 19.428 28.1413 20.8627 28.168C19.48 29.2507 17.7427 29.7347 16 29.5293C17.4533 30.4613 19.1773 31.004 21.0307 31.004C27.1267 31.004 30.5693 25.856 30.3613 21.2387C31.004 20.7773 31.56 20.1987 32 19.54Z" fill="white"/>
                            </svg> </router-link>
                        <router-link to="https://instagram.com"> <svg width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M24 48C37.2548 48 48 37.2548 48 24C48 10.7452 37.2548 0 24 0C10.7452 0 0 10.7452 0 24C0 37.2548 10.7452 48 24 48Z" fill="#F07566"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M24 16C21.8267 16 21.556 16.0093 20.7013 16.0493C17.7947 16.1827 16.1813 17.7947 16.048 20.7013C16.0093 21.556 16 21.828 16 24C16 26.1733 16.0093 26.4453 16.048 27.2987C16.1813 30.204 17.7947 31.8187 20.7013 31.952C21.556 31.9907 21.8267 32 24 32C26.1733 32 26.4453 31.9907 27.3 31.952C30.2013 31.8187 31.8213 30.2067 31.952 27.2987C31.9907 26.4453 32 26.1733 32 24C32 21.828 31.9907 21.556 31.952 20.7013C31.8213 17.7987 30.2067 16.1813 27.3 16.0493C26.4453 16.0093 26.1733 16 24 16ZM24 17.4427C26.136 17.4427 26.3893 17.4507 27.2333 17.4893C29.4027 17.588 30.4133 18.616 30.5133 20.768C30.5507 21.612 30.5587 21.864 30.5587 24C30.5587 26.136 30.5507 26.3893 30.5133 27.232C30.4133 29.3827 29.404 30.4133 27.2333 30.512C26.3893 30.5493 26.1373 30.5587 24 30.5587C21.864 30.5587 21.6107 30.5507 20.768 30.512C18.5947 30.412 17.588 29.38 17.488 27.232C17.4507 26.3893 17.4413 26.136 17.4413 24C17.4413 21.864 17.4507 21.6107 17.488 20.768C17.5867 18.6147 18.5973 17.5867 20.768 17.488C21.6107 17.4493 21.864 17.4427 24 17.4427ZM19.892 24C19.892 21.7307 21.732 19.892 24 19.892C26.268 19.892 28.108 21.732 28.108 24C28.108 26.2693 26.268 28.108 24 28.108C21.732 28.108 19.892 26.2693 19.892 24ZM24 26.6667C22.5267 26.6667 21.3333 25.4733 21.3333 24C21.3333 22.528 22.5267 21.3333 24 21.3333C25.472 21.3333 26.668 22.5267 26.668 24C26.668 25.4733 25.472 26.6667 24 26.6667ZM27.3093 19.7307C27.3093 19.2 27.74 18.7707 28.2693 18.7707C28.8013 18.7707 29.2307 19.2 29.2307 19.7307C29.2307 20.2613 28.8 20.6907 28.2693 20.6907C27.7387 20.6907 27.3093 20.26 27.3093 19.7307Z" fill="white"/>
                            </svg> </router-link>
                    </div>
                </div>
          </div>
        <hr class="footer__line">
        <div class="footer-terms">
            <div class="footer__copy">Copyright © 2020 Laaqiq. All Rights Reserved.</div>
            <div class="footer-privacy">
                <p class="footer__privacy">Terms of Use</p>
                <p class="footer__privacy">Privacy Policy</p>
            </div>
        </div>
      </div>
  </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss">
    .footer{
        background-color: #494949;
        padding: 76px 0 0 0;
        margin-top: 128px;
        &-container{
          display: flex;
          justify-content: space-between;
          align-items: flex-start;
        }
        &-social{
            display: flex;
            gap: 8px;
        }
        &-link{
            display: flex;
            flex-direction: column;
            gap: 20px;
            padding-left: 0;
            margin-top: 32px;
            &__item{
                font-family: 'Work Sans';
                font-style: normal;
                font-weight: normal;
                font-size: 16px;
                line-height: 32px;
                color: #FFFFFF;
            }
        }
        &__subtitle{
            font-weight: bold;
            font-size: 16px;
            line-height: 32px;
            letter-spacing: 1px;
            text-transform: uppercase;
            color: #F07566;
        }
        &__logo{
            object-fit: contain;
        }
        &__line{
            border: 1px solid #fff;
            background: #fff;
            text-align: center;
            width: 100%;
            margin: 70px 0 0 0;
        }
        &-terms{
            margin-top: 58px;
            display: flex;
            justify-content: space-between;
        }
        &-privacy{
            display: flex;
            gap: 67px;
        }
        &__privacy{
            font-family: 'Work Sans';
            font-size: 16px;
            line-height: 32px;
            text-align: right;
            color: #FFFFFF;
        }
        &__copy{
            font-family: 'Work Sans';
            font-style: normal;
            font-weight: normal;
            text-align: center;
            font-size: 16px;
            line-height: 32px;
            color: rgba(255, 255, 255, 0.502972);
        }
    }
    @media (max-width: 769px) {
        .footer{
            &-terms{
                flex-direction: column;
                justify-content: center;
                align-items: center;
        }
        }
    }
    @media (max-width: 586px) {
        .footer{
            &-container{
                flex-direction: column;
                align-items: flex-start;
                gap: 20px;
            }
            &-link{
                margin-top: 20px;
            }
        }
    }
</style>