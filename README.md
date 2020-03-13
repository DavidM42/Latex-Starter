# Latex-Starter

This is a latex starter project for use in vscode. It's default setup is for a4 apa-style papers.
Some german workaround and configurations are included but can be removed or changed to other localizations

## How to use
0. Install latex obviously
1. Get repo `git clone TODO`
2. Install and setup [latex workshop addon](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) (for [more info](https://github.com/James-Yu/LaTeX-Workshop/wiki/Install))
3. Install [ltex addon](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex) for spellchecking
4. Install language pack addon for your language (just search `ltex <your_language> support` in vscode marketplace)
5. For language config see localization
6. Start editing!


## Localization
1. Open settings.json file in project
2. First line `"ltex.language": "de-DE",` change the value to your language and region for ltex spellcheck (see [for more info](https://github.com/valentjn/vscode-ltex#extension-settings))
3. Go to `main.tex` search for german and edit all values to your language
4. And remove all german specific stuff