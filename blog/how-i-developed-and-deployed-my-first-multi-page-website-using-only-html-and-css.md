---
title: How I developed and deployed my first multi-page website using only HTML and CSS
description: An article about learning HTML and CSS, buying a domain name from Hostinger and deploying the website on Netlify.
author: GJ Tiquia
date: 2023-03-02
tags: {"Web Dev", "HTML", "CSS", "Netlify", "Hostinger"}
---

# How I developed and deployed my first multi-page website using only HTML and CSS

As a kid I always dreamed about having my very own website. Now as I grew older, I finally learnt how to create one and how to deploy it. This article is about how I created my website using only HTML and CSS, how I bought my own domain name with Hostinger and how I deployed my website on Netlify.



- add github repo link to exact commit, and say the website keeps on evolving as I learn more, might be updated.

## Website Development

### Why only HTML and CSS?

You may have heard that [HTML, CSS and JavaScript are the basic building blocks of the Web](https://www.freecodecamp.org/news/html-css-and-javascript-explained-for-beginners/amp/). 

- briefly explain what is HTML and CSS
- motivation for making website only with HTML and CSS with nothing fancy

  - want to get a good solid foundation without using frameworks

  - know how things fundamentally work without CSS frameworks like Bootstrap or TailwindCSS, or JavaScript frameworks like React, Angular or Vue

    - appreciate frameworks and how they actually work under the hood in case if encounter any bugs in the future

    - extend the frameworks in the future if needed

  - finish a project
  
    - importance of finishing

    - tutorial hell

    - cement the knowledge just learnt

    - can scale or convert to another framework in the future anyways, which is exactly the case now. (reference the GitHub repo and the exact commit)

### How to learn HTML and CSS?

- freeCodeCamp

### How to develop a website with only HTML and CSS?

- vscode
- live server extension
- HTML file structure (for multi-page)
- styles.css philosophy and class naming
  - freeCodeCamp taught semantic class names, but I have a lot of reusable components, want to make as generic as possible.
  - later on learnt that this is a utility first approach, which is exactly the same philosophy behind Tailwind CSS. 

### Tips on building a multi-page website with only HTML and CSS

With only HTML and CSS, most tutorials only teach you how to create a single-page website. Largely because as a website grows with more content and more pages, it becomes difficult to maintain and scale using only HTML and CSS. This gives rise to various frameworks such as React, Angular and Vue for developing a scalable website.  
Nonetheless, it is still possible to make a simple multi-page website using only HTML and CSS. Here are a few tips that I found useful when making my own website.

#### File Structure

#### Styling
- think about how to reuse styles across different pages, and create generic classes. 
- there are in general two ways about creating classes, component based vs utility based = bootstrap vs tailwindcss. 
- (make an illustration with the difference of component based and utility based, eg. Card)
- When i designed my website, I didn't design them with reusable components in mind. 



## Website Domain

### What is a Domain Name?

- terms such as domain registrar, difference between domain 

### How to find a good domain registrar?

- reference article from Google

### What domain registrars options are there?

- suggested ones from the reddit article
- Hostinger mainly for the price, but only the domain and not the server, read below to see

## Website Deployment

### What is a deployment server?

### What deployment options are there?

- Netlify (by far most popular that I find, more tutorials, more than enough free plan)
- Hostinger (heard bad things about it)

### How to deploy a site on Netlify?

- account
- own site
- link to public repo
- free => auto build only on public repo

### How to use a Custom Domain on Netlify?

- bought domain name with Hostinger
- CName
- takes up to 48 hours
- wait for the automatic SSL certificate