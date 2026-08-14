Policekari — Professional News Website

<!DOCTYPE html>
<html lang="ur" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Policekari | پولیس کاری - تازہ ترین خبریں</title>

<meta name="description" content="Policekari - پاکستان کی تازہ ترین خبریں، پولیس، کرائم، مقامی اور اہم خبریں۔">
<meta name="keywords" content="Policekari, پولیس کاری, Pakistan News, Police News, Crime News">
<meta name="author" content="Policekari">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial,"Noto Nastaliq Urdu",sans-serif;
    background:#f4f6f9;
    color:#17202a;
}

header{
    background:linear-gradient(135deg,#071952,#0b5ed7);
    color:white;
    padding:18px 5%;
    position:sticky;
    top:0;
    z-index:1000;
    box-shadow:0 5px 20px #0003;
}

.nav{
    max-width:1200px;
    margin:auto;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:15px;
}

.logo{
    font-size:30px;
    font-weight:bold;
}

.logo span{
    color:#ffd43b;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 8px;
    font-weight:bold;
}

nav a:hover{
    color:#ffd43b;
}

.hero{
    max-width:1200px;
    margin:25px auto;
    padding:55px 25px;
    border-radius:25px;
    background:
    linear-gradient(135deg,#071952dd,#0b5ed7dd),
    url("https://images.unsplash.com/photo-1450101499163-c8848c66ca85?auto=format&fit=crop&w=1400&q=80");
    background-size:cover;
    background-position:center;
    color:white;
    text-align:center;
    box-shadow:0 15px 40px #0003;
}

.hero h1{
    font-size:45px;
    margin-bottom:15px;
}

.hero p{
    font-size:19px;
    margin-bottom:25px;
}

.search{
    max-width:650px;
    margin:auto;
    display:flex;
    background:white;
    border-radius:50px;
    padding:6px;
}

.search input{
    flex:1;
    border:0;
    outline:0;
    padding:14px 20px;
    font-size:16px;
    border-radius:50px;
}

.search button{
    border:0;
    background:#ffcc00;
    padding:0 25px;
    border-radius:40px;
    font-weight:bold;
    cursor:pointer;
}

.container{
    max-width:1200px;
    margin:35px auto;
    padding:0 15px;
}

.section-title{
    display:flex;
    justify-content:space-between;
    align-items:center;
    margin-bottom:20px;
}

.section-title h2{
    border-right:5px solid #0b5ed7;
    padding-right:12px;
}

.categories{
    display:flex;
    gap:10px;
    overflow:auto;
    padding-bottom:15px;
}

.categories button{
    white-space:nowrap;
    border:0;
    padding:12px 20px;
    border-radius:30px;
    background:white;
    box-shadow:0 5px 15px #0001;
    cursor:pointer;
}

.categories button:hover{
    background:#0b5ed7;
    color:white;
}

.grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:22px;
}

.card{
    background:white;
    border-radius:18px;
    overflow:hidden;
    box-shadow:0 8px 25px #0001;
    transition:.3s;
}

.card:hover{
    transform:translateY(-7px);
    box-shadow:0 15px 35px #0002;
}

.card img{
    width:100%;
    height:200px;
    object-fit:cover;
}

.card-content{
    padding:18px;
}

.tag{
    display:inline-block;
    background:#e7f0ff;
    color:#0b5ed7;
    padding:5px 10px;
    border-radius:20px;
    font-size:13px;
    margin-bottom:10px;
}

.card h3{
    font-size:21px;
    line-height:1.5;
    margin-bottom:10px;
}

.card p{
    color:#667085;
    line-height:1.7;
}

.date{
    color:#999;
    font-size:13px;
    margin-top:12px;
}

.breaking{
    background:#111827;
    color:white;
    padding:13px;
    overflow:hidden;
}

.breaking strong{
    background:#e11d48;
    padding:8px 15px;
    border-radius:20px;
    margin-left:10px;
}

footer{
    margin-top:50px;
    background:#071952;
    color:white;
    padding:40px 20px;
    text-align:center;
}

footer h2{
    margin-bottom:10px;
}

.social{
    margin-top:20px;
}

.social a{
    display:inline-block;
    color:white;
    text-decoration:none;
    margin:5px;
    padding:10px 18px;
    background:#ffffff20;
    border-radius:20px;
}

@media(max-width:800px){
    nav{
        display:none;
    }

    .hero h1{
        font-size:32px;
    }

    .grid{
        grid-template-columns:1fr;
    }

    .logo{
        font-size:25px;
    }
}
</style>
</head>

<body>

<header>
<div class="nav">

<div class="logo">
Police<span>kari</span>
</div>

<nav>
<a href="#">Home</a>
<a href="#news">News</a>
<a href="#police">Police</a>
<a href="#crime">Crime</a>
<a href="#contact">Contact</a>
</nav>

</div>
</header>

<div class="breaking">
<strong>BREAKING</strong>
 تازہ ترین اہم خبریں یہاں دکھائی جائیں گی۔
</div>

<section class="hero">

<h1>پولیس کاری</h1>

<p>
پاکستان کی تازہ ترین خبریں، پولیس، کرائم اور اہم معلومات ایک جگہ
</p>

<div class="search">
<input id="searchInput" type="text" placeholder="خبر تلاش کریں...">
<button onclick="searchNews()">Search</button>
</div>

</section>

<div class="container">

<div class="section-title">
<h2>News Categories</h2>
</div>

<div class="categories">
<button onclick="filterNews('all')">تمام خبریں</button>
<button onclick="filterNews('police')">پولیس</button>
<button onclick="filterNews('crime')">کرائم</button>
<button onclick="filterNews('pakistan')">پاکستان</button>
<button onclick="filterNews('local')">مقامی خبریں</button>
</div>

</div>

<section class="container" id="news">

<div class="section-title">
<h2>تازہ ترین خبریں</h2>
</div>

<div class="grid" id="newsGrid">

<article class="card" data-category="police">

<img src="https://images.unsplash.com/photo-1450101499163-c8848c66ca85?auto=format&fit=crop&w=800&q=80">

<div class="card-content">

<span class="tag">پولیس</span>

<h3>پولیس سے متعلق تازہ ترین اہم خبر</h3>

<p>
یہاں آپ اپنی اصل خبر، تفصیل اور مکمل معلومات شامل کر سکتے ہیں۔
</p>

<div class="date">14 اگست 2026</div>

</div>
</article>

<article class="card" data-category="crime">

<img src="https://images.unsplash.com/photo-1505664194779-8beaceb93744?auto=format&fit=crop&w=800&q=80">

<div class="card-content">

<span class="tag">کرائم</span>

<h3>اہم کرائم نیوز اور تازہ صورتحال</h3>

<p>
اپنی تازہ کرائم نیوز یہاں خوبصورت انداز میں شائع کریں۔
</p>

<div class="date">آج کی خبر</div>

</div>
</article>

<article class="card" data-category="pakistan">

<img src="https://images.unsplash.com/photo-1523731407965-2430cd12f5e4?auto=format&fit=crop&w=800&q=80">

<div class="card-content">

<span class="tag">پاکستان</span>

<h3>پاکستان کی اہم ترین خبریں</h3>

<p>
پاکستان بھر کی اہم خبریں اور تازہ ترین اپڈیٹس۔
</p>

<div class="date">Latest Update</div>

</div>
</article>

</div>
</section>

<section class="container" id="police">

<div class="section-title">
<h2>Police News</h2>
</div>

<div class="card">
<div class="card-content">

<span class="tag">Policekari Special</span>

<h3>Policekari پر پولیس کی خبریں</h3>

<p>
اس سیکشن میں پولیس کے آپریشنز، اہم اعلانات، عوامی معلومات
اور دیگر متعلقہ خبریں شائع کی جا سکتی ہیں۔
</p>

</div>
</div>

</section>

<footer id="contact">

<h2>Policekari</h2>

<p>پاکستان کی تازہ ترین خبروں کے لیے Policekari کے ساتھ رہیں۔</p>

<div class="social">
<a href="#">Facebook</a>
<a href="#">YouTube</a>
<a href="#">WhatsApp</a>
</div>

<p style="margin-top:25px;">
© 2026 Policekari.com — All Rights Reserved
</p>

</footer>

<script>

function filterNews(category){

let cards=document.querySelectorAll(".card");

cards.forEach(card=>{

if(!card.dataset.category || category==="all"){
card.style.display="block";
}
else if(card.dataset.category===category){
card.style.display="block";
}
else{
card.style.display="none";
}

});

}

function searchNews(){

let input=document
.getElementById("searchInput")
.value
.toLowerCase();

let cards=document.querySelectorAll("#newsGrid .card");

cards.forEach(card=>{

let text=card.innerText.toLowerCase();

card.style.display=text.includes(input)
?"block":"none";

});

}

</script>

</body>
</html>

اب اسے Live کیسے کرنا ہے

1. اوپر والا پورا code Copy کریں۔
2. موبائل میں کوئی code/text editor کھولیں۔
3. New file بنائیں۔
4. نام رکھیں "index.html"
5. Code paste کرکے Save کریں۔
6. GitHub repository میں Upload files سے "index.html" upload کریں۔
7. پھر Settings → Pages → main → root → Save کریں۔

بعد میں UltaHost سے آپ کا domain GitHub Pages کے ساتھ connect ہوگا۔ GitHub کے مطابق custom domain کے لیے DNS میں GitHub کے A records استعمال کیے جا سکتے ہیں، اور DNS changes کو 24 گھنٹے تک لگ سکتے ہیں۔

نوٹ: آپ کا domain اردو/IDN domain ہے، اس لیے GitHub Pages میں custom domain ڈالتے وقت اس کا Punycode version درکار ہوگا۔
