# markdown-it-cooklang

The markdown-it SIMILAR implementation of https://cooklang.org. This fork of https://github.com/ulfschneider/markdown-it-cooklang does not mean to be compatible with Cook Lang, but to fit my needs at https://wiki.anarchist.work.

## Diferences

- ingredients and cookware must have a `{`, this is mainly because I do use `@` and `#` as normal characters when I write and I didn't want to render them as ingredients or cookware. e.g. `@tomate{}` will be rendered as Ingredient, `@Unicamp` won't.
