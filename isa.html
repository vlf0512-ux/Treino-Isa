<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Meu Treino</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: #1e1e1e;
      color: #fff;
      padding: 20px;
    }

    h1 {
      text-align: center;
      margin-bottom: 20px;
    }

    select, input, button {
      margin: 5px 0;
      padding: 10px;
      font-size: 16px;
      border-radius: 8px;
      border: 1px solid #666;
    }

    button {
      cursor: pointer;
    }

    .treino {
      background: rgb(51, 43, 43);
      padding: 20px;
      border-radius: 10px;
      margin-top: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.4);
    }

    .exercicio {
      margin-bottom: 15px;
    }

    label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
      color: #fff;
    }

    h3 {
      color: #ffeb3b;
      margin-top: 20px;
    }

    .pesos {
      display: flex;
      gap: 8px;
    }

    .pesos input {
      width: 70px;
      padding: 5px;
      text-align: center;
    }

    .salvo {
      border: 2px solid #4caf50 !important;
      background: #e8f5e9;
      color: #000;
    }

    @media (max-width: 600px) {
      .pesos {
        flex-direction: column;
      }
      .pesos input {
        width: 100%;
      }
    }
  </style>
</head>

<body>
  <h1>TREINO SEMANAL <br>(Isa)</h1>

  <label for="dia">Selecione o treino:</label>
  <select id="dia" onchange="carregarTreino()">
    <option value="treinoA">Treino A</option>
    <option value="treinoB">Treino B</option>
    <option value="treinoC">Treino C</option>
  </select>

  <button id="btnduvidas">Dúvidas</button>

  <div id="treino" class="treino"></div>

<script>
  const treinos = {
    treinoA: {
      Quadriceps: ["Agachamento Smith", "Cadeira Extensora", "Búlgaro ", "Abdutora ","20min cardio"],
      
    },

    treinoB: {
      Superiores: ["Puxada Alta", "Remada Baixa", "Desenvolvimento ", "Rosca Martelo ", "Tríceps Corda ", "20min cardio"],
      
    },

    treinoC: {
      Posteriores: ["Stiff", "Mesa Flexora", "Elevação Pelvica", "Coice Na Polia", "Cadeira Abdutora", "20min cardio"],
     
    }
  };

  function carregarTreino() {
    const dia = document.getElementById("dia").value;
    const treinoDiv = document.getElementById("treino");
    treinoDiv.innerHTML = "";

    for (const categoria in treinos[dia]) {
      treinoDiv.innerHTML += `<h3>${categoria.toUpperCase()}</h3>`;

      treinos[dia][categoria].forEach(exercicio => {
        treinoDiv.innerHTML += `
          <div class="exercicio">
            <label>${exercicio}</label>
            <div class="pesos">
              ${[1,2,3,4].map(i => {
                const pesoSalvo = localStorage.getItem(`${dia}-${exercicio}-rep${i}`) || "";
                return `<input type="text" value="${pesoSalvo}" 
                  onkeydown="formatarPeso(event, '${dia}', '${exercicio}', ${i}, this)">`;
              }).join("")}
            </div>
          </div>
        `;
      });
    }
  }

  function formatarPeso(event, dia, exercicio, rep, input) {
    if (event.key === "Enter") {
      let valor = input.value.replace("kg", "").trim();
      if (valor && !isNaN(valor)) {
        input.value = valor + " kg";
        localStorage.setItem(`${dia}-${exercicio}-rep${rep}`, input.value);

        input.classList.add("salvo");
        setTimeout(() => input.classList.remove("salvo"), 600);

        const proximo = input.parentElement.querySelectorAll("input")[rep];
        if (proximo) proximo.focus();
      }
      event.preventDefault();
    }
  }

  window.onload = carregarTreino;

  document.getElementById("btnduvidas").onclick = function() {
    window.open("duvidas.html", "_blank");
  };
</script>
</body>
</html>
