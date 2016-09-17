# SPSA Invoices

Copy `template.tex` to `YYYYMMDD-<serial>-<slug>.tex` and change the content to
your liking.

For compiling, you can use a tool like [rubber](https://github.com/petrhosek/rubber)...

    rubber -m pdftex <input>.tex

Or you can use a tool like `pdflatex` or `xelatex` directly.

    pdflatex <input>.tex

Keep in mind that you may have to call `pdflatex` multiple times for everything
to be correct, that's why I usually prefer wrapper scripts like rubber.
