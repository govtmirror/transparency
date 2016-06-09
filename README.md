# A collection of thoughts and resources about doing good science in the service of good government

A paper to help Social and Behavioral Science teams do good science in the service of good government.

Open science and open government are both good things. We are trying to do open
science in the service of good government, which may often be open government. 

We are not yet sure about how open government and open science ought to relate
to good government, even if we have a pretty good sense about how open science
relates to good science.

[HTML Version of the paper](http://htmlpreview.github.io/?https://github.com/sbstusa/transparency/blob/master/OpenSBST.html)

# To build a pdf from the markdown

If you have [pandoc](http://pandoc.org/getting-started.html) installed on your system, and you are using the unix command line, replace the path to your bibtex file and do:

```
pandoc -r markdown+simple_tables+table_captions+yaml_metadata_block --mathjax --bibliography=references.bib --to=latex  -s -S  --normalize --filter pandoc-crossref --filter pandoc-citeproc OpenSBST.md --template=bowersarticletemplate.latex -o OpenSBST.pdf
```

