### Variáveis e Tipos de Dados
1. Crie uma variável `nome` usando `let` e atribua o seu nome. Em seguida, crie uma constante `idade` com o valor da sua idade e imprima ambas no console.
2. Declare uma variável `altura` com valor decimal e use `typeof` para verificar o tipo de dado dela. Exiba o resultado no console.
3. Crie uma variável `isEstudante` e atribua `true` ou `false` dependendo do seu status. Imprima o valor e o tipo dessa variável.
4. Crie um script que receba uma string numérica e a converta em número usando `Number()`. Depois, multiplique esse número por 10 e exiba o resultado.
5. Declare uma constante que armazene o valor de `PI` e crie um cálculo para obter a área de um círculo usando essa constante.
### Operadores
1. Declare duas variáveis `a` e `b` com valores numéricos e imprima o resultado das operações aritméticas (adição, subtração, multiplicação, divisão e módulo) entre elas.
2. Crie duas variáveis `x` e `y` e use operadores de comparação para verificar se são iguais (`==`) e se são estritamente iguais (`===`). Imprima os resultados.
3. Crie um script que defina duas condições booleanas e use os operadores lógicos `&&` e `||` para avaliar se a pessoa tem autorização para acessar um sistema.
4. Defina uma variável `nota` e use um operador ternário para determinar se o aluno foi aprovado ou reprovado (considerando `nota >= 6`).
5. Crie duas variáveis `idade1` e `idade2` e use o operador de comparação para verificar qual é a maior. Imprima o resultado.

### Estruturas de Controle
1. Crie um script que verifique se um número armazenado na variável `numero` é positivo, negativo ou zero, usando uma estrutura `if...else`.
2. Declare uma variável `nota` e use `if...else if...else` para imprimir se o aluno foi `Aprovado`, `Recuperação`, ou `Reprovado` com base no valor.
3. Crie um `switch` que verifique a variável `diaSemana` e imprima o nome do dia da semana (de `1` a `7`).
4. Crie um script que verifique se uma pessoa pode dirigir (idade >= 18 e possui carteira de motorista). Imprima `Pode dirigir` ou `Não pode dirigir`.
5. Declare uma variável `mes` e use `switch` para retornar quantos dias tem o mês correspondente.

### Loops
1. Crie um loop `for` que imprima todos os números de `1` a `20`.
2. Crie um loop `while` que exiba os números de `10` a `1` em ordem decrescente.
3. Crie um loop `do...while` que execute enquanto uma variável `contador` for menor que `5` e imprima o valor do `contador`.
4. Crie um array de frutas e use um loop `for...of` para imprimir cada fruta no console.
5. Crie um array de números e use um loop `for` para calcular a soma de todos os elementos e exiba o resultado.

## 3. Funções

### Declaração e Invocação
1. Crie uma função `saudacao()` que imprima `Olá, seja bem-vindo!` no console e invoque a função.
2. Declare uma função `soma()` que receba dois números como parâmetros e retorne a soma deles. Invoque a função passando valores diferentes.
3. Crie uma função `mostrarIdade()` que receba uma idade como parâmetro e imprima uma mensagem com a idade no console.
4. Defina uma função `parOuImpar()` que receba um número como argumento e retorne `par` ou `ímpar` dependendo do valor.
5. Crie uma função `calcularMedia()` que receba três números como parâmetros e retorne a média deles.

### Parâmetros e Argumentos
1. Crie uma função `calcularAreaRetangulo()` que receba dois parâmetros `largura` e `altura` e retorne a área do retângulo.
2. Defina uma função que receba um nome e um sobrenome e retorne o nome completo.
3. Crie uma função que receba um valor em graus Celsius e retorne o equivalente em Fahrenheit.
4. Crie uma função que receba um número e retorne o seu fatorial.
5. Defina uma função `verificarMaiorNumero()` que receba três números e retorne o maior entre eles.

### Funções Anônimas e de Callback
1. Declare uma função anônima e atribua a uma variável chamada `saudacao`. Use essa variável para invocar a função.
2. Crie uma função `processar()` que receba um valor e uma função como callback. O callback deve dobrar o valor e imprimir no console.
3. Utilize uma função `forEach()` em um array de números para imprimir cada número usando uma função de callback.
4. Crie uma função que utilize `setTimeout()` para imprimir uma mensagem após 2 segundos. Passe uma função de callback para realizar essa tarefa.
5. Crie uma função `calcular()` que receba dois números e uma função de callback para realizar a operação matemática desejada.

### Arrow Functions
1. Crie uma função `somar` como Arrow Function que receba dois números e retorne a soma deles.
2. Defina uma Arrow Function que receba uma string e retorne a quantidade de caracteres dessa string.
3. Crie um array de números e use o método `map()` com uma Arrow Function para dobrar os valores do array.
4. Crie uma Arrow Function que receba uma string e retorne essa string em letras maiúsculas.
5. Utilize uma Arrow Function como argumento em uma função `filter()` para filtrar apenas números pares em um array.

### Escopo de Variáveis
1. Crie uma variável global chamada `mensagem` e uma função que declare uma variável local com o mesmo nome. Verifique o que acontece com o valor dentro e fora da função.
2. Declare uma função que tenha uma variável `let` dentro de um bloco `if` e tente acessá-la fora do bloco. O que acontece?
3. Crie um loop `for` que declare uma variável `let` e tente acessar a variável fora do loop. Verifique se é possível.
4. Defina uma função que tenha uma variável local e, fora dela, uma variável global com o mesmo nome. Teste como o JavaScript trata esses valores.
5. Crie um exemplo que mostre a diferença entre `var`, `let` e `const` dentro de uma função e fora dela.

[Voltar para o índice](#índice)
