# About this repository

Here we have provided a very simple html file for the purpose of learning HTML. Here style file is also included. 

## HTML Elements and attributes
The HTML element is everything from the start tag to the end tag. HTML attributes provide additional information about HTML elements.
Attributes usually come in name/value pairs like: name="value"

`<tagname> Content goes here...</tagname>`

#### Example:
`<a href="https://www.google.com">Visit Google</a> ` Here `href` is attribute, which specifies the url of the page the link goes to.

## Some basic terminology used
- All HTML documents must start with a document type declaration: `<!DOCTYPE html>`.
- The HTML document itself begins with `<html>` and ends with `</html>`.
    ```
    <html>
        Everything is added here.
    </html>
    ```
- The visible part of the HTML document is between `<body>` and `</body>`.
- So basic structure of a HTML file is
  ```
  <!DOCTYPE html>
    <html>
    <body>
        Everything is added here. Here you can add additional headings, paragraphs etc.
    </body>
    </html>
    ```
## Headings
HTML headings are defined with the `<h1>` to `<h6>` tags. Here `<h1>` defines the most important heading and `<h6>` defines the least important heading. 
The basic structure of the headings are as follows:
```
<h1>Heading </h1>
<h2>Subheading </h2>
<h3>Subsubeading </h3>
```

## Paragraphs
HTML paragraphs are defined with the `<p>` tag and are a paragraph is written in between 
```
<p>
Your paragraph.
</p>
```

## Style 
The HTML style attribute is used to add styles to an element, such as color, font, size, and more by using `<tagname style="property:value;">`.

**Example:**
```
<!DOCTYPE html>
<html>
<body>
<h1 style="color:blue;">This is a heading</h1>
<p>I am normal</p>
<p style="color:red;">I am red</p>  
<p style="color:blue;">I am blue</p>
<p style="font-size:50px;">I am big</p>
</body>
</html>
```
Here, we can change the body color by changing style of body to: `<body style="background-color:#1e90ff;"> Add something..... </body>`

|Style name | explanation | Example |
|-----------|-------------|---------|
|color      | for changing the color | for changing paragraph color`<p style="color:blue;">I am blue</p>` |


## Links
HTML links are defined with the `<a>` tag and a link is added as: `<a href="url">link text</a>`

```
<a href="https://www.google.com">Write some text about which the link is added</a>
```

The link's destination is specified in the `href` attribute. Attributes are used to provide additional information about HTML elements.

By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link. The target attribute specifies where to open the linked document. The target attribute can have one of the following values:

* `_self` - Default. Opens the document in the same window/tab as it was clicked
* `_blank` - Opens the document in a new window or tab
* `_parent` - Opens the document in the parent frame
* `_top` - Opens the document in the full body of the window
    
So to open a link in a new tab, following can be used: `<a href="https://www.google.com/" target="_blank">Visit Google!</a>`. 


## Images
HTML images are defined with the `<img>` tag. The source file (`src`), alternative text (`alt`), `width`, and `height` are provided as attributes:
```
<img src="yourimage.png" alt="Github logo" width="104" height="142">
```









# Reference

For more details, you can follow following reference

[Reference:](https://www.w3schools.com/html/)