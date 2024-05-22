<script>

</script>

<template>
  <main>
    <div class="main_first">
      <h1>CoffeeCrew</h1>
      <h2>Французские кофейни<br/>в Томске</h2>
      <h3>Проспект Ленина,75<br/>Улица Кулёва,24 (через бронь)
      </h3>
    </div>
    <div class="main_second">
      <p>Наши кофейни — это маленькая Франция <br>
        в разных уголках Томска. Мы делаем десерты, <br>
        варим кофе и дарим хорошее настроение. К нам приходят завтракать,<br>
        обедать и ужинать, общаться с друзьями и коллегами. Bienvenue!</p>
    </div>




  </main>
</template>

<style>
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
  padding-top:2em ;
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
  padding-top:120px ;
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