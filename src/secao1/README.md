# Introdução

HTML não é considerada uma linguagem de programação por não possuir lógica computacional. Em vez disso, é uma linguagem de marcação cuja função é descrever e organizar o conteúdo de uma página.

CSS também não é considerada uma linguagem de programação. Trata-se de uma linguagem utilizada para definir a aparência e o estilo dessas páginas.
Caso seja necessário adicionar lógica computacional, normalmente utilizamos JavaScript.

## Funcões

Todas as tags são exibidas dentro de <>, quando estão dentro de <>...</> isso que dizer onde começa e onde termina, respectivamente, uma tag.

- Quebra de linha: br (quando se usa paragrafos, automaticamente já tem uma quebra de linha).
- Qubra de linha (mostrando uma linha horizontal): hr.
- Título: h1.
- Subtitulo: h2.
- Os níveis de título vão até h6, representam hierarquia.
- Paragrafo: p.

Enfâse em texto

- Itálico: i.
- Itálico semântico: em.
- Negrito: b.
- Negrito semântico: strong.

Listas não ordenadas

- Lista não ordenada: ul.
- Item de lista: li.

Lista ordenada

- Lista ordenada: ol.
- Item de lista: li.

Links

Usasse a tag "a" que representa uma âncora. Estrutura:

    <p>Texto com <a>link</a> aqui</p>

Tipos de links

    Link externo: <a href="http://www...com.br">.
    Link interno: <a href="outraPagina.html">.
    Link de seção (navegar na mesma página): <a href="secao">.
    Link de email (menos usado): <a href="pessoa.email.com">.

Atributos

É possível definir um atributo para representar um link.

    <tag atributo="valor"> texto aqui </tag>
    <p> saiba masi sobre
    <a href="http://www...com.br">HTML5</a>
    visitando nosso blog e seja feliz </p>

Abrir a página em outra aba: target

    <p> saiba masi sobre
    <a href="http://www...com.br" target="_blank">HTML5</a>
    visitando nosso blog e seja feliz </p>

## Estrutura Semântica - Básica

Assim que uma nova página é criada ela começa em branco. Antes de qualquer código iniciamos com uma abertura e fechamento com a tag html. Logo em seguida temos as tags head e body, onde a tag head serve para passar informações adicionais para o agente de úsuario e a tag body vai todo o conteúdo da página.

Estrutura:

    <html lang="pt-br">
        <head>
            <title> título da página </title>
            <meta tags>
            <link para arquivos externos>
        </head>

        <body>
        </body>
    </html>

Doctype

É colocado no inicio, antes mesmo do html.

    <!doctype html>

Imagem, arquivos externos e links

    <img> -> src e alt (texto se a imagem não carregar)
    <script> -> src
    <link> -> href e rel
    <a> -> href e title
