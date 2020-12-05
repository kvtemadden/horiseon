# Horiseon

The Repository
Hosting and editing the site for Horiseon, a Marketing Agency who specialise in SEO, Online Reputation (branding) and Social Media. This source code is available under the standard MIT licence.
<br><br>
## Contents

Section | Description
------------ | -------------
[Screenshots](#screenshots) | Screenshots of the site and information on Horiseon
[Changes](#changes) | Changes that were made on the site
[CSS](#css) | CSS changes on the document
[HTML](#html) | HTML changes on the document
[Licence](#licence) | Licence for the source code
<br>

## Screenshots

## First Screenshot of Horiseon Site
![Screenshot of working Horiseon site (first screenshot)](https://github.com/kvtemadden/horiseon/blob/main/assets/images/ReadMe/Screenshot%20of%20Horiseon%20site%201.PNG)

## Second Screenshot of Horiseon Site
![Screenshot of working Horiseon site (second screenshot)](https://github.com/kvtemadden/horiseon/blob/main/assets/images/ReadMe/Screenshot%20of%20Horiseon%20site%202.PNG)

Horiseon are a Marketing Agency who specifically focus in three main areas:
1. SEO
2. Online reputation
3. Social media

The goal of their website is to try and explain the benefits of each of their services in order to attract more clients.

The purpose of their service is to be able to grow a company's reputation and land more "leads" which hopefully turn to a conversion of sales.<br><br>

## Changes

Within the code there were a few changes that I'd made...<br><br>

### CSS

I've condensed the following CSS classes as they all had the same styling:

*Changed to .benefit*
.benefit-lead
.benefit-brand
.benefit-cost 

*Changed to .service*
.search-engine-optimisation
.online-reputation-management
.social-media-marketing

I removed all of the individual instances of...

font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;

...and applied it to the body element.

This applied it throughout the document.

I re-arranged the CSS so that the general element classes were at the top of the file, then the classes were in order of section.

I changed the h2 in the footer section to h4 to make it follow a more sequential order.<br><br>

### HTML

I removed the unnecessary IDs from the HTML as they weren't being used, and recreated IDs for the "SEO" section in the Horiseon logo.

I added in an anchor link for the SEO link at the top of the page as it wasn't previously working.

I've added in alt tags for all of the images to make them descriptive and accessible.

I changed the divs to show what information is being held in that area.

E.g. <br>
`<nav>` to define the navigation bar<br>
`<section>` tags to define main content of the page.<br>
`<header>` tag for the hero section<br>
`<footer>` tag for the footer information<br>
`<article>` tags for any information (text/images) in the main page<br>

I also added `<title>` tags in to the hero image and the Horiseon logo as they're not images and therefore didn't use alt text.

## Licence
> This site was created under the standard MIT licence.