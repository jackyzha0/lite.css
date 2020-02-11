# 💡 lite.css
### A <2kB just-add-water CSS library.

Tired of huge CSS bundles? Want something lightweight enough that will barely dent your page-load times? you came to the right place! `lite.css` is a grand total of ~1.77kB minified, meaning it will barely impact your page load time, while still coming with the standard HTML elements that you need.

## Examples
See example usages on the [project page](https://jzhao.xyz/lite.css/).

## How do I use it?
You can use `lite.css` in your project by adding the stylesheet to the `<head>` of your page:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jackyzha0/lite.css@latest/src/lite.min.css"/>
```

## Theming
By default, `lite.css` comes with a few colours (that I think look pretty spicy).
* ![#fbfffe](https://placehold.it/15/fbfffe/000000?text=+) `--lt-colours-light: #fbfffe`
* ![#f0f0f0](https://placehold.it/15/f0f0f0/000000?text=+) `--lt-colours-lightgray: #f0f0f0`
* ![#284b63](https://placehold.it/15/284b63/000000?text=+) `--lt-colours-dark: #284b63`
* ![#84a59d](https://placehold.it/15/84a59d/000000?text=+) `--lt-colours-secondary: #84a59d`

If you happen to not like them, you can override these in your own CSS:

```css
:root {
  --lt-colours-light: #<some new colour> !important;
  --lt-colours-lightgray: #<some new colour> !important;
}
```
