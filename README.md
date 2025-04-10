<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Games.zone</title>
    <style>
        body {
            background-color: #121212;
            font-family: Arial, sans-serif;
            color: white;
            text-align: center;
        }

        input {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: none;
            font-size: 16px;
        }

        .app-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            padding: 20px;
        }

        .app-card {
            background-color: #1E1E1E;
            padding: 15px;
            border-radius: 10px;
            width: 200px;
            text-align: center;
        }

        .app-card img {
            width: 100px;
            height: 100px;
            border-radius: 10px;
        }

        .install-btn {
            background-color: #22c55e;
            color: white;
            padding: 10px;
            border-radius: 5px;
            text-decoration: none;
            display: block;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <h1>Games.zone</h1>
    <input type="text" placeholder="Search for an app or game"/>

    <div class="app-container">
        <div class="app-card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/1/19/Roblox_Logo_2021.png" alt="Roblox"/>
            <h3>Roblox</h3>
            <p>Platforms: Android / iOS</p>
            <a href="https://www.roblox.com/download" class="install-btn">Install</a>
        </div>

        <div class="app-card">
            <img src="https://www.stickpng.com/assets/images/580b57fcd9996e24bc43c2f7.png" alt="Subway Surfers"/>
            <h3>Subway Surfers</h3>
            <p>Platforms: Android / iOS</p>
            <a href="https://subwaysurfers.com/download" class="install-btn">Install</a>
        </div>

        <div class="app-card">
            <img src="https://www.citypng.com/public/uploads/preview/hd-call-of-duty-mobile-cod-m-game-official-logo-png-11640440468j8zj3v6n8a.png" alt="Call of Duty Mobile"/>
            <h3>Call of Duty Mobile</h3>
            <p>Platforms: Android / iOS</p>
            <a href="https://www.callofduty.com/mobile/download" class="install-btn">Install</a>
        </div>

        <div class="app-card">
            <img src="https://www.stickpng.com/assets/images/580b57fcd9996e24bc43c2f8.png" alt="Clash Royale"/>
            <h3>Clash Royale</h3>
            <p>Platforms: Android / iOS</p>
            <a href="https://clashroyale.com/download" class="install-btn">Install</a>
        </div>

        <div class="app-card">
            <img src="https://www.citypng.com/public/uploads/preview/free-fire-new-logo-battle-in-style-hd-png-11658215552h6v7j2xw5e.png" alt="Free Fire"/>
            <h3>Free Fire</h3>
            <p>Platforms: Android / iOS</p>
            <a href="https://ff.garena.com/download" class="install-btn">Install</a>
        </div>

        <div class="app-card">
            <img src="https://www.stickpng.com/assets/images/5cb480cd5f1b6d3fbadece79.png" alt="Brawl Stars"/>
            <h3>Brawl Stars</h3>
            <p>Platforms: Android / iOS</p>
            <a href="https://supercell.com/en/games/brawlstars/download" class="install-btn">Install</a>
        </div>
    </div>

</body>
</html>
