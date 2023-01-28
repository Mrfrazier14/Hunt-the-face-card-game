# Hunt-the-face-card-game
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-title-container">
            <h1>Hunt the Ace card game</h1>
        </div>
        <div class="header-round-info-container">
            <div class="header-img-container">
                <img src="/images/AceSpades.png" alt="" class="header-img">
            </div>
            <div class="header-score-container">
                <h2 class="score">Score&nbsp;<span class="badge">0</span></h2>
            </div>
            <div class="header-round-container">
                <h2 class="round">Round&nbsp;<span class="badge">0</span></h2>
            </div>
        </div>
        <div class="header-status-info-container">
            <p class="current-status">
                Click 'Play Game' button to play game
            </p>
        </div>
        <div class="header-button-container">
            <div class="game-play-button-container">
                <button id = "playGame" class="play-game">Play Game</button>
            </div>
        </div>
    </header>
    <main>
        <div class="card-container">
            <div class="card-pos-a">
            </div>
            <div class="card-pos-b">
            </div>
            <div class="card-pos-c">
            </div>
            <div class="card-pos-d">
            </div>
        </div>
    </main>
    <script src="index.js"></script>
</body>
</html>
