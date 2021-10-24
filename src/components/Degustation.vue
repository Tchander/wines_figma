<template>
  <div class="wines-degustation-section">
    <div class="wines-container">
      <div class="wines-degustation-rectangle wines-rectangle">
        <div class="wines-degustation-rectangle__title">
          Запись на дегустацию
        </div>
        <img
          src="../assets/images/degustation/degustation_01.png"
          alt="01"
          class="wines-degustation-rectangle__image-left"
        />
        <img
          src="../assets/images/degustation/degustation_02.png"
          alt="02"
          class="wines-degustation-rectangle__image-right"
        />
        <div class="wines-degustation__inner-wrapper">
          <div class="wines-degustation__line"></div>
          <div class="wines-degustation__text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Feugiat
            enim tortor in hac id imperdiet adipiscing. Pellentesque nisi, mi
            sit non sit sed fermentum.
          </div>
          <form @submit.prevent="" class="wines-degustation-form">
            <div class="wines-degustation-form__inputs-top">
              <input type="text" placeholder="Имя" />
              <input type="text" placeholder="Телефон" />
            </div>
            <div class="wines-degustation-form__inputs-bottom">
              <input type="text" placeholder="Бутик на Невском 103" />
            </div>
            <button class="wines-degustation-form__btn">Записаться</button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Degustation",
};
</script>

<style lang="scss" scoped>
.wines-degustation-section {
  background: #282828;
  padding: 130px 0 100px 0;
  @media (max-width: 959px) {
    padding: 70px 0 50px 0;
  }
  .wines-degustation-rectangle {
    position: relative;
    padding: 61px 0 76px 0;
    @media (max-width: 959px) {
      padding: 50px 0 40px 0;
    }
    .wines-degustation-rectangle__image-left {
      position: absolute;
      left: -33px;
      top: -71px;
      @media (max-width: 1263px) {
        left: -20px;
        width: 200px;
      }
      @media (max-width: 959px) {
        display: none;
      }
    }
    .wines-degustation-rectangle__title {
      position: absolute;
      top: -32px;
      left: 28%;
      font-family: "Playfair Display", sans-serif;
      font-weight: 700;
      font-size: 36px;
      line-height: 150%;
      text-align: center;
      color: #ffffff;
      background: #282828;
      padding: 0 49px;
      @media (max-width: 1263px) {
        left: 24%;
      }
      @media (max-width: 959px) {
        font-size: 24px;
        left: 18%;
        top: -22px;
      }
    }
    .wines-degustation-rectangle__image-right {
      position: absolute;
      right: -56px;
      top: -68px;
      @media (max-width: 1263px) {
        right: -22px;
        width: 180px;
      }
      @media (max-width: 959px) {
        display: none;
      }
    }
    .wines-degustation__inner-wrapper {
      width: 100%;
      max-width: 540px;
      margin: 0 auto;
      .wines-degustation__line {
        border-bottom: 1px solid #fff;
        width: 21.85%;
        margin: 0 auto 40px auto;
      }
      .wines-degustation__text {
        font-size: 16px;
        line-height: 150%;
        text-align: center;
        color: #fff;
        margin-bottom: 82px;
      }
      .wines-degustation-form {
        .wines-degustation-form__inputs-top {
          display: flex;
          justify-content: space-between;
          margin-bottom: 39px;
          input {
            width: 100%;
            max-width: 255px;
            background: #282828;
            color: #fff;
            font-weight: 500;
            font-size: 13px;
            line-height: 150%;
            padding-bottom: 10px;
            border-bottom: 1px solid #fff;
            &::placeholder {
              color: #fff;
              opacity: 1;
              transition: opacity 0.3s ease;
            }
            &:focus::placeholder {
              opacity: 0;
            }
          }
        }
        .wines-degustation-form__inputs-bottom {
          margin-bottom: 50px;
          input {
            width: 100%;
            background: #282828;
            color: #fff;
            font-weight: 500;
            font-size: 13px;
            line-height: 150%;
            padding-bottom: 10px;
            border-bottom: 1px solid #fff;
            &::placeholder {
              color: #fff;
              opacity: 1;
              transition: opacity 0.3s ease;
            }
            &:focus::placeholder {
              opacity: 0;
            }
          }
        }
        .wines-degustation-form__btn {
          width: 100%;
          color: #fff;
          background: transparent;
          border: 1px solid #fff;
          text-transform: uppercase;
          font-weight: 500;
          font-size: 16px;
          line-height: 20px;
          text-align: center;
          letter-spacing: 0.05em;
          padding: 14px 0;
          transition: ease-in-out 0.35s;
          &:hover {
            background: #fff;
            color: #282828;
          }
        }
      }
    }
  }
}
</style>
