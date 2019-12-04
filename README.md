# Spike - Convert Markdown to .docx

A spike to test the conversion from Markdown to .docx with [pandoc](https://pandoc.org/) CLI.

```shell
pandoc -o output.docx -f markdown --reference-doc=.\templates\template.dotx -t docx .\content\Chapter-1.md
```