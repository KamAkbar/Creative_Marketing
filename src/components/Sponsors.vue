<template>
  <section class="sponsors">
      <img src="../img/s1.png" alt="Sponsors" class="sponsors__item">
      <img src="../img/s2.png" alt="Sponsors" class="sponsors__item">
      <img src="../img/s3.png" alt="Sponsors" class="sponsors__item">
      <img src="../img/s4.png" alt="Sponsors" class="sponsors__item">
      <img src="../img/s5.png" alt="Sponsors" class="sponsors__item">
      <img src="../img/s6.png" alt="Sponsors" class="sponsors__item">
  </section>
</template>

<script>
export default {
    name: 'Sponsors'
}
</script>

<style lang="scss">
    .sponsors{
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        gap: 50px;
        margin-top: 140px;
        &__item{
            object-fit: contain;
        }
    }
    @media (max-width: 1200px) {
        .sponsors{
            justify-content: center;
        }
    }
</style>