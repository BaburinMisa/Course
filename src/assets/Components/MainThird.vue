<script>

</script>

<template>
  <main>
    <div class="main_first">
      <h1>CoffeeCrew</h1>
      <h2>Наша команда</h2>

      <div class="OurTeam">
        <div class="ourTeamOneTwo">
          <div class="ourTeamOne">
            <p>Никита Ананьев <span>Генеральный директор</span></p>
          </div>
          <div class="ourTeamTwo">
            <p>Артем Мрасов <br> <span>Старший администратор</span></p>
          </div>
        </div>
        <div class="ourTeamOneTwoSecond">
          <div class="ourTeamOneSecond">
            <p>Катерина Денилолер <span>Старший бариста</span></p>
          </div>
          <div class="ourTeamTwoSecond">
            <p>Азиза Мухтарова<br> <span>Шеф-повар</span></p>
          </div>
        </div>
      </div>



    </div>

    <div class="main_second">
      <p>Каждый прожитый миг ценен. Мы стараемся перенять многовековой <br> опыт французских мастеров и внести в него что-то новое, чтобы
        <br> дарить улыбки и настроение нашим гостям, даже если на посещение <br> кофейни у них совсем мало времени.</p>
    </div>

  </main>
</template>

<style>
.OurTeam{
  margin-bottom: 2em;
}
.ourTeamOne{
  color: white;
  font-family: "Roboto", sans-serif;
  font-weight: lighter;
  font-size: 48px;
  text-align: center;
}
.ourTeamOne span{
  font-size: 32px;
}
.ourTeamTwo{
  color: white;
  font-family: "Roboto", sans-serif;
  font-weight: lighter;
  font-size: 48px;
  text-align: center;
}
.ourTeamTwo span{
  font-size: 32px;
}
.ourTeamOneTwo{
  display: flex;
  justify-content: space-between;
  margin-top: 3em;
}
.ourTeamOne, .ourTeamTwo {
  flex: 1;
}
.ourTeamOneSecond{
  color: white;
  font-family: "Roboto", sans-serif;
  font-weight: lighter;
  font-size: 48px;
  text-align: center;
}
.ourTeamOneSecond span{
  font-size: 32px;
}
.ourTeamTwoSecond{
  color: white;
  font-family: "Roboto", sans-serif;
  font-weight: lighter;
  font-size: 48px;
  text-align: center;
}
.ourTeamTwoSecond span{
  font-size: 32px;
}
.ourTeamOneTwoSecond{
  display: flex;
  justify-content: space-between;
  margin-top: 3em;
}
.ourTeamOneSecond, .ourTeamTwoSecond {
  flex: 1;
}

.main_first{
  background: url("../img/back2.png") no-repeat top center;
  width: 100%;
  height: 55em;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.main_first h1{
  color: #fff;
  font-size: 4.5rem;
  font-family: "Roboto", sans-serif;
  font-weight: 500;
  display: flex;
  align-items: center;
  justify-content: center;


}
.main_first h2{
  font-family: "Roboto", sans-serif;
  font-weight: 300;
  color: #fff;
  font-size: 3.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;

}
.main_first h3{
  font-family: "Roboto", sans-serif;
  font-weight: 200;
  color: #ffffff;
  font-size: 1.75rem;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;

}
.main_second{
  font-family: "Roboto", sans-serif;
  font-size: 1.75rem;
  align-items: center;
  text-align: center;
  font-weight: 300;
  padding-top: 1em;
}
</style>