# Exercício 2.08 - Qual é o elemento HTML que permite associar um documento CSS a uma página web na seção de metainformações?

O elemento HTML que permite associar um documento CSS a uma página web na seção
de metainformações é o elemento `<link>`. O `<link>` é usado para criar um link
entre o documento HTML e um arquivo externo de folha de estilo (CSS) que contém
as **regras de estilização** para a página.

Dentro do elemento `<head>` da página HTML, podemos incluir o seguinte código
para vincular o arquivo CSS externo:

```html
<head>
    <link rel="stylesheet" type="text/css" href="estilo.css" />
</head>
```

Neste exemplo, o atributo `rel="stylesheet"` indica que estamos **vinculando**
uma folha de estilo ao documento. O atributo `type="text/css"` especifica o tipo
MIME do arquivo vinculado (no caso, um arquivo de estilo CSS). O atributo
`href="estilo.css"` especifica o caminho do arquivo CSS externo que será
associado à página.

Ao utilizar o elemento `<link>` dessa forma, podemos centralizar as regras de
estilização em um arquivo externo, facilitando a **manutenção** e a
**reutilização** das folhas de estilo em várias páginas do site, proporcionando
uma experiência visual consistente em todo o projeto.
