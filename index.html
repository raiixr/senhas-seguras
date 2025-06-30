<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Gerador de Senhas</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>🔐 Gerador de Senhas</h1>

        <div class="options">
            <label><input type="checkbox" id="maiusculas" checked> Letras maiúsculas (A-Z)</label>
            <label><input type="checkbox" id="minusculas" checked> Letras minúsculas (a-z)</label>
            <label><input type="checkbox" id="numeros" checked> Números (0-9)</label>
            <label><input type="checkbox" id="simbolos" checked> Símbolos (!@#$%)</label>
        </div>

        <div class="password-box">
            <input type="text" id="senha" readonly>
            <button onclick="gerarSenha()">Gerar Senha</button>
        </div>

        <p id="forcaSenha">Força da senha: <span id="nivelForca">---</span></p>
    </div>

    <script>
        function gerarSenha() {
            const maiusculas = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
            const minusculas = "abcdefghijklmnopqrstuvwxyz";
            const numeros = "0123456789";
            const simbolos = "!@#$%&*";

            let caracteres = "";

            if (document.getElementById("maiusculas").checked) caracteres += maiusculas;
            if (document.getElementById("minusculas").checked) caracteres += minusculas;
            if (document.getElementById("numeros").checked) caracteres += numeros;
            if (document.getElementById("simbolos").checked) caracteres += simbolos;

            if (caracteres === "") {
                alert("Selecione pelo menos uma opção!");
                return;
            }

            let senha = "";
            const tamanho = 12; // Pode ajustar o tamanho

            for (let i = 0; i < tamanho; i++) {
                const randIndex = Math.floor(Math.random() * caracteres.length);
                senha += caracteres[randIndex];
            }

            document.getElementById("senha").value = senha;
            avaliarForca(senha);
        }

        function avaliarForca(senha) {
            let forca = 0;

            if (senha.length >= 8) forca++;
            if (/[A-Z]/.test(senha)) forca++;
            if (/[a-z]/.test(senha)) forca++;
            if (/[0-9]/.test(senha)) forca++;
            if (/[^A-Za-z0-9]/.test(senha)) forca++;

            const nivel = document.getElementById("nivelForca");

            if (forca <= 2) {
                nivel.textContent = "Fraca";
                nivel.style.color = "red";
            } else if (forca === 3 || forca === 4) {
                nivel.textContent = "Média";
                nivel.style.color = "orange";
            } else {
                nivel.textContent = "Forte";
                nivel.style.color = "green";
            }
        }
    </script>
</body>
</html>
