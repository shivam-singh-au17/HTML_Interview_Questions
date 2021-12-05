
# HTML INTERVIEW QUESTIONS : -

## HTML Questions

| No. | Questions |
|----|------------------------------------|
|01. |[What is difference between HTML and XHTML?](#1-what-is-difference-between-html-and-xhtml)|
|02. |[What are the semantic tags available in html5?](#2-what-are-the-semantic-tags-available-in-html5)|
|03. |[Why you would like to use semantic tag?](#3-why-you-would-like-to-use-semantic-tag)|
|04. |[What does a `<DOCTYPE html>` do?](#4-what-does-a-doctype-html-do)|
|05. |[What happens when DOCTYPE is not given?](#5-what-happens-when-doctype-is-not-given)|
|06. |[What is difference between `span` tag and `div` tag?](#6-what-is-difference-between-span-tag-and-div-tag)|
|07. |[What are optional closing tag?](#7-what-are-optional-closing-tag)|


### 1. What is difference between HTML and XHTML?

The Extensible Hypertext Markup Language, or XHTML, has two important notes for front end developers.

1) It needs to be well formed, meaning all elements need to be closed and nested correctly or you will return errors.
2) Since it is more strict than HTML is requires less pre-processing by the browser, which may improve your sites performance.

<div align="right">
    <b><a href="#">⬆ Back to Top</a></b>
</div>


### 2. What are the semantic tags available in html5?

HTML5 semantic tags define the function and the category of your text, simplifying the work for browsers and search engines, as well as developers.

HTML5 offers new semantic elements to define different parts of a web page:

* `<article>`
* `<aside>`
* `<details>`
* `<figcaption>`
* `<figure>`
* `<footer>`
* `<header>`
* `<main>`
* `<mark>`
* `<nav>`
* `<section>`
* `<summary>`
* `<time>`

Syntax:

```html
<header></header>
<section>
	<article>
		<figure>
			<img>
			<figcaption></figcaption>
		</figure>
	</article>
</section>
<footer></footer>
```

<div align="right">
    <b><a href="#">⬆ Back to Top</a></b>
</div>


### 3. Why you would like to use semantic tag?

* Search Engine Optimization, accessibility, repurposing, light code. 
* Many visually impaired person rely on browser speech and semantic tag helps to interpret page content clearly.
* Search engine needs to understand page content to rank and semantic tag helps.
* Semantic code aids accessibility. Specially, many people whose eyes are not good rely on speech browsers to read pages to them. These programs cannot interpret pages very well unless they are clearly explained.
* Help Search engines to better understand pages. Search engine need to understand what your content is about when rank you properly on search engines. Semantic code tends to improve your placement on search engines, as it is easier for the "search engine spiders" to understand.
* It\'s easier to read and edit, which saves time and money during maintenance.

<div align="right">
    <b><a href="#">⬆ Back to Top</a></b>
</div>


### 4. What does a `<DOCTYPE html>` do?

A DOCTYPE is always associated to a `DTD` ( **Document Type Definition** ). A DTD defines how documents of a certain type should be structured (i.e. a `button` can contain a `span` but not a `div`), whereas a DOCTYPE declares what DTD a document supposedly respects (i.e. this document respects the HTML DTD). For webpages, the DOCTYPE declaration is required. It is used to tell user agents what version of the HTML specifications your document respects. 

Once a user agent has recognized a correct DOCTYPE, it will trigger the `no-quirks mode` matching this DOCTYPE forreading the document. If a user agent doesn't recognize a correct DOCTYPE, it will trigger the `quirks mode`.

<div align="right">
    <b><a href="#">⬆ Back to Top</a></b>
</div>


### 5. What happens when DOCTYPE is not given?

The web page is rendered in quirks mode. The web browsers engines use quirks mode to support older browsers which does not follow the **W3C specifications**. In quirks mode CSS class and id names are case insensitive. In standards mode they are case sensitive.

<div align="right">
    <b><a href="#">⬆ Back to Top</a></b>
</div>


### 6. What is difference between `span` tag and `div` tag?

The primary difference between div and span tag is their default behavior. By default, a `<div>` is a **block-level-element** and a `<span>` is an **inline element**.

* `<div>` is a block level element which means it will render it on it\'s own line with a width of a 100% of the parent element.
* `<span>` is an inline element which means it will render on the same line as the previous element, if it is also an inline element, and it's width will be determined by it\'s content.

```html
<div>Demo Text, with <span>some other</span> text.</div>
```

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## 7. What are optional closing tag?

`<p>, <li>, <td>, <tr>, <th>, <html>, <body>`, etc. don\'t have to provide end tag. Whenever browser hits a new tag it automatically ends the previous tag. 

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>
