---
layout: default
title: "Exercícios de JavaScript"
description: "Página com exercícios práticos de JavaScript para iniciantes e avançados. Acompanhe e aprenda as bases da linguagem com exemplos práticos."
---

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercícios de JavaScript</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }
        h1 {
            color: #4CAF50;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            margin: 10px 0;
        }
        a {
            text-decoration: none;
            color: #4CAF50;
            transition: color 0.3s;
        }
        a:hover {
            color: #388E3C;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .back-to-top {
            display: inline-block;
            margin-top: 20px;
            color: #4CAF50;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Exercícios de JavaScript</h1>
        <p>Bem-vindo à página de exercícios de JavaScript! Aqui você encontrará uma coleção organizada de atividades para ajudá-lo a desenvolver suas habilidades em JavaScript, do nível básico ao avançado.</p>
        
        <h2>Índice</h2>
        <ul>
            <li><a href="#variaveis-e-tipos-de-dados">2. Conceitos Básicos - Variáveis e Tipos de Dados</a></li>
            <li><a href="#operadores">2. Conceitos Básicos - Operadores</a></li>
            <li><a href="#estruturas-de-controle">2. Conceitos Básicos - Estruturas de Controle</a></li>
            <li><a href="#loops">2. Conceitos Básicos - Loops</a></li>
            <li><a href="#declaracao-e-invocacao">3. Funções - Declaração e Invocação</a></li>
            <li><a href="#parametros-e-argumentos">3. Funções - Parâmetros e Argumentos</a></li>
            <li><a href="#funcoes-anonimas-e-de-callback">3. Funções - Funções Anônimas e de Callback</a></li>
            <li><a href="#arrow-functions">3. Funções - Arrow Functions</a></li>
            <li><a href="#escopo-de-variaveis">3. Funções - Escopo de Variáveis</a></li>
            <li><a href="#criacao-e-manipulacao-de-arrays">4. Arrays e Objetos - Criação e Manipulação de Arrays</a></li>
            <li><a href="#metodos-de-arrays">4. Arrays e Objetos - Métodos de Arrays</a></li>
            <li><a href="#objetos">4. Arrays e Objetos - Objetos</a></li>
            <li><a href="#iteracao-de-objetos-e-arrays">4. Arrays e Objetos - Iteração de Objetos e Arrays</a></li>
            <li><a href="#json">4. Arrays e Objetos - JSON</a></li>
        </ul>
        
        <h2 id="variaveis-e-tipos-de-dados">Variáveis e Tipos de Dados</h2>
        <p>1. Crie uma variável <code>nome</code> usando <code>let</code> e atribua o seu nome...</p>
        <a class="back-to-top" href="#">Voltar ao índice</a>
        
        <h2 id="operadores">Operadores</h2>
        <p>1. Declare duas variáveis <code>a</code> e <code>b</code> com valores numéricos...</p>
        <a class="back-to-top" href="#">Voltar ao índice</a>
        
        <h2 id="estruturas-de-controle">Estruturas de Controle</h2>
        <p>1. Crie um script que verifique se um número armazenado na variável <code>numero</code>...</p>
        <a class="back-to-top" href="#">Voltar ao índice</a>
        
        <h2 id="loops">Loops</h2>
        <p>1. Crie um loop <code>for</code> que imprima todos os números de <code>1</code> a <code>20</code>...</p>
        <a class="back-to-top" href="#">Voltar ao índice</a>
        
        <h2 id="declaracao-e-invocacao">Declaração e Invocação de Funções</h2>
        <p>1. Crie uma função <code>saudacao()</code> que imprima <code>Olá, seja bem-vindo!</code>...</p>
        <a class="back-to-top" href="#">Voltar ao índice</a>
        
        <h2 id="parametros-e-argumentos">Parâmetros e Argumentos</h2>
        <p>1. Crie uma função <code>calcularAreaRetangulo()</code> que receba dois parâmetros...</p>
        <a class="back-to-top" href="#">Voltar ao índice</a>
        
        <!-- Continue para os outros tópicos de forma similar -->
    </div>
</body>
</html>



# JavaScript

## Índice
- [1. Introdução ao JavaScript](#introdução-ao-javascript)
  - [O que é JavaScript?](#o-que-é-javascript)
  - [Histórico e Evolução](#histórico-e-evolução)
  - [Como Funciona na Web](#como-funciona-na-web)
  - [Configuração do Ambiente de Desenvolvimento](#configuração-do-ambiente-de-desenvolvimento)
- [2. Conceitos Básicos](#2-conceitos-básicos)
  - [Variáveis e Tipos de Dados](#variáveis-e-tipos-de-dados)
  - [Operadores](#operadores-aritméticos-lógicos-comparação)
  - [Estruturas de Controle](#estruturas-de-controle-if-else-switch)
  - [Loops](#loops-for-while-dowhile)
- [3. Funções](#3-funções)
  - [Declaração e Invocação](#declaração-e-invocação)
  - [Parâmetros e Argumentos](#parâmetros-e-argumentos)
  - [Funções Anônimas e de Callback](#funções-anônimas-e-de-callback)
  - [Arrow Functions](#arrow-functions)
  - [Escopo de Variáveis](#escopo-de-variáveis-local-e-global)
- [4. Arrays e Objetos](#4-arrays-e-objetos)
  - [Criação e Manipulação de Arrays](#criação-e-manipulação-de-arrays)
  - [Métodos de Arrays](#métodos-importantes-de-arrays)
  - [Objetos](#objetos-propriedades-e-métodos)
  - [Iteração de Objetos e Arrays](#iteração-de-objetos-e-arrays)
  - [JSON](#json-javascript-object-notation)
- [5. Manipulação do DOM (Document Object Model)](#5-manipulação-do-dom-document-object-model)
  - [Seleção de Elementos](#seleção-de-elementos-getelementbyid-queryselector)
  - [Manipulação de Conteúdo e Estilos](#manipulação-de-conteúdo-e-estilos)
  - [Eventos](#eventos-click-submit-mouseover)
  - [Criação e Remoção de Elementos](#criação-e-remocao-de-elementos)
  - [Navegação entre Elementos](#navegação-entre-elementos-parentnode-childnodes)
- [6. Programação Assíncrona](#6-programação-assíncrona)
  - [Conceito de Assincronismo](#conceito-de-assincronismo)
  - [Callbacks](#callbacks)
  - [Promises](#promises)
  - [Async/Await](#asyncawait)
  - [Tratamento de Erros Assíncronos](#tratamento-de-erros-assíncronos)
  - [Fetch API e Ajax](#fetch-api-e-ajax)
- [7. Classes e Programação Orientada a Objetos](#7-classes-e-programação-orientada-a-objetos)
  - [Conceitos Básicos de POO](#conceitos-básicos-de-poo)
  - [Definição de Classes e Instância de Objetos](#definição-de-classes-e-instância-de-objetos)
  - [Herança e Polimorfismo](#herança-e-polimorfismo)
  - [Encapsulamento](#encapsulamento)
  - [Métodos Estáticos e de Instância](#métodos-estáticos-e-de-instância)

---

## Introdução ao JavaScript

### O que é JavaScript?
JavaScript é uma linguagem de programação versátil e poderosa, projetada principalmente para desenvolver funcionalidades interativas em páginas web. Ao contrário de linguagens de marcação como HTML e CSS, que são usadas para estruturar e estilizar uma página, JavaScript é uma linguagem de script que adiciona lógica e comportamento dinâmico, possibilitando interatividade com o usuário. É uma das três principais tecnologias da web, juntamente com HTML e CSS, sendo amplamente usada para melhorar a experiência do usuário, desde animações e validações de formulário até a comunicação assíncrona com servidores (AJAX).

Além de ser usado no front-end (navegador), JavaScript também é muito utilizado no back-end por meio do Node.js, que permite que JavaScript seja executado no servidor. Isso possibilita que os desenvolvedores usem uma única linguagem em toda a pilha de desenvolvimento web, facilitando a integração e manutenção de projetos.

### Histórico e Evolução
JavaScript foi criado em apenas 10 dias, em 1995, por Brendan Eich enquanto trabalhava na Netscape Communications. Originalmente chamado "Mocha", depois "LiveScript", e finalmente renomeado para "JavaScript" para aproveitar a popularidade do Java na época, apesar de não ter relação direta com ele. A primeira versão do JavaScript foi bastante limitada, sendo usada principalmente para pequenas interações em páginas web.

Com o passar dos anos, JavaScript passou por grandes atualizações e evoluiu significativamente. O ECMAScript, que é o padrão oficial do JavaScript, lançou sua primeira versão em 1997 e, desde então, introduziu diversas funcionalidades modernas como `let` e `const`, classes, `async/await`, e módulos. A versão mais revolucionária foi o ES6 (ou ECMAScript 2015), que trouxe diversas melhorias na linguagem, tornando o JavaScript mais poderoso e organizado.

Hoje, JavaScript é utilizado não apenas para desenvolver páginas web interativas, mas também para desenvolver aplicativos móveis, APIs, jogos, entre outras aplicações, graças ao vasto ecossistema de bibliotecas e frameworks como React, Angular, Vue.js, Node.js, e muitos outros.

### Como Funciona na Web
JavaScript é uma linguagem que roda no navegador do usuário, o que significa que é uma linguagem de front-end. Cada vez que um usuário acessa uma página web, o navegador carrega o JavaScript incorporado e o executa, o que permite manipular elementos do documento HTML, responder a eventos como cliques e mudanças de input, e fazer chamadas a servidores para obter ou enviar dados, tudo isso sem recarregar a página. Esse comportamento é conhecido como `cliente-side`, já que o código roda no dispositivo do usuário, e não no servidor.

JavaScript funciona em conjunto com o HTML e o CSS para criar páginas completas. O HTML fornece a estrutura da página, o CSS define a aparência visual, e o JavaScript adiciona a lógica e a interação. Por exemplo, quando você clica em um botão e algo muda na página sem recarregar, é o JavaScript que está sendo executado para realizar essa interação.

Além do uso no front-end, com o advento do Node.js, JavaScript pode ser executado também no servidor (`server-side`). Isso significa que a mesma linguagem pode ser utilizada para escrever a lógica tanto do lado do cliente quanto do servidor, simplificando o fluxo de desenvolvimento e reduzindo a necessidade de múltiplas linguagens de programação.

### Configuração do Ambiente de Desenvolvimento
Para começar a programar em JavaScript, é necessário configurar um ambiente de desenvolvimento. Existem algumas ferramentas e etapas essenciais para isso:

1. **Editor de Código**: Um editor de código-fonte ou IDE (Ambiente de Desenvolvimento Integrado) facilita muito a escrita de JavaScript. Editores populares incluem o Visual Studio Code (VS Code), Sublime Text e Atom. O VS Code é altamente recomendado devido ao suporte integrado para JavaScript, extensões úteis e depurador.

2. **Navegador**: JavaScript é executado diretamente no navegador. Os navegadores modernos, como Google Chrome, Firefox, Edge e Safari, possuem consoles de desenvolvedor integrados (geralmente acessíveis pressionando F12), onde você pode testar trechos de código JavaScript, depurar problemas e monitorar o desempenho.

3. **Node.js**: Para executar JavaScript fora do navegador, por exemplo, para construir servidores ou automatizar tarefas, o Node.js é essencial. Node.js é um runtime de JavaScript que permite executar scripts diretamente na linha de comando. Ele também inclui o npm (Node Package Manager), que facilita a instalação de pacotes e bibliotecas JavaScript.

4. **Git e GitHub**: Embora não sejam obrigatórios, ferramentas como Git (para controle de versão) e GitHub (para hospedagem de repositórios) são altamente recomendadas para gerenciar o código e colaborar com outros desenvolvedores.

5. **Instalação de Ferramentas de Build**: Em projetos modernos, podemos usar ferramentas como Webpack, Babel, ou Parcel para empacotar o código JavaScript, convertendo recursos modernos em um formato compatível com todos os navegadores e melhorando o desempenho da aplicação.

6. **Extensões e Plugins**: No editor de código, você pode instalar extensões que ajudam a aumentar a produtividade. Algumas das mais populares para JavaScript no VS Code são: Prettier (para formatação automática de código), ESLint (para garantir qualidade e estilo do código), e Debugger for Chrome (para depurar diretamente do VS Code).

Com essa configuração, você terá um ambiente adequado para desenvolver em JavaScript, tanto para projetos simples de aprendizado quanto para aplicações mais complexas e profissionais.

[Voltar para o índice](#índice)

## 2. Conceitos Básicos

### Variáveis e Tipos de Dados
JavaScript utiliza variáveis para armazenar dados. As palavras-chave principais para declarar variáveis são `let`, `const`, e `var`. Vamos ver cada uma delas:

- `let`: Usada para declarar variáveis que podem ser alteradas ao longo do tempo. Utiliza-se amplamente por sua flexibilidade e bom escopo de bloco.
- `const`: Declara uma constante, ou seja, um valor que não pode ser modificado depois de atribuir.
- `var`: Era o método mais comum de declarar variáveis antes do ES6. Seu escopo é diferente do `let` e pode levar a comportamentos inesperados, portanto deve ser usado com cuidado.

#### Exemplo de Variáveis em JavaScript
```javascript
let idade = 25; // Variável que pode ser alterada
const PI = 3.14; // Constante que não pode ser alterada
var nome = "João"; // Forma mais antiga de declarar variáveis
```

#### Explicação Detalhada do Código
- `let idade = 25;`: Aqui estamos declarando uma variável chamada `idade` com o valor `25`. Como foi declarada com `let`, podemos mudar o valor dela mais tarde.
- `const PI = 3.14;`: O `PI` é declarado com `const`, significando que seu valor é constante e não pode ser alterado após a declaração.
- `var nome = "João";`: `var` é uma forma mais antiga e menos segura de declarar variáveis. O escopo de `var` não respeita os blocos de código de maneira intuitiva.

[Voltar para o índice](#índice)

### Operadores (Aritméticos, Lógicos, Comparação)
Operadores são usados para realizar operações sobre valores e variáveis. Vamos ver alguns dos operadores principais do JavaScript:

- **Operadores Aritméticos**: +, -, *, /, % (adição, subtração, multiplicação, divisão e módulo).
- **Operadores Lógicos**: &&, ||, ! (e, ou, não).
- **Operadores de Comparação**: ==, ===, !=, !== (igual, igual estrito, diferente, diferente estrito).

#### Exemplo de Operadores em JavaScript
```javascript
let soma = 5 + 3;          // 8
let diferenca = 10 - 4;    // 6
let produto = 6 * 7;       // 42
let quociente = 20 / 4;    // 5
let resto = 10 % 3;        // 1
let ehMaior = 5 > 3;       // true
let ehIgual = 5 == "5";  // true (compara apenas valor)
let ehIgualEstrito = 5 === "5"; // false (compara valor e tipo)
```

#### Explicação Detalhada do Código
- **Aritméticos**: `5 + 3` realiza a soma e retorna `8`. Da mesma forma, `10 - 4` retorna `6`.
- **Comparação**: `5 == "5"` retorna `true` porque compara apenas o valor, enquanto `5 === "5"` retorna `false` pois compara valor e tipo (número e string).

[Voltar para o índice](#índice)

### Estruturas de Controle (if, else, switch)
As estruturas de controle são usadas para tomar decisões com base em condições.

- **if/else**: Usado para executar um bloco de código se uma condição for verdadeira, e um bloco alternativo se for falsa.
- **switch**: Utilizado para selecionar um dos muitos blocos de código a serem executados, com base em diferentes valores.

#### Exemplo de Estruturas de Controle
```javascript
let nota = 85;

if (nota >= 90) {
  console.log("Aprovado com Excelência");
} else if (nota >= 60) {
  console.log("Aprovado");
} else {
  console.log("Reprovado");
}

let diaSemana = 3;
switch (diaSemana) {
  case 1:
    console.log("Domingo");
    break;
  case 2:
    console.log("Segunda-feira");
    break;
  case 3:
    console.log("Terça-feira");
    break;
  default:
    console.log("Dia inválido");
}
```

#### Explicação Detalhada do Código
- **if/else**: A variável `nota` é usada para decidir qual mensagem imprimir. Se `nota` for maior ou igual a `90`, a mensagem é "Aprovado com Excelência".
- **switch**: Dependendo do valor de `diaSemana`, uma mensagem diferente é impressa. Isso é útil para casos em que precisamos comparar uma variável com muitos valores diferentes.

[Voltar para o índice](#índice)

### Loops (for, while, do...while)
Loops permitem executar um bloco de código repetidamente enquanto uma condição for verdadeira.

- **for**: Usado quando sabemos quantas vezes queremos repetir um bloco de código.
- **while**: Executa enquanto a condição for verdadeira.
- **do...while**: Semelhante ao `while`, mas garante que o código seja executado ao menos uma vez.

#### Exemplo de Loops
```javascript
for (let i = 0; i < 5; i++) {
  console.log("Valor de i: " + i);
}

let contador = 0;
while (contador < 3) {
  console.log("Contagem: " + contador);
  contador++;
}

do {
  console.log("Este bloco será executado pelo menos uma vez");
  contador++;
} while (contador < 5);
```

#### Explicação Detalhada do Código
- **for**: Começamos com `i = 0` e continuamos enquanto `i < 5`, incrementando `i` a cada iteração.
- **while**: `contador` é incrementado em `1` enquanto for menor que `3`.
- **do...while**: Sempre executa o bloco uma vez antes de verificar a condição.

[Voltar para o índice](#índice)

## 3. Funções
Funções em JavaScript são blocos de código que podem ser reutilizados para realizar uma tarefa específica. Elas são fundamentais para modularizar o código e facilitar a reutilização.  
[Voltar para o índice](#índice)

### Declaração e Invocação
Para declarar uma função, usamos a palavra-chave `function`, seguida do nome da função, parâmetros (se houver) e um bloco de código entre chaves.

#### Exemplo de Declaração de Função
```javascript
function saudacao() {
  console.log("Olá, mundo!");
}

saudacao(); // Invoca a função e exibe: "Olá, mundo!"
```

#### Explicação Detalhada do Código
- `function saudacao() {}`: Declara uma função chamada `saudacao` que não recebe parâmetros e apenas exibe uma mensagem no console.
- `saudacao();`: A função é invocada, ou seja, executada, e imprime "Olá, mundo!" no console.

[Voltar para o índice](#índice)

### Parâmetros e Argumentos
Parâmetros são valores que uma função espera receber quando é chamada. Esses parâmetros são usados para que a função realize uma operação específica com os dados fornecidos.

#### Exemplo de Função com Parâmetros
```javascript
function saudacaoPersonalizada(nome) {
  console.log("Olá, " + nome + "!");
}

saudacaoPersonalizada("Maria"); // Exibe: "Olá, Maria!"
saudacaoPersonalizada("Carlos"); // Exibe: "Olá, Carlos!"
```

#### Explicação Detalhada do Código
- `function saudacaoPersonalizada(nome) {}`: A função aceita um parâmetro `nome`.
- `saudacaoPersonalizada("Maria");`: A função é chamada com o argumento "Maria", e o resultado é "Olá, Maria!" impresso no console.

[Voltar para o índice](#índice)

### Funções Anônimas e de Callback
Uma função anônima é uma função sem nome, muitas vezes atribuída a uma variável. Funções de callback são passadas como argumentos para outras funções, sendo executadas após uma tarefa específica.

#### Exemplo de Função Anônima e de Callback
```javascript
let saudacao = function(nome) {
  console.log("Olá, " + nome + "!");
};

saudacao("Ana"); // Exibe: "Olá, Ana!"

function processar(valor, callback) {
  let resultado = valor * 2;
  callback(resultado);
}

processar(5, function(resultado) {
  console.log("Resultado: " + resultado); // Exibe: "Resultado: 10"
});
```

#### Explicação Detalhada do Código
- `let saudacao = function(nome) {}`: Função anônima atribuída à variável `saudacao`.
- `processar(5, function(resultado) { ... })`: Uma função de callback é passada como argumento para `processar`. Essa função será executada com o valor calculado.

[Voltar para o índice](#índice)

### Arrow Functions
Introduzidas no ES6, as arrow functions oferecem uma sintaxe mais curta para definir funções. Elas são especialmente úteis quando precisamos de funções de callback concisas.

#### Exemplo de Arrow Function
```javascript
let dobro = (n) => n * 2;
console.log(dobro(4)); // Exibe: 8

let saudacao = (nome) => {
  console.log("Olá, " + nome + "!");
};
saudacao("Paulo"); // Exibe: "Olá, Paulo!"
```

#### Explicação Detalhada do Código
- `let dobro = (n) => n * 2;`: Uma função arrow que retorna o dobro do valor de `n`.
- `let saudacao = (nome) => { ... }`: Uma função arrow que imprime uma saudação com o nome fornecido.

[Voltar para o índice](#índice)

### Escopo de Variáveis (Local e Global)
O escopo de uma variável define onde ela é acessível no código. Existem dois tipos principais de escopo em JavaScript: 

- **Global**: Variáveis declaradas fora de qualquer função possuem escopo global e podem ser acessadas de qualquer lugar do código.
- **Local**: Variáveis declaradas dentro de uma função possuem escopo local e só podem ser acessadas de dentro dessa função.

#### Exemplo de Escopo de Variáveis
```javascript
let global = "Estou no escopo global";

function exemplo() {
  let local = "Estou no escopo local";
  console.log(global); // Pode acessar a variável global
  console.log(local);  // Pode acessar a variável local
}

exemplo();
// console.log(local); // Erro: local não está definida
```

#### Explicação Detalhada do Código
- `let global = "Estou no escopo global";`: Esta variável pode ser acessada de qualquer lugar, incluindo dentro da função `exemplo()`.
- `let local = "Estou no escopo local";`: Esta variável é acessível apenas dentro da função `exemplo()`. Tentar acessá-la de fora resulta em erro.

[Voltar para o índice](#índice)

## 4. Arrays e Objetos
Arrays e objetos são estruturas fundamentais em JavaScript, permitindo o armazenamento e manipulação de coleções de dados de maneira eficiente e organizada.  
[Voltar para o índice](#índice)

### Criação e Manipulação de Arrays
Um array é uma coleção ordenada de elementos, que podem ser de qualquer tipo (números, strings, objetos, etc.). Arrays são definidos usando colchetes `[]` e seus elementos são separados por vírgulas.

#### Exemplo de Criação de Arrays
```javascript
let frutas = ["Maçã", "Banana", "Laranja"];
console.log(frutas[0]); // Exibe: "Maçã"
```

#### Explicação Detalhada do Código
- `let frutas = ["Maçã", "Banana", "Laranja"];`: Um array chamado `frutas` é criado, contendo três elementos: "Maçã", "Banana" e "Laranja".
- `frutas[0]`: Os elementos do array são indexados a partir de `0`, então `frutas[0]` retorna "Maçã".

[Voltar para o índice](#índice)

### Métodos Importantes de Arrays
JavaScript fornece diversos métodos para manipular arrays, facilitando tarefas como adicionar, remover, filtrar e transformar elementos.

- **`push()`**: Adiciona um elemento ao final do array.
- **`pop()`**: Remove o último elemento do array.
- **`shift()`**: Remove o primeiro elemento do array.
- **`unshift()`**: Adiciona um elemento no início do array.
- **`map()`**: Cria um novo array aplicando uma função a cada elemento.
- **`filter()`**: Cria um novo array contendo apenas os elementos que satisfazem uma condição.
- **`reduce()`**: Aplica uma função cumulativa aos elementos do array, resultando em um único valor.

#### Exemplo de Uso dos Métodos de Arrays
```javascript
let numeros = [1, 2, 3, 4, 5];

// Adicionar e remover elementos
numeros.push(6); // [1, 2, 3, 4, 5, 6]
numeros.pop();   // [1, 2, 3, 4, 5]

// Transformar elementos
let dobrados = numeros.map(n => n * 2); // [2, 4, 6, 8, 10]

// Filtrar elementos
let pares = numeros.filter(n => n % 2 === 0); // [2, 4]

// Reduzir elementos a um único valor
let soma = numeros.reduce((total, n) => total + n, 0); // 15
```

#### Explicação Detalhada do Código
- **`push(6)`**: Adiciona o valor `6` ao final do array `numeros`.
- **`pop()`**: Remove o último elemento do array, que é `6`.
- **`map(n => n * 2)`**: Aplica a função `n * 2` a cada elemento, retornando um novo array `dobrados`.
- **`filter(n => n % 2 === 0)`**: Filtra apenas os elementos pares, resultando no array `pares`.
- **`reduce((total, n) => total + n, 0)`**: Soma todos os elementos do array, iniciando do valor `0`.

[Voltar para o índice](#índice)

### Objetos: Propriedades e Métodos
Objetos são coleções de pares chave-valor. Eles permitem armazenar valores que podem ser de qualquer tipo, inclusive outros objetos ou arrays.

#### Exemplo de Criação de Objetos
```javascript
let pessoa = {
  nome: "Carlos",
  idade: 30,
  saudacao: function() {
    return "Olá, meu nome é " + this.nome;
  }
};

console.log(pessoa.nome); // Exibe: "Carlos"
console.log(pessoa.saudacao()); // Exibe: "Olá, meu nome é Carlos"
```

#### Explicação Detalhada do Código
- **`pessoa`**: Objeto criado com as propriedades `nome` e `idade`, e o método `saudacao()`.
- **`this.nome`**: Dentro de um método, `this` refere-se ao próprio objeto, permitindo acessar suas propriedades.

[Voltar para o índice](#índice)

### Iteração de Objetos e Arrays
Podemos usar `for...in` e `for...of` para iterar sobre objetos e arrays.

- **`for...of`**: Itera sobre os valores de um array.
- **`for...in`**: Itera sobre as chaves de um objeto.

#### Exemplo de Iteração
```javascript
let frutas = ["Maçã", "Banana", "Laranja"];
for (let fruta of frutas) {
  console.log(fruta);
}

let pessoa = { nome: "Ana", idade: 28 };
for (let chave in pessoa) {
  console.log(chave + ": " + pessoa[chave]);
}
```

#### Explicação Detalhada do Código
- **`for (let fruta of frutas)`**: Itera sobre cada elemento do array `frutas`, imprimindo seus valores.
- **`for (let chave in pessoa)`**: Itera sobre as chaves do objeto `pessoa`, imprimindo cada chave e seu valor correspondente.

[Voltar para o índice](#índice)

### JSON (JavaScript Object Notation)
JSON é um formato leve para troca de dados, muito utilizado em aplicações web para transmitir informações entre cliente e servidor. Um objeto JSON é semelhante a um objeto JavaScript, mas suas chaves precisam estar entre aspas duplas.

#### Exemplo de JSON
```javascript
// Objeto JavaScript
let objeto = {
  nome: "Carlos",
  idade: 28,
  habilidades: ["JavaScript", "HTML", "CSS"]
};

// Converter para JSON
let jsonString = JSON.stringify(objeto);
console.log(jsonString); // Exibe: '{"nome":"Carlos","idade":28,"habilidades":["JavaScript","HTML","CSS"]}'

// Converter de JSON para Objeto
let novoObjeto = JSON.parse(jsonString);
console.log(novoObjeto.nome); // Exibe: "Carlos"
```

#### Explicação Detalhada do Código
- **`JSON.stringify(objeto)`**: Converte um objeto JavaScript em uma string JSON, que pode ser enviada por rede.
- **`JSON.parse(jsonString)`**: Converte uma string JSON de volta em um objeto JavaScript.

[Voltar para o índice](#índice)

## 5. Manipulação do DOM (Document Object Model)
O DOM (Document Object Model) é uma representação da estrutura de um documento HTML ou XML na forma de uma árvore, onde cada nó representa uma parte do documento. Com JavaScript, podemos manipular dinamicamente o DOM para alterar o conteúdo, estilos e estrutura da página.  
[Voltar para o índice](#índice)

### Seleção de Elementos (getElementById, querySelector)
Para manipular o DOM, o primeiro passo é selecionar os elementos que desejamos alterar. JavaScript fornece várias funções para isso, como `getElementById`, `querySelector` e `querySelectorAll`.

- **`getElementById()`**: Seleciona um elemento pelo seu ID único.
- **`querySelector()`**: Seleciona o primeiro elemento que corresponde ao seletor CSS fornecido.
- **`querySelectorAll()`**: Seleciona todos os elementos que correspondem ao seletor CSS fornecido.

#### Exemplo de Seleção de Elementos
```javascript
// Selecionar um elemento pelo ID
let titulo = document.getElementById("titulo-principal");

// Selecionar um elemento usando um seletor CSS
let paragrafo = document.querySelector(".paragrafo");

// Selecionar todos os elementos com uma determinada classe
let listaItens = document.querySelectorAll(".item");
```

#### Explicação Detalhada do Código
- **`getElementById("titulo-principal")`**: Seleciona o elemento com o ID `titulo-principal`.
- **`querySelector(".paragrafo")`**: Seleciona o primeiro elemento com a classe `paragrafo`.
- **`querySelectorAll(".item")`**: Seleciona todos os elementos com a classe `item` e retorna uma NodeList.

[Voltar para o índice](#índice)

### Manipulação de Conteúdo e Estilos
Depois de selecionar um elemento, podemos alterar seu conteúdo ou estilo. O JavaScript fornece propriedades como `textContent`, `innerHTML` e `style` para isso.

- **`textContent`**: Altera ou obtém o conteúdo de texto de um elemento.
- **`innerHTML`**: Altera ou obtém o conteúdo HTML interno de um elemento.
- **`style`**: Permite alterar os estilos CSS diretamente a partir do JavaScript.

#### Exemplo de Manipulação de Conteúdo e Estilos
```javascript
let titulo = document.getElementById("titulo-principal");

// Alterar o texto do título
titulo.textContent = "Bem-vindo ao JavaScript";

// Alterar o conteúdo HTML de um parágrafo
let paragrafo = document.querySelector(".paragrafo");
paragrafo.innerHTML = "<strong>Conteúdo atualizado!</strong>";

// Alterar o estilo do título
titulo.style.color = "blue";
titulo.style.fontSize = "2em";
```

#### Explicação Detalhada do Código
- **`titulo.textContent = "Bem-vindo ao JavaScript"`**: Altera o conteúdo textual do elemento `titulo`.
- **`paragrafo.innerHTML = "<strong>Conteúdo atualizado!</strong>"`**: Altera o conteúdo HTML do parágrafo, adicionando um texto em negrito.
- **`titulo.style.color = "blue"`**: Altera a cor do texto do `titulo` para azul.
- **`titulo.style.fontSize = "2em"`**: Aumenta o tamanho da fonte do `titulo`.

[Voltar para o índice](#índice)

### Eventos (click, submit, mouseover)
Eventos são ações que ocorrem na página e às quais podemos responder, como cliques do usuário, envio de formulários ou movimentos do mouse. Para adicionar um evento a um elemento, usamos o método `addEventListener()`.

- **`click`**: Disparado quando o elemento é clicado.
- **`submit`**: Disparado quando um formulário é enviado.
- **`mouseover`**: Disparado quando o ponteiro do mouse passa sobre um elemento.

#### Exemplo de Manipulação de Eventos
```javascript
let botao = document.getElementById("meu-botao");

// Adicionar um evento de clique
botao.addEventListener("click", function() {
  alert("Botão clicado!");
});

// Adicionar um evento de mouseover
botao.addEventListener("mouseover", function() {
  botao.style.backgroundColor = "lightgray";
});
```

#### Explicação Detalhada do Código
- **`botao.addEventListener("click", function() { ... })`**: Adiciona um evento que exibe um alerta quando o botão é clicado.
- **`botao.addEventListener("mouseover", function() { ... })`**: Adiciona um evento que altera a cor de fundo do botão quando o mouse passa sobre ele.

[Voltar para o índice](#índice)

### Criação e Remoção de Elementos
Podemos criar novos elementos no DOM ou remover elementos existentes dinamicamente. Para isso, utilizamos métodos como `createElement()`, `appendChild()`, e `remove()`.

#### Exemplo de Criação e Remoção de Elementos
```javascript
// Criar um novo elemento
let novoParagrafo = document.createElement("p");
novoParagrafo.textContent = "Este é um novo parágrafo.";

// Adicionar o parágrafo ao corpo do documento
document.body.appendChild(novoParagrafo);

// Remover o parágrafo depois de 3 segundos
setTimeout(() => {
  novoParagrafo.remove();
}, 3000);
```

#### Explicação Detalhada do Código
- **`document.createElement("p")`**: Cria um novo elemento `<p>`.
- **`document.body.appendChild(novoParagrafo)`**: Adiciona o novo parágrafo ao final do `<body>` do documento.
- **`novoParagrafo.remove()`**: Remove o parágrafo após 3 segundos usando `setTimeout()`.

[Voltar para o índice](#índice)

### Navegação entre Elementos (parentNode, childNodes)
Podemos navegar pela árvore DOM usando propriedades como `parentNode`, `childNodes`, `firstChild`, e `lastChild`.

- **`parentNode`**: Retorna o nó pai do elemento.
- **`childNodes`**: Retorna uma lista de todos os nós filhos de um elemento.
- **`firstChild`** e **`lastChild`**: Retornam o primeiro e o último filho, respectivamente.

#### Exemplo de Navegação entre Elementos
```javascript
let lista = document.getElementById("minha-lista");

// Acessar o pai da lista
let paiDaLista = lista.parentNode;

// Acessar os filhos da lista
let filhos = lista.childNodes;
for (let filho of filhos) {
  console.log(filho.textContent);
}
```

#### Explicação Detalhada do Código
- **`lista.parentNode`**: Acessa o elemento pai de `lista`.
- **`lista.childNodes`**: Obtém todos os nós filhos da `lista` e itera sobre eles para imprimir seu conteúdo.

[Voltar para o índice](#índice)

## 6. Programação Assíncrona
A programação assíncrona em JavaScript é uma técnica que permite executar tarefas sem bloquear o fluxo principal de execução do código. Isso é especialmente útil para operações demoradas, como chamadas de rede ou leitura de arquivos, permitindo que outras partes do código sejam executadas enquanto essas operações ocorrem.  
[Voltar para o índice](#índice)

### Conceito de Assincronismo
O JavaScript é single-threaded, ou seja, executa uma tarefa por vez. Para evitar bloquear a execução enquanto aguardamos por operações longas, como chamadas de rede, utilizamos mecanismos assíncronos. Com isso, o código pode continuar sendo executado enquanto espera pela resposta de uma tarefa demorada.

[Voltar para o índice](#índice)

### Callbacks
Callbacks são funções passadas como argumento para outras funções e são chamadas quando uma operação é concluída. Callbacks foram uma das primeiras maneiras de lidar com operações assíncronas em JavaScript.

#### Exemplo de Função Callback
```javascript
function processar(valor, callback) {
  let resultado = valor * 2;
  callback(resultado);
}

function exibirResultado(resultado) {
  console.log("Resultado: " + resultado);
}

processar(5, exibirResultado); // Exibe: "Resultado: 10"
```

#### Explicação Detalhada do Código
- **`processar(valor, callback)`**: Função que recebe um valor e uma função `callback`.
- **`callback(resultado)`**: Após calcular `resultado`, a função `callback` é chamada para lidar com o resultado.
- **`processar(5, exibirResultado)`**: Chamamos `processar()` e passamos a função `exibirResultado` como callback.

[Voltar para o índice](#índice)

### Promises
Promises são objetos que representam a eventual conclusão (ou falha) de uma operação assíncrona e seu valor resultante. Elas melhoram a legibilidade do código, facilitando o encadeamento de operações assíncronas.

- **`resolve`**: Quando a operação é bem-sucedida, a `Promise` é resolvida com um valor.
- **`reject`**: Quando a operação falha, a `Promise` é rejeitada com um motivo.

#### Exemplo de Uso de Promises
```javascript
let minhaPromise = new Promise((resolve, reject) => {
  let sucesso = true;

  if (sucesso) {
    resolve("Operação bem-sucedida!");
  } else {
    reject("Falha na operação.");
  }
});

minhaPromise
  .then(resultado => {
    console.log(resultado); // Exibe: "Operação bem-sucedida!"
  })
  .catch(erro => {
    console.error(erro);
  });
```

#### Explicação Detalhada do Código
- **`new Promise((resolve, reject) => { ... })`**: Cria uma nova `Promise`.
- **`resolve("Operação bem-sucedida!")`**: A promise é resolvida com a mensagem "Operação bem-sucedida!".
- **`.then()`**: O método `.then()` é chamado quando a promise é resolvida com sucesso.
- **`.catch()`**: O método `.catch()` é chamado quando a promise é rejeitada.

[Voltar para o índice](#índice)

### Async/Await
`async/await` é uma sintaxe introduzida no ES8 que simplifica o uso de `Promises` e deixa o código mais próximo do estilo síncrono, facilitando a leitura e a manutenção.

- **`async`**: Define uma função assíncrona que sempre retorna uma `Promise`.
- **`await`**: Pausa a execução da função assíncrona até que a `Promise` seja resolvida.

#### Exemplo de Uso de Async/Await
```javascript
async function buscarDados() {
  try {
    let resposta = await fetch("https://api.exemplo.com/dados");
    let dados = await resposta.json();
    console.log(dados);
  } catch (erro) {
    console.error("Erro ao buscar dados:", erro);
  }
}

buscarDados();
```

#### Explicação Detalhada do Código
- **`async function buscarDados()`**: Declara uma função assíncrona.
- **`await fetch("https://api.exemplo.com/dados")`**: Espera pela resposta da chamada de rede antes de prosseguir.
- **`try...catch`**: Captura erros que possam ocorrer durante a execução assíncrona.

[Voltar para o índice](#índice)

### Tratamento de Erros Assíncronos
Em operações assíncronas, precisamos tratar erros corretamente. Podemos fazer isso usando `.catch()` nas Promises ou o bloco `try...catch` com `async/await`.

#### Exemplo de Tratamento de Erros Assíncronos
```javascript
// Usando Promise com .catch()
let minhaPromise = new Promise((resolve, reject) => {
  reject("Erro durante a operação");
});

minhaPromise
  .then(resultado => {
    console.log(resultado);
  })
  .catch(erro => {
    console.error("Erro capturado: ", erro); // Exibe: "Erro capturado: Erro durante a operação"
  });

// Usando async/await com try...catch
async function executar() {
  try {
    let resultado = await minhaPromise;
    console.log(resultado);
  } catch (erro) {
    console.error("Erro capturado (async/await):", erro);
  }
}

executar();
```

#### Explicação Detalhada do Código
- **`.catch()`**: Captura o erro de uma `Promise` rejeitada.
- **`try...catch` em `async`**: Envolve a chamada `await` em um bloco `try...catch` para lidar com possíveis falhas.

[Voltar para o índice](#índice)

### Fetch API e Ajax
A Fetch API é uma interface moderna que permite fazer requisições HTTP de maneira fácil e mais legível que as técnicas mais antigas, como `XMLHttpRequest`. `fetch()` retorna uma `Promise` que é resolvida com a resposta da requisição.

#### Exemplo de Uso da Fetch API
```javascript
fetch("https://api.exemplo.com/dados")
  .then(response => {
    if (!response.ok) {
      throw new Error("Erro na resposta: " + response.status);
    }
    return response.json();
  })
  .then(dados => {
    console.log(dados);
  })
  .catch(erro => {
    console.error("Erro ao fazer a requisição: ", erro);
  });
```

#### Explicação Detalhada do Código
- **`fetch("https://api.exemplo.com/dados")`**: Faz uma requisição para o URL especificado.
- **`if (!response.ok)`**: Verifica se a resposta da requisição foi bem-sucedida.
- **`response.json()`**: Converte a resposta em JSON para ser usada no código.
- **`.catch()`**: Captura e lida com qualquer erro durante o processo.

[Voltar para o índice](#índice)

## 7. Classes e Programação Orientada a Objetos
JavaScript permite a utilização de conceitos de Programação Orientada a Objetos (POO) para estruturar e organizar o código de maneira mais modular e reutilizável. A introdução das `classes` no ES6 facilitou a implementação de POO em JavaScript, permitindo a criação de objetos com propriedades e métodos.  
[Voltar para o índice](#índice)

### Conceitos Básicos de POO
Programação Orientada a Objetos é um paradigma que utiliza `objetos` e `classes` para organizar o código de forma mais eficiente e modular. Alguns dos principais conceitos de POO incluem:

- **Classes**: Moldes para criar objetos com propriedades e métodos comuns.
- **Objetos**: Instâncias de classes.
- **Herança**: Permite que uma classe derive características de outra classe.
- **Polimorfismo**: Capacidade de uma função ou método ter diferentes comportamentos.
- **Encapsulamento**: Esconde detalhes internos de uma classe e protege o estado do objeto.

[Voltar para o índice](#índice)

### Definição de Classes e Instância de Objetos
Uma `classe` é um molde a partir do qual criamos `objetos`. Podemos definir uma classe usando a palavra-chave `class`, e um objeto é criado instanciando essa classe com a palavra-chave `new`.

#### Exemplo de Definição de Classe e Instância de Objeto
```javascript
class Pessoa {
  constructor(nome, idade) {
    this.nome = nome;
    this.idade = idade;
  }

  cumprimentar() {
    console.log(`Olá, meu nome é ${this.nome} e tenho ${this.idade} anos.`);
  }
}

// Criar uma instância da classe Pessoa
let pessoa1 = new Pessoa("Carlos", 30);
pessoa1.cumprimentar(); // Exibe: "Olá, meu nome é Carlos e tenho 30 anos."
```

#### Explicação Detalhada do Código
- **`class Pessoa`**: Define uma classe `Pessoa`.
- **`constructor(nome, idade)`**: Método especial para inicializar propriedades ao criar um objeto.
- **`this.nome` e `this.idade`**: A palavra `this` refere-se à instância da classe.
- **`new Pessoa("Carlos", 30)`**: Cria uma nova instância da classe `Pessoa` com nome e idade específicos.

[Voltar para o índice](#índice)

### Herança e Polimorfismo
A `herança` permite que uma classe herde propriedades e métodos de outra, permitindo reutilizar código e criar hierarquias de classes. O `polimorfismo` ocorre quando métodos herdados podem ser sobrescritos para modificar ou estender o comportamento da classe base.

#### Exemplo de Herança e Polimorfismo
```javascript
class Animal {
  constructor(nome) {
    this.nome = nome;
  }

  emitirSom() {
    console.log("Som genérico de animal");
  }
}

class Cachorro extends Animal {
  emitirSom() {
    console.log("Latido");
  }
}

let animal = new Animal("Animal");
animal.emitirSom(); // Exibe: "Som genérico de animal"

let cachorro = new Cachorro("Rex");
cachorro.emitirSom(); // Exibe: "Latido"
```

#### Explicação Detalhada do Código
- **`class Animal`**: Classe base que possui um método `emitirSom`.
- **`class Cachorro extends Animal`**: Classe `Cachorro` herda de `Animal` e sobrescreve o método `emitirSom`.
- **`emitirSom()`**: O método `emitirSom` de `Cachorro` é um exemplo de polimorfismo, pois redefine o comportamento do método da classe base.

[Voltar para o índice](#índice)

### Encapsulamento
O encapsulamento é a prática de esconder os detalhes internos de uma classe e restringir o acesso direto a certos componentes, permitindo controlar como os dados são acessados e modificados. Em JavaScript, podemos simular o encapsulamento usando propriedades privadas e métodos getters e setters.

#### Exemplo de Encapsulamento
```javascript
class ContaBancaria {
  constructor(saldoInicial) {
    let _saldo = saldoInicial; // Variável privada

    this.depositar = function (valor) {
      if (valor > 0) {
        _saldo += valor;
      }
    };

    this.getSaldo = function () {
      return _saldo;
    };
  }
}

let conta = new ContaBancaria(1000);
conta.depositar(500);
console.log(conta.getSaldo()); // Exibe: 1500
```

#### Explicação Detalhada do Código
- **`let _saldo = saldoInicial`**: Variável `_saldo` é privada e não acessível fora da classe.
- **`this.getSaldo()`**: Método público para acessar o saldo.
- **`this.depositar(valor)`**: Método público para adicionar um valor ao saldo, desde que o valor seja maior que zero.

[Voltar para o índice](#índice)

### Métodos Estáticos e de Instância
Em JavaScript, métodos podem ser `estáticos` ou de `instância`. Métodos estáticos são chamados diretamente na classe e não podem acessar propriedades da instância. Já os métodos de instância são chamados nos objetos criados a partir da classe.

#### Exemplo de Métodos Estáticos e de Instância
```javascript
class Matematica {
  static somar(a, b) {
    return a + b;
  }

  multiplicar(a, b) {
    return a * b;
  }
}

// Método estático é chamado diretamente na classe
console.log(Matematica.somar(5, 3)); // Exibe: 8

// Método de instância precisa de um objeto
let calc = new Matematica();
console.log(calc.multiplicar(5, 3)); // Exibe: 15
```

#### Explicação Detalhada do Código
- **`static somar(a, b)`**: Método estático `somar` que pode ser chamado diretamente na classe `Matematica` sem a necessidade de criar uma instância.
- **`multiplicar(a, b)`**: Método de instância que requer um objeto da classe `Matematica` para ser chamado.

[Voltar para o índice](#índice)

