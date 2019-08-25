# Payseur Lab R Markdown Workshop

The goal of this workshop is to introduce you to R Markdown and get you to try it out. This will not be comprehensive, but it will get you started. 

## Pre-Workshop Instructions 

First, make sure that your laptop has a working version of R and RStudio. Install the following packages in order to run the example:

~~~~~~~~~~~~~~~~~~
install.packages("knitr")
install.packages("ggplot2")
install.packages("kableExtra")
~~~~~~~~~~~~~~~~~~

You may get more out of the workshop if you bring your own data! If you want, bring an R script you already have, or even just a data set. If you have a big data set on your desktop, you can subset it and save that as an R image using `saveRDS(dataframe, file = "mydata.rds")` and bring that. If you aren't currently using R, just bring a dataset and we can get it loaded in. 

Choose something that you can make simple figures from, or bring the code to make the figure, too. 

Finally, download this workshop using one of the two options below. 

1. With Git: 
~~~~~~~~~~~~~~~~~~
git clone https://github.com/mfrayer/rmarkdown-ws.git
~~~~~~~~~~~~~~~~~~
2. Download directly from GitHub: Go to `https://github.com/mfrayer/rmarkdown-ws`, click `Clone or Download` and `Download Zip`. 


## Workshop Itinerary 

1. Set Up 
2. Introduction using `workshop.Rmd`
3. Try it out using `skeleton.Rmd`
4. Discuss other features using `data_example_html.Rmd`


## A Note on Data Example 

The `data_example_html` and `data_example_pdf` files are very basic R Markdown reports with examples of some additional features. Feel free to play around with them or use them as guides. Running them with all of thier features may require the installation of additional programs. 
