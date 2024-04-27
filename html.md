# HTML Online Editor & Compiler

Write, Run & Share HTML code online using OneCompiler's HTML online Code editor for free. It's one of the robust, feature-rich online Code editor for HTML language, running on the latest version HTML5. Getting started with the OneCompiler's HTML compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `HTML`. You can also specify the stylesheet information in `styles.css` tab and scripts information in `scripts.js` tab and start coding. 

# About HTML

HTML(Hyper Text Markup language) is the standard markup language for Web pages, was created by Berners-Lee in the year 1991. Almost every web page over internet might be using HTML.

# Syntax help

## Fundamentals

* Any HTML document must start with document declaration `<!DOCTYPE html>`
* HTML documents begin with `<html>` and ends with `</html>`
* Headings are defined with `<h1>` to `<h6>` where `<h1>` is the highest important heading and `<h6>` is the least important sub-heading.
* Paragrahs are defined in `<p>..</p>` tag.
* Links are defined in `<a>` tag.
    #### Example:
    ```
    <a href="https://onecompiler.com/html">HTML online compiler</a>
    ```
* Images are defined in `<img>` tag, where `src` attribute consists of image name.
* Buttons are defined in `<button>..</button>` tag 
* Lists are defined in `<ul>` for unordered/bullet list and `<ol>` for ordered/number list, and the list items are defined in `<li>`.

## HTML Elements and Attributes

* HTML element is everything present from start tag to end tag.
* The text present between start and end tag is called HTML element content. 
* Anything can be a tagname but it's preferred to put the meaningful title to the content present as tag name.
* Do not forget the end tag.
* Elements with no content are called empty elements.
* Elements can have attributes which provides additional information about the element.
* In the below example, href is an attribute and a is the tag name.
    #### Example:
    ```
    <a href="https://onecompiler.com/html">HTML online compiler</a>
    ```
## CSS

CSS(cascading style sheets) describes how HTML elements will look on the web page like color, font-style, font-size, background color etc.

### Example:

Below is a sample style sheet which displays heading in green and in Candara font with padding space of 25px.

```css
body{
  padding: 25px;
}
.title {
	color: #228B22;
	font-family: Candara;
}
```

## HTML Tables

* HTML Tables are defined in `<table>` tag.
* Table row should be defined in `<tr>` tag
* Table header should be defined in `<th>` tag
* Table data should be defined in `<td>` tag
* Table caption should be defined in `<caption>` tag

## HTML-Javascript

* Javascript is used in HTML pages to make them more interactive.
* `<script>` is the tag used to write scripts in HTML
* You can either reference a external script or write script code in this tag.

### Example

```html
<script src="script.js"></script>
```
