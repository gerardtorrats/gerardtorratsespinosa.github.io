---
title: "Data Demo 1"
subTitle: "This is the Subtile"
id: teaching
sidebar: true
date: "2019-11-30"
Plotly: true

# Summary. An optional shortened abstract.
summary: This study investigates the effect of violent crime on school district–level achievement in English language arts (ELA) and mathematics. The research design exploits variation in achievement and violent crime across 813 school districts in the United States and seven birth cohorts of children born between 1996 and 2002. The identification strategy leverages exogenous shocks to crime rates arising from the availability of federal funds to hire police officers in the local police departments where the school districts operate. Results show that children who entered the school system when the violent crime rate in their school districts was lower score higher in ELA by the end of eighth grade, relative to children attending schools in the same district but who entered the school system when the violent crime rate was higher. A 10% decline in the violent crime rate experienced at ages 0–6 raises eighth-grade ELA achievement in the district by 0.03 standard deviations. Models that estimate effects by race and gender show larger impacts among Black children and boys. 

btn:
- url : "#"
  name: 
- url : "#"
  name: 

catType: "Columbia University"
---
## demo text

This is a post written in plain Markdown (`*.md`) instead of R Markdown (`*.Rmd`). The major differences are:

- ABC
- CDE

1. You cannot run any R code in a plain Markdown document, whereas in an R Markdown document, you can embed R code chunks (```` ```{r} ````);
2. A plain Markdown post is rendered through [Blackfriday](https://gohugo.io/overview/configuration/), and an R Markdown document is compiled by [**rmarkdown**](http://rmarkdown.rstudio.com) and [Pandoc](http://pandoc.org).

There are many differences in syntax between Blackfriday's Markdown and Pandoc's Markdown. For example, you can write a task list with Blackfriday but not with Pandoc:

- [x] Write an R package.
- [ ] Write a book.
- [ ] ...
- [ ] Profit!

Similarly, Blackfriday does not support LaTeX math and Pandoc does. I have added the MathJax support to this theme ([hugo-lithium](https://github.com/yihui/hugo-lithium)) but there is a caveat for plain Markdown posts: you have to include math expressions in a pair of backticks (inline: `` `$ $` ``; display style: `` `$$ $$` ``), e.g., `$S_n = \sum_{i=1}^n X_i$`.^[This is because we have to protect the math expressions from being interpreted as Markdown. You may not need the backticks if your math expression does not contain any special Markdown syntax such as underscores or asterisks, but it is always a safer choice to use backticks. When you happen to have a pair of literal dollar signs inside the same element, you can escape one dollar sign, e.g., `\$50 and $100` renders "\$50 and $100".] For R Markdown posts, you do not need the backticks, because Pandoc can identify and process math expressions.

When creating a new post, you have to decide whether the post format is Markdown or R Markdown, and this can be done via the `ext` argument of the function `blogdown::new_post()`, e.g.

```r
blogdown::new_post("Post Title", ext = '.Rmd')

```


**USE fence code like below**

`$S_n = \sum_{i=1}^n X_i$`

## Step 1
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

## Step 2
 Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Step 3
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Step 4
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Step 5
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


``Use `code` in your Markdown file.``

```python 
def foo():
  x = 1
  y = 2
  z = 3
```

```js 
def foo():
  x = 1
  y = 2
  z = 3
```
```ruby
def hello object
  puts "Hello, #{object}"
end 
```

```r
a <- c(1:7, NA)
mean(a, na.rm = TRUE)
```
 


## Tables

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

### Alignment

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |


{{ < plot  id="myDiv" >}}
  hello
{{ < /plot > }}



{{< html-window src="/blog/new-hugo-post/html-for-blog-post.html" title="Html" width="100%" >}}