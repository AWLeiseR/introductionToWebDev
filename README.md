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