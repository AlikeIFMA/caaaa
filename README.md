<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora Geométrica</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <main>
        <div class="container2">
            <p class="para">Esta calculadora foi feita de forma simples e objetiva. Essa calculadora faz o cálculo com base nos números de quantidade de lados fornecidos pelo usuário. Ela calcula formas geométricas de 3 até 10 lados. </p>
        </div>
        <div class="container">
          <div class="title"> Calculadora Geométrica </div>
          <div class="input">
              <label>Quantidade de lados:</label>
              <input type="number" id='qtd'>
          </div>

          <button id='calcular'>Calcular</button>
 
          <div class="result" id='resultado'></div>
        </div>
      </main>
    <script src="geo.js"></script>
</body>
</html>