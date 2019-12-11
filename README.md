# Spike - Convert Markdown to .docx

A spike to test the conversion from Markdown to .docx with [pandoc](https://pandoc.org/) CLI.

```shell
cd .\content\
choco install pip
pip install pandoc-mermaid-filter
pandoc -o "output.docx" -f markdown --table-of-contents --filter pandoc-mermaid --reference-doc=.\..\templates\template.dotx -t docx (gci *.md -name -file)
```