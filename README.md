# Home (Test)
Some text here
# Research interests

<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Daniel Rotmeister</title>
    <style>
        body {
            margin: 0;
            min-height: 100vh;
            display: flex;
            justify-content: center;   /* Centraliza na horizontal */
            align-items: flex-end;     /* Joga tudo para o final da página */
            background-color: #0d1117; /* Fundo escuro */
            color: #8b949e;            /* Cor do texto cinza discreto */
            font-family: sans-serif;
            padding-bottom: 20px;      /* Distância da bordinha de baixo */
            box-sizing: border-box;
        }
    </style>
</head>
<body>

    <p>&copy; <span id="ano"></span> Daniel Rotmeister</p>

    <script>
        document.getElementById('ano').textContent = new Date().getFullYear();
    </script>

</body>
</html>
