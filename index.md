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

ex: $$ a = b^c $$ (b la puterea c)

## Ridicarea la putere (superscript)

Se foloseste metacaracterul `LaTeX` : `^`

*Exemplu*

$$a= b^c$$

Subscript- indice:

Se foloseste metacaracterul `LaTeX` : `_`

*Exemplu*

$$ a_i = b^c $$

## Gruparea elementelor din formule

Elementele din formule se grupeaza prin metacaracterul "{" si "}"

$$ 10^{10} $$

## Litere grecesti

*Exemplu:*

`\alpha` : alfa litera mica ($\alpha$)

`\Alpha` : alfa litera mare ($\Alpha$)

## Parantezele 

- Parantezele rotunde se scriu direct (nu au vreun inteles special)
- Parantezele drepte se scriu direct (nu au...)
- Parantezele acolade, deoarece sunt metacaractere de grupare, vor fi renderizate corect daca sunt escapate de intelesul original punand in fata lor metacaracterul \

*Exemplu:*

$$ a = (b + c)^{3x} - [3 + 6x]$$

## Fractiile

*Exemplu:*

`\frac{numarator}{numitor}`

$$\frac{a+b+c}{d-c}$$

## Semnele de multiplicare respectiv de diviziune

*Exemple:*

$$a= c + 10 \times x $$

$$a= c + 10 \cdot x $$

$$a = b \div c$$




