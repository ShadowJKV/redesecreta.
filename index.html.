<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rede Secreta</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #111;
            color: white;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: #222;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.1);
        }
        h1 {
            font-size: 24px;
        }
        textarea {
            width: 100%;
            height: 100px;
            margin: 10px 0;
        }
        button {
            background-color: #e91e63;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
        }
        #mensagens {
            margin-top: 20px;
            text-align: left;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bem-vindo à Rede Secreta</h1>
        <p>Envie sua fofoca de forma totalmente anônima.</p>
        <textarea id="fofoca" placeholder="Digite sua fofoca aqui..."></textarea>
        <button onclick="enviarFofoca()">Enviar</button>
        <div id="mensagens">
            <h2>Últimas Fofocas</h2>
            <ul id="listaFofocas"></ul>
        </div>
    </div>

    <script>
        function enviarFofoca() {
            let fofoca = document.getElementById('fofoca').value;
            if (fofoca.trim() !== '') {
                let lista = document.getElementById('listaFofocas');
                let novaFofoca = document.createElement('li');
                novaFofoca.textContent = fofoca;
                lista.prepend(novaFofoca);
                document.getElementById('fofoca').value = '';
            }
        }
    </script>
</body>
</html>
