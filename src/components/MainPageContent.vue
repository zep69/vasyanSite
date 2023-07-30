<template>
  <div style="display: flex; justify-content: center; ">
    <div class="animate__animated animate__slideInLeft cardStyle" style="height: 400px; background-color: #e8e5e5; padding:2rem; width: 35rem ">
      <h2>Информация о компании: </h2>
      <div style="display: block">
        <li>Основана в феврале 2023 года Маратом Чукчей</li>
        <li>Марат оказался жоским Васяном в написании кода</li>
      </div>
    </div>

    <div class="animate__animated animate__slideInRight cardStyle" style="height: 400px; background-color: #e8e5e5; margin-left: 2rem; padding: 2rem; width:35rem">
      <h2>Наши "проекты" </h2>
      <h3>Первым и единственным проектом на данный момент является телеграм бот</h3>
      <h3>Главные фичи, которые были реализованы в проекте:</h3>
      <li>Полная не работоспособность без своего "хозяина", ибо чтобы запустить сие чудо, нужно выпить галлон пульсапа</li>
      <li>Краш бота после каждого "харам" действия</li>
      <li>Для запуска бота, так же требуется один Васян или любой мусульман</li>
      <li>Не юзер френдли функционал </li>
      <li>Он что-то умеет делать, но это не точно</li>
    </div>
  </div>
  <br>
  <div style="display: flex; justify-content: center">
    <div class="animate__animated  animate__rollIn cardStyle" style="width: 70rem; background-color: #e8e5e5; padding: 2rem ">
      <h2>Немного об основателе "{{nameOrg}}"</h2>
      <img class="imgVasyan" src="../assets/mainVasyan.jpg" alt="">
      <br>
      <h2>Марат "Васян" Вагапов</h2>
      <h4>CEO организации {{nameOrg}}</h4>
      <span>Данный персонаж родился в городе Тольятти, в семье татарина и русской. До 2022 года вёл довольно-таки маргинальный  образ жизни. В 2022 году устраивается в компанию "Мега Хенд" на должность специалиста тех.поддержки.
        Был на грани увольнения, но чудом засейвился. Спустя 5 месяцев работы, понял что хочет быть прогером, а не додиком. К сожалению додиком он не перестал быть, зато начал делать успехи в написании плохого кода, из-за чего и был награжден прозвищем "Васян".
        На волне хайпе создаёт организацию из одного человека, и называет её в честь себя "{{nameOrg}}". В данный момент занимается в соло проектом веб-приложения для кого-то в АвтоВАЗе.
      </span>
      <h3 style="color:red">ВНИМАНИЕ!!! Заказчики, будьте осторожный данный персонаж любит оставлять пенисы в коде!!! </h3>
    </div>
  </div>
  <br>
  <div style="display:flex; justify-content: center">
    <div class="animate__animated animate__slideInLeft cardStyle" style="width: 70rem; background-color: #e8e5e5; padding: 2rem ">
      <h2>Расценки за работу:</h2>
      <li>В зависимости от проекта Х банок PulseUp </li>
      <li>Сроки выполнения: от "Я ебу" до "Хуй знает"</li>
      <li>Качество работы "Ахуенное"</li>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainPageContent",
  data(){
    return{
      nameOrg : '<Vasyan Development />'
    }
  }
}
</script>

<style scoped>
.cardStyle{
  border-radius: 2rem;
  border: 1px solid grey
}
.imgVasyan{
  width:40rem;
  border-radius: 2rem;
  transition: 2s;
}
.imgVasyan:hover{
  transform: scale(1.25);
}

</style>