<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Friendship Day</title>

<style>
body{
margin:0;
font-family:Arial,sans-serif;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
background:linear-gradient(135deg,#ffd6e7,#fff4b3,#d7f8d0);
overflow:hidden;
}

.card{
background:white;
padding:30px;
border-radius:25px;
width:85%;
max-width:400px;
text-align:center;
box-shadow:0 10px 25px rgba(0,0,0,.15);
animation:fade 1.2s;
}

h1{
color:#ff5b95;
}

p{
font-size:18px;
color:#444;
line-height:1.6;
}

button{
margin-top:20px;
padding:14px 30px;
font-size:18px;
border:none;
border-radius:30px;
background:#ff6fa5;
color:white;
cursor:pointer;
transition:.3s;
}

button:hover{
transform:scale(1.08);
}

.flower{
position:absolute;
font-size:25px;
animation:fall linear infinite;
}

@keyframes fall{
0%{
transform:translateY(-10vh);
}
100%{
transform:translateY(110vh);
}
}

@keyframes fade{
from{
opacity:0;
transform:translateY(20px);
}
to{
opacity:1;
transform:translateY(0);
}
}
</style>

</head>

<body>

<div class="card">

<h1>🌼 Happy Friendship Day 🌼</h1>

<p>
Every friendship has a story...
This little website is a small gift made especially for someone amazing.
I hope it makes you smile today. 💛
</p>

<button onclick="location.href='letter.html'">
Open My Gift 🎁
</button>

</div>

<script>

let emojis=["🌸","🌼","✨","💛","🦋"];

for(let i=0;i<35;i++){

let e=document.createElement("div");

e.className="flower";

e.innerHTML=emojis[Math.floor(Math.random()*emojis.length)];

e.style.left=Math.random()*100+"vw";

e.style.animationDuration=(5+Math.random()*6)+"s";

e.style.fontSize=(18+Math.random()*18)+"px";

document.body.appendChild(e);

}

</script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Letter For You 💌</title>

<style>
body{
margin:0;
font-family:Arial,sans-serif;
background:linear-gradient(135deg,#ffe6f2,#fff8cc,#e6ffe6);
display:flex;
justify-content:center;
align-items:center;
height:100vh;
}

.card{
background:white;
width:88%;
max-width:450px;
padding:30px;
border-radius:20px;
box-shadow:0 10px 25px rgba(0,0,0,.15);
animation:fade 1s;
}

h1{
text-align:center;
color:#ff5b95;
}

p{
font-size:18px;
line-height:1.8;
color:#444;
text-align:justify;
}

button{
display:block;
margin:25px auto 0;
padding:14px 30px;
border:none;
border-radius:30px;
background:#ff6fa5;
color:white;
font-size:18px;
cursor:pointer;
}

button:hover{
transform:scale(1.05);
}

@keyframes fade{
from{opacity:0;transform:translateY(20px);}
to{opacity:1;transform:translateY(0);}
}
</style>

</head>

<body>

<div class="card">

<h1>💌 A Small Letter</h1>

<p>
Dear Friend,<br><br>

Happy Friendship Day! 🌼

I just wanted to say thank you for being such a wonderful friend. Every conversation, every laugh, and every memory has made our friendship more special.

You have a unique personality that makes people smile, and I truly hope you always stay happy, confident, and successful in life.

This little website is simply a small way of saying that I appreciate our friendship and wish you nothing but the best.

Keep smiling, keep shining, and never stop being yourself. ✨💛

Happy Friendship Day once again!

</p>

<button onclick="location.href='qualities.html'">
Next ➜
</button>

</div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>6 Things I Like About You</title>

<style>
body{
margin:0;
font-family:Arial,sans-serif;
background:linear-gradient(135deg,#FFE5EC,#FFF7CC,#E8FFD9);
padding:20px;
}

h1{
text-align:center;
color:#ff4f87;
}

.card{
background:white;
padding:20px;
margin:18px auto;
border-radius:18px;
max-width:450px;
box-shadow:0 8px 18px rgba(0,0,0,.15);
animation:fade .8s;
}

h2{
margin-top:0;
color:#ff6699;
}

p{
font-size:17px;
line-height:1.7;
color:#444;
}

button{
display:block;
margin:30px auto;
padding:14px 35px;
font-size:18px;
border:none;
border-radius:30px;
background:#ff6fa5;
color:white;
cursor:pointer;
}

button:hover{
transform:scale(1.05);
}

@keyframes fade{
from{
opacity:0;
transform:translateY(20px);
}
to{
opacity:1;
transform:translateY(0);
}
}
</style>

</head>

<body>

<h1>🌸 Six Wonderful Things About You 🌸</h1>

<div class="card">
<h2>😂 1. Funny</h2>
<p>
You have a natural talent for making people laugh. Even the simplest conversations become memorable because of your sense of humor. Keep spreading smiles! 😂✨
</p>
</div>

<div class="card">
<h2>💖 2. Kind</h2>
<p>
Your kindness makes people feel comfortable around you. A caring heart is one of the most beautiful qualities anyone can have, and you have it. 🌸💛
</p>
</div>

<div class="card">
<h2>😎 3. That Attitude</h2>
<p>
Your confidence gives you your own unique style. That little attitude makes your personality stand out—in a cool way. Just keep smiling too! 😎✨🌼
</p>
</div>

<div class="card">
<h2>🤝 4. Respectful</h2>
<p>
The way you respect others shows your good character. People always remember someone who treats everyone with kindness and respect. 🌷🤝
</p>
</div>

<div class="card">
<h2>🫶 5. Caring</h2>
<p>
You care about the people around you more than you probably realize. Those little acts of care make a big difference. 💕🫶
</p>
</div>

<div class="card">
<h2>🧸 6. Cute</h2>
<p>
Your smile, expressions, and the little things you do make you genuinely adorable in a wholesome way. Never lose that cheerful side of yourself. 🌼😊✨
</p>
</div>

<button onclick="location.href='memories.html'">
Next ➜
</button>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Our Memories 📸</title>

<style>
body{
margin:0;
font-family:Arial,sans-serif;
background:linear-gradient(135deg,#FFE8F0,#FFF9D6,#E9FFD8);
padding:20px;
}

h1{
text-align:center;
color:#ff4f87;
}

.box{
background:white;
max-width:450px;
margin:20px auto;
padding:20px;
border-radius:20px;
box-shadow:0 8px 18px rgba(0,0,0,.15);
}

.photo{
height:180px;
border:3px dashed #ff8ab3;
border-radius:15px;
display:flex;
justify-content:center;
align-items:center;
font-size:18px;
color:#777;
margin-top:15px;
}

p{
font-size:17px;
line-height:1.7;
color:#444;
}

button{
display:block;
margin:25px auto;
padding:14px 30px;
font-size:18px;
border:none;
border-radius:30px;
background:#ff6fa5;
color:white;
cursor:pointer;
}
</style>

</head>

<body>

<h1>📸 Friendship Memories</h1>

<div class="box">

<p>
Every friendship is made of little moments that become unforgettable memories.

One day, when we look back, we'll remember the laughs, the random conversations, and the simple moments that made us smile.

This page is for those beautiful memories. 🌸✨
</p>

<div class="photo">
📷 Add Your Favorite Photo Here
</div>

<div class="photo">
🌼 Another Memory
</div>

<div class="photo">
💛 One More Happy
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Friendship Day</title>

<style>
body{
margin:0;
font-family:Arial,sans-serif;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
background:linear-gradient(135deg,#FFD6E8,#FFF7C2,#D8FFD8);
overflow:hidden;
}

.card{
background:white;
width:90%;
max-width:420px;
padding:30px;
border-radius:25px;
text-align:center;
box-shadow:0 10px 25px rgba(0,0,0,.2);
animation:fade 1s;
z-index:2;
}

h1{
color:#ff4f87;
font-size:30px;
}

p{
font-size:18px;
line-height:1.7;
color:#444;
}

.name{
font-size:32px;
color:#ff6
