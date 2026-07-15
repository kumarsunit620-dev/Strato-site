<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>STRATO | Coming Soon</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{

background:url('background.png') center center/cover no-repeat fixed;
height:100vh;
overflow:hidden;
position:relative;

}

/* Dark Overlay */

body::before{

content:"";
position:absolute;
top:0;
left:0;
right:0;
bottom:0;

background:linear-gradient(
90deg,
rgba(0,25,60,.75),
rgba(0,20,50,.45),
rgba(0,0,0,.30)
);

z-index:1;

}

.container{

position:relative;
z-index:5;

height:100vh;

display:flex;
align-items:center;

padding-left:8%;
padding-right:8%;

}

.content{

max-width:650px;

backdrop-filter:blur(12px);
background:rgba(255,255,255,.05);

padding:60px;

border-radius:25px;

border:1px solid rgba(255,255,255,.12);

animation:fadeUp 1.2s ease;

}

.logo{

font-size:72px;
font-weight:700;
letter-spacing:12px;
color:white;

}

.wave{

font-size:18px;
color:#00c6ff;
margin-bottom:15px;

}

h2{

font-size:48px;
font-weight:500;
color:white;
margin-top:10px;
margin-bottom:25px;

}

.line{

width:120px;
height:4px;
background:#00B8FF;
margin-bottom:30px;
border-radius:50px;

}

p{

font-size:22px;
line-height:1.8;
color:white;
opacity:.95;
margin-bottom:40px;

}

.subscribe{

display:flex;
gap:15px;
flex-wrap:wrap;

}

.subscribe input{

flex:1;

padding:18px;

border:none;

border-radius:50px;

font-size:16px;

outline:none;

}

.subscribe button{

padding:18px 40px;

border:none;

border-radius:50px;

background:#00B8FF;

color:white;

font-size:16px;

font-weight:600;

cursor:pointer;

transition:.3s;

}

.subscribe button:hover{

background:#0095d9;
transform:translateY(-3px);

}

.footer{

position:absolute;

bottom:30px;

left:50%;

transform:translateX(-50%);

z-index:10;

color:white;

font-size:14px;

opacity:.8;

}

@keyframes fadeUp{

from{

opacity:0;
transform:translateY(40px);

}

to{

opacity:1;
transform:translateY(0);

}

}

@media(max-width:768px){

.container{

justify-content:center;
text-align:center;
padding:25px;

}

.content{

padding:35px 25px;

}

.logo{

font-size:50px;
letter-spacing:6px;

}

h2{

font-size:34px;

}

p{

font-size:18px;

}

.line{

margin:auto;
margin-bottom:25px;

}

.subscribe{

flex-direction:column;

}

.subscribe button{

width:100%;

}

}

</style>

</head>

<body>

<div class="container">

<div class="content">

<div class="wave">❄ PREMIUM AIR CONDITIONING</div>

<div class="logo">
STRATO
</div>

<h2>Coming Soon to Fiji</h2>

<div class="line"></div>

<p>

Tropical-ready air conditioning designed for Fiji homes,
offices, hotels and commercial spaces.

Engineered for performance.
Built for the Pacific.

</p>

<form class="subscribe">

<input
type="email"
placeholder="Enter your email">

<button>

Notify Me

</button>

</form>

</div>

</div>

<div class="footer">


</div>

</body>
</html>
