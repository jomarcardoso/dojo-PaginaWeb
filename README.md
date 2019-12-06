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

É a forma do cliente se comunicar com o servidor.

#### Métodos

GET, HEAD, POST, PUT, DELETE, TRACE, OPTIONS e CONNECT

#### Códigos de estado

200, 404, 503...

### O que vêm na primeira requisição?

Um arquivo HTML. HTML é uma linguagem de marcação interpretada pelo navegador.

### Navegador

O que ele faz com esse textão? Assim como os destacadores de sintaxe e as linguagens de programação fazem, o navegador interpreta o que veio.

```html
<html>
  <head>
    <title>Olá mundo</title>
  </head>
  <body>
    <h1 id="title">Olá mundo</h1>
  </body>
</html>
```

Depois ele começa a "pedir" pelos conteúdo referenciados, os "assets".

```
<img src="img.jpg" />
<script src="main.js"></script>
<link rel="stylesheet" type="text/css" href="main.css">
```

## Assets?

Arquivos estáticos normalmente vindos de uma CDN. No navegador os assets são buscador por via HTTP pelo método GET e esse método o navegador faz cache.

JS, CSS, imgs.

### Servidor e CDN

### Cache

Cache não acontece com marcação, apenas com assets.

### CORS

Protege o usuário e protege o servidor.

## Renderização

Após o navegador interpretar o conteúdo HTML, este será colocado na tela, após isso conforme chegam os arquivos estáticos a página vai mudando. Alguns navegadores optam por segurar a renderização até a chegada do CSS.

Nessa etapa muitas técnicas são importantes para a melhor experiência do usuário, entre elas:

- evitar saltos de renderização
- placeholders
- renderização estática
- renderização do lado do servidor
- estilo de primeira quebra

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


