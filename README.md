# Strange Tech: Topological Data Analysis

> Part of the **Strange Tech** series — short, standalone books about advanced
> technologies that most engineers don't know about but might need.

Topological Data Analysis (TDA) applies tools from algebraic topology to
discover the "shape" of data — connected components, holes, cavities — at
multiple scales simultaneously. Its key contribution is that these features
are invariant under continuous deformations and mathematically stable under
perturbations, making them robust descriptors where classical statistics and
deep learning see only point clouds. The price: constructing the topological
structures scales poorly with dimension and number of points, limiting its
practical use to moderately sized datasets.

## Read Online

| Language | Preface | Chapter |
|----------|---------|---------|
| English  | [Preface](https://marcmagransdeabril.github.io/strange-tech-tda/book/en/index.html) | [Topological Data Analysis](https://marcmagransdeabril.github.io/strange-tech-tda/book/en/tda.html) |
| Español  | [Prefacio](https://marcmagransdeabril.github.io/strange-tech-tda/book/es/index.html) | [Análisis Topológico de Datos](https://marcmagransdeabril.github.io/strange-tech-tda/book/es/tda.html) |

## Download

| Language | PDF | EPUB |
|----------|-----|------|
| English  | [strange-tech-tda.en.pdf](https://raw.githubusercontent.com/marcmagransdeabril/strange-tech-tda/main/book/en/strange-tech-tda.en.pdf) | [strange-tech-tda.en.epub](https://raw.githubusercontent.com/marcmagransdeabril/strange-tech-tda/main/book/en/strange-tech-tda.en.epub) |
| Español  | [strange-tech-tda.es.pdf](https://raw.githubusercontent.com/marcmagransdeabril/strange-tech-tda/main/book/es/strange-tech-tda.es.pdf) | [strange-tech-tda.es.epub](https://raw.githubusercontent.com/marcmagransdeabril/strange-tech-tda/main/book/es/strange-tech-tda.es.epub) |

## Code Examples

All code examples from the book live in [`code/tda/`](code/tda/), with unit
tests in [`tests/tda/code/`](tests/tda/code/).

```bash
pip install -r requirements.txt
python code/tda/quick_start.py
pytest tests/tda/code
```

## About the Series

**Strange Tech** (*Tecnologías Extrañas* in Spanish) is a series of short,
standalone books, each covering one advanced but underused technology —
technologies that are strange today but may become mainstream tomorrow.
Every book mixes personal anecdotes with evidence-based technical analysis.

## License

This work is licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/).
See [LICENSE](LICENSE) for the full text.
