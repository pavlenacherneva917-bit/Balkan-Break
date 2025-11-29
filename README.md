<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Balkan Break – Examenreis Bulgarije</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f2f6fa;
        }
        header {
            background: #0a3d62;
            color: white;
            padding: 30px;
            text-align: center;
        }
        nav {
            background: #07466f;
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.1em;
        }
        .container {
            width: 90%;
            max-width: 1100px;
            margin: 40px auto;
        }
        section { display:none; }
        section.active { display:block; }
        .pakket, .activiteit {
            background: white;
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 40px;
            box-shadow: 0 3px 8px rgba(0,0,0,0.15);
        }
        h2 { color: #0a3d62; }
        h3 { margin-top: 20px; }
        .bestemming, .activiteit-box {
            background: #eaf0f5;
            padding: 15px;
            border-radius: 6px;
            margin-bottom: 15px;
        }
        button {
            padding: 12px 25px;
            background: #0a3d62;
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1em;
            margin-top: 10px;
        }
    </style>
    <script>
        function openPage(id) {
            document.querySelectorAll('section').forEach(s=>s.classList.remove('active'));
            document.getElementById(id).classList.add('active');
            window.scrollTo(0,0);
        }
    </script>
</head>
<body>
    <header>
        <h1>Balkan Break – Examenreis Bulgarije</h1>
        <p>De ultieme examenreis voor eindexamenleerlingen!</p>
    </header>

    <nav>
        <a href="#" onclick="openPage('home')">Home</a>
        <a href="#" onclick="openPage('reizen')">Pakketten</a>
        <a href="#" onclick="openPage('activiteiten')">Activiteiten</a>
        <a href="#" onclick="openPage('fotos')">Foto's</a>
    </nav>

    <div class="container">

        <!-- HOME -->
        <section id="home" class="active">
            <h2>Welkom bij Balkan Break</h2>
            <p>Balkan Break is dé examenreis naar Bulgarije voor leerlingen die hun examen willen vieren met avontuur, ontspanning en cultuur.</p>
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Sunny_Beach.jpg" style="width:100%; border-radius:10px; margin-top:20px;" />
            <p>Kies uit drie topbestemmingen: Plovdiv, Sunny Beach en Velingrad. Met drie pakketten: Basic, Premium en Ultra.</p>
        </section>

        <!-- PAKKETTEN -->
        <section id="reizen">
            <h2>Reispakketten</h2>

            <!-- Basic -->
            <div class="pakket">
                <h3>Basic Pakket – €754 p.p.</h3>
                <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Plovdiv_Old_Town.jpg" style="width:100%; border-radius:10px;" />
                <div class="bestemming"><strong>Plovdiv – Expo Hotel:</strong> vlucht €270 + hotel €164 = €434<br>Adres: Ruski blvd. 38</div>
                <div class="bestemming"><strong>Sunny Beach – New Line Village:</strong> €157<br>Adres: Sunny Beach Resort</div>
                <div class="bestemming"><strong>Velingrad – City Apartments 4:</strong> €163<br>Adres: Сергей Румянцев 26</div>
                <button>Boek Basic</button>
            </div>

            <!-- Premium -->
            <div class="pakket">
                <h3>Premium Pakket – €823 p.p.</h3>
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Sunny_Beach.jpg" style="width:100%; border-radius:10px;" />
                <div class="bestemming"><strong>Plovdiv – Hill House:</strong> €170</div>
                <div class="bestemming"><strong>Sunny Beach – Ivana Palace:</strong> €223</div>
                <div class="bestemming"><strong>Velingrad – Zdravets SPA:</strong> €160</div>
                <button>Boek Premium</button>
            </div>

            <!-- Ultra -->
            <div class="pakket">
                <h3>Ultra Pakket – €1984 p.p.</h3>
                <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Velingrad_Center.jpg" style="width:100%; border-radius:10px;" />
                <div class="bestemming"><strong>Plovdiv – Gallery 37:</strong> €314</div>
                <div class="bestemming"><strong>Sunny Beach – Helena Sands:</strong> €676</div>
                <div class="bestemming"><strong>Velingrad – Sante Spa:</strong> €724</div>
                <button>Boek Ultra</button>
            </div>
        </section>

        <!-- ACTIVITEITEN -->
        <section id="activiteiten">
            <h2>Activiteiten in Bulgarije</h2>

            <div class="activiteit">
                <h3>Plovdiv wandeltour (2 uur – €12)</h3>
                <div class="activiteit-box">Een begeleide wandeling door het historische hart van Plovdiv.</div>
            </div>

            <div class="activiteit">
                <h3>Oude Stad tour + audiogids + museum (2.5 uur – €15)</h3>
                <div class="activiteit-box">Verken de oude stad met een gids en musea inbegrepen.</div>
            </div>

            <div class="activiteit">
                <h3>Voedselwandeling Plovdiv (3 uur – €35)</h3>
                <div class="activiteit-box">Proef de Bulgaarse cultuur en gerechten met een ervaren gids.</div>
            </div>

            <div class="activiteit">
                <h3>E-motorfietstocht Rodopegebergte (3–5 uur – €100)</h3>
                <div class="activiteit-box">Een avontuurlijke rit naar een verbluffende kloof in de natuur.</div>
            </div>
        </section>

        <!-- FOTO PAGINA -->
        <section id="fotos">
            <h2>Foto's van Bulgarije</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Plovdiv_Old_Town.jpg" style="width:100%; border-radius:10px; margin-bottom:20px;" />
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Sunny_Beach.jpg" style="width:100%; border-radius:10px; margin-bottom:20px;" />
            <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Velingrad_Center.jpg" style="width:100%; border-radius:10px; margin-bottom:20px;" />
        </section>

    </div>
</body>
</html>
