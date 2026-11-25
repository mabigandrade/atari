# 🚀 Space Invaders

Um jogo clássico de arcade, onde o jogador controla uma nave espacial e precisa defender a tela contra ondas de alienígenas.
<img width="802" height="602" alt="image" src="https://github.com/user-attachments/assets/8c4d1958-69ce-439f-8a82-18e9d4039cb8" />
//imagem
---

## 🎮 Como Jogar

1. Na tela inicial, clique no botão **JOGAR** para iniciar a partida.
2. Mova a nave horizontalmente para desviar da horda e mirar nos inimigos.
3. Atire para destruir todas as 4 fileiras de alienígenas antes que eles alcancem a parte inferior da tela ou encostem na sua nave.

### ⌨️ Controles
* **Seta Esquerda (`⬅️`):** Move a nave para a esquerda.
* **Seta Direita (`➡️`):** Move a nave para a direita.
* **Barra de Espaço (`Espaço`):** Dispara projéteis (com intervalo de recarga de 0,3 segundos).
<img width="811" height="611" alt="image" src="https://github.com/user-attachments/assets/fb68bb9f-802a-4669-ab1b-36741f377bd1" />

---

## ⚙️ Regras e Mecânicas

* **Pontuação:** Cada alienígena destruído concede **+10 pontos**.
* **Temporizador:** Um cronômetro no topo da tela registra o tempo total da partida em segundos.
* **Sistema de Vidas:** O jogador inicia com **3 vidas (❤️)**. Caso um alienígena encoste na nave ou chegue ao fundo da tela, o jogador perde 1 vida e a horda é recuada para dar tempo de reação.
* **Condição de Vitória:** Destruir todos os 32 alienígenas da tela.
* **Game Over:** Perder todas as 3 vidas. Ao final, é exibida a pontuação total e o tempo sobrevivido, com opção de reiniciar imediatamente.
<img width="798" height="41" alt="image" src="https://github.com/user-attachments/assets/9fddd5d8-1149-4622-8c30-78f9f2dabe26" />

---

## 📁 Estrutura de Arquivos

```text
JOGUINHO/
├── img/
│   ├── alien1.png      # Sprite dos inimigos da 1ª fileira
│   ├── alien2.png      # Sprite dos inimigos da 2ª fileira
│   ├── alien3.png      # Sprite dos inimigos da 3ª fileira
│   ├── alien4.png      # Sprite dos inimigos da 4ª fileira
│   └── nave1.png       # Sprite da nave do jogador
├── index.html          # Estrutura, estilos (CSS) e lógica completa do jogo (JS)
└── README.md           # Documentação do projeto
