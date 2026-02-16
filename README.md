# Latex template for papers

Latex bootstrap template for BMSTU lab reports, courseworks, etc.

## Setup

Install `latex workshop` vs code extension. Configure it to use xelatex and enable hot reload in [settings](./.vscode/settings.json).

~7.4GB

```bash
sudo apt update
# Texlive
sudo apt install -y texlive-full
# if you wish to fuck around with minimal setup
# sudo apt install -y texlive latexmk texlive-xetex texlive-lang-cyrillic

# Fonts
sudo apt install -y ttf-mscorefonts-installer
```

## Structure

Import chapters to the [content.tex](./src/content.tex) from the [Content](./src/Content/) folder where you write your text.

Edit [main.tex](./src/main.tex) to configure the rest.

- [src](./src/) - main latex report code
- [forms](./forms/) - docx blanks that are needed for coursework
- [examples](./examples/) - latex hints

## Hints

Use git clean to remove all gitignored files

```bash
git clean -fX
```

## See also

- [forked from here](https://github.com/mirea-ninja/Latex-Template-for-Report-Diploma-Thesis) - more examples and details
- [VS code setup](https://github.com/mirea-ninja/Latex-Template-for-Report-Diploma-Thesis/issues/16)
- [typst template](https://github.com/pluttan/typst-bmstu)
- [curated list of templates for BMSTU](https://github.com/TonitaN/Blanks-4LaTeX)
