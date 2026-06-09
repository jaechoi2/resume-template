# Placeholder Resume TeX

This repository contains a placeholder copy of the resume TeX files. The experience role entries have been replaced with generic text.

## Compile

Compile the resume from this directory with XeLaTeX:

```sh
cd placeholder_tex
xelatex resume.tex
```

LuaLaTeX should also work:

```sh
cd placeholder_tex
lualatex resume.tex
```

Tectonic is another option:

```sh
cd placeholder_tex
tectonic resume.tex
```

Tectonic may download missing TeX packages on its first run.

Do not use `pdflatex`; the resume uses `fontspec`, which requires a Unicode TeX engine such as XeLaTeX, LuaLaTeX, or Tectonic.

The generated PDF will be written as:

```text
resume.pdf
```

## Files

- `resume.tex` is the main file.
- `education.tex`, `experience.tex`, and `skills.tex` are included by the main file with `\makerubric`.
