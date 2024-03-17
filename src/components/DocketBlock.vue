<template>
  <div class="docket__container">
    <div class="list__items">
      <div class="list__item">
        <p><span>Важно</span> знать</p>
      </div>
      <hr class="hr" />
      <div class="list__item">
        <p><span>гарантии,</span> прописанные в договоре</p>
      </div>
      <hr class="hr" />
      <div class="list__item">
        <p><span>структура</span> работы</p>
      </div>
    </div>
    <div class="lists__description">
      <div class="list__item">
        <p class="description">
          Мы заинтересованы в взаимовыгодных рабочих отношениях с нашими
          клиентами и в том, чтобы довести любой проект до завершения.
        </p>
      </div>
      <hr class="hr1" />
      <div class="list__item">
        <p class="description">
          Передаваемое вами ТЗ должно быть, по возможности, полным и подробным,
          чтобы мы могли максимально точно выполнить поставленную задачу.
        </p>
      </div>
      <hr class="hr1" />
      <div class="list__item">
        <p class="description">
          Нам настолько нравятся наши работы, что мы просто не можем не
          поделиться ими, поэтому по завершению проекта мы обычно размещаем его
          в нашем портфолио на сайте, со ссылкой на заказчика.
        </p>
      </div>
      <hr class="hr1" />
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.docket__container {
  padding: 100px 277px;
  background-color: #2e2e31;
  color: white;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  gap: 166px;
}
.list__items {
  display: flex;
  flex-direction: column;
}
p {
  font-size: 50px;
  color: #ea4c14;
}
p > span {
  color: white;
}
.hr {
  margin: 46px 0;
  border: 0.5px solid #e3e2e2;
  width: 486px;
  height: 0px;
  opacity: 0.2;
}
.hr1 {
  border: 0.5px solid #9da0a3;
  width: 690px;
  height: 0px;
  opacity: 0.3;
}
.description {
  padding: 30px 0;
  font-size: 22px;
  color: #fff;
}
</style>
