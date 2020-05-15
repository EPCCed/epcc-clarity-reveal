# EPCC Clarity Reveal.JS JavaScript Template

epcc_clarity.thmx-style HTML presentation built using [reveal.js](https://github.com/hakimel/reveal.js)

---

## Install nodejs (optional)

[nodejs](https://nodejs.org)

* Download for Windows (x64) 12.16.2 LTS.
* Double-click node-v12.16.2-x64.msi and follow instructions.

```console
$ cd ps-2021
$ npm install
```

---

## Present

Open .html page in browser.

---

## Print to PDF

Start a web server:

* Python example:

```console
$ python -m http.server --bind 127.0.0.1
```

* nodejs example:

```console
$ npm start
```

Open http://localhost:8000 to view your presentation

In Google Chrome:

* Visit http://127.0.0.1:8000/PAGE.html?print-pdf
* Print...

For full details, see [PDF export](https://github.com/hakimel/reveal.js/#pdf-export).

---

## Copyright and licencing

The following files were imported from reveal.js-3.9.2 and are Copyright (C) 2020 Hakim El Hattab, http://hakim.se, and reveal.js contributors and are released under the [MIT License](./LICENSE):

```
.gitignore
.travis.yml
bower.json
CONTRIBUTING.md
css/ # Except for epcc.css.
demo.html
gruntfile.js
index.html
js/
lib/
LICENSE
package.json
package-lock.json
plugin/
README.md
test/
```

`README.md` was replaced by the current content. The original content can be seen at [hakimel/reveal.js/blob/3.9.2/README.md](https://github.com/hakimel/reveal.js/blob/3.9.2/README.md)

The following files are Copyright 2020 The University of Edinburgh and are released under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/):

```
img/
EpccClarityReveal.html
README.md
```
