# Introdução a HTML

* HTML ou HyperText Markup Language no inglês, que significa Linguagem de Marcação de Hipertexto. Nada mais é do que uma linguagem usada para marcar texto... ÓBVIO né?

* Com o HTML é possível criar textos e links para outras páginas, sendo eles dentro do próprio projeto ou fora.

## Estrutura de um HTML

* Abaixo está a estrutura básica de toda página `html`.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta/>
        <title>Título</title>
    </head>
    <body></body>
</html>
```

* `<!DOCTYPE html>` - Tag utilizada uma vez somente, sempre no início do documento para dizer ao browser que o conteúdo abaixo é um `HTML`.

* `<html>` - Tag raiz, dentro dele ou a partir dele serão organizados todas as outras tag.

* `<head>` - Tag destinada a abrigar as configurações/informações da página ou documento.

* `<body>` - Tag que possui todo o conteúdo do documento. IMPORTANTE só é permitido um `<body>` por página.

* `<title>` - Tag que abriga o nome do documento(página ou aba). Deve ser utilizada somente dentro da tag `<head>`.

* `<meta>` - Tag que define qualquer informação de metadado.

## Primeira página

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Primeiro site</title>
    </head>
    <body>
        <h1>Meu primeiro site</h1>
        <p>Esse é meu primeiro parágrafo do meu site.</p>
        <a href='https://google.com'>Esse é meu primeiro link</a>
    </body>
</html>
```

### Função de cada Tag

* `<meta>` 

    `charset` - Define o tipo de caracteres usado no documento. O mais comum é o `UTF-8`.

    `name` - Define qual configuração será feita em `content`. No caso de `viewport` define a área de exibição do documento.

    `content` - Contém a configuração definida no `name`. No caso do `width=device-width, initial-scale=1.0` define a largura em pixel igual a janela e a relacão entre a lagura do dispositivo e a janela.

* `<h1>` - A tag `<h1>` na verdade é uma das posibilidades do cabeçalho de seção. O cabeçalho vai do `<h1>` até o `<h6>`, sendo o `<h1>` mais importante e o `<h6>` o menos importante. Eles variam também no tamanho sendo `<h1>` o maior e o `<h6>` o menor.

* `<p>` - Representa um parágrafo, uma porção do texto que tem um recuo (indentação).

* `<a>` - Tag âncora, usando a propriedade `href` é possivel criar uma ligação com outras páginas ou até mesmo partes de uma página.