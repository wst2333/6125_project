# MotionART

LaTeX source for **What Reveals 3D Articulation? Learning from Motion**.

## Build

Compile the paper and bibliography with:

```bash
latexmk -pdf main.tex
```

Remove generated build files with:

```bash
latexmk -c
```

The compiled paper is available as `main.pdf`.

## Project structure

- `main.tex`: document entry point
- `preamble.tex`: packages and shared commands
- `sec/`: paper sections and appendix
- `figs/`: figures and figure wrappers
- `tables/`: tables used by the paper
- `references.bib`: cited bibliography entries
- `iclr2027_conference.sty` and `iclr2027_conference.bst`: conference style files
