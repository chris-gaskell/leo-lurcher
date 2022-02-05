---
title: 'All Bark and no Bite'
subtitle: 'An insight into the anxiously aggressive pupper'
author:
- Leo de Lurchio
- Dr. Chris Gaskell
date: '2022-02-05'
site: bookdown::bookdown_site
documentclass: book
bibliography:
- book.bib
- packages.bib
link-citations: true
biblio-style: apalike
description: This is a book about me, Leo
favicon: "test.ico"
cover-image: "https://vetstreet.brightspotcdn.com/dims4/default/630978f/2147483647/crop/0x0%2B0%2B0/resize/645x380/quality/90/?url=https%3A%2F%2Fvetstreet-brightspot.s3.amazonaws.com%2Fe0%2F88adb0c81f11e09b940050568d6ceb%2Ffile%2FLurcher-3-AP-645km081611.jpg"
github-repo: "chris-gaskell/leo-lurcher/book"
always_allow_html: yes
url: "https://leo-biography.app"
---


```r
library(metathis)
meta() %>%
  meta_description(
    "Leo the lurcher"
  ) %>% 
  meta_name("github-repo" = "chris-gaskell/leo-lurcher/book") %>% 
  meta_viewport() %>% 
  meta_social(
    title = "Leo the Lurcher",
    url = "https://leo-biography.netlify.app",
    image = "https://github.com/chris-gaskell/leo-lurcher/blob/main/book/nervous_leo.png?raw=true",
    image_alt = "picture of Leo",
    og_type = "book",
    og_author = c("Chris Gaskell", "Leo de Lurchio"),
    twitter_card_type = "summary",
    twitter_creator = "@cgaskell92"
  )
```


# About {-}

<div style= "float:right;position: relative; top: 0px;">
<img src="/Users/christophergaskell/Desktop/leo-lurcher/book/nervous_leo2.jpeg" width="255" />

</div>

Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image. Testing out how to wrap text around an image. Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image. Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.


This is a _sample_ book written in **Markdown**. You can use anything that Pandoc's Markdown supports; for example, a math equation $a^2 + b^2 = c^2$.

## Usage 

Each **bookdown** chapter is an .Rmd file, and each .Rmd file can contain one (and only one) chapter. A chapter *must* start with a first-level heading: `# A good chapter`, and can contain one (and only one) first-level heading.

Use second-level and higher headings within chapters like: `## A short section` or `### An even shorter section`.

The `index.Rmd` file is required, and is also your first book chapter. It will be the homepage when you render the book.

## Render book

You can render the HTML version of this example book without changing anything:

1. Find the **Build** pane in the RStudio IDE, and

1. Click on **Build Book**, then select your output format, or select "All formats" if you'd like to use multiple formats from the same book source files.

Or build the book from the R console:


```r
bookdown::render_book()
```

To render this example to PDF as a `bookdown::pdf_book`, you'll need to install XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX): <https://yihui.org/tinytex/>.

## Preview book

As you work, you may start a local server to live preview this HTML book. This preview will update as you edit the book when you save individual .Rmd files. You can start the server in a work session by using the RStudio add-in "Preview book", or from the R console:


```r
bookdown::serve_book()
```




## test call outs

::: {.rmdnote}
## This is a note call out
:::

::: {.rmdcaution}
This is a caution call out
:::

::: {.rmdimportant}
This is a important call out
:::

::: {.rmdtip}
This is a caution call out
:::

::: {.rmdwarning}
This is a caution call out
:::

## this is a bit more complicated

This is done using the guidance here:
https://stackoverflow.com/questions/36293511/creating-custom-blocks-in-rstudios-bookdown/36343616

<div class="rmdcomment2">
<p>Some text for this block. Some text for this block. Some text for this block. Some text for this block. Some text for this block. Some text for this block.</p>
</div>


```r
#knitr::include_graphics("https://imgs.xkcd.com/comics/correlation.png")
```


Testing out how to wrap text around an image. Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.








