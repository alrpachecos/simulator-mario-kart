🏎️🏁 Mario Kart Mini Battle (JS) 🍄
<center>
  <img width="278" height="225" alt="image" src="https://github.com/user-attachments/assets/8e05e979-d243-43b3-98e6-c5b0f22fd9e0" />
</center>

Uma simulação divertida de corrida entre personagens estilo Mario Kart usando JavaScript. O jogo se baseia em sorte (dados) e atributos dos corredores para determinar o vencedor após 5 rodadas emocionantes.

🎮 Como funciona
- Dois jogadores: Mario e Luigi
- A corrida acontece em 5 rodadas, com blocos aleatórios:
  - RETA: usa velocidade
  - CURVA: usa manobrabilidade
  - CONFRONTO: usa poder e pode tirar pontos do adversário
- A cada rodada, os dois jogadores rolam um dado e somam o valor ao seu atributo correspondente
- Quem tiver o maior valor ganha 1 ponto (ou remove 1 ponto do adversário em confronto)

🚀 Como executar
1. Copie o conteúdo do código para arquivo chamado index.js
2. Execute com node: ```node index.js```

📦 Requisitos
Node.js (versão 16+)

🧠 Exemplo de saída

```
🏁🚦 Corrida entre Mario e Luigi começando...
🏁 Rodada 1
Bloco RETA
Mario 🎲 rolou um dado de velocidade 4 + 4 = 8
Luigi 🎲 rolou um dado de velocidade 3 + 3 = 6
Mario marcou um ponto 🎉
```

📌 Objetivo
Este projeto é um exemplo educativo para demonstrar:
- Funções assíncronas em JavaScript
- Lógica de jogo baseada em turnos
- Simulação de sorte e atributos de personagens
