<script>

</script>

<template>
  <div>
    <footer>
      <div class="footerFirst">
        <p class="footer_oneP">Адреса:<br/><br/></p>
        <p class="footer_twoP">Проспект Ленина 77<br/>Улица Кулёва, 4</p>
      </div>
      <div class="footerSecond">
        <p class="footer_oneP">Время работы кофеен: <br/>
          <p class="footer_twoP">ежедневно с 9:00 до 21:00</p> <br><br> </p>
        <p class="footer_oneP">Связаться с нами: <br>
          <p class="footer_twoP">client@coffeecrew.ru</p> <br><br></p>
        <p class="footer_oneP">По всем вопросам сотрудничества: <br>
          <p class="footer_twoP">oui@coffeecrew.ru</p> <br><br></p>
        <div>
          <ul class="Slider-block-list-social_two">
            <li><a href=""><img id="Facebook" src="../img/Vector (2).png" alt="facebook"></a></li>
            <li><a href=""><img id="VK" src="../img/Vector (1).png" alt="VK"></a></li>
            <li><a href=""><img id="Instagram" src="../img/insta.png" alt="instagram"></a></li>
          </ul>
        </div>
      </div>

    </footer>
  </div>
  <div class="footerUnder">
    <p>Made by Baburin Misha</p>
  </div>
</template>

<style>
footer{
  background: black;
  height: 25em;
  color: white;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  font-family: "Roboto", sans-serif;


}
.footerFirst{
  margin-right: 20em;
}
.Slider-block-list-social_two {
  display: flex;
  flex-direction: row;

}
.Slider-block-list-social_two li{
  margin-right: 1em;
  list-style-type: none;
}
.footer_oneP{
  font-size: 1.2rem;
  font-weight: bold;
}
.footer_twoP{
  font-weight: lighter;
  font-size: 1.2rem;
}
.footerUnder{
  color: #525050;
  font-family: "Roboto", sans-serif;
  font-size: 0.75rem;
  background: black;
  text-align: center;
}
</style>