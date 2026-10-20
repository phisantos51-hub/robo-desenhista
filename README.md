# Robô Desenhista

Programe o robô para desenhar formas e letras. Jogo de programação, geometria e alfabetização para o Ciclo de Alfabetização (1º ao 3º ano do Ensino Fundamental).

**Jogar:** https://phisantos51-hub.github.io/robo-desenhista/

## Como se joga
1. Escolha a cor do rastro e o seu ano.
2. Clique nas setas para montar o programa (cada seta anda uma casa).
3. Clique em **Executar**: o robô pinta as casas por onde passa.
4. Desenhe a figura pedida. Quanto menos blocos, mais estrelas (até 3).

Se algo ficar diferente, o tabuleiro mostra as casas que faltaram ou sobraram e o bloco que causou a diferença pisca. O programa não é apagado.

| Ano | Tabuleiro | Novidade | Figuras |
|-----|-----------|----------|---------|
| 1º  | 5 × 5 | Caminho pontilhado no tabuleiro | Linhas, cantos, letras L, T, I, F, E, H |
| 2º  | 6 × 6 | Bloco REPETIR e modelo ao lado | Quadrados, retângulo, escadas, letras U, C, P, J |
| 3º  | 7 × 7 | Limite de blocos e Modo Livre | Árvore, prédio, janela, casinha, robô, letras ligadas |

## Para a escola
- Funciona só com o mouse (botões grandes, sem clique duplo). Atalhos opcionais: setas, Enter (executar), Backspace (apagar), R (repetir).
- Não depende de som: o som começa desligado.
- Depois de aberto uma vez, funciona sem internet.
- As estrelas ficam guardadas em cada computador.

Feito só com HTML, CSS e JavaScript, sem instalação: tudo está em `index.html` (e `sw.js`, que guarda o jogo para uso sem internet).

## Acessibilidade
Na tela inicial, o botão **Acessibilidade** abre as opções (elas ficam guardadas em cada computador):
- **Modo Áudio** — para estudante cego, com teclado e fones de ouvido. O jogo fala em português, tem fases pequenas (3 × 3 e 4 × 4) e sons que guiam o robô (esquerda/direita no fone, agudo em cima, grave embaixo). Teclas: setas (comandos), Enter (executar), Backspace (apagar), Espaço (repetir instrução), L (onde está o robô), P (ler o programa), H (ajuda), Esc (voltar). Funciona também com NVDA e Narrador; nesse caso, desligue a "Voz do próprio jogo".
- **Modo Calmo** — cores suaves, nada piscando, barra de progresso, passos numerados, botão Pausa e recompensa sempre igual. Pode desligar todas as animações.
- **Letras e botões maiores** e **Alto contraste**.

## Área do professor
Botão discreto no canto da tela inicial, protegido por uma continha. Permite liberar todas as fases, apagar o progresso do computador e abrir as configurações de acessibilidade.
