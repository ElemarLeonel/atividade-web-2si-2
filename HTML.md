# HTML

Tag `<!DOCTYPE html>`

- Indica inicio de um arquivo html.

Tag `<html></html>`

- Inidica o conteudo html de uma pagina, tudo tem que esta dentro dessa tag.

Tag `<head></head>`

- Indica onde fica as meta tags e tags de configuração do seu site.

Tag `<body></body>`

- Indica onde fica o conteúdo que vai ser renderizado pelo navegador.

Tag `<link />`

- Contém arquivos e links que o navegador vai ter que buscar para sua pagina funcionar corretamente, por exemplo:

  - `<link rel="preconnect" href="https://fonts.googleapis.com" />` <br> Busca fonte de texto para pagina do google.
  - `<link rel="stylesheet" href="styles/global.css" />` <br> Busca arquivo css do servidor para sua pagina

Tag `<div></div>`

- Tag em bloco (caixa), basica, sem estilização padrão, sem tamanho padrão, muito usada como tag de construção. Exemplo:

```html
<div>Minha div</div>
<div>
  Algum conteúdo da minha pagina.
  <div>
    Algum outro conteúdo da pagina.
    <div>Mais um.</div>
  </div>
</div>
```

Tag `<h1></h1>`...`<h6></h6>`

- Tags que indicam titulo, quando mais proximo de 1 maior e mais chamativo sera o titulo. Exemplo:

<div style="display: flex; justify-content: space-between">

```html
<h1>Titulo 1</h1>
```

<h1>Titulo 1</h1>

</div>

<div style="display: flex; justify-content: space-between">

```html
<h2>Titulo 2</h2>
```

<h2>Titulo 2</h2>
</div>

<div style="display: flex; justify-content: space-between">

```html
<h3>Titulo 3</h3>
```

<h3>Titulo 3</h3>
</div>

<div style="display: flex; justify-content: space-between">

```html
<h4>Titulo 4</h4>
```

<h4>Titulo 4</h4>
</div>

<div style="display: flex; justify-content: space-between">

```html
<h5>Titulo 5</h5>
```

<h5>Titulo 5</h5>
</div>

<div style="display: flex; justify-content: space-between">

```html
<h6>Titulo 6</h6>
```

<h6>Titulo 6</h6>
</div>

Tag `<form></form>`

- Tag especial que indica que dentro dela é um formulario para pegar informações do seu usario, podem qualquer tipo de informação. Exemplo:

```html
<form>Meu formulario...</form>
```

Tag `<input />`

- Tag que é um input de algum tipo para o usario colocar informações. Exemplo:

<div style="display: flex; justify-content: space-between">

```html
<input type="number" placeholder="10" max="100" min="0" required />
```

<input type="number"
  placeholder=10
  max=10
  min=0
  required/>

</div>
<div style="display: flex; justify-content: space-between; gap: 4%">

```html
<input type="email" placeholder="example@example.com" required />
```

<input type="email"
  placeholder="example@example.com"
  required/>

</div>
<div style="display: flex; justify-content: space-between; gap: 4%">

```html
<input type="text" placeholder="alguma coisa" required />
```

<input type="text"
  placeholder="alguma coisa"
  required/>

</div>
<div style="display: flex; justify-content: space-between; gap: 4%">

```html
<input type="text" placeholder="alguma coisa" required />
```

<input type="text"
  placeholder="alguma coisa"
  required/>

</div>
<div style="display: flex; justify-content: space-between; gap: 4%">

```html
<input type="tel" placeholder="1234-5678" required />
```

<input type="tel"
  placeholder="1234-5678"
  required/>

</div>
<div style="display: flex; justify-content: space-between; gap: 4%">

```html
<input type="color" required />
```

<input
    type="color"
    required
/>

</div>
<div style="display: flex; justify-content: space-between; gap: 4%">

```html
<input type="date" min="2000-04-15" max="2024-04-15" required />
```

<input
    type="date"
    min="2000-04-15"
    max="2024-04-15"
    required
/>

</div>
<div style="display: flex; justify-content: space-between; gap: 4%">

```html
<input type="submit" value="Enviar" />
```

<input
  type="submit"
  value="Envio"
/>

</div>

Tag `<button></button>`

- Indica um botão que faz algo que possa ser customizado com javascript. Exemplo:

<div style="display: flex; justify-content: space-between; gap: 4%">

```html
<button type="submit">Enviar!</button>
```

<button type="submit">Enviar!</button>

</div>
<div style="display: flex; justify-content: space-between; gap: 4%">

```html
<button type="reset">Limpar!</button>
```

<button type="reset">Limpar!</button>

</div>
