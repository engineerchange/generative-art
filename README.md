# generative-art

> This is a quick xaringan deck on generative art and non-fungible tokens (NFTs). This is from a mild amount of research on both topics.

[Slides](https://github.com/engineerchange/generative-art/raw/master/generative-art.pdf)

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
pagedown::chrome_print("slides.Rmd","generative-art.pdf")
```

Note: there is an issue with the rarible slide; could not get to work with pagedown::chrome_print() or xaringan:decktape(). Have to delete that slide in order for the pdf to generate.

## Further info, check out
- Some of the R visuals: [mathart](https://github.com/marcusvolz/mathart)
- Presentation layout and design: [xaringan](https://github.com/yihui/xaringan)
- [genuary2021](https://genuary2021.github.io/)
- [@accidental__art](https://twitter.com/accidental__art)
