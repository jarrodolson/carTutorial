# Car Tutorial Repo

This is a repo for me to track some notes from re-building my 1977 Camaro LT/RS and if they are helpful to anyone, please feel free to contribute!

To build:

```bash
#HTML
pandoc -o <file>.html -c css/pandoc.css <file>.md

#PDF
pandoc -o <file>.pdf -V geometry:margin=1in <file>.md
```