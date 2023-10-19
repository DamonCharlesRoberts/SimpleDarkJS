<h4 align="center">SimpleDarkJS</h4>
<p align="center">
    <a href="https://github.com/DamonCharlesRoberts/SimpleDarkJS/commits/main">
    <img src="https://img.shields.io/github/last-commit/DamonCharlesRoberts/SimpleDarkJS.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub last commit"></a>
    <a href="https://github.com/DamonCharlesRoberts/SimpleDarkJS/issues">
    <img src="https://img.shields.io/github/issues-raw/DamonCharlesRoberts/SimpleDarkJS.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub issues"></a>
    <a href="https://github.com/DamonCharlesRoberts/SimpleDarkJS/pulls">
    <img src="https://img.shields.io/github/issues-pr-raw/DamonCharlesRoberts/SimpleDarkJS.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub pull requests"></a>
</p>

---

## Installing

```bash
quarto use template DamonCharlesRoberts/SimpleDarkJS
```
This will install the extension and create an example qmd file that you can use as a starting place for your RevealJS Slides.

## Using

Once you have installed the template, you can go to [./template.qmd](./template.qmd) and build upon that file.

For details about using RevealJS in Quarto, please see [Quarto's extensive documentation.](https://quarto.org/docs/presentations/revealjs/)

## Format Options

### `embed-resources: true`

- This is the default option using this template.
- Rather than having separate CSS and other files, it is all contained within the HTML.
    - This makes it easier to distribute as you only need one file.
    - To change this behavior, simply change `true` to `false`.
- For more information, go to [Quarto's documentation.](https://quarto.org/docs/presentations/revealjs/presenting.html#publishing)

### `transition: slide`

- This is the default option using this template.
- This means that there is no animation when you transition between slides.
- There are plenty of other options with RevealJS in Quarto.
    - To change this to another option, simply change `slide` to something else.
- For more information, go to [Quarto's documentation.](https://quarto.org/docs/presentations/revealjs/advanced.html#slide-transitions)

### `scrollable: true`

- This is the default option using this template.
- This option allows for you to scroll through the slide rather than cutting out content if there is overflow.
    - To change this behavior, simply change `true` to `false`.
- For more information, go to [Quarto's documentation.](https://quarto.org/docs/presentations/revealjs/index.html#content-overflow)

### `incremental: false`

- This is the default option using this template.
- This option allows for you to have each bullet point show up incrementally.
    - In other words, rather than showing all bullet points as soon as you transition to a slide, you will need to keep advancing to show each bullet point.
    - To change this behavior, simply change `false` to `true`.
- For more information, go to [Quarto's documentation.](https://quarto.org/docs/presentations/index.html#incremental-lists)

### `slide-number: false`

- This is the default option using this template.
- This option suppresses the display of the number of slides in the presentation.
    - To change this behavior and show the slide count, you can change `false` to a number of possible options for how you would like your slide numbers to appear. 
- For more information, go to [Quarto's documentation.](https://quarto.org/docs/presentations/revealjs/presenting.html#slide-numbers)

### `progress: false`

- This is the default option using this template.
- This option suppresses the display of a progress bar for progress in a presentation.
    - To change this behavior and show the progress bar, you can change `false` to `true`.
- For more information, go to [Quarto's documentation.](https://quarto.org/docs/presentations/revealjs/presenting.html#slide-tone)

### `menu: false`

- This is the default option using this template.
- This option suppresses the display of a hamburger icon that allows you to view a presenter menu for the slides.
    - To change this behavior and show the menu, you can change `false` to `true`.
- For more information, go to [Quarto's documentation.](https://quarto.org/docs/presentations/revealjs/presenting.html#slide-tone)

### `body-color: #ffffff`

- This is the default option using this template.
    - Specified in the ./_extensions/simpledarkjs/custom.scss file
- This option sets the default color of the text for the slide deck and borders for `mermaidJS` nodes to white (`#ffffff`) .
    - To change this behavior to a new color, simply enter a different HTML color value.

### `link-color: #b70000`

- This is the default option using this template.
    - Specified in the ./_extensions/simpledarkjs/custom.scss file
- This option sets the default color of the text for links to a maroon color (`#b70000`).
    - To change this behavior to a new color, simply enter a different HTML color value.

## Example

Here is the source code for a minimal sample document: [example.qmd](example.qmd).

## Maintainers

- [Damon C. Roberts](https://github.com/DamonCharlesRoberts)

## License

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg