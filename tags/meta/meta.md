# Tag ```<meta>```

The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data.

This tag always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.

Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.
____
## Attributes:
| Attribute        | Value           | Description  |
|------------------|:-------------:| -----:|
| ***charset***    | character_set    | Specifies the character encoding for the HTML document |
| ***content***    | text             | Specifies the value associated with the http-equiv or name attribute |
| ***http-equiv*** | content-security-policy <br> content-type <br> default-style <br> refresh      | Provides an HTTP header for the information/value of the content attribute |
| ***name*** | application-name <br> author <br> description <br> generator <br> keywords <br> viewport      | Specifies a name for the metadata |

---

## Examples: 

* Define keywords for search engines:
```html
<meta name="keywords" content="HTML, CSS, JavaScript">
```
---
* Define a description of your web page:
```html
<meta name="description" content="Free Web tutorials for HTML and CSS">
```
---
* Define the author of a page:
```html
<meta name="author" content="John Doe">
```
---
* Refresh document every 30 seconds:
```html
<meta http-equiv="refresh" content="30">
```
---
* Setting the viewport to make your website look good on all devices:
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

-----

## The list of useful meta tags used in HTML5 documents

 #### Recommended Meta Tags:
```html
<meta charset="utf-8">
```
```html
  <meta name="language" content="english"> 
```
```html
 <meta http-equiv="content-type" content="text/html">
```
```html
 <meta http-equiv="content-type" content="text/html">
```
```html
 <meta name="author" content=”MakiQqq”>
```
```html
<meta name="designer" content=”William Glen Harold Herrington”>
```
```html
 <meta name="publisher" content=”William Glen Harold Herrington”>
```
-----
#### Optimization Meta Tags:
```html
 <meta name="description" content="Learn more MakiQqq, his projects, interests and experience.">
```
```html
 <meta name="keywords" content="Software Engineer,Product Manager,Project Manager,Data Scientist,Computer Scientist">
```
```html
<meta http-equiv="refresh" content="30">
```
```html
 <meta http-equiv="content-type" content="text/html">
```
----
#### Meta Tags for HTML pages on Mobile:
```html
 <meta name="format-detection" content="telephone=yes"/>
```
```html
 <meta name="HandheldFriendly" content="true"/> 
```
```html
 <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
```

