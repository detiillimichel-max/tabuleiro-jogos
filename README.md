# 🎲 Trilha do tabuleiro 

Jogo de tabuleiro com dados, em **3 arquivos** (`index.html`, `style.css`, `script.js`), pronto para GitHub Pages como PWA.

## 🎮 Como jogar

- **20 fases = 20 tabuleiros diferentes**, cada um com tema e tamanho próprios (de 16 a ~34 casas).
- Toque em **"Rolar Dado"** 🎲: o número que sair (1-6) é quantas casas você avança.
- Seu token 🚀 se move casa por casa com animação.

## 🟦 Tipos de Casa

- **Normal**: nada acontece, role de novo.
- **⭐ Bônus**: ganha pontos extras.
- **🪙 Moeda**: ganha moedas.
- **⚠️ Armadilha**: perde 1 vida ❤️ (a não ser que tenha 🛡️ Escudo ativo).
- **🔀 Bifurcação (Fork)**: você escolhe entre dois caminhos:
  - **⚡ Atalho**: avança mais casas no tabuleiro, mas ganha **menos pontos**.
  - **🛡️ Rota Segura**: avança menos casas, mas ganha **mais pontos**.
- **🚩 Início** e **🏆 Fim**: chegar ao 🏆 conclui a fase com bônus de pontos.

## ❤️ Vidas

- Você começa com 3 vidas.
- Cada casa de armadilha sem escudo custa 1 vida.
- 0 vidas = Fim de Jogo.

## 🛒 Loja de Power-ups (compra com ⭐ pontos)

- **🎲 Dado Extra** (20⭐): role o dado novamente após o turno atual.
- **🛡️ Escudo** (25⭐): protege contra a próxima armadilha.
- **🚀 Impulso** (15⭐): avança 2 casas imediatamente.
- **💖 Recuperar Vida** (40⭐): restaura 1 vida (até o máximo).
- **🍀 Trevo da Sorte** (18⭐): a próxima Rota Segura dá +10 pontos bônus.

## 🏁 Fim de Fase e Loop

Ao chegar na casa 🏆, você recebe um bônus de pontos (cresce com a fase) e pode avançar para o próximo tabuleiro.

Ao completar os **20 tabuleiros**, o jogo mostra "Mestre da Trilha" 🏆 e, ao continuar:
- Os **20 tabuleiros recebem novos temas e novo layout** (tamanhos, casas especiais e bifurcações são regerados aleatoriamente)
- Pontuação e moedas continuam acumulando

## 📂 Arquivos

- `index.html` — estrutura da página
- `style.css` — visual completo
- `script.js` — lógica do jogo (geração de tabuleiros, dado, bifurcações, loja)
- `manifest.json` — configuração PWA
- `sw.js` — service worker (cache offline)

## 📱 PWA

Inclui `manifest.json` e `sw.js`. Adicione `icon-192.png` e `icon-512.png` na mesma pasta para instalação completa.

## 🚀 Deploy no GitHub Pages

1. Suba todos os arquivos (mesma pasta) para o repositório.
2. Ative o GitHub Pages na branch principal.
3. Acesse pelo link gerado.
4. 
