# How to use this website  `gerardtorratsespinosa.github.io`


# Prerequisites for Local testing

Firstly, ensure you have installed the latest  version of Hugo. See installation steps from Hugo’s official docs.

## Download  the website code 

Clone this repository into your Hugo project.

```
git clone https://github.com/gerardtorrats/gerardtorratsespinosa.github.io.git
```

Then run

```
hugo server

```

Hurray! :) 

## A little info about your website  and/ or overview that explains  **How** the website update.

##  How to modify Home page ?

- 1. Open **config file** its global settign for website like title, Menu,  meta,  copyright etc.  Remove  true or replace with false in ```underconstruction``` for live the website and also change googleAnalitycsID.
```
[params]
  # Google Analitycs
  googleAnalitycsID = "Your ID"
  underconstruction = true / false
```
- 2. Changes for About Section top of the page
   - Goto folder  `/content/authors/gerard`
   - Change following Variables which you want 
     ```
        bio: My research interests include distributed robotics, mobile computing and programmable matter.
        email: ""
        name: Gerard Torrats-Espinosa
        role: "Assistant Professor <br>  Department of Sociology <br> Columbia University"
        cv: "/cv"
        cvtext: "Download CV"
        courses:
        - course:
        institution: 
        year: 
        social:
        - icon: twitter
        icon_pack: fa
        image: /images/twitter_logo.png 
        link: "twitter"
        - icon: google
        icon_pack: fa
        image: /images/google-scholar.png 
        link: #
        - icon: github
        icon_pack: fa
        image: /images/github_logo.png 
        link: #
        - icon: envelope
        icon_pack: fa
        image: /images/gmail_logo.png 
        link: #
     ```
   - You can change right side content below the `---` where is my **My Research**
- 3. **Selected Publications** coming dynamic latest 3 post from  **Research** tabs.
- 3. **News and Updates** coming dynamic latest 3 from  **newsupdate**.



## How to modify Research page ?

- Open folder `gerardtorratsespinosa.github.io/content/research` and select any folder page and change content of index.md file whatever you want like button , text, page content etc.
  
  - change title from `title:`
  - change title from `subTitle:`
  - Always use id of for main nav like  `id: research:`
  - change title from `summary:`
  - Add/Remove `btn:` as per your need 
    ```    
    btn:
    - url : "#"
      name: Doc
    - url : "#"
      name: pdf  
    ```
    Use blank if you don't want to show button.
  - Add/Remove `images:` as per your need 
    ```    
    images:
    - path: "images/linear_mixed_multilevel_model.svg"
      caption: "alt text"
    - path: "images/general_linear_model_ordinary_least_square.svg"
      caption: "alt text"
    ```
    Remove/ blank if you do not want to add images
  - Add/Remove `area:` as per your need 
    ```    
    area:
      - Methods
      - Inequality
      - Experiments
    ```
  - Add/Remove category  `catType:` as per your need 
    ```    
    catType: "Journal Articles"
    ```

 -  If you want to open pdf/external/internal link
  
    **Internal**
    ```
    linkType: "internal"
    permalinks: "/images/pdf/balcells-torrats-espinosa-2018-pnas-terrorism.pdf"
    ```
    **External**
    ```
    permalinks: "https://www.google.com/"
    linkType: "external"
    ```
- if you want to hide sidebar or not
    ```    
    sidebar: true /false 
    ```

## How to create buttons for Research and publications ?
- Add/Remove buttons `btn:` as per your need like 
  
  **no Button**
  ```
  btn:
  - url : 
    name: 
 ```

    ```    
    btn:
    - url : "#"
      name: Doc
    - url : "#"
      name: pdf  
    ```
    Use blank if you don't want to show button.

## How to add more Rmarkdown pages like KNN page ?

you can follow all as `How to modify Research page ?` but you need to add  more variable for that  
 ```
 pageType: "r"
 ```

 and paste R code below of `---`

## How to add more Jupyter like DataCamp page ?

you can follow all as `How to modify Research page ?` 

## How to modify Data Demo 1 ?

you can follow all as `How to modify Research page ?`  and  add 
Plotly: true 


## How to add new publication page ?


you can follow all as `How to modify Research page ?` 

## How to add new blog post ?

you can add any page under **blog folder** with file name and follow below as per required : 

```
title: "New Hugo Post"

date: 2018-09-23T11:35:34+06:00 

description : "This is meta description"

id: blog # use always for blog

author: Gerard Torrats-Espinosa

authorImage: "images/gerard.jpg"

authorUrl: "https://gerardtorratsespinosa.com/"

authorPost: "Assistant Professor of Sociology <br> Columbia University"

type: post # use always for post

image: images/blog/hashtag_beach.jpg

Plotly: true # as per required 

categories:   # as per your need 
  - "Investment"
  - "consultancy"

tags:  # as per your need 
  - "Business"
  - "Marketing"
  - "Revenue"

```

