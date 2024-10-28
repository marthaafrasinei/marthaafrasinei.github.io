![Text descriptiv imagine](https://t4.ftcdn.net/jpg/02/89/58/51/360_F_289585146_KrE8Cg2iaFR0fgV3nauV9Xu4UdsUGKmR.jpg)
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

**Cuprins**

[Elemente avansate de Markdown](avansate.md)
[Formule cu mathcharts](mathcharts.md)



***

# Implementarea relatiilor in Markdown

## Implementarea relatiilor/legaturilor catre alte fisiere

Fisierele accesate prin link-uri pot fi:
1. Gazduite pe alte servere (de ex.: accesarea unui alt site)
2. Gazduite pe serverul site-ului curent

De asemenea, prin aceste link-uri se pot accesa si sectiuni din pagina curenta sau sectiuni din alte pagini ale aceluiasi site

### Sintaxa unui link Markdown

Tipuri de linkuri in Markdown:
1. Linkuri clasice (normale)
2. Linkuri referentiate

#### Linkurile clasice

**variante**

1.[Textul linkului- descriptiv, care apare cand nu se poate accesa link-ul sau cand tinem mouse-ul pe el](https://google.com)
2.[Textul linkului](https://google.com accesare site Google)

### Linkurile referentiate

Iata un [link][link1] catre site-ul google

[link1]: https://google.com

varianta prescurtata a link-urilor referentiate

Iata un link [important] catre site-ul google.

[important]: https://google.com

#### Link-uri catre imagini

![Text descriptiv imagine](https://t4.ftcdn.net/jpg/02/89/58/51/360_F_289585146_KrE8Cg2iaFR0fgV3nauV9Xu4UdsUGKmR.jpg)

# Inserarea ecuatiilor si formulelor Mathjax

Formulele Mathjax sunt inserate in aceeasi linie daca sunt plasate intr-o pereche de simboluri "$"

ex: Aceasta este o ecuatie: $a = b * c$

Formulele "Latex" din Mathjax se introduc pe rand nou intre doua perechi de simboluri "$$"

ex: $$ a = b^c (b la puterea c)

## Ridicarea la putere (superscript)

Se foloseste metacaracterul `LaTeX` : `^`

Subscript- indice:

Se foloseste metacaracterul `LaTeX` : `_`








