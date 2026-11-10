# web-calculator

A four function calculator in a single HTML page. The first thing I built with JavaScript, kept as it was written.

## What it does

- Digits 0 to 9 and a decimal point
- Add, subtract, multiply and divide
- AC to clear the whole display, DE to remove the last character
- Equals evaluates the expression in the display

## Files

```
index.html    Markup and the click handlers, all inline
css.css       Grid layout, button states and colours
```

That is the whole project. No build step, no dependencies.

## Running it

Open `index.html` in any browser.

## How the calculation works

Each button appends its value to the display input, and equals passes the whole string to `eval`. It works, and it is the shortest route for a learning exercise. If this were used by anyone else, `eval` would have to go: a small tokenizer or a running total would replace it, and the display would stop being an editable input.

## Author

Enoch Philip Dibal, https://devenoch.cv
