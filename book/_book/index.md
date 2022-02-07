---
title: 'All Bark and no Bite'
subtitle: 'An insight into the anxiously aggressive pupper'
keywords: "testing" 
author:
- Leo de Lurchio
- Dr. Chris Gaskell
date: '2022-02-06'
site: bookdown::bookdown_site
documentclass: book
bibliography:
- book.bib
- packages.bib
link-citations: true
biblio-style: apalike
description: This is a book about me, Leo the lurcher
favicon: "test.ico"
cover-image: "https://github.com/chris-gaskell/leo-lurcher/blob/main/book/images/nervous_leo.jpeg?raw=true"
github-repo: "chris-gaskell/leo-lurcher/book"
always_allow_html: yes
url: "https://leo-biography.nerlify.app"
---


```r
library(metathis)
knitr::write_bib(c(.packages(), "bookdown"), "packages.bib")
```


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
    image = "https://github.com/chris-gaskell/leo-lurcher/blob/main/book/images/nervous_leo.jpeg?raw=true",
    image_alt = "picture of Leo",
    og_type = "book",
    og_author = c("Chris Gaskell", "Leo de Lurchio"),
    twitter_card_type = "summary",
    twitter_creator = "@cgaskell92"
  )
```

# Leo the Lurcher {-}

<div style= "float:right;position: relative; top: 0px;">
<img src="images/nervous_leo.jpeg" width="184" />

</div>

Thank you for buying my first book!

My name is Leo. I'm a 4 year old lurcher pup. This book is all about what it means when I barks.

Testing some more text alignment, Testing some more text alignment, Testing some more text alignment, Testing some more text alignment, Testing some more text alignment, Testing some more text alignment, Testing some more text alignment,

::: {.infobox .caution}
**Note**: This book has yet to be picked up by a major publisher. The online version of this book is free to read here, and licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/). If you have any feedback, please feel free to [file an issue on GitHub](https://github.com/chris-gaskell/leo-lurcher/book). Thank you!
:::
before you think about leaving... let me leave you with a little message.
<p style="text-align: center;"><a href="https://www.routledge.com/p/book/9780367563837"><img src="https://media4.giphy.com/media/u5cc08LvthuBa7HwEU/200.gif?cid=ecf05e47j7uqkv61hg634eie1zl04d868nsrg3sx87tje91l&rid=200.gif&ct=g" alt="please don't go" /></a></p>


# Usage {-}

I recommend that you read this book cover-to-cover.

Here are some features of the book

<div class="pawcomment">
<h3 class="unnumbered" id="raise-a-paw">Raise a paw</h3>
<p>If you have a question. Simply raise a paw.</p>
</div>

<div class="bonecomment">
<h3 class="unnumbered" id="have-a-treat">Have a treat</h3>
<p>Here is a greatttttt tip!</p>
</div>

<div class="dogcomment">
<h3 class="unnumbered" id="fancy-a-walk">Fancy a walk</h3>
<p>Here is a task for you</p>
</div>



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

<div class="rmdcomment2">
<p>Some text for this block. Some text for this block. Some text for this block. Some text for this block. Some text for this block. Some text for this block.</p>
</div>


```r
#knitr::include_graphics("https://imgs.xkcd.com/comics/correlation.png")
```


Testing out how to wrap text around an image. Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.Testing out how to wrap text around an image.


::: {.flushright data-latex=""}
Yihui Xie  
Elkhorn, Nebraska
:::



