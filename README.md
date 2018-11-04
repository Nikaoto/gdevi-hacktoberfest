# reveal.js [![Build Status](https://travis-ci.org/hakimel/reveal.js.svg?branch=master)](https://travis-ci.org/hakimel/reveal.js) <a href="https://slides.com?ref=github"><img src="https://s3.amazonaws.com/static.slid.es/images/slides-github-banner-320x40.png?1" alt="Slides" width="160" height="20"></a>

A framework for easily creating beautiful presentations using HTML. [Check out the live demo](http://revealjs.com/).

reveal.js comes with a broad range of features including [nested slides](https://github.com/hakimel/reveal.js#markup), [Markdown contents](https://github.com/hakimel/reveal.js#markdown), [PDF export](https://github.com/hakimel/reveal.js#pdf-export), [speaker notes](https://github.com/hakimel/reveal.js#speaker-notes) and a [JavaScript API](https://github.com/hakimel/reveal.js#api). There's also a fully featured visual editor and platform for sharing reveal.js presentations at [slides.com](https://slides.com?ref=github).

# CUSTOM NOTES
### PDF Export
To convert to pdf, do `npm start` and visit http://localhost:8000/?print-pdf

If pdf should include presenter notes, then visit instead http://localhost:8000/?print-pdf&showNotes=true

Then <kbd>ctrl</kbd> / <kbd>command</kbd> + <kbd>p</kbd> and print to pdf.

1. Open your presentation with `print-pdf` included in the query string i.e. http://localhost:8000/?print-pdf. You can test this with [revealjs.com?print-pdf](http://revealjs.com?print-pdf).
  * If you want to include [speaker notes](#speaker-notes) in your export, you can append `showNotes=true` to the query string: http://localhost:8000/?print-pdf&showNotes=true
1. Open the in-browser print dialog (CTRL/CMD+P).
1. Change the **Destination** setting to **Save as PDF**.
1. Change the **Layout** to **Landscape**.
1. Change the **Margins** to **None**.
1. Enable the **Background graphics** option.
1. Click **Save**.

![Chrome Print Settings](https://s3.amazonaws.com/hakim-static/reveal-js/pdf-print-settings-2.png)

Alternatively you can use the [decktape](https://github.com/astefanutti/decktape) project.
## License

MIT licensed

Copyright (C) 2018 Hakim El Hattab, http://hakim.se
