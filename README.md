# drahmetk.github.io

Personal site of Ahmet Kara, served by GitHub Pages at https://drahmetk.github.io.

It's a single static page with no build step: edit `index.html`, push to `main`, and GitHub Pages republishes it within a minute or two.

## Updating the career timeline

Each bar in the timeline is placed by two numbers in its `style` attribute, the start and end year as decimals:

```html
<div class="bar" style="--s:2017.0;--e:2026.45">Mobile Action</div>
```

`--s:2017.0` means early 2017; `--e:2026.45` means roughly mid-2026. The axis runs from 1999 to 2027; to extend it, change `1999` and `28` (the span in years) in the `.bar` and `.axis span` rules in the stylesheet.
