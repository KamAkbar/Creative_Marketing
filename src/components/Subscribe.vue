<template>
  <section class="subscribe">
      <h1 class="subscribe__title">Company Newsletter</h1>
      <div class="subscribe-email">
          <input type="text" class="subscribe__input" placeholder="Your Email">
          <button class="btn btn_primary">SUBSCRIBE</button>
      </div>
  </section>
</template>

<script>
export default {
    name: 'Subscribe'
}
</script>

<style lang="scss">
    .subscribe{
        margin-top: 108px;
        display: flex;
        justify-content: space-between;
        &__title{
            font-weight: bold;
            font-size: 40px;
            line-height: 48px;
            letter-spacing: -1px;
            color: #333333;
        }
        &__input{
            background: #FFFFFF;
            border: 1px solid #DADADA;
            box-sizing: border-box;
            border-radius: 6px;
            outline: none;
            padding: 9px 100px 7px 16px;
            max-width: 100%;
        }
        &-email{
            display: flex;
            align-items: center;
            gap: 30px;
        }
    }
    @media (max-width: 992px) {
        .subscribe{
            flex-direction: column!important;
            align-items: flex-start;
            &-email{
                flex-direction: column;
                align-items: flex-start;
            }
        }
    }
</style>