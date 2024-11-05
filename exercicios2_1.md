

# Exercícios de JavaScript - Nível Intermediário

Bem-vindo à página de exercícios intermediários de JavaScript! Estes exercícios têm como objetivo ajudá-lo a aplicar conceitos importantes de JavaScript em funcionalidades úteis para sites e páginas web.



> Pratique JavaScript criando scripts que simulam funcionalidades reais de sites. Esse é o próximo passo na sua jornada como desenvolvedor web.

## Índice
- [2. Conceitos Básicos para Web](#2-conceitos-básicos-para-web)
  - [Manipulação de Elementos](#manipulação-de-elementos)
  - [Eventos e Interação com o Usuário](#eventos-e-interação-com-o-usuário)
  - [Validação de Formulário](#validação-de-formulário)
  - [Manipulação de Estilos CSS](#manipulação-de-estilos-css)
  - [Navegação Dinâmica](#navegação-dinâmica)
- [3. Funções para Projetos Web](#3-funções-para-projetos-web)
  - [Criação de Componentes Reutilizáveis](#criação-de-componentes-reutilizáveis)
  - [Manipulação de Dados de Formulários](#manipulação-de-dados-de-formulários)
  - [Uso de Funções Anônimas e Callbacks](#uso-de-funções-anônimas-e-callbacks)
  - [Arrow Functions em Sites](#arrow-functions-em-sites)
  - [Escopo e Modularidade no JavaScript](#escopo-e-modularidade-no-javascript)

## 2. Conceitos Básicos para Web

### Manipulação de Elementos
1. **Crie uma página HTML com um botão que, ao ser clicado, altere o texto de um `<div>` para "Botão clicado!".**
   - Dica: Primeiro, crie um arquivo HTML e adicione um botão e um `<div>` com algum texto inicial. Depois, escreva um script JavaScript que selecione o `<div>` usando `getElementById()`. Em seguida, adicione um evento `onclick` ao botão que altere o valor de `innerHTML` do `<div>` para "Botão clicado!".
     
2. **Crie um script que adicione um novo item a uma lista `<ul>` toda vez que um botão "Adicionar Item" for clicado.**
   - Dica: Crie um arquivo HTML com uma `<ul>` vazia e um botão. Em JavaScript, use `createElement('li')` para criar um novo item da lista e `appendChild()` para adicioná-lo à `<ul>`. Utilize `addEventListener()` para adicionar o evento ao botão.
     
3. **Selecione um elemento `<img>` e altere o atributo `src` para trocar a imagem ao passar o mouse sobre ela.**
   - Dica: No HTML, adicione uma imagem com um `id`. No JavaScript, selecione a imagem usando `getElementById()`. Utilize os eventos `onmouseover` e `onmouseout` para alterar o atributo `src` da imagem, usando a função `setAttribute()`.
     
4. **Crie um contador que aumenta em 1 cada vez que um botão for pressionado, exibindo o valor atual em um elemento `<span>`.**
   - Dica: Adicione um botão e um `<span>` ao HTML. No JavaScript, crie uma variável para armazenar o valor do contador. Use `addEventListener()` no botão e incremente a variável toda vez que o botão for clicado. Atualize o valor do `<span>` usando `textContent`.
     
5. **Desenvolva um script que permita ao usuário adicionar parágrafos personalizados a uma página, usando um campo de texto e um botão.**
   - Dica: Crie um campo de entrada (`<input>`) e um botão no HTML. No JavaScript, use `value` do campo de texto para obter o texto digitado e `createElement('p')` para criar um novo parágrafo. Adicione o parágrafo à página com `appendChild()`.

[Voltar ao índice](#índice)

### Eventos e Interação com o Usuário
1. **Crie um evento que modifique a cor de fundo da página toda vez que o usuário pressionar uma tecla específica.**
   - Dica: Use o evento `keydown` em `document`. Verifique qual tecla foi pressionada usando `event.key`, e altere `document.body.style.backgroundColor` para uma cor de sua escolha.
     
2. **Adicione um campo de texto e um evento `input` que exiba em tempo real a quantidade de caracteres digitados.**
   - Dica: Adicione um campo `<input>` e um elemento `<span>` para mostrar a contagem. No JavaScript, adicione um evento `input` ao campo de texto que atualize o valor do `<span>` usando `value.length` do campo.
     
3. **Crie um menu dropdown que exibe e esconde itens ao clicar em um botão, simulando um menu responsivo.**
   - Dica: Use um `<div>` para representar o menu e um botão para ativá-lo. No JavaScript, use `classList.toggle()` para alternar uma classe que define a visibilidade do menu. No CSS, defina essa classe para exibir ou ocultar o menu.
     
4. **Implemente um botão que, ao ser pressionado, mude a visibilidade de uma imagem (exibir/ocultar).**
   - Dica: Use um `<img>` com um `id` e um botão. No JavaScript, use `getElementById()` para selecionar a imagem e altere `style.display` entre `none` e `block` ao clicar no botão.
     
5. **Desenvolva uma funcionalidade que permita ao usuário arrastar e soltar elementos dentro da página, alterando sua posição.**
   - Dica: Adicione a propriedade `draggable="true"` ao elemento. Use os eventos `dragstart`, `dragover` e `drop` no JavaScript para controlar o movimento dos elementos, e `event.preventDefault()` no evento `dragover` para permitir o drop.

[Voltar ao índice](#índice)

### Validação de Formulário
1. **Crie um formulário de login e implemente uma validação que exiba uma mensagem de erro se o campo de senha for deixado vazio.**
   - Dica: Adicione um formulário com campos `<input>` de email e senha. No JavaScript, adicione um evento `submit` ao formulário e use `preventDefault()` para impedir o envio se o campo de senha estiver vazio. Exiba a mensagem de erro usando `innerHTML`.
     
2. **Adicione validação ao formulário para garantir que o campo de email contenha um valor válido antes do envio.**
   - Dica: Use uma expressão regular (regex) para validar o valor do campo de email. No JavaScript, verifique se o valor corresponde ao formato de email (`test()`) antes de permitir o envio do formulário.
     
3. **Desenvolva um script que valide um formulário de contato, verificando se todos os campos obrigatórios foram preenchidos.**
   - Dica: Use `querySelectorAll()` para selecionar todos os campos obrigatórios e um loop para verificar se cada campo possui valor (`value`). Se algum estiver vazio, exiba uma mensagem de erro e evite o envio com `preventDefault()`.
     
4. **Crie um campo de senha e outro de confirmação de senha, garantindo que ambos os valores sejam iguais antes de enviar o formulário.**
   - Dica: Adicione dois campos de senha e no evento `submit` do formulário, compare os valores dos dois campos. Se forem diferentes, mostre uma mensagem de erro.
     
5. **Implemente um sistema que exiba uma mensagem de "Envio bem-sucedido" após validar todos os campos corretamente.**
   - Dica: Após validar todos os campos, use `alert()` ou exiba uma mensagem no HTML usando `innerHTML` para indicar o sucesso.

[Voltar ao índice](#índice)

### Manipulação de Estilos CSS
1. **Crie um botão que, ao ser pressionado, altere o estilo de todos os parágrafos da página para que tenham a cor de texto vermelha.**
   - Dica: Use `querySelectorAll('p')` para selecionar todos os parágrafos e um loop `forEach()` para alterar a propriedade `style.color` para `red`.
     
2. **Desenvolva um script que, ao clicar em um elemento `<div>`, aumente sua largura em 20 pixels.**
   - Dica: Use `element.style.width` e incremente o valor em pixels cada vez que o elemento for clicado. Inicialize o valor da largura, se necessário.
     
3. **Adicione uma classe CSS a um elemento ao clicar em um botão, mudando sua aparência.**
   - Dica: Crie uma classe CSS no arquivo de estilo. No JavaScript, use `classList.add()` para adicionar essa classe ao elemento ao clicar no botão.
     
4. **Crie um sistema que mude a cor de fundo da página para uma cor aleatória cada vez que um botão for pressionado.**
   - Dica: Gere valores aleatórios para `rgb()` usando `Math.random()` e aplique esses valores a `document.body.style.backgroundColor`.
5. **Implemente um botão "Modo Escuro" que troque a folha de estilo da página para um tema escuro ao ser ativado.**
      - Dica: Use `classList.toggle()` para alternar entre uma classe que define o estilo do modo escuro e o modo padrão.
        

[Voltar ao índice](#índice)

### Navegação Dinâmica
1. **Crie um script que permita navegar entre diferentes seções da página ao clicar em links, fazendo scroll suave até a seção correspondente.**
   - Dica: Adicione `id` às seções da página e `href` aos links apontando para esses `id`s. No JavaScript, use `scrollIntoView({ behavior: 'smooth' })` para implementar o scroll suave.
     
2. **Desenvolva um menu fixo que destaque a seção atualmente visível ao fazer scroll na página.**
   - Dica: Use `IntersectionObserver` para detectar qual seção está visível e adicione uma classe de destaque ao link correspondente no menu.
     
3. **Implemente um botão "Voltar ao Topo" que leve o usuário de volta ao início da página ao ser pressionado.**
   - Dica: Use `window.scrollTo()` com `{top: 0, behavior: 'smooth'}` para fazer o scroll suave até o topo.
     
5. **Crie um sistema de tabs onde o usuário pode alternar entre diferentes conteúdos ao clicar em diferentes abas.**
   - Dica: Adicione um conjunto de botões para as abas e divs correspondentes ao conteúdo. Use `classList.add()` e `classList.remove()` para mostrar/esconder o conteúdo conforme a aba selecionada.
     
6. **Desenvolva um script que altere o título da aba do navegador quando o usuário muda de seção na página.**
   - Dica: Use o evento `scroll` e `document.title` para alterar o título com base na seção visível.

[Voltar ao índice](#índice)

## 3. Funções para Projetos Web

### Criação de Componentes Reutilizáveis
1. **Crie uma função que gere um card de produto com nome, preço e botão de "Comprar", e adicione esse card à página toda vez que for chamado.**
   
   - Dica: Crie um modelo de card em HTML e transforme-o em uma função JavaScript que receba parâmetros como `nome` e `preço`. Use `createElement()` para gerar os elementos e `appendChild()` para adicionar ao DOM. Crie também um botão "Comprar" que dispare um alerta com a mensagem "Produto adicionado ao carrinho!".
     
3. **Desenvolva uma função que crie uma barra de progresso e a adicione ao documento, podendo ser utilizada em diferentes partes do site.**
   - Dica: Crie uma função JavaScript que gere um elemento `<div>` com classes apropriadas para representar a barra de progresso. Adicione atributos para definir o valor da barra. Use `style.width` para controlar o progresso, e a função pode ser chamada várias vezes para reutilização em locais diferentes.
     
4. **Crie uma função que gere botões de compartilhamento para redes sociais, e adicione esses botões automaticamente ao final de artigos.**
   - Dica: Use `createElement()` para criar botões com ícones de redes sociais (Facebook, Twitter, LinkedIn). A função deve selecionar o artigo por classe ou `id` e anexar os botões de compartilhamento usando `appendChild()`.
     
5. **Implemente uma função que crie uma janela modal para exibir informações detalhadas sobre um item quando solicitado.**
   - Dica: Crie uma função que adicione uma `<div>` como modal ao corpo do documento. Inclua um botão de fechar que remova o modal do DOM. Utilize `classList.add()` para adicionar estilos específicos que façam o modal ser exibido e `classList.remove()` para ocultá-lo.
     
6. **Crie uma função que gere automaticamente links de navegação com base em um array de seções.**
   - Dica: Crie um array contendo os nomes das seções e uma função que crie elementos `<a>` para cada seção, apontando para seus respectivos `id`s. Use `appendChild()` para adicionar os links a um menu de navegação.

[Voltar ao índice](#índice)

### Manipulação de Dados de Formulários
1. **Crie uma função que colete dados de um formulário de registro e armazene-os em um objeto JavaScript.**
   - Dica: Crie um formulário com campos como `nome`, `email`, `senha`. No JavaScript, selecione cada campo usando `getElementById()` ou `querySelector()`, e crie um objeto para armazenar os valores de cada campo ao enviar o formulário.
     
2. **Desenvolva uma função que receba dados de um formulário de contato e envie esses dados usando uma requisição `fetch` simulada.**
   - Dica: Crie um formulário de contato e, no evento `submit`, use a função `fetch()` para enviar os dados (simuladamente). Use `preventDefault()` para evitar o comportamento padrão do formulário e `JSON.stringify()` para converter os dados do formulário antes de enviá-los.
     
3. **Crie uma função que limpe todos os campos de um formulário ao ser chamada, usando JavaScript.**
   - Dica: Selecione todos os campos do formulário usando `querySelectorAll()` e itere sobre cada campo definindo seu valor como vazio (`campo.value = ''`).
     
4. **Implemente uma função que preencha automaticamente um formulário com dados fictícios, útil para testes de validação.**
   - Dica: Crie uma função que selecione os campos do formulário e atribua valores fictícios (ex.: `nome.value = 'John Doe'`). Use um botão de "Preencher automaticamente" para acionar a função.
     
5. **Crie uma função que verifique se os dados de um campo de senha atendem a critérios específicos de segurança (mínimo de caracteres, símbolos, etc.).**
   - Dica: Use uma função que receba o valor do campo de senha e utilize condições (`if`) para verificar critérios como comprimento mínimo, inclusão de símbolos, letras maiúsculas, etc. Mostre mensagens de feedback ao usuário.

[Voltar ao índice](#índice)

### Uso de Funções Anônimas e Callbacks
1. **Crie um evento de clique em um botão que utilize uma função anônima para mudar o conteúdo de um elemento `<p>`.**
   - Dica: Use `addEventListener('click', function() { ... })` para associar a função anônima ao evento de clique no botão. Altere o conteúdo do `<p>` usando `textContent`.
     
2. **Implemente um sistema de contagem regressiva usando `setInterval` e uma função anônima como callback para atualizar o valor na página.**
   - Dica: Use `setInterval()` para criar a contagem regressiva, atualizando o valor em um elemento HTML a cada segundo. Use `clearInterval()` para parar a contagem ao atingir zero.
     
3. **Crie uma função `executarDepois` que receba uma callback e um tempo, e execute a callback após o tempo definido usando `setTimeout`.**
   - Dica: Crie uma função que receba como parâmetros outra função (callback) e um valor de tempo. Use `setTimeout(callback, tempo)` para chamar a função depois do tempo determinado.
     
4. **Desenvolva um sistema que simule a verificação de disponibilidade de um item, usando `setTimeout` com uma função de callback para exibir o resultado.**
   - Dica: Use `setTimeout()` para simular uma requisição de verificação. Passe uma função de callback para ser chamada após o tempo, que exibirá a mensagem "Item disponível" ou "Item não disponível".
     
5. **Crie uma lista de tarefas e use uma função de callback para marcar uma tarefa como concluída ao clicar sobre ela.**
   - Dica: Crie uma lista de tarefas (`<ul>`). No JavaScript, adicione um evento `click` a cada `<li>` que chame uma função de callback para adicionar uma classe de "concluída", alterando o estilo da tarefa.

[Voltar ao índice](#índice)

### Arrow Functions em Sites
1. **Reescreva uma função que altera o estilo de um elemento para usar Arrow Function.**
   - Dica: Se você tiver uma função tradicional como `function mudarCor() { ... }`, reescreva-a como uma Arrow Function: `const mudarCor = () => { ... }`.
     
2. **Crie um script que utiliza Arrow Functions para manipular elementos de um array e exibi-los em um elemento `<div>`.**
   - Dica: Use o método `map()` com uma Arrow Function para manipular os valores de um array e `innerHTML` para exibir o resultado em um `<div>`.
     
3. **Desenvolva uma Arrow Function que receba dois números e retorne sua multiplicação, e use-a para calcular valores em um formulário.**
   - Dica: Crie uma Arrow Function `const multiplicar = (a, b) => a * b;`. Use essa função em um evento de formulário para calcular valores e exibir o resultado.
     
4. **Crie um evento que, ao ser disparado, use uma Arrow Function para exibir uma mensagem no console.**
   - Dica: Adicione um `addEventListener()` a um botão, passando uma Arrow Function como o segundo argumento, que exibirá uma mensagem usando `console.log()`.
     
5. **Use Arrow Functions com o método `map()` para formatar uma lista de nomes, deixando todos os nomes em maiúsculas e exibindo na página.**
   - Dica: Crie um array de nomes e use `map(name => name.toUpperCase())` para criar um novo array com os nomes formatados. Exiba o resultado usando `innerHTML`.

[Voltar ao índice](#índice)

### Escopo e Modularidade no JavaScript
1. **Crie um script onde uma função local modifique variáveis globais e observe o comportamento.**
   - Dica: Declare uma variável global fora da função. Dentro da função, modifique o valor dessa variável e observe como o valor é atualizado globalmente.
     
2. **Desenvolva um módulo que contenha funções para manipulação de DOM e importe-as em outro script usando ES6 modules.**
   - Dica: Crie um arquivo `domUtils.js` com funções como `alterarTexto(id, texto)`. No arquivo principal, importe essas funções usando `import { alterarTexto } from './domUtils.js'`.
     
3. **Crie um exemplo que utilize o escopo de bloco com `let` e `const` dentro de uma função, observando o comportamento dessas variáveis.**
   - Dica: Dentro de uma função, crie blocos (`if`, `for`) que declarem variáveis usando `let` e `const`. Teste o acesso às variáveis fora do bloco para ver as restrições de escopo.
     
4. **Organize suas funções em módulos diferentes para separar a lógica de manipulação de formulário, lógica de validação e manipulação de estilos.**
   - Dica: Crie três arquivos separados: `formUtils.js`, `validateUtils.js`, `styleUtils.js`. Em cada módulo, agrupe funções relacionadas. Importe os módulos conforme necessário no arquivo principal.
     
5. **Desenvolva um script que utilize IIFE (Immediately Invoked Function Expression) para proteger o escopo das variáveis de um determinado bloco.**
   - Dica: Use `(function() { ... })();` para criar um escopo fechado, evitando que variáveis dentro da função vazem para o escopo global.

[Voltar ao índice](#índice)
