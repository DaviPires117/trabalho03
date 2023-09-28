<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="cssFontColor.css">
    <title>Exemplo de Estilos CSS</title>
</head>
<body>
    <div class="color-example">
        <h1>Cores por Nome</h1>
        <p class="color-name">Red</p>
        <p class="color-name">Green</p>
        <p class="color-name">Blue</p>
    </div>

    <div class="color-example">
        <h1>Cores por Hexadecimal</h1>
        <p class="color-hex">#FF0000</p>
        <p class="color-hex">#00FF00</p>
        <p class="color-hex">#0000FF</p>
    </div>

    <div class="color-example">
        <h1>Cores por Hexa Abreviado</h1>
        <p class="color-hex-short">#F00</p>
        <p class="color-hex-short">#0F0</p>
        <p class="color-hex-short">#00F</p>
    </div>

    <div class="color-example">
        <h1>Cores por RGB</h1>
        <p class="color-rgb">rgb(255, 0, 0)</p>
        <p class="color-rgb">rgb(0, 255, 0)</p>
        <p class="color-rgb">rgb(0, 0, 255)</p>
    </div>

    <div class="color-example">
        <h1>Cores por HSL</h1>
        <p class="color-hsl">hsl(0, 100%, 50%)</p>
        <p class="color-hsl">hsl(120, 100%, 50%)</p>
        <p class="color-hsl">hsl(240, 100%, 50%)</p>
    </div>

    <div class="font-example">
        <h1>Configuração de Fonte</h1>
        <p class="font-properties">Exemplo de Texto</p>
    </div>
</body>
</html>


.color-name {
    color: red;
}

.color-hex {
    color: #00FF00;
}

.color-hex-short {
    color: #0000FF;
}


.color-rgb {
    color: rgb(255, 0, 0);
}


.color-hsl {
    color: hsl(0, 100%, 50%);
}


.font-properties {
    font-family: Arial, sans-serif;
    font-weight: bold;
    font-style: italic;
    line-height: 1.5;
    text-align: center;
    text-indent: 20px;
    text-shadow: 2px 2px 4px #000;
}
