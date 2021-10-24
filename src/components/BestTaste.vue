<template>
  <div class="wines-best-section">
    <div class="wines-container">
      <div class="wines-best-rectangle wines-rectangle">
        <div class="wines-best__inner-wrapper">
          <div class="wines-best__title">
            Лучший вкус, это вкус долголетнего вина
          </div>
          <div class="wines-best__line"></div>
          <div class="wines-best__text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Feugiat
            enim tortor in hac id imperdiet adipiscing. Pellentesque nisi, mi
            sit non sit sed fermentum. Felis adipiscing morbi sodales ac. Mauris
            dictumst risus pulvinar blandit elit. Vestibulum quam ultrices
            nascetur et viverra suscipit. Proin vitae aliquet leo aliquam amet
            rutrum. Lectus auctor purus ultrices enim ultrices. Augue fringilla
            tellus tortor orci ultrices sed. Viverra cras sapien, pellentesque
            viverra malesuada. Tellus dolor, eget vitae dignissim molestie eget
            sit duis. Vitae dui vel pretium euismod diam. Pellentesque amet,
            lacus, amet, quis risus. Pellentesque scelerisque nunc, orci aliquam
            quis.
          </div>
          <img src="../assets/images/wineglass.png" alt="Wineglass" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BestTaste",
};
</script>

<style lang="scss" scoped>
.wines-best-section {
  background: #282828;
  padding: 98px 0;
  @media (max-width: 959px) {
    padding: 48px 0;
  }
  .wines-best-rectangle {
    .wines-best__inner-wrapper {
      width: 100%;
      max-width: 736px;
      margin: 0 auto;
      .wines-best__title {
        font-family: "Playfair Display", sans-serif;
        font-size: 36px;
        font-weight: 700;
        margin-bottom: 56px;
        @media (max-width: 959px) {
          font-size: 26px;
        }
      }
      .wines-best__line {
        border-bottom: 1px solid #fff;
        width: 21.7%;
        margin: 0 auto 40px auto;
      }
      .wines-best__text {
        font-size: 16px;
        font-weight: 400;
        line-height: 24px;
        max-width: 733px;
        margin-bottom: 50px;
      }
    }
  }
}
</style>
