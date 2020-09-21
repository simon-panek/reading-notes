# Code 102: Class 05 - Design web pages with CSS

***

## Read: 5 Chapter 10

CSS (Cascading Style Sheets) *alows developer to set rules to specify how content and layout should appear*

- Every element should be treated as though it has a bouding box, each box and its contents can be controlled by CSS
- CSS associates rules with html elements

CSS Rule *governs how content of specified elements should be displayed*

- Rule contains two parts: selector and declaration
  - Example = `p {font-family: Arial;}`
  - `p` = Selector *indicates which elements rule applies to*
  - `font-family: Arial;` = Declaration *how the elements should be styled*
    - CSS Declaration sits inside `{}` and is made up of two parts: a property and a value
    - Property *indicates the aspects of an element that you want to control*
    - Value *specifies the setting to use for a chosen property*
    - Can specify more than one property in one declaration, seperated by a `;`

External CSS *Allows a single seperate file to contain all of the style information for a multipage website*

- `<link>` *element placed inthe html document in the `<head>` element telling the browswer where to find the CSS
- Example = `<link href="urlofcss" type="textorcss" rel="stylesheet" />`
  - `href` *indicates the path to the CSS file*
  - `type` *specifies type of doc being linked to text or css*
  - `rel` *specifies relationship between html page and file linked to, should be stylesheet when linking to CSS file*

Internal CSS *can use CSS in html page by placing them within a `<style>` element, usually inside a `<head>` element

- When building a site with more than one page, should use an external CSS file to keep consistant and for ease of updates/changes
- Example:

``` html

<head>
    <title>Using Internal CSS</title>
    <style type="text/css">
        body {
                font-family: arial;
                background-color: rgb(185,179,175);}
    </style>
</head>

```

CSS Selectors

Selector | Meaning | Example
--- | --- | ---
Universal Selector | applies to all elements in doc | `*{}`
Type Selector | matches element names | `h1, h2, h3 {}`
Class Selector | matches element whose class attribute has value specified after the `.` | `.example {}`
ID Selector | matches element whose id attribute has value specified after the `#` | `#example {}`
Child Selector | matches the element that is a direct child of another | `li>a {}`
Descendant Selector | matches element that is a descendant of another specified element | ` p a {}`
Adjacent Sibling Selector | matches and element that is the next sibling of another | `h1+p {}`
General Sibling Selector | matches element that is a sibling of another, does not have to be directly preceding element | `h1~p {}`

Cascading Rules

- Last Rule *if two selectors are identical the latter will take precedence*
- Specificity *more specific rules will apply over more genaric rules*
- Important *can add `!important` after any rule to indicate that it should be treated as more important than other rules that apply to the same element*
    - Example: `p b { color: blue !important:}`

Inheritance *style properties that are inheritable can be given to all children of an element by default*
- Some properties like font-family default to be inherited by children of an element
- Some properties like background-color are not inheritable
- Can force many properties to inherit by setting `inherit` in the value of the property

Online tools that allow developer to test CSS appearance in multiple virtual browsers and or OS
- BrowserCam.com
- BrowserLab.Adobe.com
- [BrowserShots.org](browsershots.org)
- [CrossBrowserTesting.com](crossbrowsertesting.com)

CSS Bug Fixes and Tools
- [PositionisEverything.net](positioniseverything.net)
- [QuirksMode.org](quirksmode.org)


## Read: 5 Chapter 11

Color *the `color:` property allows you to specify text color in an element*

- RGB Values *express colors in terms of how much red, green, and blue are used `rgb(100,100,90)`
- Hex Codes *express the color using six-digit code representing amount of red, green, and blue in a color preceeded by a `#`, example: `#ee3e80`*
- Color Names *there are 147 predefined named colors, example: `DarkCyan`*

CSS Comments *developer notes that will not effect the code*
- Place comments between `/*comment*/`

Background Color *background color is set to transparent by default, most browsers show white, but not always*

``` css
body {
    background_color: rgb(200,200,200):}
```

Online Color Picking Tool
[Color Scheme Designer](https://colorschemedesigner.com/csd-3.5/)

Opacity *allows developer to set the opacity of an element and its children, values from 0.0 to 1.0*

- To set opacity, indicate a color in `rgba`, example: `rgba(231,112,56,0.5)`

HSL Colors *defines a color in three terms: hue, saturation, and lightness*

- Hue *colloquial idea of color, often shown as a color wheel indicated by degrees 0-360*
- Saturation *amount of gray in a color, 100% is full saturation, 0% is a shade of gray*
- Lightness *amount of white or black in a color, 0% Lightness is black, 100% Lightness is white, 50% is normal. AKA Luminosity*
- HSLA *adds the alapha value for transparency from 0 to 1.0*

***
[Return to reading-notes Deployed Site](https://paneks19.github.io/reading-notes/)

[Return to reading-notes Mark Down](https://github.com/paneks19/reading-notes)
