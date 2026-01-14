manhwa-pl/
├── index.html
├── style.css
└── script.js
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Manhwy – Tłumaczenia</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Manhwa PL</h1>
    <p>tłumaczenia manhw na język polski</p>
    <nav>
        <a href="#o-nas">O nas</a>
        <a href="#projekty">Tytuły</a>
        <a href="#dolacz">Dołącz</a>
        <a href="#kontakt">Kontakt</a>
    </nav>
</header>

<main>

<section id="o-nas">
    <h2>O nas</h2>
    <p>
        Tłumaczymy wszystko fanoiwsko
    </p>
</section>

<section id="Tytuły">
    <h2>Aktualne tłumaczenia</h2>

    <div class="manhwa">
        <h3>16647: game and reality</h3>
        <p>Status: <span class="status aktywne">aktywne</span></p>
    </div>

    <div class="manhwa">
        <h3>love me, revive me</h3>
        <p>Status: <span class="status aktywne">aktywne</span></p>
    </div>
    
    <div class="manhwa">
        <h3>La Mèche</h3>
        <p>Status: <span class="status aktywne">aktywne</span></p>
    </div> 

    <div class="manhwa">
        <h3>You Can't Come, Sir!</h3>
        <p>Status: <span class="status aktywne">aktywne</span></p>
    </div>  

    <div class="manhwa">
        <h3>Blossoms of the white night</h3>
        <p>Status: <span class="status aktywne">aktywne</span></p>
    </div> 

    <div class="manhwa">
        <h3>Devil's Knight</h3>
        <p>Status: <span class="status aktywne">aktywne</span></p>
    </div> 

    <div class="manhwa">
        <h3>Distorted Love</h3>
        <p>Status: <span class="status aktywne">aktywne</span></p>
    </div>

    <div class="manhwa">
        <h3>Under the moonlight</h3>
        <p>Status: <span class="status aktywne">zakończone</span></p>
    </div>

    <div class="manhwa">
        <h3>Pieta</h3>
        <p>Status: <span class="status aktywne">aktywne</span></p>
    </div>


    <div class="manhwa">
        <h3>Love and roll</h3>
        <p>Status: <span class="status aktywne">aktywne</span></p>
    </div>

    <div class="manua">
        <h3>The golden goose dressed as Alpha boss</h3>
        <p>Status: <span class="status wstrzymane">aktywne</span></p>
    </div>
</section>

<section id="dolacz">
    <h2>Dołącz do zespołu</h2>
    <p>Szukamy:</p>
    <ul>
        <li>tłumacz</li>
        <li>korektor</li>
        <li>cleaner</li>
        <li>typesetter</li>
    </ul>
    <button onclick="dolacz()">Chcę dołączyć</button>
</section>

<section id="kontakt">
    <h2>Kontakt</h2>
    <p>Discord: <strong>https://discord.gg/H4A5hTS7Gw</strong></p>
</section>

</main>

<footer>
    <p>© 2026 Manhwy PL | tłumaczenia</p>
</footer>

<script src="script.js"></script>
</body>
</html>

<css>

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    color: #333;
}

header {
    background-color: #D1C6DA;
    color: white;
    padding: 30px;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

nav a:hover {
    text-decoration: underline;
}

main {
    padding: 40px;
    max-width: 900px;
    margin: auto;
}

section {
    margin-bottom: 50px;
}

.manhwa {
    background: white;
    padding: 15px;
    margin-bottom: 15px;
    border-left: 5px solid #0077cc;
}

.status {
    font-weight: bold;
}

.aktywne {
    color: green;
}

.wstrzymane {
    color: orange;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}

footer {
    background-color: #ddd;
    text-align: center;
    padding: 15px;
}
