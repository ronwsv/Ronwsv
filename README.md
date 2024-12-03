<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil de Ron Williams</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2f;
            color: #ffffff;
            margin: 0;
            padding: 20px;
        }
        h1, h2 {
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            border-radius: 10px;
            background-color: #282a36;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
        }
        .stats {
            display: flex;
            justify-content: space-around;
            margin-bottom: 20px;
        }
        .tech-icons {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 20px;
        }
        .tech-icons img {
            border-radius: 8px;
        }
        .react-counter {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-top: 20px;
        }
        .react-counter img {
            height: 50px;
            width: 50px;
            cursor: pointer; /* Para indicar que é clicável */
        }
        .react-count {
            font-size: 24px;
            margin-left: 10px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Olá, eu sou Ron Williams &#128526;</h1>

    <div class="stats">
      <a href="https://github.com/ronwsv">
          <img height="180em" src="https://github-readme-stats.vercel.app/api?username=ronwsv&show_icons=true&theme=synthwave&include_all_commits=true&count_private=true"/>
          <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ronwsv&show_icons=true&theme=synthwave&include_all_commits=true&count_private=true"/>
      </a>
    </div>

    <h2>Tecnologias usadas no meu dia a dia</h2>
    <div class="tech-icons">
      <img alt="python" height="50" width="50" src="https://github.com/ronwsv/Ronwsv/blob/main/python.svg">
      <img alt="css" height="50" width="50" src="https://github.com/ronwsv/Ronwsv/blob/main/css3-original-wordmark.svg">
      <img alt="html" height="50" width="50" src="https://github.com/ronwsv/Ronwsv/blob/main/html5-original-wordmark.svg">
      <img alt="java" height="50" width="50" src="https://github.com/ronwsv/Ronwsv/blob/main/javascript-original.svg">
      <img alt="node" height="50" width="50" src="https://github.com/ronwsv/Ronwsv/blob/main/icons8-nodejs-48.png">
      <img alt="react" height="50" width="50" src="https://github.com/ronwsv/Ronwsv/blob/main/react-1-logo.svg">
    </div>

    <h2>Contador de Reações</h2>
    <div class="react-counter">
      <img id="react-icon" alt="react-icon" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Emoji_u1f44d.svg/1200px-Emoji_u1f44d.svg.png">
      <span id="react-count" class="react-count">0</span>
    </div>
</div>

<script>
    // Exemplo de contagem de reações
    let reactCount = 0;

    // Função para incrementar o contador
    function addReact() {
        reactCount++;
        document.getElementById('react-count').innerText = reactCount;
    }

    // Adiciona um evento para incrementar ao clicar no ícone
    document.getElementById('react-icon').addEventListener('click', addReact);
</script>

</body>
</html>
