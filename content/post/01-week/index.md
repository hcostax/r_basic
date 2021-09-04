---
authors:
- hcostax
date: "2020-09-21T00:00:00Z"
draft: false
featured: false
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/IuLgi9PWETU)'
  focal_point: ""
  placement: 2
  preview_only: true
lastmod: "2021-08-08T00:00:00Z"
projects: []
subtitle: "Uma introdução suave ao R, Rstudio e Tidyverse. Esta sessão prática introduz o ciclo da ciência de dados. Nosso foco será o Tidyverse, especificamente os pacotes dplyr e ggplot2."
title: "Dia 1 - 👾 The whole game of Dataviz 📊"
---

No **Dia 1** você terá:

- 👾 **_The whole game_**: uma introdução suave ao R, Rstudio e Tidyverse. Esta sessão prática introduz o ciclo da ciência de dados. Nosso foco será o Tidyverse, especificamente os pacotes dplyr e ggplot2. Tidyverse, é um conjunto acessível de ferramentas consistentes de ciência de dados utilizada através da linguagem de programação estatística R.

- 📊 **_Visualização de dados (dataviz)_**: as habilidades de ciência de dados estão cada vez mais importantes para pesquisas e projetos no mercado. Trabalhar com projetos complexos de ciência de dados trás a necessidades complexas para compreensão e comunicação de processos e resultados da análise final. A caixa de ferramentas de ciência de dados de um analista está incompleta sem habilidades de visualização.

Incorporar visualizações eficazes diretamente na ferramenta de análise que você está usando pode facilitar a rápida exploração de dados, simplificar seu processo de pesquisa e melhorar a reprodutibilidade de sua pesquisa.

Neste módulo vamos focar no ggplot2, uma pacote (biblioteca) para R que cria visualizações claras e bem projetadas baseadas na gramática dos gráficos, e que trabalha bem com outros pacotes de tidyverse.


<br>

### Cronograma


| <div style="width:50px;text-align:center">Data</div> | <div style="width:250px;text-align:left">Tópico</div> | <div style="width:80px;text-align:center">Assíncrona</div> | <div style="width:80px;text-align:center">Síncrona</div> |  <div style="width:80px;text-align:center">Slides</div> | <div style="width:80px;text-align:center">Duração</div> |
|:-------:|:---------------------|:-------:|:-----------:|:--------:|:------:|
| 21/08  | Boas vindas | | | | 19:30 - 19:40 | 
  | 21/08  | Introdução - the whole game 👾 | <span style='color: gray;'><i class='fab fa-youtube fa-lg'></i></span> | <span style='color: gray;'><i class='fas fa-file-video fa-lg'></i></span>  | [<span style='color: gray;'><i class='fas fa-desktop fa-lg'></i></span>](slides/01-whole-game/01-whole-game.html) | 19:40 - 09:45 | 
| 21/08  | Coffee break ☕ | | | | 09:45 - 10:00 | 
| 21/08  | Visualize os dados 📊 | <span style='color: gray;'><i class='fab fa-youtube fa-lg'></i></span> |  | <span style='color: gray;'><i class='fas fa-desktop fa-lg'></i></span> | 10:00 - 10:50 | 
| 21/08  | Code Along | | | | 10:50 - 11:00 |

<br>

**Leituras - Introdutória** 

| <div style="width:50px"></div>  | <div style="width:420px"></div>  |  <div style="width:200px"></div> |
|:---:|:---|:---:|
| 📖 | [Cap 1, Introdução](http://sillasgonzaga.com/material/cdr/introdu%C3%A7%C3%A3o.html) | **Requerido** | 
| 📖 | [Cap 1,  Instalação](https://livro.curso-r.com/1-instalacao.html) | **Requerido** |
| 📖 | [Cap 2,  RStudio](https://livro.curso-r.com/2-rstudio.html) | **Requerido** |
| 📖 | [Cap 2, Conceitos Básicos](http://sillasgonzaga.com/material/cdr/conceitos-b%C3%A1sicos.html) | **Requerido** |
| 📖 | [Cap 3, R Básico](https://socviz.co/appendix.html#a-little-more-about-r) | Opcional | 
| 📄 | [Como ler uma página de ajuda R (inglês)](https://socviz.co/appendix.html#a-little-more-about-r) | Opcional |
| 📄 | [Guia de reprodutibilidade do rOpenSci (inglês)](https://ropensci.github.io/reproducibility-guide/sections/introduction/) | Opcional |
| 📄 | [1.500 cientistas levantam a tampa da reprodutibilidade (inglês)](https://www.nature.com/news/1-500-scientists-lift-the-lid-on-reproducibility-1.19970) | Opcional |
| 🖋 | [Como R me mudou como analista (inglês)](https://nhsrcommunity.com/blog/how-r-changed-me-as-an-analyst/) | Opcional |

<br>

**Leituras - DataViz** 

| <div style="width:50px"></div>  | <div style="width:420px"></div>  |  <div style="width:200px"></div> |
|:---:|:---|:---:|
| 📖 | [Cap 8, Visualisação](https://livro.curso-r.com/8-graficos.html) | **Requerido** | 
| 📖 | [Cap 12,  Visualizações de dados (ggplot2)](http://sillasgonzaga.com/material/cdr/ggplot2.html) | **Requerido** |
| 📖 | [Cheatsheet (inglês)](https://github.com/rstudio/cheatsheets/blob/master/data-visualization-2.1.pdf) | **Requerido** |
| 📖 | [Cap 3, Data visualisation (inglês)](https://r4ds.had.co.nz/data-visualisation.html) | **Requerido** |
| 📖 | [Cap 28, Graphics for communication (inglês)](https://r4ds.had.co.nz/graphics-for-communication.html) | **Requerido** | 
| 📄 | [Make a plot (inglês)](https://socviz.co/makeplot.html) | Opcional |
| 📄 | [Explorar tendências de pesquisa de sintomas COVID-19 (inglês)](https://pair-code.github.io/covid19_symptom_dataset/?date=2020-09-07&country=GB) | Opcional |
| 📄 | [Data Visualization with ggplot2 (inglês)](https://towardsdatascience.com/data-visualization-with-ggplot2-db04c4956236) | Opcional |
| 🖋 | [A Comprehensive Guide to the Grammar of Graphics for Effective Visualization of Multi-dimensional Data (inglês)](https://towardsdatascience.com/a-comprehensive-guide-to-the-grammar-of-graphics-for-effective-visualization-of-multi-dimensional-1f92b4ed4149) | Opcional |

<br>

### Code-along

Para o **_Dia 1_** vamos trabalhar com os [Dados de economia de combustível de 1999 a 2008 para 38 modelos populares de carros](https://ggplot2.tidyverse.org/reference/mpg.html) do pacote ggplot2. Este conjunto de dados contém um subconjunto dos dados de economia de combustível disponibilizado em https://fueleconomy.gov/. Ele contém apenas modelos que tiveram um novo lançamento a cada ano entre 1999 e 2008 - este foi usado como um proxy para a popularidade dos carros.


| <div style="width:200px"></div>  | <div style="width:480px"></div>  |
|:---|:---|
| Gravação | <span style="color: gray;"><i class="fab fa-youtube fa-lg"></i></span>  |
| Script | **`01_code-along.R`** |
| Relatório | **`01_code-along.Rmd`** |

<br>

### Tutoriais interativos no RStudio Cloud

O seguinte tutorial interativos na plataforma do RStudio Cloud, foi projetados para dar-lhe mais prática com R. Se você está tendo dificuldades com qualquer um dos tópicos abordados no **_Dia 1_**, recomendo fortemente que você trabalhe através deste tutorial. _Uma observação importante: este tutorial está completamente em inglês_.


|  <div style="width:480px"></div>  |  <div style="width:200px"></div>  |
|:---|:---|
| [Noções básicas de visualização de dados (inglês)](https://rstudio.cloud/learn/primers/1.1) | Prática extra |
