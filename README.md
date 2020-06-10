# Black Lives Matter

We take our website offline as a small mark of respect, and expression of solidarity.

## Getting started

This website is built simply using plain HTML and CSS (using tailwind). You can copy this website and adjust it.

The CSS file only contains classes that are used in the HTML. If you make any small edits and you use additional classes from tailwind, simply run:

```
npx tailwindcss build styles.css -o output.css && npx clean-css-cli -o output.min.css output.css
```

For bigger edits, consider setting up a proper environment or temporarily replace the css file with:

```
<link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">
```
