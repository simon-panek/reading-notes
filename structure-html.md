# Code 102: Class 4 - Structure of a Website HTML

***

## Read: 04 HTML & CSS Textbook Chapter 18

### Process and Design

- When creating a website, create fictional visitors complete with a variety of target demographic information. Use them to drive design choices.
- What are the primary motivations and goals of users of your site?
- What information do your users need?
- How often a site should be updated may depend on content and frequency of user visits.
- Card sorting is a methode of determining page and content layout.
- Wireframe *simple sketch that covers the primary info and structure needed for each page*
- Good idea to show wireframe to client prior to showing design, this ensures that content and functionality drive the page build.

Visual Hierarchy *most users do not read entire web pages. Using contrast can help focus a users attention.*

- Size *larger elements grab attention*
- Color *differences between foreground and background color can draw attention*
- Style *changine the style of an element in relation to is adjacent items helps it to stand out*

Grouping and Similarity *visually grouping items of related content through similar element styles*

- Proximity *placing related elements close together*
- Closure *a real or imaginary box that can be drawn around related elements*
- Continuance *items in a line or continous curve are precieved as more related than those that are not*
- White Space *intentionally using gaps to deliniate different groups of elements*
- Color *background color placed behind related items*
- Borders *line drawn around related elements*

Navigation *a good design allows users to better find and understand your content*

- Concise *quick and easy to read, ideally no more than 8 links or options in a menu*
- Clear *predictable outcomes based on link descriptions*
- Selective *primary navigation should only focus on navigation not other items such as login*
- Context *good navigation indicates to the user where they are in relation to the site overall*
- Interactive *links should be physically easy to use and differenciate from other text on the screen*
- Consistent *keep the primary navigation structure the same throughout*

## Read: 04 HTML & CSS Textbook Chapter 1

### Structure

HTML (Hypertext Markup Language) *describes the structure of a webpage*

HTML Elements *usually made up of two tags inside angle brackets `<example></example>`

Attributes *provide more information and instruciton in a tag, consist of two parts: name and value seperated by "="*

- Example `<p lang="en-us">Paragraph in English</p>`
  - `lang` = name
  - `"en-us"` = attribute value



List of Tags

- `<body></body>` *everything in this element is shown in the browser window*
- `<head></head>` *contains information about the page*
- `<title></title>` *title above the window tab*

View Source *in browser allows you to see the code for the current page, this can be useful in figuring out how to achieve certain structures*

## Read: 04 HTML & CSS Textbook Chapter 17

### HTML 5 Layout

HTML 5 *introduced new tags that are more specific for the structure of the page*

Common Structural Tags
 - `<header>` *used at the top of a page or the top of a section to hold the descriptive info for that section*
 - `<footer>` *at the bottom of a page to contain info like copyright or at the bottom of a section*
 - `<nav>` *used to contain the major navigational blocks*
 - `<article>` *used to contain any section that could potentially stand alone*
 - `<aside>` *when used nested inside an article it should convery secondary information like a quote, when outside of an article acts as container for info relating to the entire page*
 - `<section>` *element groups related content to gether*
 - `<hgroup>` *used to contain a title and subtitle within an element*
 - `<figure>` *used to contain any content that is referenced from a main article, the article should still make sense even if the figure is moved to another location*
 - `<figurecaption>` *provides a text caption of the figure*
 - `<div>` *contains related elements*
 - `<a href="url">` *allows whole sections to be treated as a link if nested insde the `<a></a>`*

 Older browsers may need to be updated or have extra JavaScript added to function properly.

 ## Read: 04 HTML & CSS Textbook Chapter 8

### Extra Markup

- HTML 4
  - Released in 1997
  - Most elements from HTML 5 are available in 4
  - A few specific tags are no longer recomended although they still work

- XHTML 1.0
  - Released 2000
  - This was a re-write of HTML 4 to follow the rules of XML
  - More strict that 4

- HTML 5
  - Work in progress
  - Browser builders are implimenting now
  - May need to provide backwards compatibility for older browsers

Doctypes *tells the browser what kind of HTML it is using*

- HTML 5 = `<!DOCTYPE html>`
- HTML 4 = `<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3org/TR/html14/loose.dtd">`
- Transitional XHTML 1.0 = `<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">`
- Strict XHTML 1.0 = `<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">`
- XML Declaration = `<?xml version="1.0" ?>`

Comments in HTML
`<!--Comment-->` *allows coder to place notes in the code ignored by the computer*

Left off at pg 181



***
[Return to reading-notes Deployed Site](https://paneks19.github.io/reading-notes/)

[Return to reading-notes Mark Down](https://github.com/paneks19/reading-notes)
