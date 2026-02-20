# UCL Beamer Theme 2026

A LaTeX Beamer theme following the [UCL 2026 brand guidelines](https://www.ucl.ac.uk/brand-and-experience/brand/visual-guidelines).

## Requirements

- **XeLaTeX** or **LuaLaTeX** (pdfLaTeX is not supported due to font requirements)

### Fonts

**Main text font** (one of the following):
- **UCL Sans** (preferred) — available to UCL staff and students from the [UCL brand resources](https://www.ucl.ac.uk/brand-and-experience/brand/brand-resources)
- **Aptos** — included with Microsoft Office 365 and Windows 11

**Math font** (optional but recommended):
- **Fira Math** — available from [CTAN](https://ctan.org/pkg/firamath) or [GitHub](https://github.com/firamath/firamath)

The theme will issue an error if neither UCL Sans nor Aptos is found. If Fira Math is not installed, a warning is issued but compilation will proceed using the default math font.

## Installation

### Option 1: User installation (recommended)

Copy the theme files to your local texmf directory:

```
~/Library/texmf/tex/latex/ucl-beamer-2026/    (macOS)
~/texmf/tex/latex/ucl-beamer-2026/            (Linux)
C:\Users\<username>\texmf\tex\latex\ucl-beamer-2026\  (Windows)
```

After copying, run:
```bash
texhash ~/Library/texmf   # macOS
texhash ~/texmf           # Linux
```

### Option 2: Project-local installation

Simply place the `.sty` files in the same directory as your `.tex` file.