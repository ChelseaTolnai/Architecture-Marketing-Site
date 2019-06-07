# Smith and Jones Architects - Marketing Site

## Overview

One week solo project to build a responsive multi-page user interface webiste for a fictional architectural firm named Smith and Jones Architects using provided style guides.

## Deployment

Deployed via netlify at [https://catolnai-ui-architects.netlify.com](https://catolnai-ui-architects.netlify.com/)

## Tech Stack
HTML | CSS | Less | JavaScript | GreenSock | ScrollMagic

## Third-Party HTML Scripts
- GreenSock: 
	`<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/2.0.2/TweenMax.min.js"></script>`
- ScrollMagic: 
	```
	<script src="https://cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.6/ScrollMagic.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.6/plugins/debug.addIndicators.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.6/plugins/animation.gsap.js"></script>
	```

## Project File Structure
- Root Directory
	- Main Page html file (index.html)
	- Secondary Pages html files (about.html, contact.html, projects.html, services.html)
- Design Files
	- Includes Style Guide text document
	- Sub Folders include style guide images for each page
- CSS
	- Compiled using Less
- IMG
	- General Images for all pages
	_ Images for specific pages located within Sub Folders
- JS
	- JavaScript for Navigation (index.js) 
	- JavaScript for Projects Carousel (carousel.js)
	- JavaScript for About Page Scroll Animation (scroll.js)
	- JavaScript for Services Page Tab Navigation (tabs.js)
- LESS
	- Import Less files (index.less)
	- Variables and Mixins (variables.less, mixins.less)
	- Reset and Global Styles(reset.less, global.less)
	- Reusable Components (navigation.less, footer.less)
	- Page Specific (home-page.less, services-page.less, contact-page.less, about-page.less, projects-page.less)

## Assets Provided:
* [Style guide:](/DesignFiles/style-guide.md) File to identify font sizes, colors, and font families across the site.
* [Images for both desktop and mobile:](/img) Mobile images hto match design files.
* [Design Files:](/DesignFiles) Guides for what the pages should look like on desktop and mobile.  

## Page Features:

### All Pages:

- Fixed Navigation bar with animated toggle navigation links. Animation implemented with GreenSock.
- Footer with contact input and firm locations
- Fully desktop, mobile, and tablet responsive

### Landing Page:

- Firm's general images and descriptions with button links to About Page and Products Page
- Components for recent projects with images and desriptions

### Services Page:

- Breakdown of firm's services displayed with interactived JavaScript tag navigation

### Contact Page:

- Usuable contact form including text, dropdown, and radio selection inputs.

### About Page:

- Components for general firm information which appear on down scroll. Scroll animation implement with ScrollMagic.

### Projects Page:

- Carousel of components for recent projects with title, image and desription. Carousel written in vanilla JavaScript.
