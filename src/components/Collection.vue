<template>
  <div class="wines-collection-section">
    <div class="wines-container">
      <div class="wines-collection__content">
        <div class="wines-collection__content-info">
          <div class="wines-collection__content-info__subtitle">
            Новинки коллекций
          </div>
          <div class="wines-collection__content-info__title">
            Март 1980 Урожай Марселя
          </div>
          <div class="wines-collection__content-info__line"></div>
          <div class="wines-collection__content-info__text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Feugiat
            enim tortor in hac id imperdiet adipiscing. Pellentesque nisi, mi
            sit non sit sed fermentum. Felis adipiscing morbi sodales ac.
          </div>
          <div class="wines-collection__content-info__cards">
            <div class="wines-collection__content-info__cards-card">
              <div class="wines-collection__content-info__cards-card__year">
                1980
              </div>
              <div class="wines-collection__content-info__cards-card-info">
                <div
                  class="wines-collection__content-info__cards-card-info__title"
                >
                  Colli Euganei Bianco Ca' Lustra 1980
                </div>
                <div
                  class="
                    wines-collection__content-info__cards-card-info__description
                  "
                >
                  Красочная бутылка вина из Марселя
                </div>
              </div>
            </div>
            <div class="wines-collection__content-info__cards-card">
              <div class="wines-collection__content-info__cards-card__year">
                1980
              </div>
              <div class="wines-collection__content-info__cards-card-info">
                <div
                  class="wines-collection__content-info__cards-card-info__title"
                >
                  Colli Euganei Bianco Ca' Lustra 1980
                </div>
                <div
                  class="
                    wines-collection__content-info__cards-card-info__description
                  "
                >
                  Красочная бутылка вина из Марселя
                </div>
              </div>
            </div>
            <div class="wines-collection__content-info__cards-card">
              <div class="wines-collection__content-info__cards-card__year">
                1980
              </div>
              <div class="wines-collection__content-info__cards-card-info">
                <div
                  class="wines-collection__content-info__cards-card-info__title"
                >
                  Colli Euganei Bianco Ca' Lustra 1980
                </div>
                <div
                  class="
                    wines-collection__content-info__cards-card-info__description
                  "
                >
                  Красочная бутылка вина из Марселя
                </div>
              </div>
            </div>
          </div>
          <div class="wines-collection__content-info__text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Feugiat
            enim tortor in hac id imperdiet adipiscing. Pellentesque nisi, mi
            sit non sit sed fermentum. Felis adipiscing morbi sodales ac.
          </div>
          <div class="wines-collection-section__btn">
            <a class="wines__btn" href="#">Узнать подробнее</a>
          </div>
        </div>
        <div class="wines-collection__content-images">
          <div class="wines-collection__content-images__top">
            <img src="../assets/images/collection/collection_01.png" alt="01" />
          </div>
          <div class="wines-collection__content-images__bottom">
            <img src="../assets/images/collection/collection_02.png" alt="02" />
            <img src="../assets/images/collection/collection_03.png" alt="03" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Collection",
};
</script>

<style lang="scss" scoped>
.wines-collection-section {
  background: #e6e3c4;
  padding: 80px 0;
  .wines-collection__content {
    display: flex;
    border-top: 1px solid #998431;
    border-bottom: 1px solid #998431;
    padding: 60px 0;
    .wines-collection__content-info {
      margin-right: 110px;
      .wines-collection__content-info__subtitle {
        font-size: 16px;
        line-height: 150%;
        margin-bottom: 30px;
      }
      .wines-collection__content-info__title {
        font-family: "Playfair Display", sans-serif;
        font-weight: 700;
        font-size: 36px;
        line-height: 150%;
        color: #282828;
        width: 100%;
        max-width: 298px;
        margin-bottom: 30px;
      }
      .wines-collection__content-info__line {
        width: 100%;
        max-width: 160px;
        border-bottom: 1px solid #282828;
        margin-bottom: 30px;
      }
      .wines-collection__content-info__text {
        line-height: 150%;
        color: #282828;
        width: 100%;
        max-width: 445px;
        margin-bottom: 30px;
      }
      .wines-collection__content-info__cards {
        display: flex;
        flex-direction: column;
        margin-bottom: 30px;
        .wines-collection__content-info__cards-card {
          display: flex;
          border-bottom: 1px solid #282828;
          &:last-child {
            border-bottom: none;
          }
          .wines-collection__content-info__cards-card__year {
            display: flex;
            align-items: center;
            line-height: 150%;
            color: #282828;
            padding: 0 24px 0 19px;
            border-right: 1px solid #282828;
          }
          .wines-collection__content-info__cards-card-info {
            margin: 5px 0 15px 30px;
            .wines-collection__content-info__cards-card-info__title {
              font-family: "Playfair Display", sans-serif;
              font-weight: 700;
              font-size: 18px;
              line-height: 150%;
              color: #282828;
              margin-bottom: 5px;
            }
            .wines-collection__content-info__cards-card-info__description {
              line-height: 150%;
              color: #282828;
            }
          }
        }
      }
      .wines-collection-section__btn {
        margin-top: 45px;
      }
    }
    .wines-collection__content-images {
      margin-left: 5px;
      .wines-collection__content-images__top {
        margin-bottom: 30px;
        img {
          width: 100%;
          max-width: 540px;
        }
      }
      .wines-collection__content-images__bottom {
        display: flex;
        justify-content: space-between;
        img {
          width: 100%;
          max-width: 255px;
        }
      }
    }
  }
}
</style>
