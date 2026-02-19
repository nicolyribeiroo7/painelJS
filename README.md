

# 📘 Painel de Operadores JavaScript

## 📌 Sobre o Projeto

O **Painel de Operadores JavaScript** é uma aplicação simples desenvolvida com **HTML, CSS e JavaScript** com o objetivo de praticar e demonstrar o funcionamento dos principais operadores da linguagem JavaScript.

O sistema permite que o usuário insira dois números e visualize automaticamente o resultado de diferentes tipos de operadores:

* Operadores Aritméticos
* Operadores de Atribuição
* Operadores de Comparação

---

## 🎯 Objetivo

Este projeto foi criado para:

* Praticar manipulação do DOM
* Trabalhar com funções em JavaScript
* Utilizar template strings (`` ` ` ``)
* Aplicar operadores matemáticos e lógicos
* Implementar validação de entrada de dados

---

## 🛠️ Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript (puro)

---

## 📂 Estrutura do Projeto

O projeto está organizado em três partes principais:

### 🔹 1. Estrutura HTML

* Campos de entrada para dois números
* Botão para executar os cálculos
* Div para exibir os resultados dinamicamente

### 🔹 2. Estilização CSS

* Layout centralizado
* Design moderno com sombra e bordas arredondadas
* Estilo organizado para melhor leitura dos resultados

### 🔹 3. Lógica JavaScript

A função `calcular()`:

1. Captura os valores digitados
2. Converte para número usando `Number()`
3. Valida se os valores são numéricos usando `isNaN()`
4. Exibe os resultados dinamicamente usando `innerHTML`

---

## 🔢 Operadores Demonstrados

### 🧮 A. Aritméticos

* Soma (+)
* Subtração (-)
* Multiplicação (*)
* Divisão (/)
* Resto (%)
* Potência (**)

Inclui verificação para evitar divisão por zero.

---

### 📝 B. Atribuição

* Simples (=)
* Soma com atribuição (+=)
* Subtração com atribuição (-=)
* Multiplicação com atribuição (*=)

---

### ⚖️ C. Comparação

* Igual (==)
* Estritamente igual (===)
* Diferente (!=)
* Maior que (>)
* Menor ou igual (<=)

---

## 🚀 Como Executar

1. Copie o código.
2. Cole em um arquivo chamado, por exemplo:

   ```
   index.html
   ```
3. Abra o arquivo no navegador.
4. Insira dois números.
5. Clique em **"Calcular Tudo"**.

---

## ⚠️ Validação Implementada

O sistema impede cálculos caso:

* Um dos campos esteja vazio
* O valor digitado não seja numérico

Nesse caso, um alerta é exibido solicitando números válidos.

---

## 📚 Conceitos Trabalhados

* Manipulação de elementos com `getElementById`
* Funções em JavaScript
* Escopo de variáveis (`let`)
* Template literals
* Operador ternário
* Estruturas condicionais (`if`)
* Eventos via `onclick`

---

## 💡 Possíveis Melhorias Futuras

* Adicionar operadores lógicos (&&, ||, !)
* Criar versão com botão para limpar resultados
* Separar CSS e JS em arquivos externos
* Implementar animações
* Adicionar tratamento visual para erro em vez de `alert()`

---

## 👩‍💻 Finalidade Educacional

Este projeto é ideal para iniciantes que estão começando os estudos em JavaScript e desejam entender como os operadores funcionam na prática, visualizando resultados em tempo real.

---

