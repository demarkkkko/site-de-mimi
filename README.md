<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My space de mimi</title>
    <link rel ="icon" type="image/jpeg"
    href="images.jpeg">
</head>
<body>
    <style>
  

body {
    background-color: #000;
    color: #fff;
    font-family: 'Courier New', Courier, monospace;
    display: flex;
    justify-content: center;
    padding: 50px 20px;
}

.container {
    max-width: 500px;
    width: 100%;
}

/* Layout em Grid para o topo */
.main-grid {
    display: grid;
    grid-template-columns: 1.2fr 1fr;
    gap: 20px;
    margin-bottom: 30px;
}

.profile-pic img {
    width: 100%;
    border: 1px solid #333; /* Bordinha sutil */
}

/* Estilo do bloco DNI e Kins (Branco com texto preto) */
.dni-header, .kins-box {
    background-color: #fff;
    color: #000;
    text-align: center;
    padding: 10px;
    font-weight: bold;
    margin-bottom: 10px;
}

.dni-box {
    border: 1px solid #fff;
    padding: 5px;
}

.middle-section {
    display: flex;
    justify-content: space-between;
    margin-top: 20px;
}

/* Lista sem bolinhas */
ul {
    list-style: none;
    padding: 0;
}

ul li::before {
    content: "• ";
}

/* Efeito de texto pequeno para os fandoms */
.fandoms p {
    font-size: 0.75rem;
    line-height: 1.4;
    text-align: justify;
}

.mini {
    width: 40px;
    filter: grayscale(100%); /* Deixa as imagens P&B */
}

  </style>

<div class="container">
    <header class="main-grid">
        <div class="profile-pic">
            <p>this is me btw :3 if u even care..</p>
            <img src="tf2-out-of-conext-tf2.gif" alt="Me">
        </div>

        <div class="info-text">
            <h1>MIGUEL / MIMI</h1>
            <p>Ele / Dele</p>
            <p>🎂  15 out XII . ' ! !</p>
            <p>pt , eng</p>
            <div class="small-icons">
                <img src="cyberpunk-ghost-in-the-shell.gif" class="mini">
                <img src="e9e9bc4f350b984809f19ba230277800.gif" class="mini">
                <img src="kill-bill-the-bride.gif" class="mini">
            </div>
        </div>
    </header>

    <section class="fandoms">
        <h2>✧ fandoms ________</h2>
        <p>gits, tf2, furry, heteros anonimos, silent hill...</p>
    </section>

    <div class="middle-section">
        <div class="i-fw">
            <h3> FW</h3>..</h3>
            <ul>
                <li>AMIGOS</li>
                <li>FURRYS</li>
                <li>JOGOS</li>
                <li>COMPUTAÇÃO</li>
            </ul>
        </div>

        <div class="dni-box">
            <div class="dni-header">DNI ...</div>
            <ul>
                <li>Gays</li>
                <li>Negros</li>
                <li>Jogadores de free fire
                    <li> Fumantes</li>
                </li>
            </ul>
        </div>
    </div>

    <div class="kins-box">
         kins : viciados em jogar, computadores, rafael, biel meu bestie ><
    </div>

    <footer>
        btw i love twin, my friends ^^
    </footer>
</div>

</body>
</html>
