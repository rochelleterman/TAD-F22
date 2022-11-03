# Tech Requirement and Installation

To participate in PLSC 21510/31510, you will need access to the software described below. Please intall them before the first class. 

##  R

[R](http://www.r-project.org/) is a programming language that is especially powerful for data exploration, visualization, and statistical analysis. 

For this class, please install **R version 4.2.1 (Funny-Looking Kid)**. 

To download R, go to [CRAN](https://cran.r-project.org/) (the **C**omprehensive **R** **A**rchive **N**etwork). Ensure that you download **R version 4.2.1 (Funny-Looking Kid)**.

## RStudio

To interact with R, we use RStudio. Please install the latest desktop version of [RStudio IDE](http://www.rstudio.com/ide/download/desktop). We will not support RStudio Cloud.

## R Packages

You will also need to install the following R packages: `tidyverse, knitr, rtweet, devtools, quanteda, quanteda.textmodels, quanteda.textstats, quanteda.textplots, spacyr, wordcloud, matrixStats, SnowballC, tidytext, textdata, stm, readtext`

To download a couple other packages, run this code in RStudio:

```{r}
devtools::install_github("quanteda/quanteda.corpora")
devtools::install_github("kbenoit/quanteda.dictionaries")
```

__NB__: We will need to install additional packages as the class progresses.

## LaTeX

In order to knit R Markdown files to PDF files, you need to install some version of LaTeX. For students who have not installed LaTeX before, we recommend that you install TinyTeX (https://yihui.name/tinytex/).

Open RStudio and type these lines into the command-line console:

```{r}
install.packages("tinytex")
tinytex::install_tinytex() 
```

## Git

Git is a version control system that lets you track who made changes to what when and has options for easily updating a shared or public version of your code on github.com. 

Download git here: https://git-scm.com/downloads.

After installing Git, there will not be anything in your `/Applications` folder, as Git is a command line program.

## Google Chrome

You will need to have a modern web browser installed to perform some of the tasks in this class. The recommended browser for this class is [Google Chrome](https://www.google.co.uk/intl/en_uk/chrome/).

## Selector Gadget

As part of the webscraping process, you will need to examine HTML elements in your data. In this class we will be using [Selector Gadget](https://selectorgadget.com/) for this purpose.

If using Google Chrome, you can simply install the [Selector Gadget Chrome extension](https://chrome.google.com/webstore/detail/selectorgadget/mhjhnkcfbdhnjickkkdbjoemdmbfginb?hl=en). If for any reason you cannot use Chrome extensions (including on Chrome itself), you can instead install Selector Gadget by following the instructions on the [Selector Gadget website](https://selectorgadget.com/).

## Other Helpful Tools

While not required, I recommend you install [Sublime Text](https://www.sublimetext.com/3), which is a free, advanced text editor. 

## Troubleshooting

Software Carpentry maintains a list of common issues that occur during installation that may be useful for our class here: [Configuration Problems and Solutions wiki page](https://github.com/swcarpentry/workshop-template/wiki/Configuration-Problems-and-Solutions).

If you still have difficulties installing, please post a question on Piazza with details on what you are trying to install, what actions you took, any error messages, etc.
