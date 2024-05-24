# Analyze with regex office documents

To use only with doc, ppt and xls files.

```bash
$ find . -regextype egrep -regex '.+(doc|ppt|xls)$' | xargs -d '\n' grep -Pria 'regexToSearch' --color always
```

To analyze docx, pptx and xlsx files use the script "unzipOfficeFiles"
