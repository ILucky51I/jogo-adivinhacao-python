# Jogo de adivinhação em Python - Projeto Iniciante

## 🎲 Jogo de Adivinhação em Python

Este projeto é um simples jogo de adivinhação de números em Python, ideal para quem está começando na programação. Ele demonstra conceitos básicos como entrada de dados, condicionais, loops, conversão de tipos e uso de módulos da biblioteca padrão (neste caso, o random).

## 📹 Sobre

* O algoritmo escolhe, aleatoriamente, um número dentro de um intervalo definido pelo usuário.
* O usuário deve tentar adivinhar o número.
* A cada tentativa, o programa informa se o palpite foi alto ou baixo demais.
* O número total de tentativas é exibido ao final.

### Esse exercício é excelente para praticar:

* Importação de módulos.
* Validação e conversão de entradas (strings para inteiros).
* Uso eficiente de loops e condicionais.
* Manipulação de erros simples.
* Exibição de dicas ao usuário.

## 📝 Lógica do Jogo

* O programa solicita que o usuário informe o número máximo do intervalo para o sorteio (exemplo: 10, 100).

* O número randômico será sorteado entre 0 e esse teto.

* O usuário deve digitar tentativas de adivinhação.

### A cada rodada:
* Se o valor não for numérico, o programa pede um novo valor.
* Se for um número maior que o sorteado, avisa para tentar um número menor.
* Se for um número menor, avisa para tentar mais alto.
* Se acertar, encerra o jogo e mostra o total de tentativas.

## 🧐 O que você aprende com este projeto

* Importação do módulo random: uso da função randint(a, b) para gerar inteiros aleatórios.
* Validação de entradas: garantindo que somente números sejam aceitos, usando métodos como .isnumeric().
* Conversão de tipos: usando int() e str() conforme necessário.
* Estruturas de repetição e controle de fluxo: uso de while True:, if, elif, else, continue e break.
* Contagem de tentativas: incrementando uma variável a cada tentativa correta de palpite.

## 🔖 Possíveis melhorias

* Tratar casos de números negativos ou zero no teto do desafio.
* Oferecer limite de tentativas para aumentar a dificuldade.
* Adicionar funcionalidade para reiniciar o jogo automaticamente.
* Exibir ranking das menores tentativas.
