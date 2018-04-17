# Roteiro das Aulas

[\# 01 - Apresentação da Disciplina (14/03/2018)](#-01---apresentação-da-disciplina-14032018)<br>
[\# 02 - Linguagem de Marcação (16/03/2018)](#-02---linguagem-de-marcação-16032018)<br>
[\# 03 - Primeiros passos com HTML (21/03/2018)](#-03---primeiros-passos-com-html-21032018)<br>
[\# 04 - Sintaxe e Estruturas do HTML (23/03/2018)](#-04---sintaxe-e-estruturas-do-html-23032018)<br>
[\# 05 - Analisando uma página (28/03/2018)](#-05---analisando-uma-página-28032018)<br>
[\# 06 - Criando a página da disciplina com imagens (04/04/2018)](#-06---criando-a-página-da-disciplina-com-imagens-04042018)<br>
[\# 07 - Criando um currículo em HTML (06/04/2018)](#-07---criando-um-currículo-em-html-06042018)<br>
[\# 08 - Linguagem de Estilo e o CSS (11/04/2018)](#-08---linguagem-de-estilo-e-o-css-11042018))<br>
[\# 09 - Primeiros Passos com CSS (13/04/2018)](#-09---primeiros-passos-com-css-13042018))<br>
[\# 10 - Primeiros Passos com CSS (18/04/2018)](#-10---primeiros-passos-com-css-18042018)<br>
[\# 11 - Estilizando Texto (20/04/2018)](#-11---estilizando-texto-20042018)<br>

## \# 01 - Apresentação da Disciplina (14/03/2018)
---

**Conteúdo:**
- [Apresentação da disciplina](https://ifpb.github.io/lm/):
  - Objetivo, conteúdo, avaliação, comunicação, bibliografia e ferramentas
  - [O que você vai aprender em LM?](http://slides.com/luizcarlos/o-que-vou-aprender-em-lm#/)
- Fundamento e finalidade do HTML e CSS usando como base a página do [IFPB](http://www.ifpb.edu.br/)
- Fundamento e finalidade do XML

**Exercício:**
* Analise o [site da discplina](https://ifpb.github.io/lm/) e se inscrever no channel `#lm20181` do [slack do ifpb](https://ifpb.slack.com).
* Configure seu computador com essas [ferramentas](TOOLS.md).

## \# 02 - Linguagem de Marcação (16/03/2018)
---

**Conteúdo:**
- Exibindo a [arquitetura da Web](https://www.youtube.com/watch?v=guvsH5OFizE) (Tripé: URL, HTTP, HTML; [slide](https://ifpb.github.io/web-guide/slides/web.pdf))
- Fundamentos de uma Linguagem de Marcação ([guide](https://ifpb.github.io/html-guide/markup/))

**Exercício:**
* Descreva o que acontecer ao acessar uma página da Web, como a do [IFPB](http://www.ifpb.edu.br)
* Pesquise sobre a evolução da Web
  * O que é Web de documentos e Web de dados?
  * O que é Web 1.0, Web 2.0 e Web 3.0?
* Descreva o que é uma Linguagem de Marcação


## \# 03 - Primeiros passos com HTML (21/03/2018)
---

**Conteúdo:**
- Editando HTML com [Visutal Studio Code (vscode)](http://code.visualstudio.com) e visualizando com o [Google Chrome](https://www.google.com/chrome/)
- [Trabalhando com HTML](https://ifpb.github.io/html-guide/html/)
  - Conceitos básicos
  - Estrutura básica
    - Cabeçalho e Corpo
  - Metadados do Hyper Texto
    - Título da página
    - Encoding e UTF-8
  - Elementos do Hyper Texto
    - Títulos
    - Parágrafos
    - Negrito e Itálico
  - [Referências dos Elementos no MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/)
- Criando a página Hello World
- Criando a primeira página da Web

**Exercício:**
* Analise os elementos HTML: [Content sectioning](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Content_sectioning), [Text content](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Text_content), [Inline text](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Inline_text_semantics).
* [Crie sua Primeira Página Web](https://ifpb.github.io/html-exercises/challenges/hello-world-html/)

## \# 04 - Sintaxe e Estruturas do HTML (23/03/2018)
---

**Conteúdo:**
- [Sintaxe do HTML](https://ifpb.github.io/html-guide/html/)
  - Tags, atributos (`charset` do meta e `lang` no html), entidades e comentários
  - Como acessar a documentação de uma tag ou atributo usando o portal [MDN](https://developer.mozilla.org/kab/docs/Web/HTML)
- [Listas `<ol>`, `<ul>`, `<dl>`](https://ifpb.github.io/html-guide/html/#lists)
  - Definição, Ordenada, Não ordenado
  - Personalizando marcadores
  - Lista aninhada
- [Hyperlink `<a>`](https://ifpb.github.io/html-guide/html/#hyperlink)
  - Endereço absoluto e relativo
  - Abrindo recurso em nova aba
  - Links locais e externos

**Exercício:**
* Reconstrua a [Primeira Página da Web](https://ifpb.github.io/html-exercises/challenges/first-web-page/)

<!-- 
TODO
https://www.w3.org/TR/2011/WD-html5-20110525/content-models.html#kinds-of-content
 -->

## \# 05 - Analisando uma página (28/03/2018)
---

**Conteúdo:**
- Analisando uma página HTML
  - Analisando a *Primeira Página da Web* com HTML recente
  - Ver Código Fonte, Ferramenta de Desenvolvedor e Plugin Web Developer
  - Ferramenta de Desenvolvedor
    - Inspecionar e editar código, Toogle device toolbar, Network e Screenshot
- Linha Horizontal `<hr>`

**Exercício:**
* [Inspecione uma página na Web](https://ifpb.github.io/html-exercises/challenges/inspect-page/)
* Reproduza a [Página LM](https://ifpb.github.io/html-exercises/challenges/page-lm-simple/)

## \# 06 - Criando a página da disciplina com imagens (04/04/2018)
---

**Conteúdo:**
- Analisando a Página de LM
- [Imagem `<img>`, `<figure>`, `<figcaption>`](https://ifpb.github.io/html-guide/html/#image-and-multimedia)
  - Imagem dentro (Data URI), próximo ou distante do HTML
    - Custos e benefícios
  - Atributos: `src`, `alt`, `width`, `title`
  - Imagem com link

**Exercício:**
* [Página LM usando imagem](https://ifpb.github.io/html-exercises/challenges/page-lm-img/)

## \# 07 - Criando um currículo em HTML (06/04/2018)
---

**Conteúdo:**
- Revisão de HTML

**Exercício:**
* [Curriculum Vitae](https://ifpb.github.io/html-exercises/challenges/curriculum-simple/)
* [Curriculum Vitae com Sumário](https://ifpb.github.io/html-exercises/challenges/curriculum-linkinternal/)

## \# 08 - Linguagem de Estilo e o CSS (11/04/2018)
---

**Conteúdo:**
- [Linguagem de Estilo](https://ifpb.github.io/css-guide/style/)
  - Definição e exemplos
- [Cascade Style Sheet (CSS)](https://ifpb.github.io/css-guide/css/)
  - [Origem do CSS](https://ifpb.github.io/css-guide/css/#problem)
  - [Declarações do CSS](https://ifpb.github.io/css-guide/css/#how-to-apply-your-css-to-your-html): local (`style=""`), interna ([`<style>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/style)), externa ([`<link>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link))
  - Sintaxe do CSS
    - [Propriedades](https://ifpb.github.io/css-guide/css/#properties):
      - Texto & Fonte
        - `color`
        - `font-size`
    - [Seletores básicos](https://ifpb.github.io/css-guide/css/#selectors): 
      - tipo (`elementname`)
        - Agrupamentos com [`<span>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span) e [`<div>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)
      - id (`#idname` e `id=""`)
      - classe (`.classname` e `class=""`)
      - Múltiplas classes `.classA.classB`

**Reflexão**
* O que é uma Linguagem de Estilo?
* O que é e como funciona o CSS?
* Quais são os possíveis locais que o CSS pode existir junto com o HTML?
* Qual a relação do atributo global `class` e `id` com o CSS?
* Qual é a composição da sintaxe do CSS?
* Qual é o benefício de definir mais de uma classe à um elemento?

**Exercício:**
* [Criando seu primeiro estilo](https://ifpb.github.io/css-exercises/challenges/hello-world-css/)


## \# 09 - Primeiros Passos com CSS (13/04/2018)
---

**Conteúdo:**
- [Herança de estilo](https://ifpb.github.io/css-guide/css/#inheritance)
- [Inspecionando estilos dos Elementos](https://developers.google.com/web/tools/chrome-devtools/inspect-styles/): Analisando e editando estilos
- Sintaxe do CSS
  - [Funções](https://ifpb.github.io/css-guide/css/#functions)
  - [Seletores](https://ifpb.github.io/css-guide/css/#selectors)
    - Básico: Atributo `[]`
    - Combinação: Child `A > B`, Descendant `A B`, Adjacent sibling `A + B`, General sibling `A ~ B`
    - Pseudo-class: `:hover`, `:first-child`, `:nth-child`
    - Pseudo-element: `::selection`

**Reflexão**
* Qual é a composição da sintaxe do CSS?
* Qual é o benefício da herança no CSS?
* Como é possível identificar o estilo atribuído a algum elemento no HTML?
* O que acontece quando um elemento carrega um estilo inválido? É possível identificar?

**Exercício:**
* [Analisando uma página com Estilo](https://ifpb.github.io/css-exercises/challenges/inspect-style/)
* [Selecionando Elementos no HTML](https://ifpb.github.io/css-exercises/challenges/selector-css/)


## \# 10 - Primeiros Passos com CSS (18/04/2018)
---

**Conteúdo:**
- Sintaxe do CSS
  - [At-rules](https://ifpb.github.io/css-guide/css/#at-rules)
    - @import
    - @font-face
    - @media
  - [Media query](https://ifpb.github.io/css-guide/css/#media-queries)
    - Media types
    - Media features
    - Logical operators

**Reflexão**
* Qual é a composição da sintaxe do CSS?
* Qual é a utilidade dos at-rules no CSS?
* O que é Media query? Qual é a sua composição? Onde definimos?
* Como personalizamos uma página de impressão?
* Qual a relação entre Media query e Design responsivo? Como definos *breakpoint* no Design responsivo?

**Exercício:**
* [Adpatando a página de impressão](https://ifpb.github.io/css-exercises/challenges/customize-print/)

## \# 11 - Estilizando Texto (20/04/2018)
---

**Conteúdo:**
- [Estilizando Texto](https://ifpb.github.io/css-guide/css/typography.html):
  - [Texto e fonte](https://ifpb.github.io/css-guide/css/typography.html#text-and-font)
  - [Alinhamento de Texto](https://ifpb.github.io/css-guide/css/typography.html#text-layout)
- [Estilizando links](https://ifpb.github.io/css-guide/css/links.html)
  - Selector pseudo-class: `:hover`, `:link`, `:active`, `:visited`, `:focus`

**Reflexão**
* Quais são os estilos de alinhamento e aparência para fonte?
* Qual cor combina com o vermelho tomate?
* Se não for definido nenhum font-family, qual será a fonte atribuída?
* O que acontece se font-family não possuir a fonte instalada no computador?
* Qual é a diferença entre <font-family> e <generic-family>?
* Qual é a recomendação para se difinir uma família de fonte?
* Qual a diferança entre unidades de medida relativa e absoluta?
* Como funciona a sobra para um texto?
* Como estilizamos um hyperlink?

**Exercício:**
* No exercício [Adpatando a página de impressão](https://ifpb.github.io/css-exercises/challenges/customize-print/), crie alguns links e depois tente estilizá-los nos estados `:hover`, `:link`, `:active`, `:visited`, `:focus`. Alterando `color`, `outline`, `text-decoration`, `cursor`.

<!-- 
## \# 12 -  Estilizando Texto (25/04/2018)
---

**Conteúdo:**
- [Estilizando Texto](https://ifpb.github.io/css-guide/css/typography.html)
- [Estilizando links](https://ifpb.github.io/css-guide/css/links.html)

**Reflexão**
* Quais são os estilos de alinhamento e aparência para fonte?

**Exercício:**
* Criando o [Curriculum Vitae com Estilo](https://ifpb.github.io/css-exercises/challenges/curriculum-style-text/)

## \# 13 -  Web Fonts e Ícones (27/04/2018)
---

**Conteúdo:**

**Reflexão**

**Exercício:**
* [Curriculum Vitae com Web fontes e Ícones](https://ifpb.github.io/css-exercises/challenges/curriculum-style-icon/)

## \# 14 - Cascata no CSS (02/05/2018)
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 15 - Box Model (04/05/2018)
---

**Conteúdo:**
- [Inline text semantics \| W3C](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Inline_text_semantics)
**Reflexão**

**Exercício:**

## \# 16 - Box Model (09/05/2018)
---

**Conteúdo:**
- [Styling links as buttons \| W3C](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links#Including_icons_on_links)

**Reflexão**

**Exercício:**

## \# 17 - Backgound (11/05/2018)
---

**Conteúdo:**
- [Including icons on links \| W3C](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links#Including_icons_on_links)


**Reflexão**

**Exercício:**

## \# 18 - Tabela, Lista (16/05/2018)
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 19 - Curriculum Viate com Layout Básico (18/05/2018)
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 20 - Simulado I de HTML e CSS (23/05/2018)
---

## \# 21 - Avaliação I de HTML e CSS (25/05/2018)
---

## \# 22 - Apresentação do Projetos e do Blog
---

## \# 23 - Apresentação das propostas de Projetos
---

## \# 24 - Flexbox
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 25 - Flexbox
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 26 - Grid layout
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 27 - Grid layout
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 28 - Formulário
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 29 - Design Responsivo
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 30 - Design Responsivo
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 31 - Simulado II de HTML e CSS
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 32 - Avaliação II de HTML e CSS
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 33 - Posicionamento de Elementos
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 34 - Posicionamento de Elementos
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 35 - Animação com CSS
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 36 - Animação com CSS
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 37 - Componentes da Web e Publicando seu site
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 38 - XML & DTD
---

**Conteúdo:**

**Reflexão**

**Exercício:**

## \# 39 - Apresentação de Projetos
---

## \# 40 - Apresentação de Projetos
---

-->