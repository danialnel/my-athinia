<!DOCTYPE html>

<html>

<head>

<title>For My Princess Athinia 💗</title>

<style>

* {

box-sizing: border-box;

}

body {

margin:0;

font-family: Arial, sans-serif;

text-align:center;

color:white;

background:linear-gradient(#100020,#3b005c,#ff9fd8);

min-height:100vh;

overflow-x:hidden;

}

/* stars */

.star {

position:fixed;

font-size:20px;

animation:float 8s infinite;

opacity:0.8;

}

@keyframes float {

0% {

transform:translateY(100vh);

}

100% {

transform:translateY(-20vh);

}

}

/* title */

h1 {

font-size:42px;

margin-top:50px;

text-shadow:0 0 20px pink;

}

h2 {

color:#ffd1ec;

}

.card {

background:rgba(255,255,255,0.15);

backdrop-filter:blur(10px);

border-radius:30px;

padding:25px;

margin:25px auto;

width:90%;

max-width:500px;

box-shadow:0 0 20px rgba(255,255,255,0.2);

}

/* buttons */

button {

background:#ff8fd1;

border:none;

color:white;

padding:15px 30px;

border-radius:50px;

font-size:18px;

}

button:active {

transform:scale(0.9);

}

/* surprise */

#surprise {

display:none;

}

/* countdown */

#countdown {

font-size:28px;

color:#ffe4f5;

}

.song {

background:rgba(255,255,255,0.12);

padding:10px;

border-radius:20px;

margin:10px;

}

.memory {

border:2px dashed pink;

padding:20px;

border-radius:20px;

margin:10px;

}

</style>

</head>

<body>

<!-- floating stars -->

<div class="star" style="left:10%;animation-delay:0s;">✨</div>

<div class="star" style="left:30%;animation-delay:2s;">🌙</div>

<div class="star" style="left:50%;animation-delay:4s;">⭐</div>

<div class="star" style="left:70%;animation-delay:1s;">✨</div>

<div class="star" style="left:90%;animation-delay:3s;">🌸</div>

<h1>

🌙 Princess Athinia 👑💗

</h1>

<p>

Made with love from Buggy 🤍

</p>

<div class="card">

<h2>

Welcome Princess 💜

</h2>

<p>

This is a little place made only for you.

A place filled with memories, songs, and love.

🌸🌙

</p>

</div>

<div class="card">

<h2>

💌 A Letter For You

</h2>

<p>

Dear Princess,

<br><br>

Thank you for being part of my life.

You make ordinary days feel special.

I hope this little website reminds you that you are loved.

<br><br>

Love,

<br>

Buggy 💗

</p>

</div>

<div class="card">

<h2>

⏳ Our Special Day

</h2>

<p>

Counting down to 1 January 💗

</p>

<h1 id="countdown">

Loading...

</h1>

</div>

<div class="card">

<h2>

🎵 Our Soundtrack

</h2>

<div class="song">

No.1 Party Anthem - Arctic Monkeys

</div>

<div class="song">

I Wanna Be Yours - Arctic Monkeys

</div>

<div class="song">

Last Night on Earth - Green Day

</div>

<div class="song">

Kecundang - Masdo

</div>

<div class="song">

Dinda - Masdo

</div>

<div class="song">

Mabagal - Moira

</div>

</div>

<div class="card">

<h2>

📸 Our Memories

</h2>

<div class="memory">

Add your favourite picture here 💗

</div>

<div class="memory">

Add another memory 🌸

</div>

</div>

<button onclick="showLove()">

Open Surprise 💌

</button>

<div class="card" id="surprise">

<h2>

🌙 For My Princess

</h2>

<p>

No matter what happens,

I hope you always remember that you are someone special to me.

<br><br>

I love you Princess 💗

</p>

</div>

<script>

function showLove(){

document.getElementById("surprise").style.display="block";

}

let date = new Date("January 1, 2027 00:00:00").getTime();

setInterval(function(){

let now = new Date().getTime();

let distance = date-now;

let days = Math.floor(distance/(1000*60*60*24));

let hours = Math.floor((distance%(1000*60*60*24))/(1000*60*60));

let minutes = Math.floor((distance%(1000*60*60))/(1000*60));

let seconds = Math.floor((distance%(1000*60))/1000);

document.getElementById("countdown").innerHTML =

days+" days "+hours+" hours "+minutes+" minutes "+seconds+" seconds";

},1000);

</script>

</body>

</html>
