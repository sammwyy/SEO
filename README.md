# SEO
Basic and essentials tooltips for Search Engine Optimization

## Index
- [Introduction](#introduction)
- [Metatags](#metatags)
- [Content](#content)

## Introduction
SEO or "Search Engine Optimization" is a practice that aims to position our website at the top of the search results of any search engine (especially google)  
  
Therefore, in this guide I will bring you the most essential SEO tips that every website should have.  

## Metatags
html <META> tags help us to give extra information to the browser to predefine its behavior, but it also allows us to give extra information to search engines and give the user a better experience while the search engine itself rewards you placing the result of your website in a higher position.  
  
#### Content-Type
This tag is necessary to declare your character set for the page and should be present on every page. Leaving this out could impact how your page renders in the browser. A few options are listed below, but your web designer should know what's best for your site.   
```html
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
```

<hr>

#### View Port
This tag allows us to predefine a viewport to allow compatibility to the website on mobile devices.  
```html
<meta name=viewport content="width=device-width, initial-scale=1">
```

<hr>

#### Title
This is not a meta tag, but the title is very important for the website and it is recommended to use between 20 to 32 characters in it.  
```html
<title>My Website - The best site in the world!</title>
```
<img src="https://i.imgur.com/3Gq4CTR.png">

<hr>

#### Description
This meta tag allows us to provide a description that will accompany the title in the search results and it is recommended that it be between 80 to 160 characters.  
```html
<meta name="description" 
      content="Get the latest news on what is happening in the world, 
               discover the latest fashion trends and find out about everything in the world of sports.">
```
<img src="https://i.imgur.com/G7XfFJQ.png">

<hr>

#### Keywords
The keywords metadata allows us to define some keywords that will be used to find the website and you can separate them by commas.  
  
Warning: do not use words that are not in the body of your website as keywords or you will be penalized by google.  
```html
<meta name="keywords" content="news, sports, fashion, trends">
```

<hr>

#### Author
This metadata is not important and it does not have much relevance in SEO but there are still engines that use it, so it does not hurt to place it.
```html
<meta name="author" content="Sammwy">
```
[Source "moz.com"](https://moz.com/learn/seo/)
