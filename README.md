<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scouts Royale Brotherhood</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: #121212;
            color: #FFFFFF;
            text-align: center;
        }
        nav {
            background: #1E1E1E;
            padding: 15px;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        }
        nav a {
            color: #FFD700;
            text-decoration: none;
            font-size: 1.2rem;
            transition: 0.3s;
        }
        nav a:hover {
            color: #FFA500;
        }
        .hero {
            padding: 120px 20px;
            background: linear-gradient(135deg, #222, #333);
            box-shadow: 0 4px 10px rgba(255, 215, 0, 0.3);
            margin-top: 50px;
        }
        .hero img {
            width: 180px;
            height: auto;
            border-radius: 50%;
            margin-bottom: 20px;
        }
        .hero h1 {
            font-size: 3rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #FFD700;
        }
        .hero p {
            font-size: 1.2rem;
            color: #FFFFFF;
            font-style: italic;
        }
        .content-section {
            padding: 60px 20px;
            color: #FFFFFF;
            max-width: 900px;
            margin: auto;
        }
        .card {
            background: #1E1E1E;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(255, 215, 0, 0.2);
            margin-bottom: 20px;
        }
        h2 {
            color: #FFD700;
            font-size: 2rem;
        }
        .chapters {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }
        .chapter-card {
            background: #1E1E1E;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(255, 215, 0, 0.3);
            font-weight: bold;
        }
        footer {
            background: #1E1E1E;
            padding: 20px;
            color: #FFD700;
            font-size: 1rem;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#hero">Home</a>
        <a href="#about">About</a>
        <a href="#principles">Principles</a>
        <a href="#jewels">Jewels</a>
        <a href="#chapters">Chapters</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <header class="hero" id="hero">
        <img src="logo.jpg" alt="SRB Fraternity Logo">
        <h1>Scouts Royale Brotherhood</h1>
        <p>"Strength, Honor, Brotherhood."</p>
    </header>

    <section id="about" class="content-section card">
        <h2>About SRB</h2>
        <p>Scouts Royale Brotherhood (SRB) is an International Fraternity founded in the Philippines on September 22, 1975, by members of Alpha Phi Omega-Philippines at San Sebastian College. It was created to extend Alpha Phi Omega’s principles of Leadership, Friendship, and Service to high school students, later evolving into an independent service fraternity.</p>
    </section>

    <section id="chapters" class="content-section card">
        <h2>SRB’s 37 Chartered School Chapters</h2>
        <div class="chapters">
            <div class="chapter-card">Alpha – Far Eastern University</div>
            <div class="chapter-card">Alpha Alpha – Trinity University of Asia</div>
            <div class="chapter-card">Alpha Chi – Miriam College</div>
            <div class="chapter-card">Alpha Delta – San Sebastian College</div>
            <div class="chapter-card">Alpha Epsilon – Eulogio "Amang" Rodriguez Institute of Science and Technology</div>
            <div class="chapter-card">Alpha Eta – Philippine School of Business Administration</div>
            <div class="chapter-card">Alpha Lambda – Technological Institute of the Philippines</div>
            <div class="chapter-card">Alpha Theta – Lyceum of the Philippines University</div>
            <div class="chapter-card">Alpha Omicron – Divine Word University of Tacloban</div>
            <div class="chapter-card">Beta – National University</div>
            <div class="chapter-card">Beta Alpha – National College of Business and Arts</div>
            <div class="chapter-card">Beta Chi – Don Bosco Technical College</div>
            <div class="chapter-card">Beta Epsilon – De Ocampo Memorial College</div>
            <div class="chapter-card">Beta Sigma – San Beda College</div>
            <div class="chapter-card">Beta Tau – Arellano University</div>
            <div class="chapter-card">Delta – Mapúa Institute of Technology</div>
            <div class="chapter-card">Delta Alpha – University of Rizal System – Tanay</div>
            <div class="chapter-card">Delta Nu – Jose Rizal University</div>
            <div class="chapter-card">Epsilon – University of the East – Manila</div>
            <div class="chapter-card">Eta – University of the Philippines, Manila</div>
            <div class="chapter-card">Gamma Rho – Ortanez University</div>
            <div class="chapter-card">Gamma Iota – Philippine Christian University</div>
            <div class="chapter-card">Gamma Kappa – Ateneo de Manila University</div>
            <div class="chapter-card">Iota – Philippine Maritime Institute</div>
            <div class="chapter-card">Kappa – Guzman College of Science and Technology</div>
            <div class="chapter-card">Mu – Manuel L. Quezon University</div>
            <div class="chapter-card">Nu – Manila Central University</div>
            <div class="chapter-card">Omicron – Colegio de San Juan de Letran</div>
            <div class="chapter-card">Pi – University of Santo Tomas</div>
            <div class="chapter-card">Phi – Araullo University</div>
            <div class="chapter-card">Phi Omega – St. Andrew’s School</div>
            <div class="chapter-card">Rho – Central Colleges of the Philippines</div>
            <div class="chapter-card">Sigma – Adamson University</div>
            <div class="chapter-card">Tau – University of Mindanao</div>
            <div class="chapter-card">Upsilon – Philippine College of Criminology</div>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Scouts Royale Brotherhood. All Rights Reserved.</p>
    </footer>
</body>
</html>
