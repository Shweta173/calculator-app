# 🔢 Calculator App

A clean, browser-based calculator for everyday arithmetic, built with plain HTML, CSS and JavaScript.

## Features

- Addition, subtraction, multiplication and division
- Chain operations in one expression (for example `12+8*3`)
- `=` to calculate the result, `C` to clear
- Live display that updates as you click

## Tech stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## How it works

Every button shares one click handler in `script.js`. Clicks build up an expression string shown in the display; `=` evaluates it and `C` resets it.

## Run locally

```bash
git clone https://github.com/Shweta173/calculator-app.git
cd calculator-app
```

Then open `index.html` in your browser. No install or build step needed.

## Project structure

```
├── index.html   # calculator layout
├── style.css    # main styles
├── utild.css    # utility styles
└── script.js    # button handling and calculation
```

## Next improvements

- [ ] Make the memory buttons (M+, M−, MC) work
- [ ] Replace `eval` with a small safe expression parser
- [ ] Add keyboard support
- [ ] Handle invalid input (for example `5++`) with a clear error message

## Author

**Shweta Kamble** · [LinkedIn](https://www.linkedin.com/in/shweta-kamble-dev) · [GitHub](https://github.com/Shweta173)
