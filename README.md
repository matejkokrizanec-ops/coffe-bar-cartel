# coffe-bar-cartel<!DOCTYPE html>
<html lang="sl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kavarna Cartel</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#111;
    color:#fff;
    line-height:1.6;
}

header{
    min-height:100vh;
    background:
    linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
    url('https://images.unsplash.com/photo-1509042239860-f550ce710b93?auto=format&fit=crop&w=1600&q=80');
    background-size:cover;
    background-position:center;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:25px 8%;
}

.logo{
    font-size:2rem;
    font-weight:700;
    color:#d4a45d;
}

nav ul{
    display:flex;
    list-style:none;
    gap:30px;
}

nav a{
    color:white;
    text-decoration:none;
    transition:.3s;
}

nav a:hover{
    color:#d4a45d;
}

.hero{
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    height:80vh;
    flex-direction:column;
    padding:20px;
}

.hero h1{
    font-size:4rem;
    max-width:900px;
    margin-bottom:20px;
}

.hero p{
    font-size:1.2rem;
    max-width:700px;
    color:#ddd;
}

.btn{
    display:inline-block;
    margin-top:30px;
    padding:14px 35px;
    background:#d4a45d;
    color:#111;
    text-decoration:none;
    border-radius:50px;
    font-weight:600;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-3px);
}

section{
    padding:90px 8%;
}

.section-title{
    text-align:center;
    font-size:2.5rem;
    margin-bottom:50px;
    color:#d4a45d;
}

.about{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:50px;
    align-items:center;
}

.about img{
    width:100%;
    border-radius:20px;
}

.about-text p{
    color:#ccc;
}

.menu-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#1c1c1c;
    border-radius:20px;
    overflow:hidden;
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.card-content{
    padding:20px;
}

.card h3{
    margin-bottom:10px;
    color:#d4a45d;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    height:300px;
    object-fit:cover;
    border-radius:15px;
}

.contact{
    text-align:center;
}

.contact p{
    margin:10px 0;
    color:#ccc;
}

footer{
    background:#0a0a0a;
    text-align:center;
    padding:30px;
    color:#888;
}

@media(max-width:768px){

.hero h1{
    font-size:2.5rem;
}

.about{
    grid-template-columns:1fr;
}

nav ul{
    display:none;
}
}
</style>
</head>
<body>

<header>
    <nav>
        <div class="logo">CARTEL</div>

        <ul>
            <li><a href="#about">O nas</a></li>
            <li><a href="#menu">Ponudba</a></li>
            <li><a href="#gallery">Galerija</a></li>
            <li><a href="#contact">Kontakt</a></li>
        </ul>
    </nav>

    <div class="hero">
        <h1>Kjer se srečata vrhunska kava in dobra družba.</h1>
        <p>Specialty kava, domače sladice in prijeten ambient za vsak trenutek dneva.</p>
        <a href="#menu" class="btn">Oglej si ponudbo</a>
    </div>
</header>

<section id="about">
    <h2 class="section-title">O nas</h2>

    <div class="about">
        <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=900&q=80">

        <div class="about-text">
            <p>
                Kavarna Cartel je prostor za ljubitelje vrhunske kave,
                prijetnega ambienta in sproščenih srečanj.
                Naše poslanstvo je ustvariti popolno izkušnjo ob vsaki skodelici.
            </p>
        </div>
    </div>
</section>

<section id="menu">
    <h2 class="section-title">Naša ponudba</h2>

    <div class="menu-grid">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348?auto=format&fit=crop&w=900&q=80">
            <div class="card-content">
                <h3>Specialty Kava</h3>
                <p>Izbrana kavna zrna in popolna priprava.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1509440159596-0249088772ff?auto=format&fit=crop&w=900&q=80">
            <div class="card-content">
                <h3>Sveže Pecivo</h3>
                <p>Rogljički, muffin-i in dnevno sveže sladice.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b?auto=format&fit=crop&w=900&q=80">
            <div class="card-content">
                <h3>Osvežilne Pijače</h3>
                <p>Domače limonade in premium napitki.</p>
            </div>
        </div>

    </div>
</section>

<section id="gallery">
    <h2 class="section-title">Galerija</h2>

    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=900&q=80">
        <img src="https://images.unsplash.com/photo-1445116572660-236099ec97a0?auto=format&fit=crop&w=900&q=80">
        <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?auto=format&fit=crop&w=900&q=80">
        <img src="https://images.unsplash.com/photo-1521017432531-fbd92d768814?auto=format&fit=crop&w=900&q=80">
    </div>
</section>

<section id="contact" class="contact">
    <h2 class="section-title">Kontakt</h2>

    <p>📍 Ljubljana, Slovenija</p>
    <p>📞 +386 40 123 456</p>
    <p>✉ info@cartel.si</p>
    <p>⏰ Pon–Ned: 07:00 – 22:00</p>

    <a href="#" class="btn">Rezerviraj mizo</a>
</section>

<footer>
    © 2026 Kavarna Cartel. Vse pravice pridržane.
</footer>

</body>
</html>
