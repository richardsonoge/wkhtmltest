I can't convert this HTML file to PDF with "wkhtmltopdf 0.12.6.1 (with patched qt)".
Here's the command I ran in my Terminal.

    ```bash
    wkhtmltopdf notice.html notice.pdf
    ```
I had used this command to convert my PDF file to HTML with the pdf2htmlEX command

```bash
pdf2htmlEX --process-outline 0 --fit-width 1024 --space-as-offset 1 notice.pdf notice.html
```

It returned an empty PDF. I had used an older version of wkhtmltopdf, 
but it had mentioned in my Terminal to install the static version "wkhtmltopdf 0.12.6.1 (with patched qt)" but the installation of this version it became worse than the old version which was not complete. In the old version, it didn't support CSS, JS and complex fonts but in this current version "wkhtmltopdf 0.12.6.1 (with patched qt)" it's worse I don't know what to do here. What should I do?
