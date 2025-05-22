# Hiragana and Katakana Chart

A simple Hiragana and Katakana chart in $\LaTeX$.

## Getting Started

This project uses `platex`. You can build the document with `latexmk`, which should automatically pick up the `.latexmkrc` config file.

A minimal config for the LaTeX Workshop extension with `vscode` is also provided.

To convert the pdf to an image, you can use

```
magick -density 1200 chart.pdf -background white -alpha remove -alpha off -resize 50% chart.png
```

## TODOs

### High priority

- Recreate the table in tikz for easier coloring

### Medium priority

- Maybe add an option to show full romanization
- Maybe add an option to use a font that shows the stroke order, also see [this Reddit post](https://www.reddit.com/r/japaneseresources/comments/ilkott/hiragana_katakana_stroke_order_chart)

### Low priority

- Check why ん is usually placed in the "a"-column. It looks nicer in the center

## Acknowledgements

The dual layout is inspired by [this Reddit post](https://www.reddit.com/r/LearnJapanese/comments/b0jlyt/i_made_an_allinone_hiraganakatakanabasic_kanji/).
