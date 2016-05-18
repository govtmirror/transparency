# transparency

A paper to help Social and Behavioral Science teams do good science in the service of good government.

Open science and open government are both good things. We are trying to do open
science in the service of good government, which may often be open government. 

We are not yet sure about how open government and open science ought to relate
to good government, even if we have a pretty good sense about how open science
relates to good science.

# To build a pdf from the markdown

If you have pandoc installed on your system, replace the path to your bibtex file and do:

```
pandoc -r markdown+simple_tables+table_captions+yaml_metadata_block --mathjax --bibliography=/Users/jwbowers/Documents/PROJECTS/BIB/big.bib --to=latex  -s -S  --normalize --filter pandoc-crossref --filter pandoc-citeproc OpenSBST.md --template=bowersarticletemplate.latex -o OpenSBST.pdf
```

