# 🧠 Jogo do Número Secreto

Este é um projeto desenvolvido durante uma aula da [Alura](https://www.alura.com.br/), com fins **educacionais**, focado em aplicar conceitos fundamentais de **JavaScript**, **lógica de programação** e **interatividade no navegador**.

## 📚 Objetivo Educacional

- Compreender estruturas condicionais e funções.
- Praticar manipulação do DOM.
- Explorar recursos de acessibilidade com a **Web Speech API**.
- Desenvolver lógica de sorteio sem repetição.
- Criar uma aplicação divertida e interativa para fixar o aprendizado.

## 🎮 Sobre o Jogo

O jogo consiste em adivinhar um **número secreto entre 1 e 10**. A cada tentativa, o jogador recebe uma dica:
- Se o número digitado for **maior** que o número secreto: "O número é menor".
- Se for **menor**: "O número secreto é maior".
- Quando acerta, é exibida uma mensagem com a quantidade de tentativas realizadas.

A voz do navegador (quando suportada) também **fala as instruções e dicas**, promovendo mais acessibilidade.

## ⚙️ Funcionalidades

- Geração aleatória de número secreto sem repetição.
- Contagem de tentativas.
- Mensagens dinâmicas com suporte a **sintetização de fala**.
- Botão para reiniciar o jogo.
- Código 100% em JavaScript puro.

## 📁 Estrutura Principal do Código (`app.js`)

- `gerarNumeroAleatorio()`: Gera e armazena números não repetidos.
- `verificarChute()`: Avalia o palpite do jogador.
- `exibirTextoNaTela()`: Exibe e vocaliza mensagens.
- `reiniciarJogo()`: Reseta o jogo para uma nova rodada.

## 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- Web Speech API (sintetizador de voz)

## 🚀 Como Executar

1. Clone ou baixe os arquivos do projeto.
2. Abra o arquivo `index.html` no navegador (junto ao `app.js`).
3. Jogue tentando acertar o número secreto!
