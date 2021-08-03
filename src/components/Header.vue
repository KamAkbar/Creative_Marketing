<template>
  <header class="header">
      <div class="header-details">
          <img src="../img/CMP.png" alt="Logo" class="logo header__logo">
          <nav :class="isOpen ? 'active' : '' " class="nav">
              <router-link to="/" class="nav__item text">About</router-link>
              <router-link to="/" class="nav__item text">Portfolio</router-link>
              <router-link to="/" class="nav__item text">Service</router-link>
              <router-link to="/" class="nav__item text">Blog</router-link>
              <router-link to="/" class="nav__item text">Contact</router-link>
              <h1 @click="showNav()" class="close-burger">+</h1>
          </nav>
      </div>
      <button class="header__btn btn btn_secondary">CONTACT</button>
      <svg @click="showNav()" class="burger" width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M24 48C37.2548 48 48 37.2548 48 24C48 10.7452 37.2548 0 24 0C10.7452 0 0 10.7452 0 24C0 37.2548 10.7452 48 24 48Z" fill="#F07566"/>
        <path fill-rule="evenodd" clip-rule="evenodd" d="M13 16C13 15.4477 13.4477 15 14 15H34C34.5523 15 35 15.4477 35 16C35 16.5523 34.5523 17 34 17H14C13.4477 17 13 16.5523 13 16ZM13 24C13 23.4477 13.4477 23 14 23H34C34.5523 23 35 23.4477 35 24C35 24.5523 34.5523 25 34 25H14C13.4477 25 13 24.5523 13 24ZM14 31C13.4477 31 13 31.4477 13 32C13 32.5523 13.4477 33 14 33H34C34.5523 33 35 32.5523 35 32C35 31.4477 34.5523 31 34 31H14Z" fill="white"/>
        </svg>
  </header>
</template>

<script>
export default {
    name: 'Header',
    data(){
        return{
            isOpen: false,
        }
    },
    methods :{
        showNav(){
            this.isOpen = !this.isOpen;
        }
    }
}
</script>

<style lang="scss">
    .header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 16px;
        &-details{
            display: flex;
            justify-content: space-between;
        }
        &__logo{
            margin-right: 42px;
            object-fit: contain;
        }
    }
    .nav{
        display: flex;
        align-items: center;
        gap: 30px;
    }
    .burger{
        display: none;
    }
    .close-burger{
        transform: rotate(45deg);
        font-weight: 200;
        font-size: 46px;
        color: #fff;
        &:hover{
            transform: rotate(90deg);
            transition: .1s;
        }
    }
    @media only screen and (max-width: 772px) {
        .header{
            &__btn{
                display: none!important;
            }
        }
        .close-burger{
            display: none;
        }
    }

    @media only screen and (max-width: 530px) {
        .burger{
            display: block;
        }
        .nav{
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 50px;
            padding: 80px 0;
            position: absolute;
            left: -100%;
            top: 0;
            transition: all 0.35s;
            z-index: 1;
            background-color: #F07566;
            width: 100%;
            &__item{
                color: #fff!important;
            }
        }
        .active{
            left: 0;
        }

        .close-burger{
            position: absolute;
            top: 20px;
            right: 20px;
            transform: rotate(45deg);
        }
    }
</style>