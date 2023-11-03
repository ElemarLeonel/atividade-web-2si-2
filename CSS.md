# Sobre o CSS

## O que é CSS?

CSS (Cascading Style Sheets) é uma forma de estilizar elementos escritos pelo HTML. Foi desenvolvido em 1996 pela empresa W3C.

Alguns dos motivos do porque usar CSS:

- Separação de conteúdo e apresentação;
- Consistência visual;
- Facilidade de personalização.

## Anatomia de um comando CSS

Um comando básico é composto por seletor e declarações, que contém propriedade e valor.

```css
seletor {
  propriedade: valor;
}
```

Então, se quero estilizar, por exemplo, um elemento <p> com a cor do texto azul, podemos fazer a seguinte declaração:

## Cores

Os formatos de cores mais conhecidos popularmente são:

- Hexadecimal (#000000)
- RGB (Red, Green, Blue) ou RGBA (Red, Green, Blue, Opacity)

## Elementos básicos do CSS

Abaixo podemos citar alguns dos elementos básicos que utilizamos para referenciar os nossos elementos.

Podemos referenciar por meio de:

- Tags HTML
  - Body
  - H1, H2, H3...
  - p
- Classes
  - As classes geralmente são criadas para representar mais de um elemento idêntico. Geralmente são utilizadas antecendo com "." antes.
  - Exemplos: .item, .header, .nav.
- ID's
  - Um ID geralmente é representado por algo único na página. Utilizamos "#" para referenciar um ID.
    Exemplos: #button, #text, #icon.

## Variáveis Root

São variáveis CSS que utilizamos para atribuirmos valores específicos. Utilizamos para definirmos uma propriedade personalizada, podendo ser referenciada em varios locais e facilitando a manutenção.

Elas são declaradas dentro do pseudo-classe :root da seguinte forma:

```css
:root {
  --variavel-root: valor;
}
```

## CSS Reset

É uma técnica simples com o intuito de forçar todos os navegadores a terem o mesmo comportamento. Utilizamos algumas propriedades específicas para isso. Para essa aula, vamos utilizar uma forma simples de aplicar esse conceito.

```css
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: "Roboto", sans-serif;
}
```

Tem um padrão de CSS Reset feito por Eric Meyer, que é um dos mais utilizados atualmente.
[CSS Reset](https://meyerweb.com/eric/tools/css/reset/)

## Pseudoclasses

É uma palavra-chave adicionada aos seletores que especifica um estado especial do elemento selecionado.

Um dos pseudoseletores mais conhecidos é o hover, que estiliza com as propriedades ao passar o mouse.

```css
/* Qualquer botão sobre o qual o ponteiro do usuário esteja passando sobre */
button:hover {
  color: blue;
}
```

Você pode ver mais sobre pseudoclasses, clicando no link abaixo:

[Pseudoseletores CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Pseudo-classes)
