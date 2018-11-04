# gdevi-hacktoberfest
Gdevi #7

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
