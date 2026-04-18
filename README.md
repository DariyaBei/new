<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Дарья & Сергей</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display&family=Montserrat&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: 'Montserrat', sans-serif;
  text-align: center;
  background: #f2f2f2;
  color: #2c2c2c;
}

/* ОБЩИЕ СЕКЦИИ */
section {
  padding: 80px 20px;
}

/* HERO */
.hero {
  height: 100vh;
  background: url('https://sun9-61.userapi.com/s/v1/ig2/azdPZflEpbfYW10OxuwW6o15FpPhf5Z4fn_jJwlOi9VqUp-kKMh9lkw8i6pyiaw2zIfQMHDaRA5ky1T2OVQ86NWf.jpg') center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
}

.hero-box {
  background: rgba(0,0,0,0.4);
  padding: 30px;
  border-radius: 20px;
}

h1 {
  font-family: 'Playfair Display', serif;
  font-size: 50px;
}

/* СЕРЫЙ ФОН */
.gray {
  background: #f2f2f2;
}

/* КАЛЕНДАРЬ */
.calendar {
  margin-top: 20px;
}

.day {
  display: inline-block;
  border: 2px solid #2c2c2c;
  border-radius: 50%;
  padding: 10px 15px;
  margin-top: 10px;
  font-weight: bold;
}

/* ТАЙМЕР */
.timer {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 20px;
}

/* ТАЙМИНГ */
.timeline {
  max-width: 500px;
  margin: auto;
  text-align: left;
  background: white;
  padding: 30px;
  border-radius: 15px;
}

/* КАРТА */
iframe {
  width: 100%;
  max-width: 600px;
  height: 300px;
  border-radius: 15px;
  border: none;
  margin-top: 20px;
}

/* ДРЕСС-КОД */
.dress {
  background: url('https://sun9-70.userapi.com/s/v1/ig2/scrxbajPvoexCaFWXSx0KHECQM8XEAwx_kiOXZ9cYKBhVZVJKNMH64mO566B5p7-T_zYOhuKgugOdaXt_zGxSblc.jpg') center/cover;
  color: white;
}

.overlay {
  background: rgba(0,0,0,0.5);
  padding: 40px;
}

.colors {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 15px;
  margin-top: 20px;
}

.color {
  width: 70px;
  height: 70px;
  border-radius: 50%;
  border: 2px solid white;
}

.pink { background: #f8c8dc; }
.blue { background: #c8e6f8; }
.yellow { background: #fff3b0; }
.green { background: #d4f5d0; }
.olive { background: #808000; }

/* КНОПКА */
.btn {
  display: inline-block;
  padding: 15px 30px;
  border: 1px solid #2c2c2c;
  text-decoration: none;
  color: #2c2c2c;
  margin-top: 20px;
}

.btn:hover {
  background: #2c2c2c;
  color: white;
}
</style>
</head>

<body>

<!-- 1 ОБЛОЖКА -->
<section class="hero">
  <div class="hero-box">
    <h1>Дарья & Сергей</h1>
    <p>
      Дорогие наши родные и друзья!

      Позвольте пригласить вас разделить с нами столь важный день — торжество посвященное нашему бракосочетанию

      Наша свадьба состоится:
    </p>
  </div>
</section>

<!-- 2 ДАТА + ТАЙМЕР -->
<section class="gray">
  <h2>20 августа 2026</h2>

  <div class="calendar">
    <div class="day">20</div>
  </div>

  <div class="timer">
    <div><b id="d">0</b>
дней</div>
    <div><b id="h">0</b>
часов</div>
    <div><b id="m">0</b>
минут</div>
    <div><b id="s">0</b>
секунд</div>
  </div>
</section>

<!-- 3 ТАЙМИНГ -->
<section class="gray">
  <h2>Программа дня</h2>

  <div class="timeline">
    <p>12:00 — церемония бракосочетания</p>
    <p>13:00 — прогулка + фотосессия</p>
    <p>17:00 — свадебный ужин</p>
    <p>23:00 — завершение вечера</p>
  </div>
</section>

<!-- 4 МЕСТО -->
<section class="gray">
  <h2>Место проведения</h2>
  <p><b>Управление ЗАГС</b></p>

  <iframe src="https://maps.google.com/maps?q=Белгород%20Попова%2014&output=embed"></iframe>
</section>

<!-- 5 ДРЕСС-КОД -->
<section class="dress">
  <div class="overlay">
    <h2>Дресс-код</h2>

    <p>
      Нам было бы очень приятно, если бы вы выбрали наряды в этой цветовой гамме
    </p>

    <div class="colors">
      <div class="color pink"></div>
      <div class="color blue"></div>
      <div class="color yellow"></div>
      <div class="color green"></div>
      <div class="color olive"></div>
    </div>
  </div>
</section>

<!-- 6 RSVP -->
<section class="gray">
  <h2>Подтвердите присутствие</h2>

  <a href="https://forms.gle/wBGfkj6pEau3Drqj9" target="_blank" class="btn">
    Перейти к форме
  </a>

  <p style="margin-top:30px;">С нетерпением ждём вас! ❤️</p>
</section>

<script>
// ТАЙМЕР
const date = new Date("August 20, 2026 12:00:00").getTime();

setInterval(() => {
  const now = new Date().getTime();
  const diff = date - now;

  document.getElementById("d").innerText = Math.floor(diff / (1000*60*60*24));
  document.getElementById("h").innerText = Math.floor((diff / (1000*60*60)) % 24);
  document.getElementById("m").innerText = Math.floor((diff / (1000*60)) % 60);
  document.getElementById("s").innerText = Math.floor((diff / 1000) % 60);
}, 1000);
</script>

</body>
</html>/ТВОЯССЫЛ
