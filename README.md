# Tensor Networks for Image Classification — Manuscript

Repositorio del manuscrito de un futuro artículo sobre redes tensoriales para clasificación de imágenes.

## Estructura

- `main.tex`: documento principal y configuración LaTeX.
- `sections/`: resumen y secciones del artículo.
- `references.bib`: bibliografía.
- `figures/` y `tables/`: figuras y tablas del manuscrito.

Se utiliza una plantilla provisional `article`. Se sustituirá por la plantilla oficial cuando se elija el destino del artículo. El texto inicial está en inglés y contiene únicamente marcadores pendientes de completar.

## Compilación local

Con una distribución LaTeX instalada, desde la raíz del repositorio:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

También se puede compilar con `pdflatex main.tex`. Cuando haya citas, activar las dos líneas de bibliografía al final de `main.tex`; `latexmk` gestionará BibTeX y las pasadas necesarias.

## Overleaf

Importar este repositorio mediante **New project → GitHub repo**. Seleccionar `main.tex` como documento principal y pdfLaTeX como compilador. La sincronización GitHub requiere acceso a esa función premium y se realiza manualmente desde la integración de GitHub.

## Código y trazabilidad

El código se desarrolla por separado en [tensor-networks-image-classification-code](https://github.com/Manuel-Arenas-Sanchez/tensor-networks-image-classification-code).

Los repositorios originales del TFG se conservan sin cambios. No se incluyen datos, pesos de modelos ni resultados experimentales inventados.
