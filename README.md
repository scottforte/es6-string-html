# ES6 String HTML 
> [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=Tobermory.es6-string-html)

Adds syntax highlight support for code, placed in es6 multiline strings:
- HTML (incl. html quoted and unquoted attrs)
- SQL
- XML

## Community
- [es6-string-css](https://github.com/bashmish/es6-string-css) - Highlight CSS in ES6 template literals
- [python-string-sql](https://github.com/ptweir/python-string-sql) - Highlight SQL code in python multiline strings
- [es6-string-javascript](https://github.com/Zjcompt/es6-string-javascript) - Highlight JS in multiline strings

## Installation

- Install `es6-string-html` from extensions (`ctrl + shift + x`)

## Donation

If this project help you reduce time to develop, you can give me a cup of coffee :)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=68P8BFSZPG5H2)

## Example

![Example](docs/demo.png)

## Usage

Simply insert the comment /\*html\*/ or `html` (or sql instead of html) before the string
(see Requirements "section" for possible values) or select
`Insert es6-string-html comment/template` from the commands menu
(`ctrl+shift+p` or `f1`)

> Tip: Comment in the beginning of es6 string is required

## Requirements

- Visual Studio Code v1.19.0 recommended
- Comment `/*html*/` before the string. Possible values:
- - `/*HTML*/`
- - `/*html*/`
- - `/*inline-html*/`
- - `/*template*/`
- - `/*inline-template*/`
- Or
- - `html` before the string

## Release Notes

### [...]
- See changelog for previous notes

### [1.8.8] - 2019-04-12
- Match all caps for SQL (by @thebrodmann)

### [2.0.0] - 2019-04-12
- Highlight HTML w/o comments

### [2.2.0] - 2021-03-04
- Fix highlighting for cases, when there is space right after the /*html*/ comment

### [2.3.0] - 2021-04-23
- Support for uppercase /* HTML */

### [2.4.0] - 2021-04-23
- Support for XML

### [2.5.0] - 2021-04-23
- Ignore casing

### [2.5.1] - 2021-04-23
- Syntax highlighting breaks with multiple placeholders in the same attribute
- Support SVG
-----------------------------------------------------------------------------------------------------------

**Enjoy!**
