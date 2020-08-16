# Introdução a HTML (Introduction to HTML)

* HTML ou HyperText Markup Language no inglês, que significa Linguagem de Marcação de Hipertexto. Nada mais é do que uma linguagem usada para marcar texto... ÓBVIO né?(HTML or HyperText Markup Language, means that is a language to markup text that is so obvious right? )

* Com o HTML é possível criar textos e links para outras páginas, sendo eles dentro do próprio projeto ou fora.(With HTML is possible to create text and links to other pages inside your project or outside. )

## Estrutura de um HTML

* Abaixo está a estrutura básica de toda página `html`.(The box bellow there are the basics of a `html` page.)

```html
<!DOCTYPE html>
<html>
    <head>
        <meta/>
        <title>Título(Title)</title>
    </head>
    <body></body>
</html>
```

* `<!DOCTYPE html>` - Tag utilizada uma vez somente, sempre no início do documento para dizer ao browser que o conteúdo abaixo é um `HTML`.(We just use to initialize the document and tell to the browser that is a ``HTML`` page.)

* `<html>` - Tag raiz, dentro dele ou a partir dele serão organizados todas as outras tag.(Root Tag, inside of it goes the role page.)

* `<head>` - Tag destinada a abrigar as configurações/informações da página ou documento.(These tag is  used to setup some configurations' page)

* `<title>` - Tag que abriga o nome do documento(página ou aba). Deve ser utilizada somente dentro da tag `<head>`.(Here goes the name of the document. It must be used inside the ``head`` tag.)

* `<meta>` - Tag que define qualquer informação de metadado.(Tag especify configuration of the page.)

* `<body>` - Tag que possui todo o conteúdo do documento. IMPORTANTE só é permitido um `<body>` por página.(Inside these tag is all the content of the pag. IMPORTANT just one ``body`` tag is allowed on the pag.)

## Primeira página(First Page)

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Primeiro site(Fist website)</title>
    </head>
    <body>
        <h1>Meu primeiro site(My first Website)</h1>
        <p>Esse é meu primeiro parágrafo do meu site.(these is my first )</p>
        <a href='https://google.com'>Esse é meu primeiro link(My first link)</a>
    </body>
</html>
```

### Função de cada Tag(Explaining tags)

* `<meta>` 

    `charset` - Define o tipo de caracteres usado no documento. O mais comum é o `UTF-8`.(Setting-up the type of characters in the document.The most commun is `UTF-8`)

    `name` - Define qual configuração será feita em `content`. No caso de `viewport` define a área de exibição do documento.(Define which configurations will be made on `content`. In these case of ``viewport`` define the area of exhibition of the document.)

    `content` - Contém a configuração definida no `name`. No caso do `width=device-width, initial-scale=1.0` define a largura em pixel igual a janela e a relacão entre a lagura do dispositivo e a janela.(It has the configuration defined on `name`. In these case,`width=device-width, initial-scale=1.0`define: with on pixel equals the window and the relations between the device and the window.)

* `<h1>` - A tag `<h1>` é uma das posibilidades do cabeçalho de seção. O cabeçalho vai do `<h1>` até o `<h6>`, sendo o `<h1>` mais importante e o `<h6>` o menos importante. Eles variam também no tamanho sendo `<h1>` o maior e o `<h6>` o menor.(`h1` is a section heading. The heading has other options and here they are ``<h1>``,`<h2>`,`<h3>`,`<h4>`,`<h5>`,`<h6>`. the h1 tag is the bigger, the more important and the h6 is the smaller, the less important.)

* `<p>` - Representa um parágrafo, uma porção do texto que tem um recuo (indentação).(Thes that is a paragraph, a piece of text with a indentation.)

* `<a>` - Tag âncora, usando a propriedade `href` é possivel criar uma ligação com outras páginas ou até mesmo partes de uma página.(Anchor tag, it is used to make a link between another pages on the internet or on your project.)