# Fruition Hardware Specs

These are the hardware specification sheets for the products of FRUITION CO.,
LTD. These are typeset using the KOMA-script `scrreprt` class. The full
revision history of each file is contained in the commit history of this
repository.

## Compiling the TeX files

Install `texlive` either from the website (if using Windows/MacOS) or your
distribution's package manager (if using GNU/Linux).

Make sure to install the necessary CJK fonts for `texlive` to compile some of
the TeX files with Chinese. These are typically contained in a separate package
due to their immense size. In Arch Linux, this is contained in the
`texlive-langchinese` package.

Finally, simply run:

```
pdflatex [FILENAME].tex
pdflatex [FILENAME].tex
```

It is important that you run the above twice, as to generate the table of
contents properly.

## Tables

These documents take advantage of the `csvsimple` package, which allow them to
easily render tables from existing CSV files. Simply edit the CSV file in the
`tables` directory of whatever module page you are editing, and re-compile TeX
file (twice) to generate the edited table.

## Contributing

Please send me an email at `dvdqiu541 [AT] gmail [DOT] com` if you need help
contributing to the specification sheets.
