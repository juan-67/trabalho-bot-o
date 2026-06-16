# trabalho-bot-o
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Botão Minecraft</title>

<style>
body{
    margin:0;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:#2b2b2b;
    font-family:Arial, sans-serif;
}

.mc-btn{
    width:320px;
    height:50px;
    background:#7a7a7a;
    color:white;
    border:3px solid #000;
    font-size:22px;
    font-weight:bold;
    cursor:pointer;
    text-shadow:2px 2px #000;
    box-shadow:inset 2px 2px #bdbdbd,
               inset -2px -2px #4a4a4a;
    transition:all .15s;
}

.mc-btn:hover{
    background:#6ccf3b;
    animation:pulse .5s infinite alternate;
}

.mc-btn:active{
    transform:translateY(3px);
}

@keyframes pulse{
    from{
        transform:scale(1);
    }
    to{
        transform:scale(1.03);
    }
}
</style>
</head>
<body>

<button class="mc-btn">JOGAR</button>
