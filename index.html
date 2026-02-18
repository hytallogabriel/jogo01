<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emoji Luck - O Jogo mais Fácil</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { 
            background-color: #2c3e50; 
            color: white; 
            height: 100vh; 
            display: flex; 
            align-items: center; 
            justify-content: center; 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .slot-machine {
            background: #ecf0f1;
            padding: 40px;
            border-radius: 30px;
            border: 10px solid #f1c40f;
            box-shadow: 0 15px 0 #d35400;
            text-align: center;
            color: #2c3e50;
            max-width: 400px;
            width: 100%;
        }
        .fichas-display {
            font-size: 1.2rem;
            font-weight: bold;
            background: #dfe6e9;
            padding: 10px;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .reel-container {
            display: flex;
            gap: 15px;
            justify-content: center;
            margin: 30px 0;
        }
        .reel {
            width: 80px;
            height: 80px;
            background: white;
            border: 3px solid #bdc3c7;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            transition: transform 0.1s;
        }
        /* Efeito visual de girando */
        .spinning {
            animation: shake 0.1s infinite;
        }
        @keyframes shake {
            0% { transform: translateY(-5px); }
            100% { transform: translateY(5px); }
        }
        #btn-spin {
            width: 100%;
            padding: 15px;
            font-size: 1.5rem;
            font-weight: bold;
            border-radius: 50px;
            transition: 0.2s;
        }
        #btn-spin:active {
            transform: scale(0.95);
        }
    </style>
</head>
<body>

<div class="slot-machine">
    <p class="text-muted small mb-1">CASSINO ONLINE</p>
    <h2 class="mb-3 text-uppercase fw-bold">Pode Confiar👍</h2>
    
    <div class="fichas-display">
        Banca: R$ <span id="fichas-count">1000</span>
    </div>

    <div class="reel-container">
        <div id="reel1" class="reel">❓</div>
        <div id="reel2" class="reel">❓</div>
        <div id="reel3" class="reel">❓</div>
    </div>

    <button id="btn-spin" class="btn btn-warning shadow" onclick="jogar()">RODAR</button>

    <div id="resultado" class="mt-4 h4 fw-bold text-primary">Boa sorte!</div>
</div>

<script>
    const emojis = ["💀", "💸"];
    let fichas = 1000;

    function jogar() {
        const btn = document.getElementById('btn-spin');
        const resultado = document.getElementById('resultado');
        const displayFichas = document.getElementById('fichas-count');
        const reels = [
            document.getElementById('reel1'),
            document.getElementById('reel2'),
            document.getElementById('reel3')
        ];

        // 1. Verificar se tem saldo
        if (fichas <= 0) {
            resultado.innerText = "Acabou o dinheiro! 💸";
            resultado.className = "mt-4 h4 fw-bold text-warning";
            return;
        }

        // 2. Preparar rodada
        btn.disabled = true;
        fichas -= 10; // Custo de cada rodada
        displayFichas.innerText = fichas;
        resultado.innerText = "Girando...";
        resultado.className = "mt-4 h4 fw-bold text-secondary";

        // 3. Efeito de Animação
        reels.forEach(reel => reel.classList.add('spinning'));

        let giros = 0;
        const intervalo = setInterval(() => {
            reels.forEach(reel => {
                reel.innerText = emojis[Math.floor(Math.random() * emojis.length)];
            });
            giros++;
            
            // Para após 10 trocas rápidas (1 segundo)
            if (giros > 10) {
                clearInterval(intervalo);
                pararRoleta(reels, btn, resultado, displayFichas);
            }
        }, 100);
    }

    function pararRoleta(reels, btn, resultado, displayFichas) {
        // Remove animação
        reels.forEach(reel => reel.classList.remove('spinning'));

        // Define resultado final
        const final = [
            emojis[Math.floor(Math.random() * emojis.length)],
            emojis[Math.floor(Math.random() * emojis.length)],
            emojis[Math.floor(Math.random() * emojis.length)]
        ];

        reels[0].innerText = final[0];
        reels[1].innerText = final[1];
        reels[2].innerText = final[2];

        // Lógica de Premiação
        if (final[0] === "💸" && final[1] === "💸" && final[2] === "💸") {
            resultado.innerText = "🤑 Ganhou! +R$ 500 🤑";
            resultado.className = "mt-4 h3 text-success fw-bold";
            fichas += 500;
        } else {
            resultado.innerText = "Não foi dessa vez...";
            resultado.className = "mt-4 h4 fw-bold text-danger";
        }

        displayFichas.innerText = fichas;
        btn.disabled = false;
    }
</script>

</body>
</html>