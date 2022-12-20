<script></script>
<template>
  <header>
    <div class="navbar">
      <h2>inicio</h2>
      <h2>mangas</h2>
      <h2>categorias</h2>
      <h2>botao pesquisar</h2>
    </div>
  </header>
  <body>
    <div class="destaques">Destaque!! (carrosel) </div>
    <div class="atualizados">anime atualizado (carrosel) </div>

    <div class="blocao">
      <article>
        <div class="lancamentos">
          <h2>lancamentos</h2>
          <div class="animecard">

          </div>
        </div>
      </article>

      <article>
        <div class="maislidos"><h2>maislidos</h2></div>
      </article>
    </div>
  </body>
  <footer>development by jaaj</footer>
</template>
<style>
body {
  background-color: #575069;
}
header {
  background-color: #494058;
}
.navbar {
  display: flex;
  width: 100vh;
  height: 100;
}
.destaques {
  background-color: #f29a30;
  height: 260px;
  width: 1200px;
  margin: 44px;
  align-content: center;
}

.atualizados {
  background-color: #f29a30;
  height: 350px;
  width: 1200px;
  margin: 44px;
  align-content: center;
}
.navbar h2 {
  margin-left: 10px;
}
footer {
  background-color: #494058;
}

.blocao {
  display: flex;
}

.lancamentos {
  margin: 30px;
  background-color: #494058;
  height: 600px;
  width: 700px;
  box-shadow: -20px 20px #f29a30;
  display: flex;

}

.lancamentos h2 {
  color: white;
  background-color: #f29a30;
  width: 160px;
  height: 50px;
  margin: 10px;
  font-family: 'Montserrat', sans-serif;
}

.maislidos {
  margin: 30px;
  background-color: #494058;
  height: 600px;
  width: 450px;
  box-shadow: -20px 20px #f29a30;
  display: flex;
}

.maislidos h2 {
  color: white;
  background-color: #f29a30;
  width: 120px;
  height: 50px;
  margin: 10px;
  font-family: 'Montserrat', sans-serif;
}

.animecard{
  background-color:#575069;
  margin: 10px;
  width: 150px;
  height: 200px;
}

</style>
