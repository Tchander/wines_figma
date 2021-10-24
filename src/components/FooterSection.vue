<template>
  <div class="wines-footer-section">
    <div class="wines-container">
      <footer class="wines-footer">
        <div class="wines-footer-top">
          <ul>
            <li>
              <a class="wines-footer-top-links__link" href="#">Главная</a>
            </li>
            <li>
              <a class="wines-footer-top-links__link" href="#">Каталог</a>
            </li>
            <li>
              <a class="wines-footer-top-links__link" href="#">Поставщики</a>
            </li>
            <li>
              <a class="wines-footer-top-links__link" href="#">Коллекции</a>
            </li>
            <li>
              <a class="wines-footer-top-links__link" href="#">Дегустация</a>
            </li>
            <li>
              <a class="wines-footer-top-links__link" href="#"
                >Коллекция 2020</a
              >
            </li>
            <li>
              <a class="wines-footer-top-links__link" href="#">Контакты</a>
            </li>
          </ul>
        </div>
        <div class="wines-footer-bottom">
          <div class="wines-footer-bottom__item wines-footer-bottom__item-name">
            винный бутик LE CORTE
          </div>
          <div
            class="wines-footer-bottom__item wines-footer-bottom__item-phone"
          >
            8 (812) 123-45-67
          </div>
          <div class="wines-footer-bottom__icons">
            <a href="#">
              <img src="../assets/images/icons/youtube.svg" alt="youtube" />
            </a>
            <a href="#">
              <img src="../assets/images/icons/vkontakte.svg" alt="vk" />
            </a>
            <a href="#">
              <img src="../assets/images/icons/facebook.svg" alt="facebook" />
            </a>
          </div>
          <div
            class="
              wines-footer-bottom__item wines-footer-bottom__item-copyright
            "
          >
            © le-corte.ru
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterSection",
};
</script>

<style lang="scss" scoped>
.wines-footer-section {
  background: #998431;
  .wines-footer {
    display: flex;
    flex-direction: column;
    padding: 50px 0;
    .wines-footer-top {
      ul {
        display: flex;
        justify-content: space-between;
        padding: 20px 95px;
        border-top: 1px solid #fff;
        border-bottom: 1px solid #fff;
        li {
          .wines-footer-top-links__link {
            color: #fff;
            line-height: 150%;
            text-align: center;
          }
        }
      }
    }
    .wines-footer-bottom {
      display: flex;
      padding: 0 95px;
      border-bottom: 1px solid #fff;
      color: #fff;
      .wines-footer-bottom__item {
        font-weight: 600;
        line-height: 150%;
        text-transform: uppercase;
        display: flex;
        align-items: center;
        border-right: 1px solid #fff;
        padding: 20px 0;
      }
      .wines-footer-bottom__item-name {
        width: 28%;
      }
      .wines-footer-bottom__item-phone {
        width: 25%;
        text-align: center;
        justify-content: center;
      }
      .wines-footer-bottom__icons {
        display: flex;
        justify-content: space-around;
        align-items: center;
        width: 28%;
        padding: 0 35px;
        border-right: 1px solid #fff;
      }
      .wines-footer-bottom__item-copyright {
        border-right: none;
        width: 19%;
        justify-content: flex-end;
      }
    }
  }
}
</style>
