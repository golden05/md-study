# using pandoc with markdown

pandoc like swiss army knife for performing file conversions,

## getting start

download and install, pandoc is command line tool.

## converting file to html

```
pandoc filename.md -f markdown -t html -o filename.html
```

get the body of html file

## creating a full html file

```
pandoc filename.md -f markdown -t html -s -o filename.html
```

s is standalone meaning an html file with a container with

## adding a bit of style to your html files

using casading style sheets file. with css you can change fonts, sizes, colors, properties, and more.

```
pandoc filename.md -f markdown -t html -s -c myCss.css -o filename.html
```

## going from markdown to word processor

### creating a simple word processor file

format used by LibreOffice Writer. odt is short for OpenDocument text

```
pandoc -o filename.odt filename.md
```

## going from markdown to pdf

version 2.0 of pandoc introduced an option called --pdf-engine
can use TeX to create PDF files, and use lighter PDF tools:

- [WeasyPrint](https://weasyprint.org/)
- [wkhtmltopdf](https://wkhtmltopdf.org/)

```
pandoc filename.md --pdf-engine=engineName -o filename.pdf
```

### add a bit of style to a pdf file

```
pandoc filename.md --pdf-engine=engineName -c printCss.css -o filename.pdf
```
