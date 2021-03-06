# Conhecendo um pouco sobre Markdown

## O que é?
De acordo com a Wikipédia, "Markdown é uma linguagem simples de marcação originalmente criada por John Gruber e Aaron Swartz. Markdown converte seu texto em XHTML válido". Ou seja, markdown é uma ferramenta de conversão de texto em HTML. Ou seja, é a melhor forma de se escrever HTML sem escrever HTML por assim dizer.

## E para que serve?

Com Markdown você define estruturas HTML de maneira simples, fácil e rápida. Permitindo que você economize tempo. Portanto, serve basicamente para escrever textos, como: artigos de blog, documentação de software, entre outros. 

## Então posso parar de escrever sites em HTML e fazer tudo em Markdown? 

Não! Pelo simples fato de você não conseguir colocar atributos (como: class, id etc.), não ter muito controle para fazer alinhamento de tags, entre outros detalhes.

## Onde pode ser usado? 

Bem, existe vários lugares onde você pode usar Markdown. Dois exemplos legais são:
Github e Bitbucket, onde pode ser utilizado no arquivo README.md, que geralmente é utilizado para escrever a documentação do projeto. (fica localizado na raiz do projeto)
 
## Usando Markdown

## Título

Utilizando # você consegue marcar um título. Para definir o nível (como em HTML `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` ou `<h6>`), você pode acrescentar # o número de vezes que for necessário. 

Exemplo:

\# Título H1

# Título H1

\## Título H2

## Título H2

\### Título H3

### Título H3

\#### Título H4

#### Título H4

\##### Título H5

##### Título H5

\###### Título H6

###### Título H6

## Parágrafo

Simplesmente escreva o texto em uma linha.

Este é um parágrafo.

## Quebra de linha 

Simplesmente deixe uma linha em branco e escreva o texto na próxima linha.

Primeira linha.

Segunda linha.

## Ênfase (Itálico e Negrito)

Em Markdown basta usar um * ou _ para deixar a palavra em Itálico.

\_Itálico_

_Itálico_

Ou

\*Itálico*

*Itálico*

Se estiver afim de deixar em negrito, basta duplicar o \** ou \__

Assim:

\**Negrito**

**Negrito**

Ou

\__Negrito__ 

__Negrito__ 

## Links

Basta usar [ ] e ( ). Assim:

\[Daniel Nunes | Github](https://github.com/nunesdaniel)

[Daniel Nunes | Github](https://github.com/nunesdaniel)

Entre os colchetes você coloca o texto que representa o link, dentro dos parênteses, a URL.

Obs.: Se o texto que você quer que apreça, for próprio link, basta fazer: 
\<https://github.com/nunesdaniel/>


<https://github.com/nunesdaniel/>

## Imagens

A geração de imagens é bem semelhante à de links, basta acrescentar uma ! no começo.

\![ Texto alt da imagem ] \( URL da imagem ) 

[Texto alt da imagem](https://avatars2.githubusercontent.com/u/26189299?v=4&s=460)

## Citação

Para criar um bloco de citação ( `<blockquote>` `</ blockquote>` ), basta fazer:

\> Isto é um bloco de citação.

\> Posso ter várias linhas nele.

\>

\> Para um novo parágrafo, basta pular uma linha.

> Isto é um bloco de citação.
> Posso ter várias linhas nele.
>
> Para um novo parágrafo, basta pular uma linha.

## Listas

Para fazer listas, basta fazer:

\* 1º item

\* 2º item

* 1º item
* 2º item
	
Ou

\+ 1º item

\+ 2º item

+ 1º item
+ 2º item

Ou

\- 1º item

\- 2º item

- 1º item
- 2º item

Caso queira uma lista ordenada, faça:

1. 1º item
2. 2º item

## Escrever trechos de código

Basta usar \`\`. 

Exemplo:

`<h1>` 

## Escapar caracteres

Para escapar caracteres, basta você utilizar a barra invertida ( \ ), seguida do respectivo caractere. Exemplos:

\\   ( imprimir barra invertida )

\`   ( imprimir crase )

\*   ( imprimir asterisco )

\_  ( imprimir underscore )

\{ } ( imprimir chaves )

\[ ]  ( imprimir colchetes )

\( )  ( imprimir parênteses )

\#   ( imprimir jogo da velha )

\+   ( imprimir sinal de mais )

\-    ( imprimir sinal de menos )

\.    ( imprimir ponto )

\!    ( imprimir exclamação )

#### Fontes
- Wikipédia
- João Tiago

## Links Interessantes
- [Markdown](https://pt.wikipedia.org/wiki/Markdown)

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
