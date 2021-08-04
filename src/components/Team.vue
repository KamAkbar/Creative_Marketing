<template>
  <section class="team">
      <div class="team-details">
          <h5 class="team__subtitle">
              <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M6 12C9.31371 12 12 9.31371 12 6C12 2.68629 9.31371 0 6 0C2.68629 0 0 2.68629 0 6C0 9.31371 2.68629 12 6 12Z" fill="#F07566"/>
                </svg> TEAM
          </h5>
          <h1 class="team__title">Strong Members</h1>
          <p class="team__text">Formed a great hindrance to my speed, I resolved, contrary to my first intention, to make the being of a gigantic stature that is to say, about eight feet in height.</p>
      </div>
      <div class="projects">
          <div class="project">
              <div class="project-img">
                <img src="https://picsum.photos/338/320" alt="Project" class="project__img">
              </div>
              <div class="project-details">
                  <h4 class="project__title">Ingo Schimpff</h4>
                  <p class="project__info">Manager</p>
              </div>
          </div>
          <div class="project">
              <div class="project-img">
                <img src="https://picsum.photos/338/320" alt="Project" class="project__img">
              </div>
              <div class="project-details">
                  <h4 class="project__title">Gauthier Drewitt</h4>
                  <p class="project__info">Director</p>
              </div>
          </div>
          <div class="project">
              <div class="project-img">
                <img src="https://picsum.photos/338/320" alt="Project" class="project__img">
              </div>
              <div class="project-details">
                  <h4 class="project__title">Winny Rearie</h4>
                  <p class="project__info">Manager</p>
              </div>
          </div>
          
      </div>
  </section>
</template>

<script>
export default {
    name: 'Team'
}
</script>

<style lang="scss">
    .team{
        margin-top: 140px;
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
    }
    .projects{
        margin-top: 60px;
        display: flex;
        flex-wrap: nowrap;
        justify-content: space-around;
        gap: 30px;
    }
    .project{
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
            position: relative;
            max-width: 570px;
        }
        &-details{
            display: flex;
            flex-direction: column;
            align-items: start;
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
    @media (max-width: 992px) {
        .projects{
            flex-wrap: wrap;
        }
    }
    @media only screen and (max-width: 476px) {
        .team{
            margin-top: 110px;
            &__title{
                font-size: 40px;
                line-height: 48px;
            }
        }
    }
</style>