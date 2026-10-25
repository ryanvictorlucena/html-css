# CSS

CSS, assim como HTML também não é considerada uma linguagem de programação. Trata-se de uma linguagem utilizada para definir a aparência e o estilo dessas páginas.
Caso seja necessário adicionar lógica computacional, normalmente utilizamos JavaScript.

Estrutura:

    seletor { propriedade : valor; }

Exemplo:

    h1 { color : red; }

    h1 {color : red;
        font-size: 16px;
        }

## Seletores de elemento

HTML:

    <p> ... </p>

Exemmplo:

    <p class="minha-classe"> ... </p>
    <p id="meu-id"> ... </p>

CSS:

    p {...}

Exemplo:

    .minha-classe {...}
    #meu-id {...}

Obs: id por definição é único por página. Geralmente usado para efeito único, quando queremos afetar mais coisas, usamos o class.

## Fonts

- Font-family: Formata a familia da fonte.
- Font-size: Formata o tamanho da fonte.
- Font-style: Formata para normal ou itálico.
- Font-variant: Formata a forma de escrita.

## Text

- Text-align: Deixa mais a direita ou esquerda.
- Text-decoration: Sublinhado ou não.
- Text-ident: Se tem espaçamento entre parágrafo ou não.
- Text-trasform: tudo maiusculo ou minusculo.

## Cor

Codigo das cores estão em hexadecimal com F sendo o máximo da cor.

Estrutura:

    #RGB

- #FFFFFF: branco.
- #FF0000: vermelho.
- #00FF00: verde.
- #0000FF: azul escuro.
- #FFFF00: amarelo.
- #FF00FF: rosa.
- #00FFFF: azul claro.

### Background-color

Muda a cor de fundo de um elemento ou página.
