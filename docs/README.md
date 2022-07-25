# **Table of Contents**
## **General**

### Objectives

1. Provide current and future end-users (content-managers) and maintainers (developers, administrators) the fundamental understanding of how the project is structured as well as how to interact with the updated features and configurations in the new Umbraco back-office.

2. Include step-by-step guidelines on how to complete the most common tasks.


### Documentation setup

This documentation is made with **docsify.js**

Static site is generated from generated build and hosted with **Netlify**

URL: https://cpb9-documentation.netlify.app

**If you'd like to add content to it:**

 Download the project repo here: https://github.com/pdao1/cpb-upgrade-documentation

 Get docsify-cli from npm: `npm i docsify-cli -g`

  if permission error appears, try with sudo: `sudo npm i docsify-cli -g`

Open terminal and cd into directory of repo project

**Create new working branch cloned from MAIN branch.**

***This is importantant as MAIN branch is monitored for changes by Netlify and will build/deploy on any changes.  Best to do PR and once it is merged it will build**

 Run it locally to view rendered site: `docsify serve docs`

 Make edits in the **README.md** file using markdown.
 

### Search feature

There is a live-search located on the top-left of the page. Utilize this to help quickly find keywords of the subject/topic you're looking for.

## **Reference Guide**

### Theme Map

Programmed theme colors are added to the website's theme to align with CPB's Styleguide.  It also makes referencing the exact color easier than HEX codes.


    --light-swell-color: #80d8d4;
    --midnight-color: #253746;
    --sand-color: #faf6f3;
    --salt-color: #fff;
    --swell-color: #00b2a9;
    --dark-swell-color: #007b84;
    --plumeria-color: #dd74a1;
    --pacific-color: #0072ce;
    --papaya-color: #ef9600;
    --hibiscus-color: #e1523d;
    --sand-tint-color: #f7f1eb;
    --midnight-tint-color: #919ba3;
    --plumeria-tint-color: #eebad0;
    --pacific-tint-color: #80b9e6;
    --papaya-tint-color: #f7ca80;
    --hibiscus-tint-color: #f0a89e;

### CSS Classes

Usage for this is pretty easy.  When using it in an element:

Before, we would do this:

`.header-cpb {
  background-color: #faf6f3;
}`

Now

`.header-cpb {
  background-color: var(--sand-color);
}`
## **BlockList Elements**
*Previously known as **Modules & Panels***

### General Content

### General Content: Two Columns

### Product Description

### Product Hero

### Product Hero Alternative

### Fine Print

### Frequently Asked Questions

### Two/Three/Four UP Panels

## **Templates**

### Master

### Home
### Product Overview

### Product Directory

### General Content

### About

### Contact Us

### Locations (Redesigned)

## **Additional Features**

### Excel import/export to rates