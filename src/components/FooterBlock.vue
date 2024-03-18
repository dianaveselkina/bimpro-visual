<template>
  <div class="footer">
    <div class="footer__container">
      <div class="footer__top">
        <div class="footer__logo">
          <img class="logo__img" src="/img/logo__footer.png" alt="logo" />
        </div>
        <div class="footer__link">
          <ul class="footer__link-item">
            <li>
              <a href="#">Услуги</a>
            </li>
            <li>
              <a href="#">Преимущества</a>
            </li>
            <li>
              <a href="#">Проекты</a>
            </li>
            <li>
              <a href="#">Команда</a>
            </li>
            <li>
              <a href="#">Гарантии</a>
            </li>
          </ul>
        </div>
      </div>
      <div class="directions__block">
        <ul class="footer__link-item">
          <li>
            <p>Другие наши направления:</p>
          </li>
          <li>
            <a href="#">Проектирование</a>
          </li>
          <li>
            <a href="#">Дизайн</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
a {
  color: inherit;
  text-decoration: none;
}
ol,
ul {
  list-style: none;
}
.footer__container {
  padding: 15px 277px 25px 277px;
  background-color: #070707;
  color: white;
}
.footer__top {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
.logo__img {
  width: 186px;
  height: 47px;
}
.footer__link-item {
  display: flex;
  flex-direction: row;
  gap: 35px;
}
</style>
