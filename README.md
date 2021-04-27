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
remotes::install_github("jhelvy/xaringanBuilder")
xaringanBuilder::build_pdf("slides.Rmd")
```
