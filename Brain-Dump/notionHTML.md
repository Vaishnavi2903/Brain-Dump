### Fundamentals

<aside>
C - Create <br>
R - Read <br>
U - Update <br>
D - Delete <br>

</aside>

## Tags in HTML

### Paragraphs and Styling

```html
<p>This is a paragraph tag.</p>
<h1>Change the heading type by adding h1, h2, h3, h4, h5, and h6 headings</h1>
<i> for visual-only emphasis.</i>
<emp> for emphasizing a text... adding more depth to content </emp>
<b>visual only bold, it is generic like the i element, 
it does not mean anything.</b>
<strong>Adds semantic value as well as visual value to content.</strong>
```

### Lists in HTML

```html
<ol>
  <li>These are ordered lists, essentially the one we call as numbered lists.</li>
 </ol>

<ul>
  <li>These are unordered lists, essentially the one we call bulleted lists.</li>
 </ul>

<dl>Definition List
  <dt>Definition Term</dt>
  <dd>Definition</dd>
  <dd>Additional Definition</dd>
 </dl>
```

### Quotes

```html
<blockquote>This is used for its semantic value, stating to computers that hey 
this is a quote.</blockquote>
<cite> an inline element with a semantic value of citing the source of the quote.</cite>
<q>Quotes that are represented differently in different languages.</q>
```

### Inline and Block Elements

Inline elements are element that can be inserted within an existing element.

| Inline Element | Block Element |
| --- | --- |
| Inserted within the block element | Individual elements |
| Does not create a new block for content | Creates a new block for content |

!https://media.gcflearnfree.org/content/5e82363212da9215e057b928_03_30_2020/block_vs_inline_diagram.png

### Date and Time

```html
<time datetime="2023-05-08">8th May, 2023</time>

The machine readable format for the date time is YYYY-MM-DD. 
In case you want to include time, the machine readable format is hh:mm:ss
```

### CODE, PRE, and BR

```html
<p>To add a <code>code</code> in between the paragraph use the code element. 
However, in case you want to add element but do want to incorporate the semantic value 
use &lt;elementname&gt;. 
The two weird looking things are called entities that helps in adding symbols
to your HTML document so that your code does not encounter any issues due to 
errors in tag placement.</p>

<br> This element is for line breaks

<p>The browser ignores all kinds of spacing and indentation if not paired with 
the right tag. So, to keep the formatting as it is and make sure that you spacing
 and indentation is not ignored, use the <pre></pre>element</p>
```

### Subscript, Superscript, and Small Text

```html
<p>Subscripts add the text <sub>lower than the usual text</sub>
example H<sub>2</sub>O </p>

<p>Superscript add the text <sup>higher than the normal text</sup> 
example 2<sup>5</sup></p>

<p>For text that does not hold a very dramatic value in the website but needs to 
be present, we use the <small>element</small>. One good example of this could be 
the trademark and copyright text at the footer of the website.</p>
```

## Attributes, ARIA, and Characters

### **Attributes**

Global attributes includes the following:

| Attribute name | Description | Example |
| --- | --- | --- |
| class | Categorises elements into one class. Comes handy with CSS and JS. | <p class="introduction">this is an intro class</p> |
| id | unique element identifier. all ids must be unique. Used for CSS or JS. More relevant in case of JavaScript | <p id="introHeading">this is an intro heading id</p> |
| contenteditable | whether the content on the website is editable. | <blockquote contenteditable="">Enter your name here</blockquote> |
| lang | states the language of the content. | <p lang="en">tag</p> |
| dir | stands for direction. denotes the flow the content. | <p dir="ltr">Superscript add the text <sup>higher than the normal text</sup> example 2<sup>5</sup> |

**ARIA Rules**

- to add more meaning to the HTML codes.
- Provides clarification to accessibility tree.
- specially useful functionality
- use the *aria-label = “”* for areas that might be tricky for the assistive devices to read.
- use the *aria-hidden = “”* for the elements you want to hide from the assistive devices.
- allows making site accessible for everyone
- Use when the existing markup makes things confusing in the accessibility tree.

### Formatting HTML

- HTML ignores all whitespace
- Case insensitive
- Fun Fact: The elements introduced in early 80s-90s are shorter in length since they focused on optimising  space due to storage restrictions. The  elements which are longer in length were developed much later focusing on enhancing the readability of the code.
- 

```html
<!-- this is how you can add comment -->
```

### Weird Characters

| Code | Symbol |
| --- | --- |
| &copy; | copyright symbol |
| &trade; | trademark symbol |
| &star; | star symbol |
| &nbsp; | Add space asking the browser not to break the word, line, or space where the element is added.  |

## Linking and Navigation

### Links

```html
<a href="linkhere.com">add placeholder text here</a>
```

Navigation Menu

```html
<nav role="navigation" aria-label="main menu">
    <ul class="navbar">
      <li><a href="/home">Home</a></li>
      <li><a href="/product">Product</a></li>
      <li><a href="/blog">Blog</a></li>
      <li><a href="/contact">Contact</a></li>
    </ul>
  </nav>
```

Navigational menu can be of multiple types. There can be breadcrumb menu, menu in the footer containing privacy information, and many more.
