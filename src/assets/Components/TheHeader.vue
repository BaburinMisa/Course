<script>

</script>

<template>
  <header>
    <div class="header-items">
      <ul class="header-list-1">
        <li> <router-link to="/main">Главная</router-link>  </li>
        <li> <router-link to="/coffies">Кофейни</router-link> </li>
        <li> <router-link to="/about">О Нас</router-link> </li>
        <router-view />
      </ul>

      <ul class="header-list-2">
        <li><a href=""><img id="Facebook" src="../img/Vector.png" alt="facebook"></a></li>
        <li><a href=""><img id="VK" src="../img/Vector%20(1).png" alt="VK"></a></li>
        <li><a href=""><img id="Instagram" src="../img/Vector%20(2).png" alt="instagram"></a></li>
      </ul>
    </div>
  </header>
</template>




<style>
header {
  height: 3.5em;
  background:#000000;
  color: white;
  font-family: "Roboto Light";
}
.header-items {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.header-list-1 {
  font-family: "Roboto", sans-serif;
  display: flex;
  flex-direction: row;
  margin-top: 1.2em;
}
.header-list-1 li {
  list-style-type: none;
  margin-right: 1em;
}
.header-list-1 a{
  text-decoration: none;
  color: #fff;
}
.header-list-2 {
  display: flex;
  flex-direction: row;
  margin-top: 0.80em;
}


.header-list-2 li{
  list-style-type: none;
  margin-right: 0.5em;
}


</style>