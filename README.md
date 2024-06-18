-- Referência à peça
local part = game.Workspace.Part

-- Função para mudar a cor da peça
local function changeColor()
    part.BrickColor = BrickColor.Random()
end

-- Chamar a função quando o jogo começar
changeColor()
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TerraNerd Search</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>TerraNerd Search</h1>
        <input type="text" id="searchQuery" placeholder="Search...">
        <button onclick="search()">Search</button>
        <div id="results"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>
