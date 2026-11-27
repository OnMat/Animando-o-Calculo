# Animando o Cálculo com o Manim

Minicurso de 6 horas sobre o uso do [Manim](https://www.manim.community/) (*Mathematical Animation Engine*), com Python, para criar animações matemáticas que ajudem a compreender e a ensinar conceitos de Cálculo.

Oferecido na **III SEPEC** (Semana de Ensino, Pesquisa, Extensão e Cultura) da Universidade Federal do Cariri (UFCA), Campus Juazeiro do Norte, em 26 e 27 de novembro de 2026, por **Wilia Alberto** e **Vicente Sobrinho**.

**Página do minicurso:** https://onmat.github.io/Animando-o-Calculo/

## Materiais

| caderno | conteúdo | abrir |
|---|---|---|
| [`manim_dia_1_fundamentos.ipynb`](notebooks/manim_dia_1_fundamentos.ipynb) | Dia 1: primeira cena, objetos e animações (Partes 1 a 3) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OnMat/Animando-o-Calculo/blob/main/notebooks/manim_dia_1_fundamentos.ipynb) |
| [`manim_dia_2_graficos_e_oficina.ipynb`](notebooks/manim_dia_2_graficos_e_oficina.ipynb) | Dia 2: gráficos, valores dinâmicos e oficina (Partes 4 e 5) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OnMat/Animando-o-Calculo/blob/main/notebooks/manim_dia_2_graficos_e_oficina.ipynb) |

### Programa

**Dia 1 (quinta, 26/11, 14:00 às 17:00):**
1. Primeira cena: ambiente, `Scene`, `construct`, a mágica `%%manim`
2. Objetos: coordenadas, formas, atributos, posicionamento, textos e fórmulas
3. Animações: `play`, `.animate`, transformações, passagens algébricas

**Dia 2 (sexta, 27/11, 14:00 às 17:00):**

4. Gráficos e valores dinâmicos: `Axes`, `ValueTracker`, `always_redraw`
5. Estudo de caso e oficina: animando questões de Cálculo

## Como usar

**No Google Colab:** clique em *Abrir no Colab*, execute a célula de instalação (uma vez por sessão) e depois a célula `from manim import *`.

**Localmente:** instale o Manim Community seguindo a [documentação oficial](https://docs.manim.community/en/stable/installation.html), com uma distribuição LaTeX, e pule a célula de instalação com `apt-get`:

```bash
pip install manim jupyterlab
manim checkhealth
jupyter lab notebooks/
```

## Estrutura do repositório

```
index.html                  página do minicurso (GitHub Pages)
notebooks/                  os dois cadernos Jupyter
assets/videos/              animações exibidas na página, geradas pelos próprios cadernos
.github/workflows/pages.yml publicação da página a cada push na main
```

A página é publicada pelo GitHub Actions; em *Settings → Pages*, a fonte deve ser **GitHub Actions**.

## Autores

- **Wilia Alberto de Sousa** ([ORCID 0009-0008-3250-0217](https://orcid.org/0009-0008-3250-0217)), EREM Professor Manoel Joaquim Leite
- **Vicente Helano Feitosa Batista Sobrinho** ([ORCID 0000-0002-6302-9324](https://orcid.org/0000-0002-6302-9324)), Universidade Federal do Cariri

Para citar este material, use o botão *Cite this repository* do GitHub (gerado a partir de [`CITATION.cff`](CITATION.cff)).

## Licença

Material sob a licença [Creative Commons Atribuição 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.pt-br). Veja [`LICENSE`](LICENSE).
