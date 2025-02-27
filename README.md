<!DOCTYPE html>
<html lang="kk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Игілік - Мобилограф</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
<style>
body {
font-family: 'Montserrat', sans-serif;
background-color: #1a1a1a;
color: #fff;
margin: 0;
padding: 0;
text-align: center;
}
header {
background: linear-gradient(90deg, #ff8c00, #ff4500);
padding: 50px;
}
header h1 {
font-size: 2.5em;
font-weight: 700;
margin: 0;
}
.container {
max-width: 800px;
margin: 40px auto;
padding: 20px;
background: rgba(255, 255, 255, 0.1);
border-radius: 10px;
box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.2);
}
p {
font-size: 1.2em;
font-weight: 400;
}
.social-links {
margin-top: 20px;
}
.social-links a {
display: inline-block;
background: #ff4500;
color: white;
text-decoration: none;
padding: 10px 20px;
border-radius: 5px;
font-size: 1.2em;
font-weight: 700;
margin: 10px;
transition: 0.3s;
}
.social-links a:hover {
background: #ff8c00;
}
.language-buttons {
margin-top: 20px;
}
.language-buttons button {
padding: 10px 15px;
font-size: 1em;
border: none;
cursor: pointer;
margin: 5px;
border-radius: 5px;
font-weight: 700;
background: #ff8c00;
color: white;
transition: 0.3s;
}
.language-buttons button:hover {
background: #ff4500;
}
</style>
</head>
<body>

<header>
<h1 id="title">Привет, меня зовут Игілік!</h1>
<p id="subtitle">Я — молодой мобилограф из Кызылорды, мне 16 лет.</p>
</header>

<div class="container">
<p id="description">Я увлекаюсь созданием мобильных видео, монтирую и снимаю короткие ролики. Работаю над проектами для соцсетей, делаю креативный контент.</p>

<div class="social-links">
<a href="https://www.instagram.com/igilik.mobilographer?igsh=MWp1cXBrOG04dXcxdg%3D%3D&utm_source=qr" target="_blank">Instagram</a>
<a href="https://www.tiktok.com/@igilik.tynymbai?_t=ZM-8u1RFPqgLqA&_r=1" target="_blank">TikTok</a>
<a href="https://wa.me/7057233310" target="_blank">Whatsapp</a>
</div>

<div class="language-buttons">
<button onclick="setLanguage('kk')">Қазақша</button>
<button onclick="setLanguage('ru')">Русский</button>
<button onclick="setLanguage('en')">English</button>
</div>
</div>

<script>
const translations = {
kk: {
title: "Сәлем, менің атым Игілік!",
subtitle: "Мен – Қызылордадан келген жас мобилограф, 16 жастамын.",
description: "Мен мобильді бейнелер жасаумен айналысамын, қысқа роликтерді өңдеймін және түсіремін. Әлеуметтік желілер үшін креативті контент жасаймын."
},
ru: {
title: "Привет, меня зовут Игілік!",
subtitle: "Я — молодой мобилограф из Кызылорды, мне 16 лет.",
description: "Я увлекаюсь созданием мобильных видео, монтирую и снимаю короткие ролики. Работаю над проектами для соцсетей, делаю креативный контент."
},
en: {
title: "Hello, my name is Igilik!",
subtitle: "I am a young mobile videographer from Kyzylorda, I am 16 years old.",
description: "I create mobile videos, edit and shoot short clips. I work on social media projects and create creative content."
}
};

function setLanguage(lang) {
document.getElementById("title").innerText = translations[lang].title;
document.getElementById("subtitle").innerText = translations[lang].subtitle;
document.getElementById("description").innerText = translations[lang].description;
}
</script>

</body>
</html>
