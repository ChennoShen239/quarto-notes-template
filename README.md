# Quarto Notes Template

A Quarto HTML book starter for lecture and research notes. It uses Cosmo with Spectral typography, a chapter sidebar, an on-page table of contents, and styles for numbered results and proofs. [See the layout in use](https://chennoshen239.github.io/game-theory-notes/01-introduction.html)

## Start a book

Install Quarto, then create an empty directory for your notes. [Download Quarto](https://quarto.org/docs/get-started/)

```sh
mkdir my-notes
cd my-notes
quarto use template ChennoShen239/quarto-notes-template
quarto preview
```

Choose the current directory when Quarto asks where to copy the files. To start with a GitHub repository, use **Use this template** above and clone your copy.

## Edit your notes

- Set the title and author in `_quarto.yml`. List your chapter files under `book.chapters`.
- Use `index.qmd` for your preface. The example chapter shows equations, theorem numbering, proofs, and cross-references.
- Edit `theme.scss` for the Cosmo overrides and `assets/custom.css` for the colors and styles of the note blocks.

Run `quarto render --to html` to build the book in `_book/`.

## License

The template uses the MIT License. The bundled Spectral fonts use the SIL Open Font License 1.1. [Template license](LICENSE) · [Font license](assets/fonts/OFL.txt)
