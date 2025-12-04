# 🧮 Calculadora — Projeto em HTML, CSS e JavaScript

Este é um projeto de **calculadora funcional**, desenvolvida com **HTML, CSS e JavaScript puro**, contendo operações básicas, formatação de números e um visual limpo.

A calculadora possui:
- Operações de soma, subtração, multiplicação e divisão  
- Botão `AC` (limpar tudo)  
- Botão `DEL` (apagar último número)  
- Exibição separada de número atual e número anterior  
- Formatação automática no display  
- Interface construída com Grid Layout  

---

## 📸 Interface da Calculadora
*(Caso queira, posso gerar uma imagem bonitona para colocar aqui!)*

---

## 🚀 Tecnologias Utilizadas
- **HTML5** — estrutura da calculadora  
- **CSS3** — estilização e layout responsivo  
- **JavaScript** — lógica da calculadora, classes e eventos  

---

## 📂 Arquivos do Projeto

### **index.html**
Contém a estrutura base da calculadora, grid de botões e elementos do display.  
:contentReference[oaicite:0]{index=0}

### **scripts.js**
Código responsável por toda a lógica: classe da calculadora, funções de calcular, deletar, formatar números e atualizar o display.  
:contentReference[oaicite:1]{index=1}

### **styles.css**
Folha de estilo da interface (cores, grid, espaçamento, fontes, foco etc.).  
*(Você ainda não enviou o `styles.css`, mas posso gerar um tema top se quiser.)*

---

## 🧠 Como funciona a lógica (resumo)
A lógica central está na classe `Calculator`, que controla:

### ✔ `appendNumber()`
Adiciona números ao display.

### ✔ `chooseOperation()`
Define a operação clicada (+, -, ×, ÷).

### ✔ `calculate()`
Executa o cálculo usando `switch...case`.

### ✔ `delete()`
Remove o último dígito.

### ✔ `clear()`
Zera tudo (AC).

### ✔ `updateDisplay()`
Atualiza automaticamente o display de cima e de baixo com números formatados.

---

## 🔧 Como executar
1. Baixe ou clone o repositório:
```bash
git clone https://github.com/seu-usuario/nome-do-repo.git
