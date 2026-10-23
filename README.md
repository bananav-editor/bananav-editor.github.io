<p align="center">
  <img src="assets/img/bananav-icon.svg" alt="BananaV's logo" width="120">
</p>

<h1 align="center">BananaV's website</h1>

<p align="center">
  The source of <a href="https://bananav-editor.github.io/">bananav-editor.github.io</a>,
  the home page of BananaV, a free and open-source video editor for Windows and Linux.
</p>

- One static page: `index.html`, `assets/style.css` and `assets/main.js`. No build
  step: GitHub Pages serves this repository as it is.
- Written in English; `assets/i18n.js` holds the translations the language menu
  offers (Brazilian Portuguese today). A text changed in `index.html` needs its
  entry changed there too, and a new language is a new table plus a line in the
  menu.
- Preview it locally: `python -m http.server 8765`, then open http://localhost:8765.
- The screenshots show only BananaV and media it generates itself.

Talk to us on [Discord](https://discord.gg/vtC7Yasz98).

The website is free software under the GNU General Public License, version 3 or
later ([LICENSE](LICENSE)). The BananaV name and logo are the project's marks.
