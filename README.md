<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Свадебное приглашение</title>

<style>
body {
    margin: 0;
    font-family: 'Georgia', serif;
    color: #333;
    background: #f5f5f5;
    overflow-x: hidden;
}

section {
    padding: 60px 20px;
    text-align: center;
}

.hero {
    background: url('https://vk.com/away.php?to=https%3A%2F%2Fsun9-39.userapi.com%2Fs%2Fv1%2Fig2%2F7Z1uaBwNBCQ7WtjMt9vriTJbjQFEOIP-SDWu7s7qftnWk1NhlfTPS-FszPgoGgMYSIsvSKHeUbP2CEVkujuEtXB6.jpg%3Fquality%3D95%26as%3D32x48%2C48x72%2C72x108%2C108x162%2C160x240%2C240x360%2C360x540%2C480x720%2C540x810%2C640x960%2C720x1080%2C1080x1620%2C1280x1920%2C1440x2160%2C1600x2400%26from%3Dbu%26u%3Dh3LnsgLuCPFP2nIkT4zHF8EPsv19ikBM39-inDOoa4Y%26cs%3D640x0&utf=1') center/cover no-repeat;
    color: white;
    height: 100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    backdrop-filter: brightness(0.7);
}

.hero h1 {
    font-size: 48px;
    letter-spacing: 3px;
    animation: fadeInDown 2s ease;
}

.hero p {
    max-width: 600px;
    margin: 20px auto;
    animation: fadeIn 3s ease;
}

.gray {
    background: #eaeaea;
}

.date img {
    width: 200px;
    margin-top: 20px;
}

.timer {
    font-size: 28px;
    margin-top: 20px;
}

.timeline {
    display: flex;
    justify-content: center;
    gap: 40px;
    flex-wrap: wrap;
    margin-top: 30px;
}

.timeline div {
    font-size: 16px;
}

.map iframe {
    width: 90%;
    height: 300px;
    border: none;
    margin-top: 20px;
}

.dresscode {
    background: url('https://vk.com/away.php?to=https%3A%2F%2Fsun9-70.userapi.com%2Fs%2Fv1%2Fig2%2FscrxbajPvoexCaFWXSx0KHECQM8XEAwx_kiOXZ9cYKBhVZVJKNMH64mO566B5p7-T_zYOhuKgugOdaXt_zGxSblc.jpg%3Fquality%3D95%26as%3D32x48%2C48x72%2C72x108%2C108x162%2C160x240%2C240x360%2C360x540%2C480x720%2C540x810%2C640x960%2C720x1080%2C1080x1620%2C1280x1920%2C1440x2160%2C1600x2400%26from%3Dbu%26u%3DRVLVMs1F_qFgEE4R8OtfxN-QrhsGZAlULiR8qOGeBrQ%26cs%3D1600x0&utf=1') center/cover no-repeat;
    color: white;
}

.colors {
    display: flex;
    justify-content: center;
    gap: 15px;
    flex-wrap: wrap;
    margin-top: 20px;
}

.color {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    border: 2px solid white;
}

.rsvp button {
    padding: 15px 30px;
    font-size: 18px;
    border: none;
    background: #333;
    color: white;
    cursor: pointer;
    border-radius: 30px;
    transition: 0.3s;
}

.rsvp button:hover {
    background: #555;
}

@keyframes fadeIn {
    from {opacity:0;}
    to {opacity:1;}
}

@keyframes fadeInDown {
    from {opacity:0; transform: translateY(-30px);}
    to {opacity:1; transform: translateY(0);}
}
</style>
</head>

<body>

<section class="hero">
    <h1>Дарья & Сергей</h1>
    <p>
        Дорогие наши родные и друзья!

        Позвольте пригласить вас разделить с нами столь важный день — торжество нашего бракосочетания.

        Наша свадьба состоится:
    </p>
</section>

<section class="gray date">
    <h2>20 августа 2026</h2>
    <img src="https://vk.com/away.php?to=https%3A%2F%2Fsun9-27.userapi.com%2Fs%2Fv1%2Fig2%2Fx3wiCfa3eyTkbCHtko5cipJea4tKG12huEyA6BVKuEB4X7tG2WRUyoEArByVRMsPYWDNnsgaMdqHeyCy1IyyH8ph.jpg%3Fquality%3D95%26as%3D32x26%2C48x38%2C72x58%2C108x86%2C160x128%2C240x192%2C360x288%2C480x384%2C540x432%2C640x512%2C720x576%2C1080x864%2C1280x1024%2C1402x1122%26from%3Dbu%26u%3DaA7wTVtt5T4WcZkIL6UBi-drtCaOUXZvVn8XWv54PqU%26cs%3D1402x0&utf=1">
    <div class="timer" id="timer"></div>
</section>

<section>
    <h2>Тайминг дня</h2>
    <div class="timeline">
        <div>12:00
Церемония</div>
        <div>13:00
Прогулка</div>
        <div>17:00
Ужин</div>
        <div>23:00
Завершение</div>
    </div>
</section>

<section class="gray map">
    <h2>Место проведения</h2>
    <p>Управление ЗАГС</p>
    <iframe src="https://maps.google.com/maps?q=Белгород%20Попова%2014&output=embed"></iframe>
</section>

<section class="dresscode">
    <h2>Дресс-код</h2>
    <p>
        Нам будет приятно, если вы поддержите цветовую гамму праздника
    </p>
    <div class="colors">
        <div class="color" style="background:#f8c8dc"></div>
        <div class="color" style="background:#cde7ff"></div>
        <div class="color" style="background:#fff5ba"></div>
        <div class="color" style="background:#d4f5d0"></div>
        <div class="color" style="background:#808000"></div>
    </div>
</section>

<section class="gray rsvp">
    <button onclick="window.location.href='https://forms.gle/wBGfkj6pEau3Drqj9'">
        Подтвердить присутствие
    </button>
</section>

<section>
    <h2>С нетерпением ждём вас!</h2>
</section>

<script>
const weddingDate = new Date("Aug 20, 2026 00:00:00").getTime();

const timer = setInterval(function() {
    const now = new Date().getTime();
    const distance = weddingDate - now;

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 *0 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));

    document.getElementById("timer").innerHTML =
        days + " дней " + hours + " часов " + minutes + " минут";

}, 1000);
</script>

</body>
</html> 6
