Comando para crear un Word del que sacremos un PDF
```bash
pandoc -o output.docx -f markdown -t docx filename.md
```


Comando para convertir un word a Markdown de vuelta
```bash
pandoc -s output.docx -t markdown -o output.md
```