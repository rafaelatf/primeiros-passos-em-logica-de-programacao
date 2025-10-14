# 🎮 Jogo do Número Secreto

Este repositório contém o projeto prático desenvolvido durante a formação **"A partir do zero: iniciante em programação"** da Alura. O projeto é um jogo interativo onde o usuário deve adivinhar um número secreto gerado aleatoriamente dentro de um limite definido.

Ele demonstra a aplicação de conceitos fundamentais de lógica de programação e manipulação do DOM (Document Object Model) com JavaScript.

---

## 🎯 Objetivo do Projeto

O objetivo principal deste projeto é consolidar o aprendizado em:

* **Interação:** Criar uma experiência de usuário dinâmica através da manipulação de elementos da página (HTML) e eventos (cliques em botões).
* **Controle de Fluxo:** Utilizar estruturas condicionais e funções para guiar a lógica do jogo (acertar, errar, dar dicas, reiniciar).
* **Estruturas de Dados:** Aplicar o uso de arrays (`listaDeNumerosSorteados`) para garantir que o número secreto não se repita.

---

## 💡 Conceitos de Lógica e JavaScript Aplicados

O código (`app.js`) é uma demonstração prática dos seguintes conceitos:

### Fundamentos & Manipulação de Dados
| Conceito | Aplicação no Código |
| :--- | :--- |
| **Variáveis** | Armazenar o número secreto, o limite do jogo e a contagem de tentativas (`let numeroSecreto`, `let tentativas`). |
| **Arrays (Listas)** | Utilização do `let listaDeNumerosSorteados = []` para guardar números já sorteados, evitando repetição. |
| **`Math.random()`** | Geração de números aleatórios dentro de um limite (`numeroLimite`). |
| **`parseInt()`** | Conversão de números de ponto flutuante para inteiros. |

### Controle de Fluxo & Lógica do Jogo
| Conceito | Aplicação no Código |
| :--- | :--- |
| **Funções** | Organização do código em blocos reutilizáveis (`exibirTextoNaTela`, `verificarChute`, `gerarNumeroAleatorio`, `reiniciarJogo`). |
| **Estruturas Condicionais** | Uso de `if/else` para: **1.** Verificar se o chute está correto; **2.** Fornecer dicas (`maior` ou `menor`) se o chute estiver errado. |
| **Recursão e `includes()`** | Uso da função recursiva `gerarNumeroAleatorio` e o método `listaDeNumerosSorteados.includes(numeroEscolhido)` para garantir a não repetição de números. |
| **Operador Ternário** | Estratégia de legibilidade para exibir plural/singular de "tentativas" (`tentativas > 1 ? 'tentativas' : 'tentativa'`). |

### Manipulação de DOM (Interface)
| Conceito | Aplicação no Código |
| :--- | :--- |
| **`document.querySelector()`** | Seleção de elementos HTML (tags `h1`, `p`, `input`) para leitura e alteração. |
| **`innerHTML`** | Alteração dinâmica do texto (`h1` e `p`) na tela. |
| **Atributos** | Uso de `removeAttribute('disabled')` e `setAttribute('disabled', true)` para controlar o botão "Novo jogo". |
| **Limpeza de Input** | Função `limparCampo()` para melhorar a experiência do usuário. |
| **Eventos `onclick`** | Ativar funções JavaScript a partir de cliques nos botões. |
| **API Externa** | Integração da biblioteca `responsiveVoice.js` para adicionar funcionalidade de síntese de voz. |

---

## 💻 Tecnologias Utilizadas

-   **Lógica:** JavaScript
-   **Estrutura:** HTML5
-   **Estilização:** CSS3
-   **Biblioteca:** ResponsiveVoice (para síntese de voz)

---

## 📫 Contato
📧 [rafaelatf@gmail.com](mailto:rafaelatf@gmail.com)
🌐 [linkedin.com/in/rafaelatf](https://linkedin.com/in/rafaelatf)
