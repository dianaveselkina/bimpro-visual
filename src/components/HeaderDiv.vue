<template>
  <div class="header">
    <div class="header__container">
      <div class="header__logo">
        <img class="logo__img" src="../img/logo.png" alt="logo" />
      </div>
      <div class="header__link">
        <ul class="header__link-item">
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
          <li>
            <a href="#">Контакты</a>
          </li>
        </ul>
      </div>
      <div class="header__contacts">
        <span>+7 812 330 10 40</span>
        <span>project@bimpro.ru</span>
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
.header__container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 15px 277px 25px 277px;
  background-color: #222224;
  color: white;
}
.logo__img {
  width: 186px;
  height: 47px;
}
.header__link-item {
  display: flex;
  flex-direction: row;
  gap: 35px;
}
.header__contacts {
  display: flex;
  flex-direction: column;
}
</style>
