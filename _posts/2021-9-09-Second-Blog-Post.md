Programming Background
================
Alex Prevatte
9/9/2021

``` r
rmarkdown::render("~/NCSU/ST558/Repos/aprevatte.github.io/_Rmd/2021-9-09-Second-Blog-Post.Rmd", 
              output_format = "github_document", 
              output_dir = "~/NCSU/ST558/Repos/aprevatte.github.io/_posts/",
              output_options = list(
                html_preview = FALSE
                )
              )
```

## Thoughts about R Programming Language

Before taking ST558 I used R, Python, and SAS for statistics and data
analysis. R is the language I am most comfortable working in, and in my
opinion, it is more intuitive than Python or SAS. I started learning R
in my college statistics course, and I thought it was challenging. At
that time I had no experience with programming and it was steep learning
curve. After spending more time with the software, I started using it
over Excel for my data needs which went a long way.

I also learned some Python in college. Though Python has greater
functionality than R, I prefer doing statistics in R. I like how useful
the tidyverse is for manipulating data, and the graphs from ggplot look
nice. I don’t miss many parts of SAS, which is the language I used in
previous graduate classes. In my opinion, much of what I could do in SAS
could be performed in R with less code. Also, there is greater
flexibility in R for customization which I really like.

## Example R Markdown Output

``` r
plot(iris)
```

![](../imagesunnamed-chunk-3-1.png)<!-- -->
