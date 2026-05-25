
<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Gaming Site</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial;
}

body{
    background:#050505;
    color:white;
}

/* NAVBAR */

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 10%;
    background:#0d0d0d;
}

.logo{
    color:cyan;
    font-size:35px;
    text-shadow:0 0 15px cyan;
}

nav ul{
    display:flex;
    gap:30px;
    list-style:none;
}

nav ul li a{
    color:white;
    text-decoration:none;
}

nav ul li a:hover{
    color:cyan;
}

/* HERO */

.hero{
    text-align:center;
    padding:80px 20px;
}

.hero-img{
    width:700px;
    max-width:90%;
    border-radius:25px;
    box-shadow:0 0 30px cyan;
}

.hero h1{
    margin-top:30px;
    font-size:70px;
    color:cyan;
}

.hero p{
    margin-top:15px;
    color:#aaa;
    font-size:20px;
}

#playBtn{
    margin-top:30px;
    padding:15px 40px;
    border:none;
    border-radius:50px;
    background:cyan;
    color:black;
    font-size:18px;
    font-weight:bold;
    cursor:pointer;
}

#playBtn:hover{
    box-shadow:0 0 25px cyan;
}

/* CARDS */

.cards{
    padding:80px 10%;
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
}

.card{
    background:#111;
    padding:30px;
    border-radius:20px;
    border:1px solid #222;
}

.card:hover{
    box-shadow:0 0 25px rgba(0,255,255,0.4);
}

.card h2{
    color:cyan;
    margin-bottom:15px;
}

</style>

</head>
<body>

<nav>

    <h1 class="logo">GAMER🔥</h1>

    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Team</a></li>
        <li><a href="#">Contact</a></li>
    </ul>

</nav>

<!-- HERO SECTION -->

<section class="hero">

    <!-- ЗУРАГ ЭНД БАЙГАА -->

    <img 
    src="https://images.unsplash.com/photo-1542751371-adc38448a05e?q=80&w=1200&auto=format&fit=crop"
    class="hero-img">

    <h1>WELCOME GAMER</h1>

    <p>
        Best gaming website design for beginners.
    </p>

    <button id="playBtn">
        PLAY NOW
    </button>

</section>

<!-- CARDS -->

<section class="cards">

    <div class="card">
        <h2>⚡ Fast</h2>
        <p>Ultra smooth gaming experience.</p>
    </div>

    <div class="card">
        <h2>🔥 Esports</h2>
        <p>Join gaming tournaments.</p>
    </div>

    <div class="card">
        <h2>🎮 Community</h2>
        <p>Play with friends worldwide.</p>
    </div>

</section>

<script>

document.getElementById("playBtn").onclick = function(){

    alert("WELCOME TO GAMER WORLD 🔥");

}

</script>

</body>
</html>
