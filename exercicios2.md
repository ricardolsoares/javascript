---
layout: padrão
Título: "Exercícios de JavaScript - Nível Intermediário"
Descrição: "Exercícios práticos de JavaScript para nível intermediário, com foco em desenvolvimento de funcionalidades para sites. Aprenda criando scripts que podem ser aplicados diretamente em projetos reais."
---

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
   - Dica: Use o `getElementById()` para selecionar o `<div>` e `innerHTML` para alterar o texto.
2. **Crie um script que adicione um novo item a uma lista `<ul>` toda vez que um botão "Adicionar Item" for clicado.**
   - Dica: Use o método `createElement()` para criar um novo `<li>` e `appendChild()` para adicioná-lo à lista.
3. **Selecione um elemento `<img>` e altere o atributo `src` para trocar a imagem ao passar o mouse sobre ela.**
   - Dica: Use os eventos `onmouseover` e `onmouseout` para alternar o atributo `src` da imagem.
4. **Crie um contador que aumenta em 1 cada vez que um botão for pressionado, exibindo o valor atual em um elemento `<span>`.**
   - Dica: Use uma variável global para armazenar o valor do contador e `textContent` para atualizá-lo.
5. **Desenvolva um script que permita ao usuário adicionar parágrafos personalizados a uma página, usando um campo de texto e um botão.**
   - Dica: Use `value` do campo de texto e `createElement()` para criar novos parágrafos.

[Voltar ao índice](#índice)

### Eventos e Interação com o Usuário
1. **Crie um evento que modifique a cor de fundo da página toda vez que o usuário pressionar uma tecla específica.**
   - Dica: Use o evento `keydown` e altere `document.body.style.backgroundColor`.
2. **Adicione um campo de texto e um evento `input` que exiba em tempo real a quantidade de caracteres digitados.**
   - Dica: Use o evento `input` e `value.length` para contar os caracteres.
3. **Crie um menu dropdown que exibe e esconde itens ao clicar em um botão, simulando um menu responsivo.**
   - Dica: Use `classList.toggle()` para adicionar/remover uma classe que controla a visibilidade dos itens.
4. **Implemente um botão que, ao ser pressionado, mude a visibilidade de uma imagem (exibir/ocultar).**
   - Dica: Use `style.display` para alternar entre `none` e `block`.
5. **Desenvolva uma funcionalidade que permita ao usuário arrastar e soltar elementos dentro da página, alterando sua posição.**
   - Dica: Use os eventos `dragstart`, `dragover` e `drop` para implementar a funcionalidade.

[Voltar ao índice](#índice)

### Validação de Formulário
1. **Crie um formulário de login e implemente uma validação que exiba uma mensagem de erro se o campo de senha for deixado vazio.**
   - Dica: Use `if` para verificar se `value` do campo de senha está vazio, e exiba uma mensagem de erro.
2. **Adicione validação ao formulário para garantir que o campo de email contenha um valor válido antes do envio.**
   - Dica: Use uma expressão regular (regex) para validar o formato do email.
3. **Desenvolva um script que valide um formulário de contato, verificando se todos os campos obrigatórios foram preenchidos.**
   - Dica: Use `querySelectorAll()` para selecionar todos os campos e verifique se cada um deles possui valor.
4. **Crie um campo de senha e outro de confirmação de senha, garantindo que ambos os valores sejam iguais antes de enviar o formulário.**
   - Dica: Compare os valores dos dois campos e exiba uma mensagem de erro se forem diferentes.
5. **Implemente um sistema que exiba uma mensagem de "Envio bem-sucedido" após validar todos os campos corretamente.**
   - Dica: Use `preventDefault()` para evitar o envio se a validação falhar, e exiba a mensagem quando todos os campos estiverem corretos.

[Voltar ao índice](#índice)

### Manipulação de Estilos CSS
1. **Crie um botão que, ao ser pressionado, altere o estilo de todos os parágrafos da página para que tenham a cor de texto vermelha.**
   - Dica: Use `querySelectorAll()` para selecionar todos os parágrafos e altere a propriedade `color`.
2. **Desenvolva um script que, ao clicar em um elemento `<div>`, aumente sua largura em 20 pixels.**
   - Dica: Use `element.style.width` e incremente o valor em pixels.
3. **Adicione uma classe CSS a um elemento ao clicar em um botão, mudando sua aparência.**
   - Dica: Use `classList.add()` para adicionar uma classe ao elemento.
4. **Crie um sistema que mude a cor de fundo da página para uma cor aleatória cada vez que um botão for pressionado.**
   - Dica: Gere uma cor aleatória usando `Math.random()` e aplique-a ao `backgroundColor`.
5. **Implemente um botão "Modo Escuro" que troque a folha de estilo da página para um tema escuro ao ser ativado.**
   - Dica: Use `classList.toggle()` para alternar entre os temas claro e escuro.

[Voltar ao índice](#índice)

### Navegação Dinâmica
1. **Crie um script que permita navegar entre diferentes seções da página ao clicar em links, fazendo scroll suave até a seção correspondente.**
   - Dica: Use `scrollIntoView({ behavior: 'smooth' })` para implementar o scroll suave.
2. **Desenvolva um menu fixo que destaque a seção atualmente visível ao fazer scroll na página.**
   - Dica: Use `IntersectionObserver` para detectar qual seção está visível.
3. **Implemente um botão "Voltar ao Topo" que leve o usuário de volta ao início da página ao ser pressionado.**
   - Dica: Use `window.scrollTo()` com `{top: 0, behavior: 'smooth'}`.
4. **Crie um sistema de tabs onde o usuário pode alternar entre diferentes conteúdos ao clicar em diferentes abas.**
   - Dica: Use `classList.add()` e `classList.remove()` para exibir/ocultar o conteúdo de cada aba.
5. **Desenvolva um script que altere o título da aba do navegador quando o usuário muda de seção na página.**
   - Dica: Use o evento `scroll` para alterar o título com base na seção visível.

[Voltar ao índice](#índice)

## 3. Funções para Projetos Web

### Criação de Componentes Reutilizáveis
1. **Crie uma
