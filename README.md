# Dojo - Páginas Web

<img width="100px" src="https://user-images.githubusercontent.com/27368585/68813713-6d106800-0655-11ea-81ac-f9f66e9eb63d.png" />

<img width="100px" src="https://user-images.githubusercontent.com/27368585/68813714-6d106800-0655-11ea-9a3d-9ef52fa29dac.png" />

<img width="100px" src="https://user-images.githubusercontent.com/27368585/68813737-84e7ec00-0655-11ea-9736-9b534ac189ab.jpg" />

## O que é uma página web?

Simplesmente um arquivo HTML 

### De onde vem?

Podemos acessar o arquivo diretamente, porém isso limita-nos a fazer chamadas apenas em seu escopo e não permite chamadas assíncronas, como módulos ES6.

Podemos criar um servidor HTTP local para simular a internet.

Na internet vêm de um servidor HTTP, através de sua porta 80. Sem me aprofundar muito (por que não estudei isso) o servidor tem um software que cria sockets...

### O que é o protocolo HTTP?

### O que vêm na primeira requisição?

Um arquivo HTML. HTML é uma linguagem de marcação interpretada pelo navegador.

### Navegador

O que ele faz com esse textão?

### O que são os assets?

JS, CSS, imgs, json.

## Renderização

### Lado do servidor

### Lado do cliente

## Navegação

### MPA

Como vamos para próxima página?
Como era um formulário?

### SPA

`e.preventDefault()`
ajax
`history.pushState`

## Transpiladores

- browsers defasados
- minificar
- organizar o código

### HTML

**Limitações do HTML:**

Um arquivo corresponde uma página, então sem um transpilador teríamos que manipular um arquivo gigante.

Como o HTML não é uma linguagem de programação não podemos utilizar lógicas nele, como "laços", "condicionais", "funções"...

O HTML é estático, se queremos um conteúdo diferente precisamos renderizar outro.

pug, jsp...

### CSS

Aninhamento.

Código compatível com o navegador. Alguns navegadores abandonados ou atrasado não implementaram o suporte as novidades do CSS, por exemplo:

- variáveis CSS: não suportado no IE
- `text-size-adjust`: precisar do prefixo `-webkit-` em algum Chrome não atualizado

Gerar um bundle para logo o usuário ter todo o CSS disponível.

sass, stylus, less, postCSS

### JS

Cada evolução do JavaScript é uma versão do ECMAScript e o navegador deve atualizar-se para suportar.

[W3Schools - Browser support for ES](https://www.w3schools.com/js/js_versions.asp)
[Can I Use](https://caniuse.com/#feat=es6-module)

Babel, Typescript, webpack, npm


