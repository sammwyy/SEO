# SEO
Basic and essentials tooltips for Search Engine Optimization

## Index
- [Introduction](#introduction)
- [Metatags](#metatags)
  - [Content Type](#content-type)
  - [Viewport](#viewport)
  - [Title](#title)
  - [Description](#description)
  - [keywords](#keywords)
  - [author](#author)
- [Social Tags](#social-tags)
- [Website and Server](#webiste-and-server)
  - [Content](#content)
  - [URL Optimization](#url-optimization)
  - [Responsive](#responsive)
  - [Website Speed](#website-speed)
  - [404 Error](#404-error)
  - [HTTP Status](#http-status)

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

#### Viewport
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


## Social Tags
With social tags I refer to meta tags that are specific to a social network or website such as twitter or facebook.



## Website and Server
It is important that you have your website and server fairly tidy.  

#### Content
The content of your website is quite important since it is not only content that the user will qualify to continue visiting your page or not, but it also influences the search results a lot.  

Make sure to follow the following rules:  
- Have an `<h1>` (No more, no less)  
- Make sure your unique `<h1>` tag is at least 20 characters long.  
- Have a minimum of 250 words on your website (1000 is recommended)  
- Add the `rel="no-follow external"` property to external links (i.e. `<a rel="no-follow external">`)  
- Add alt property to images tags (i.e. `<img alt="icon" src="./assets/icon.jpg">`)  

I also recommend some tricks to make your website more attractive:  
- Use a fresh design that does not tire the eyes.  
- Don't use very muted colors.  
- Embed videos on your website.  
- Create a personal brand.  
- Make a quote from your clients' feedback (if applicable)  
- Create a faq page.  
- Check your grammar.  


<hr>

#### URL Optimization
Here are some good practices to optimize your URLs  
  
- Avoid use urls like this:  
https://sammwy.example.com/2020/12/08/10-best-animes-of-2020  

- Use this instead: 
https://sammwy.com/blog/best-animes-2020  

- Avoid use http  
- Avoid use subdomains  
- Avoid use long domains  
- Avoid use too long urls  
- Avoid use urls ended with .php, .html, .asp, .jsp  

<hr>

#### Responsive
Some search engines (including google) reward responsive design with a higher position than a website that is not responsive for other devices.  
  
Useful links:  
[Resonsive design tips](https://business.tutsplus.com/articles/quick-responsive-web-design-tips-tricks--cms-30684) | [Responsive design tricks](https://webflow.com/blog/responsive-web-design-tricks-and-tips)

<hr>

#### Website Speed
If your website is slow, not only will you ruin the user experience, but also the search engines will take longer to obtain details of your page which will position you lower in the search results.  

Useful tricks:  
- Use cache system (Example cloudflare)  
- Minify your HTML, CSS and JS files  
- Compress your images  
- Avoid using too js and css imports (max 5 per each)  
- Use lazy loading in your img tags  
- Use a good host provider  
- Use vectorial images instead png  
- Use a CDN for css and js externals imports  
- Get a dedicated hosting instead shared hosting  

<hr>

#### 404 Error
It is important that your website has a custom page for the 404 error and not the one that comes by default in the http software  

<hr>

#### HTTP Status
it is very important to handle the HTTP statuses correctly.  

For example, if you want to redirect www.example.com to just example.com, you must do it through the http status 301, otherwise you will have 2 websites with the same content (which is known as duplicate content and is penalized by Google)  

in turn, the internal errors using the 500 code, the request errors with the 400 and the correct requests with the 200.  

