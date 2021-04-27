# generative-art

## Install packages before running first time
```
install.packages("xaringan")
devtools::install_github("marcusvolz/mathart")
```

## Run xaringan
```
xaringan::inf_mr()
```

## To build as PDF
```
xaringan::decktape("slides.Rmd","generative-art.pdf")
```

Note: there is an issue with the rarible slide. Have to delete that in order for pdf to generate.
