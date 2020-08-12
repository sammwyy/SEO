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
- [OpenGraph](#opengraph)
  - [OG Locale](#og-locale)
  - [OG Type](#og-type)
  - [OG Description](#og-description)
  - [OG URL](#og-url)
  - [OG Image](#og-image)
  - [OG Title](#og-title)
- [Twitter](#twitter)
  - [Twitter Card](#twitter-card)
  - [Twitter URL](#twitter-url)
  - [Twitter Tittle](#twitter-title)
  - [Twitter Description](#twitter-description)
  - [Twitter Image](#twitter-image)
- [Website and Server](#webiste-and-server)
  - [Content](#content)
  - [URL Optimization](#url-optimization)
  - [Responsive](#responsive)
  - [Website Speed](#website-speed)
  - [404 Error](#404-error)
  - [HTTP Status](#http-status)
- [Crawlers](#crawlers)
 - [Robots.txt](#robots.txt)
 - [Structured Data](#structured-data)
 - [Index your website](#index-your-website)
 - [Sitemaps](#sitemaps)

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

## OpenGraph
Opengraph is a web protocol that allows you to create rich structured objects to get more detailed information about a website. Facebook uses opengraph for posts that contain a link to your website so if you want to promote your website on facebook, you need to use the opengraph tags.  

#### OG Locale
Allows you to specify the language of your website.  
```html
<meta property="og:locale" content="en_US" />
```

#### OG Type
It allows you to specify the type of content that will be on your website and thus be able to display it in a specific way.  
Available types: `apps.saves`, `article`, `book`, `books.author`, `books.genre`, `business.business`, `fitness.course`, `game.achievement`, `games.plays`, `games.saves`, `music.album`, `music.playlist`, `music.radio_station`, `music.song`, `news.publishes`, `og.follows`, `og.likes`, `pages.saves`, `place`, `product`, `product.group`, `product.item`, `profile`, `restaurant.menu`, `restaurant.menu_item`, `restaurant.menu_section`, `restaurant.restaurant`, `restaurant.visited`, `restaurant.wants_to_visit`, `sellers.rates`, `video.episode`, `video.movie`, `video.other`, `video.tv_show`, `video.wants_to_watch`, `website`
```html
<meta property="og:type" content="article" />
```

#### OG Description
Description of your article or website.
```html
<meta property="og:description" content="This is the description of my website or article" />
```

#### OG Url
Url of your article or website
```html
<meta property="og:url" content="https://example.com/article" />
```

#### OG Image
Image banner of your article or website
```html
<meta property="og:image" content="https://example.com/assets/image.jpg" />
```

#### OG Title
Title of your article or website
```html
<meta property="og:title" content="My Article" />
```

## Twitter
Just like facebook uses opengraph, twitter uses its own metadata system which in turn uses its own meta tags.

#### Twitter Card
allows you to create a twitter letter, this will make the links to your website in the tweets look more elegant. In turn, this works as an opengraph type to which you must specify the type of letter you want:  

Available types: `summary`, `summary_large_image`, `app`, `player`
```html
<meta name="twitter:card" content="summary">
```

Samples:  
**Summary**  
<img src="https://i.imgur.com/ap9xFzx.png" width="50%">

**Summary large image**  
<img src="https://i.imgur.com/44f6OY2.png" width="50%">

**App**  
<img src="https://i.imgur.com/ZsVU5hj.png" width="50%">

**Player**  
<img src="http://www.oncrawl.com/wp-content/uploads/2016/01/soundcloud-player-gweek.png"  width="50%">

#### Twitter Url
Canonical url of your card article
```html
<meta name="twitter:url" content="https://website.com/mycard">
```

#### Twitter Title
Title for your card
```html
<meta name="twitter:title" content="This is my card">
```

#### Twitter Description
Description for your card
```html
<meta name="twitter:description" content="Twitter's new Twitter Cards API allows developers to add META tags to their website, and Twitter will build card content from links to a given site.">
```

#### Twitter Image
Banner image for your card
```html
<meta name="twitter:image" content="https://davidwalsh.name/wp-content/themes/punky/images/logo.png">
```

[Source 1: oncrawl.com](https://www.oncrawl.com/oncrawl-seo-thoughts/a-complete-guide-to-twitter-cards/)
[Source 2: neilpatel.com](https://neilpatel.com/blog/open-graph-meta-tags/)

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

## Crawlers
Crawlers or robots are small programs that are responsible for collecting information from websites for various purposes.  
  
Google has a bot that allows us to obtain data for the correct indexing of our website and there are many ways to help this bot.

#### Robots.txt
Robots txt is a file that we should have on our web server, so google robots will go to that file to take their configuration and not use the predefined one.  

In this file we can index specific urls or create urls that are not going to be indexed.  
 
Even if we do not use this file, it is considered good practice to create it and set this default configuration:  
```
User-agent: *
Disallow:
```

And if we have a RestAPI on our website that users should not access but is used for backend purposes, we can use this configuration:
```
User-agent: *
Disallow: /api/
```

The file must be created with the name robots.txt in the root directory of the website, for example:  
https://2lstudios.dev/robots.txt or https://disney.com/robots.txt

#### Structured Data
The data structuring allows to help the google bot to have more information from our website to give a preview or widget in the search results.

For example:  
<img src="https://developers.google.com/search/docs/data-types/images/recipe02.png" width="50%">
<img src="https://lh3.googleusercontent.com/IuoQrJBjUNsrOHmuHAQ99ehEiX6zCR2NZLl_2wZFkUkSjyotostXtkc2uIqDQgbieEI=w675" width="50%">

More info at [developers.google.com](https://developers.google.com/search/docs/guides/intro-structured-data) 

#### Index your website
You can index your website on google manually by visiting the [Google Search Console](https://search.google.com/search-console/).  
  
In this panel you can also upload a sitemap that we will see below.

#### Sitemaps
Sitemap is a way that google has to structure the different links to your website with a certain order of priority and which ones will be indexed and which ones will not.  
  
the most common is to create a sitemap.xml file in the root of your website and send that link to google.  
a sitemap looks like this:
```xml
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://www.sitemaps.org/schemas/sitemap/0.9 http://www.sitemaps.org/schemas/sitemap/0.9/sitemap.xsd">
  <url>
    <loc>https://2lstudios.dev/</loc>
    <lastmod>2020-08-10T20:40:50+00:00</lastmod>
    <priority>1.00</priority>
  </url>
  
  <url>
    <loc>https://2lstudios.dev/projects</loc>
    <lastmod>2020-08-10T20:40:50+00:00</lastmod>
    <priority>0.80</priority>
  </url>
  
  
  <url>
    <loc>https://2lstudios.dev/team</loc>
    <lastmod>2020-08-10T20:40:50+00:00</lastmod>
    <priority>0.80</priority>
  </url>
  
  <url>
    <loc>https://2lstudios.dev/community</loc>
    <lastmod>2020-08-10T20:40:50+00:00</lastmod>
    <priority>0.80</priority>
  </url>
</urlset>
```

This tool will generate a sitemap.xml automatically by scanning your website: [xml-sitemaps.com](https://www.xml-sitemaps.com/)
