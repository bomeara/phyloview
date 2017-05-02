# phyloview
Overview of the state of phylogenetic information for a group of organisms. Run through Rstudio.

If you want to just enter the name (say, "formicidae"), just call

```
rmarkdown::render("phyloview.Rmd", params = list(
  clade = "formicidae"
))
```

If you want a pop up to type this in, use the code below.

```
rmarkdown::render("phyloview.Rmd", params = "ask")
```

Will let you enter a name of a clade and get the state of info.
