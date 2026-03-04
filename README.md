<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title> Laboratório Web</title>

  <style>
      body { 
        font-family: Arial, sans-serif;
        background-color:#add8e6;
        margin: 0;
        padding: 0;
      }

  header {
    background-color: #000080;
    color: navyblue;
    text-aling: center;
  }

    main {
      padding: 20px;
    }

    .card {
      backgroud-color: white;
      padding: 15px;
      margin-bottom: 8px;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba (0,0,0,0.2);
    }

    img {
      width: 200px;
      border-radius: 8px;
    }

    a {
      color: #000080;
      text-decoration: none;
      font-weigth: bold;
    }

    a:hover {
      color: red;
    }

    button {
      background-color: #1f4e79;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
    }

    buttoon:hover {
      background-color: #add8e6;
    }

    footer {
      backgroud-color: #FFFFFF;
      color: white;
      text-aling: center;
      padding: 10px;
    }
    </style>
    
    
</head>
<body>

  <header>
    <h1>Lboratório Web</h1>
    <p>Exemplo de página com HTML e CSS</p>
  </header>

  <main>

  <div class="card">
    <h2>Sobre o aluno</h2>
    <p>Nome: Alice Costa Ribeiro</p>
    <p>Turma: 301</p>
    <p>Data: 25/02/2026</p>
  </div>

  <div class="card">
    <h2>Conteúdos Aprendidos</h2>
    <ul>
      <li>Estruturas de páginas web</li>
      <li>Criação de sites</li>
      <li>Uso de iamgens</li>
      <li>Estilização com CSS</li>
    </ul>
  </div>

  <div class="card">
     <h2>Imagens de exemplo</h2>
     <img src="https://via.placeholder.com/200">
  </div>

  <div class="card">
    <h2>Link de exemplo</h2>
    <p>
      <a href="https://www.google.com" target="_blank">
        Abrir o google
      </a>
    </p>
  </div>

  <div class="card">
    <h2>Interações</h2>
    <button onclick=" mostrarMensagem() ">Clique aqui</button>
    <p id=" mensagem"></p>
  </div>

  <footer>
    Página criada do Laboratório Web
  </footer>

  <script>
    function mostrarMensagem() {
      document.getElementById ("mensagem").innerHTML=
        "Divou bebê! Você executou um comando usando JavaScript.";
    }
  </script>

    
</body>
</html>
