# Kaliedo Theme
A work-in-progress theme for my personal websites that emphasize visual aspects such as posts, and portfolio sections above more corporate-centric websites that emphasize text content, and navigation.

The primary usage case for this theme is in conjunction with GitHub Pages and will align with the documentation for GitHub pages.

https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll

This theme aims to incorporate aspects of accessibility, and SEO while still remaining visually appealing and minimalistic.

Based upon the Jasper themes re-developed for Jekyll, originally the default themes for the Ghost CMS created by John Nolan.

## Style Guide
Fira sans (400; 15px) for menus
Source Sans Pro (400 weight; 16px) for content
Source Sans Pro (500; 32px) for call-outs and hero content.
Bebas Neue
Rubik
Oxygen
Hind Siliguri

# Colour Design

## Live demo

## Screenshots

## Jasper theme includes

* Pagination
* Google Analytics tracking
* Author's profile with picture
* Disqus comments (not Ghost standard)
* Author page (New 07.02.2015)
* Tag page(s) (New 07.02.2015)
* 404 page (New 07.02.2015)
* Toggleable sliding sidebar (New 07.02.2015)
* Related posts view (New 30.10.2015)
* Tag description(s) (New 30.10.2015)
* Code Syntax Highlight (New 24.11.2015)
* Code Syntax Highlight with [highlight.js](https://highlightjs.org/) (New 06.04.2016)
* Rss updated to Jekyll v3 (New 06.04.2016)
* Updated to Casper v1.3.7 **(New 17.11.2017)**  
* 'Out of the box' support for Multiple Authors **(New 17.11.2017)**  

## How to use it

### Deployment

**Important:**  For security reasons, Github does not allow plugins (under _plugins/) when deploying with Github Pages. This means:

**1)** that we need to generate your site locally (more details below) and push the resulting HTML to a Github repository;

**2)** built the site with [travis-ci](https://travis-ci.org/) (with goodies from [jekyll-travis](https://github.com/mfenner/jekyll-travis)) automatically pushing the generated *_site/* files to your *gh-pages* branch.
 This later approach is the one I am currently using to generate the live demo.

For option **1)** simply clone this repository (*master branch*), and then run `bundle exec jekyll serve` inside the directory. Upload the resulting *_site/* contents to your repository (*master branch* if uploading as your personal page (username.github.io) or *gh-pages branch* if uploading as a project page (as for the [demo](https://github.com/jekyller/jasper/tree/gh-pages)).

For option **2)** you will need to set up travis-ci for your personal fork. Briefly all you need then is to change your details in *[\_config.yml](_config.yml)* so that you can push to your github repo. You will also need to generate a secure key to add to your *[.travis.yml](.travis.yml)* (you can find more info on how to do it in that file). Also make sure you read the documentation from [jekyll-travis](https://github.com/mfenner/jekyll-travis). This approach has clear advantages in that you simply push changes to your files and all the html files are generated for you. Also you get to know if everything is still fine with your site builds. Don't hesitate to contact me if you still have any issues (see below about issue tracking).

## Issues and contributing

This install builds well with Ruby v2.4.2 and Jekyll v3.7.4. If you run into any problems please log them on the [issue tracker](https://github.com/jekyller/jasper/issues).

Feel free pull-request your patches and fixes.

## Dependencies
[![Ruby](https://img.shields.io/badge/ruby-3.1.1-blue.svg?style=flat)](https://www.ruby-lang.org/)
[![Jekyll](https://img.shields.io/badge/jekyll-3.9.2-brightgreen.svg?style=flat)](https://github.com/jekyll/jekyll/releases)
GitHub Pages
Rake
Nokogiri
Webrick

## Copyright & License

Same licence as the one provided by Ghost's team. See Casper's theme [license](GHOST.txt).

Copyright (C) 2015-2017 - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.