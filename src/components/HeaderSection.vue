<template>
  <div class="wines-header-section">
    <div class="wines-container">
      <header class="wines-header">
        <div class="wines-header-info">
          <div class="wines-header-info__address">
            Новокузнечный переулок 4/1
          </div>
          <div class="wines-header-info__phone">8 (812) 123-45-67</div>
        </div>
        <nav class="wines-header-navigation">
          <ul>
            <li>
              <a class="wines-header-navigation__link" href="#">Каталог</a>
            </li>
            <li>
              <a class="wines-header-navigation__link" href="#">Доставка</a>
            </li>
            <li>
              <a class="wines-header-navigation__link" href="#">Коллекции</a>
            </li>
            <li>
              <a class="wines-header-navigation__link" href="#">Контакты</a>
            </li>
          </ul>
        </nav>
      </header>
      <div class="wines-header-section-buttons">
        <a class="wines-header-section-buttons__btn wines__btn" href="#"
          >Винная карта</a
        >
        <a class="wines-header-section-buttons__btn wines__btn" href="#"
          >Дегустация</a
        >
      </div>
    </div>
    <img
      class="wines-header-section__image"
      src="../assets/images/header_background.png"
      alt="Background"
    />
  </div>
</template>

<script>
export default {
  name: "HeaderSection",
};
</script>

<style lang="scss" scoped>
.wines-header-section {
  position: relative;
  .wines-header {
    color: #fff;
    display: flex;
    flex-direction: column;
    margin-top: 30px;
    .wines-header-info {
      display: flex;
      justify-content: space-between;
      font-size: 13px;
      font-weight: 500;
      margin-bottom: 20px;
    }
    .wines-header-navigation {
      ul {
        display: flex;
        justify-content: space-around;
        text-align: center;
        li {
          width: 100%;
          border: 1px solid #fff;
          border-left: none;
          padding: 14px 0;
          &:last-child {
            border-right: none;
          }
          .wines-header-navigation__link {
            color: #fff;
            transition: ease-in-out 0.35s;
            &:hover {
              color: #ecdec6;
            }
          }
        }
      }
    }
  }
  .wines-header-section-buttons {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 100%;
    max-width: 415px;
    margin: 0 auto;
    padding: 582px 0 150px 0;
  }
  .wines-header-section__image {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    z-index: 1;
  }
}
</style>
