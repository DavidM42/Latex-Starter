# Latex-Starter

This is my latex starter project for use with vscode.
It is setup for A4 [https://apastyle.apa.org/](APA-Style papers) as default but can be easily changed just like any LateX project.
Some workarounds and configurations to use it with the german language are included but can be removed or adapted to other localizations.

## It features
* 🗄️ A Solid base structure of
  * 📄 Document itself
  * 📂 Source files
* 👨‍💻 Nice vscode working environment familiar to many programmers
* 🌐 Github actions to preview/download resulting PDF online
* ✍️ Really good Grammar, Style and Spell Checking by [languagetool](https://languagetool.org/)
* ❓ Examples for common things in LateX like
  * Citing with biblatex
  * Tables
  * PDF embeddings
  * Picture embeddings
  * Links and Table of content


## Github actions are configured to 
* Automatically build a pdf file
* Make it available as artifact in the build
* Deploy it to `gh-pages` branch for github pages (see [preview online](https://davidm42.github.io/Latex-Starter/))
You may have to turn off github pages in the repository settings or switch them to master, then back to `gh-pages` branch as source for it to work

## How to use
0. Install latex obviously
1. Fork repo, use as template or clone repo directly `git clone git@github.com:DavidM42/Latex-Starter.git`
2. Install and setup [latex workshop addon](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) (for [more info](https://github.com/James-Yu/LaTeX-Workshop/wiki/Install))
3. Install [ltex addon](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex) for spellchecking
4. For language config see localization
5. Start editing!
The addon willl start building and refreshing the pdf on every save


## Localization
1. Open settings.json file in project
2. First line `"ltex.language": "de-DE",` change the value to your language and region for ltex spellcheck (see [for more info](https://github.com/valentjn/vscode-ltex#extension-settings))
3. Go to `main.tex` search for german and edit all values to your language
4. And remove all german specific stuff
