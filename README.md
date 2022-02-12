
<!-- README.md is generated from README.Rmd. Please edit that file -->

# templates.SER

<!-- badges: start -->
<!-- badges: end -->

Este pacote está em desenvolvimento. O objetivo do pacote
`templates.SER` é deixar disponível templates em RMarkdown para utilizar
no evento [SER](http://ser.uff.br/).

## Instalação

Você pode instalar através do GitHub utilizando o seguinte código:

``` r
# install.packages("devtools")
devtools::install_github("eventoseroficial/templates.SER")
```

Após a instalação, você pode utilizar o seguinte código para incorporar
esse template a lista dos modelos do RMarkdown:

``` r
rmarkdown::draft("minha apresentação.Rmd", template = "slides", package = "templates.SER")
```

![](https://raw.githubusercontent.com/eventoseroficial/templates.SER/master/img/imagem1.png)

Apresentação feita com o pacote xaringan.
