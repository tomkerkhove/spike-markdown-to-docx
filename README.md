# Spike - Convert Markdown to .docx

A spike to test the conversion from Markdown to .docx with [pandoc](https://pandoc.org/) CLI.

```shell
cd .\content\
pandoc -o "output.docx" -f markdown --table-of-contents --reference-doc=.\..\templates\template.dotx -t docx (gci *.md -name -file)
```