# Hiragana and Katakana Chart

A simple Hiragana and Katakana chart in $\LaTeX$.

[![](doc/chart_preview.jpg)](doc/chart.pdf)

## Getting Started

This project uses `platex`. You can build the document with `latexmk`, which should automatically pick up the `.latexmkrc` config file.

A minimal config for the LaTeX Workshop extension with `vscode` is also provided.

To convert the pdf to an image, you can use

```bash
# good quality
magick -density 1200 chart.pdf -background white -alpha remove -alpha off -resize 50% chart.png

# small preview
magick -density 300 chart.pdf -background white -alpha remove -alpha off -resize 50% doc/chart_preview.jpg
```

## TODOs

### Medium priority

- Maybe add an option to show full romanization
- Maybe add an option to use a font that shows the stroke order

### Low priority

- Automatically build and upload PDF & preview
- Check why ん is usually placed in the "a"-column

## Acknowledgements

The dual layout was initially inspired by [this Kana chart by Danilinky](https://www.reddit.com/r/LearnJapanese/comments/b0jlyt/i_made_an_allinone_hiraganakatakanabasic_kanji/).

The color scheme is inspired by [this Kana chart by Moer_by](https://www.reddit.com/r/japaneseresources/comments/ilkott/hiragana_katakana_stroke_order_chart/).
