<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora - Einstein do ZapZap</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh; /* Altura da viewport */
            margin: 0;
        }

        h1 {
            color: green;
            font-size: 24px;
            display: flex;
            align-items: center; /* Centralizar a imagem verticalmente */
        }

        /* Estilos adicionais podem ser adicionados aqui conforme necessário */

        /* Estilos para a imagem do gatinho */
        img.gatinho {
            max-height: 300px; /* Altura máxima da imagem do gatinho (duplicada para 300px) */
            margin-right: 10px; /* Espaço à direita da imagem */
        }

        /* Estilos para a imagem de Albert Einstein */
        img.einstein {
            max-height: 150px; /* Altura máxima da imagem de Einstein */
        }

        /* Estilos para a imagem à direita do título */
        img.right-image {
            max-height: 150px; /* Altura máxima da imagem à direita do título */
            margin-left: 10px; /* Espaço à esquerda da imagem */
        }

        /* Estilos para a caixa de enviar pergunta */
        #mathQuestionForm {
            margin-top: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        label {
            font-size: 16px;
            margin-bottom: 10px;
        }

        input[type="text"] {
            width: 300px;
            padding: 5px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        button[type="submit"] {
            background-color: green;
            color: white;
            font-size: 16px;
            padding: 5px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button[type="submit"]:hover {
            background-color: darkgreen;
        }

        /* Estilos para a resposta */
        #answer {
            font-size: 18px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>
        <img class="einstein" src="https://static.todamateria.com.br/upload/al/be/alberteinstein-cke.jpg" alt="Imagem de Albert Einstein">
        Calculadora - Einstein do ZapZap
        <img class="right-image" src="https://thumbs.dreamstime.com/z/e-134796795.jpg" alt="Imagem à Direita do Título">
    </h1>
    
    <form id="mathQuestionForm">
        <label for="question">Digite sua pergunta matemática:</label>
        <input type="text" id="question" name="question" required>
        <button type="submit">Calcular</button>
    </form>

    <div id="answer"></div>

    <!-- Substitua 'URL_DA_IMAGEM_DO_GATINHO' pelo URL real da imagem do gatinho -->
    <img class="gatinho" src="https://www.cafunepets.com.br/images/h0nadbhvm6m4/1lqQlGlCeH8GJTEN3aLg5Z/aa2b2c76fc36dca91bb3df2a10b85a07/a2l0dGVuLWxpdHRlci1oZXJvLXN3aXJsLmpwZw/1280w-720h/adotei-um-gatinho.jpg" alt="Imagem de Gatinho">

    <script>
        // Adicione aqui a lógica JavaScript para calcular a resposta
        document.getElementById('mathQuestionForm').addEventListener('submit', function (e) {
            e.preventDefault();

            const question = document.getElementById('question').value;

            // Função para calcular a potência com suporte a parênteses
            function calculatePower(expression) {
                const regex = /\(([^)]+)\)\^(\d+)/g;
                let result = expression;
                let match = regex.exec(expression);
                while (match !== null) {
                    const base = eval(match[1]);
                    const exponent = parseFloat(match[2]);
                    if (!isNaN(base) && !isNaN(exponent)) {
                        const powerResult = Math.pow(base, exponent);
                        result = result.replace(match[0], powerResult.toString());
                    }
                    match = regex.exec(expression);
                }
                return result;
            }

            // Verifique se a entrada contém o símbolo de potência (^) e faça o cálculo correto
            if (/\^/.test(question)) {
                try {
                    const resultWithPower = calculatePower(question);
                    const answer = eval(resultWithPower);
                    document.getElementById('answer').textContent = `Resposta: ${answer}`;
                } catch (error) {
                    document.getElementById('answer').textContent = 'Erro na pergunta matemática.';
                }
            } else {
                // Se não houver símbolo de potência, avalie a expressão normalmente
                try {
                    const answer = eval(question);
                    document.getElementById('answer').textContent = `Resposta: ${answer}`;
                } catch (error) {
                    document.getElementById('answer').textContent = 'Erro na pergunta matemática.';
                }
            }
        });
    </script>
</body>
</html>
