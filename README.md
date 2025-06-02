<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Você decide o futuro da IA</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
        }
        
        .caixa-principal {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 600px;
            padding: 30px;
        }
        
        h1 {
            color: #2c3e50;
            text-align: center;
            margin-bottom: 30px;
        }
        
        .caixa-perguntas {
            font-size: 18px;
            margin-bottom: 20px;
            min-height: 60px;
        }
        
        .caixa-alternativas {
            display: flex;
            flex-direction: column;
            gap: 10px;
            margin-bottom: 20px;
        }
        
        .alternativa {
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .alternativa:hover {
            background-color: #f8f9fa;
        }
        
        .caixa-resultado {
            text-align: center;
            margin-top: 20px;
            padding: 15px;
            border-radius: 5px;
            display: none;
        }
        
        .controles {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }
        
        button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            background-color: #3498db;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        
        button:hover {
            background-color: #2980b9;
        }
        
        button:disabled {
            background-color: #bdc3c7;
            cursor: not-allowed;
        }
    </style>
</head>
<body>
    <div class="caixa-principal">
        <h1>Você decide o futuro da IA</h1>
        <div class="caixa-perguntas" id="pergunta"></div>
        <div class="caixa-alternativas" id="alternativas"></div>
        <div class="controles">
            <button id="anterior" disabled>Anterior</button>
            <button id="proximo">Próxima</button>
        </div>
        <div class="caixa-resultado" id="resultado">
            <h2>Seu Resultado:</h2>
            <p class="texto-resultado" id="texto-resultado"></p>
        </div>
    </div>
    <script>
        // Aqui viria todo o JavaScript para tornar o quiz funcional
        // Incluindo:
        // - Array de perguntas e respostas
        // - Lógica de navegação
        // - Cálculo de resultados
        // - Event listeners
    </script>
</body>
</html>
