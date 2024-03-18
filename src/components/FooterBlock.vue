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
        <ul class="footer__link1-item">
          <li>
            <p>Другие наши направления:</p>
          </li>
          <li>
            <a class="link" href="#">Проектирование</a>
          </li>
          <li>
            <a class="link" href="#">Дизайн</a>
          </li>
        </ul>
      </div>
      <div class="footer__contacts">
        <div class="footer__map">
          <p class="address">г. Санкт-Петербург, Шпалерная ул. д. 51</p>
          <div class="map__wrapper">
            <div class="email__block">
              <p>+7 812 330 10 40</p>
              <p>project@bimpro.ru</p>
            </div>
            <div class="schedule__block">
              <p>ПН-ПТ 9:00 — 18:00</p>
              <p>СБ, ВС — Выходные</p>
            </div>
          </div>
          <img class="map__img" src="/img/map.png" alt="map" />
        </div>
        <div class="telephone__block">
          <div class="telephone__madrid">
            <p class="orange">Calle Gravina 21, Bajo 3</p>
            <p class="city">Madrid</p>
            <p class="city__tel">+34 657 57 25 65</p>
            <p>+34 653 53 35 68</p>
          </div>
          <div class="telephone__múnich">
            <p class="orange">Zentnerstraße 35</p>
            <p class="city">Múnich</p>
            <p class="city__tel">+49 157 325 40 621</p>
            <p>+49 157 703 06 271</p>
          </div>
          <div class="telephone__astana">
            <p class="orange">Мекен Жайы 5 Көше</p>
            <p class="city">Астана</p>
            <p class="city__tel">+34 657 57 25 65</p>
            <p>+34 653 53 35 68</p>
          </div>
        </div>
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
  padding: 100px 0 0;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
.footer__contacts {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  gap: 20px;
}
.map__wrapper {
  padding-bottom: 47px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  font-size: 18px;
}
.link {
  font-size: 18px;
  color: #ea4c14;
  text-decoration: underline;
}
.address {
  font-size: 18px;
  color: #ea4c14;
  padding-bottom: 47px;
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
.footer__link1-item {
  padding: 66px 0 55px;
  display: flex;
  flex-direction: row;
  gap: 35px;
}
.telephone__block {
  display: grid;
  grid-template-columns: repeat(2, 240px);
  grid-template-rows: repeat(3, 1fr);
  justify-items: center;
}
.orange {
  color: #ea4c14;
  font-size: 18px;
}
.city {
  padding: 12px 0 36px;
}
.city__tel {
  padding-bottom: 12px;
}
</style>
