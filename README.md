# passthrough_rate
An exploration of internal website traffic in R.

This was a timed exercise that I chose to do with dplyr syntax while I was
learning to use the tidyverse. Usually I use data.table syntax. This was
an exploratory data analysis project with no concrete objective; I chose to
explore "passthrough target rate", the proportion of pages' traffic that
comes from other pages within the site. Because the dataset did not include
source urls, I had to infer passthroughs based on visit times.

This repo does not include the proprietary 2-million record dataset used in
the analysis. Users will not be able to knit the .RMD file without this
dataset, so a fully-knit .html document of the final output is included.
Page URLs are anonymized.
