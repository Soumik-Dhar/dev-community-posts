It's happening again. You stare at your screen, trying to figure out why your write-up looks like an IKEA manual, written using only the stuff that comes after the question mark in an URL. Wouldn't it be great to create content and format it seamlessly without making it less human-readable in the process?

This is where Markdown comes in. Markdown allows you to quickly write and format structured content for the web. It is easy to learn and can be used to create websites, notes, technical documentation, and even books! Read till the end to find an awesome cheat sheet for this tutorial which has been created using Markdown itself!

Here's a small clip of Markdown in action -

> insert clip

---

# Wait...What's Markdown Again?

Markdown is a lightweight markup language used for formatting plain text documents with a simple, unobtrusive syntax. It was created by John Gruber with Aaron Swartz in 2004. From the official documentation at Daring Fireball, Markdown can be defined as,

> "a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML)."

Okay, let's break that down. A Markup language is a human-readable language that provides a system to annotate text inside a document. These annotations (or tags) can then be used to structure and format the document.
One of the most commonly used markup languages is the HyperText Markup Language, better known as HTML. Despite being the de facto standard for web design, HTML comes with a few downsides.

<figure>
<img src="https://imgs.xkcd.com/comics/tags.png" alt="xkcd-tag-comic">
<figcaption> 
source: <a href="https://xkcd.com/1144">xkcd comics</a>
</figcaption>
<figure>

HTML relies heavily on syntax-specific tags which make the content hard to read. This problem inspired John Gruber to come up with a cleaner, more readable markup language called Markdown. In his own words,

> "The overriding design goal for Markdown's formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions."
> (_[https://daringfireball.net/projects/markdown/](https://daringfireball.net/projects/markdown/)_)

---

# ~~Turn down~~ Markdown For What!?

Due to its highly intuitive and portable nature, Markdown is used in a wide variety of applications. Some of its use cases are -

- Documents - While Markdown is not as powerful as Microsoft Word or similar What You See Is What You Get (WYSIWYG) editors, it is good enough for lightweight formatting
- Websites - Static site generators like Jekyll convert Markdown files into static HTML websites that can be hosted for free on platforms like GitHub Pages
- Documentation - Markdown offers the ideal syntax for technical documentation and is widely used for writing scientific papers, articles, and even the README.md files in GitHub (like the one shown below)

![markdown-in-readme](https://dev-to-uploads.s3.amazonaws.com/i/8g79m7dxbymal6skqxop.png)

---

# How To Get Started

One of the biggest advantages of learning Markdown is that it does not require downloading a whole bunch of applications (paid or otherwise) to create Markdown-formatted documents. Simply choose from a wide array of free online markdown editors to learn and practice the syntax or, just launch your favorite text editor and you're good to go!

## Markdown Editors

To get started with Markdown, you have the following options (and more) at your disposal -

### Online Markdown Editors -

- Dillinger
- StackEdit
- Markdown Editor
- Markdown Live Preview

### Desktop Applications -

- Visual Studio Code
- Atom
- Typora
- MacDown (only available for macOS)

---

# How to get the most out of this tutorial?

To follow along with the tutorial, choose an online editor like Dillinger and try out the syntax as you learn it. After you get accustomed to the syntax, you can switch to an offline text editor like VS Code to create fully-fledged Markdown documents. Just create a plain text file with the .md or .markdown extension, open it using your editor of choice and you're off to the races!

For this tutorial, I've used VS Code with the extension Markdown Preview Enhanced installed. You can use the Markdown previewer that comes bundled with VS Code as well. Also included at the very end, is a cheat sheet summarizing the entire tutorial. So, without any further ado, let's get started!

![Dillinger](https://dev-to-uploads.s3.amazonaws.com/i/jbg87bx3v0xxmtu0qlr3.png)

---

# Basic Markdown Syntax

Almost all Markdown applications support the basic syntax outlined in John Gruber's original documentation. The most commonly used elements in the basic Markdown syntax are discussed below.

## Headings

Heading elements in markdown can be created by prepending the number symbol `#` to a word or phrase.
The number of hashes (#) indicates the level of the heading. One hash (#) corresponds to a level 1 heading - all the way up to six hashes (######) for a level 6 heading.

**Pro-tip**: Always add a space between the hash symbol and the heading name for consistent results.

<table width="100%">
  <tr>
    <th>Markdown</th>
    <th>Equivalent HTML</th>
  </tr>
  <tr>
    <td>
      <pre>
# Level 1 Heading
## Level 2 Heading
### Level 3 Heading
#### Level 4 Heading
##### Level 5 Heading
###### Level 6 Heading
</pre>  
    </td>
    <td>
      <pre>
&lt;h1&gt;Level 1 Heading&lt;/h1&gt;
&lt;h2&gt;Level 2 Heading&lt;/h2&gt;
&lt;h3&gt;Level 3 Heading&lt;/h3&gt;
&lt;h4&gt;Level 4 Heading&lt;/h4&gt;
&lt;h5&gt;Level 5 Heading&lt;/h5&gt;
&lt;h6&gt;Level 6 Heading&lt;/h6&gt;
</pre>
    </td>
  </tr>
</table>

![headings-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/g86wpg4t37zthnyx8vgc.png)

---

## Paragraphs

To separate multiple lines of text into paragraphs, simply use one or more blank lines.

**Pro-tip**: To force a line break (without using the `<br />` tag), end a line or paragraph with two or more spaces, and then press return (enter).

<table width="100%">
  <tr>
    <th>Markdown</th>
    <th>Equivalent HTML</th>
  </tr>
  <tr>
    <td>
      <pre>
This is a paragraph. 
Insert a blank line 
to add another one!

This is another paragraph.
It's that simple!

</pre>  
 </td>
<td>
<pre>
&lt;p&gt;This is a paragraph.
Insert a blank line to
add another one!&lt;/p&gt;
&lt;br /&gt;
&lt;p&gt;This is another paragraph.
It's that simple!&lt;/p&gt;
</pre>
</td>
  </tr>
</table>

![paragraphs-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/0u3ng1tcbm2cs5ozrkhu.png)

---

## Horizontal Rules

Thematic breaks in the form of horizontal rules can be inserted by using three or more asterisks `***`, hyphens `---`, or underscores `___`, with or without spaces in between.

<table width="100%">
  <tr>
    <th>Markdown</th>
    <th>Equivalent HTML</th>
  </tr>
  <tr>
    <td>
      <pre>
***
---
___ 
</pre>  
    </td>
    <td>
      <pre>
&lt;hr /&gt;
&lt;hr /&gt;
&lt;hr /&gt; 
</pre>
    </td>
  </tr>
</table>

![horizontal-rules-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/w70ul8qclvdbnyvpier4.png)

---

## Text Formatting - Emphasis

Text can be emphasized by making it bold or italicized.  
To make the text bold, add double asterisks `**` or double underscores `__` before and after a word or phrase. To italicize text, wrap the word or phrase inside a pair of a single asterisk `*` or a single underscore `_`.

**Pro-tip**: Use asterisks instead of underscores when formatting words inside of a phrase.

<table width="100%">
  <tr>
    <th>Markdown</th>
    <th>Equivalent HTML</th>
  </tr>
  <tr>
    <td>
      <pre>
__This text is in bold__
And so is this **word**

_This text is italicized_
And so is this _word_

**_This text is in
both bold and italics_**
And so is this **_word_**

</pre>  
 </td>
<td>
<pre>
&lt;strong&gt;This text is in bold&lt;/strong&gt;
And so is this &lt;strong&gt;word&lt;/strong&gt;

&lt;em&gt;This text is italicized&lt;/em&gt;
And so is this &lt;em&gt;word&lt;/em&gt;

&lt;strong&gt;&lt;em&gt;This text is in
both bold and italics&lt;/em&gt;&lt;/strong&gt;
And so is this &lt;em&gt;&lt;strong&gt;word&lt;/strong&gt;&lt;/em&gt;

</pre>
</td>
  </tr>
</table>

![text-formatting-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/65ibj19w8o0makhtv0wp.png)

---

## Blockquotes

Blockquotes can be created by adding the `>` symbol in front of a line of text.
To add blockquotes comprising of multiple paragraphs, add a `>` on each black line.

**Pro-tip**: To create nested blockquotes, add two or more `>` symbols depending upon the level.

<table width="100%">
  <tr>
    <th>Markdown</th>
    <th>Equivalent HTML</th>
  </tr>
  <tr>
    <td>
      <pre>
>"I'm gonna make him an 
offer he can't refuse."

> Fate whispers to the Warrior,
> A storm is coming,
>
> > And the Warrior whispers back,
> > I am the Storm.

</pre>
    </td>
    <td>
      <pre>
&lt;blockquote&gt;"I'm gonna
make him an offer he can't
refuse."&lt;/blockquote&gt;

&lt;blockquote&gt;
Fate whispers to the Warrior,
A storm is coming,
&lt;blockquote&gt;And the Warrior
whispers back, I am the Storm.
&lt;/blockquote&gt;
&lt;/blockquote&gt;

</pre>
</td>
  </tr>
</table>

![blockquotes-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/lyw725ozxgdlqjdhewgp.png)

---

## Lists

Using markdown, related items can be grouped in the form of unordered or ordered lists.

### Unordered Lists

To create unordered (bullet) lists, prefix the list items with asterisks `*`, hyphens `-` or plus signs `+`.

<table width="100%">
  <tr>
    <th>Markdown</th>
    <th>Equivalent HTML</th>
  </tr>
  <tr>
    <td>
      <pre>
* First list item
* Second list item
* Third list item

- Element 1
- Element 2
- Element 3

* List item 1
* List item 2
* List item 3
</pre>  
   </td>
  <td>
  <pre>
&lt;ul&gt;
&lt;li&gt;First list item&lt;/li&gt;
&lt;li&gt;Second list item&lt;/li&gt;
&lt;li&gt;Third list item&lt;/li&gt;
&lt;/ul&gt;

&lt;ul&gt;
&lt;li&gt;List item 1&lt;/li&gt;
&lt;li&gt;List item 2&lt;/li&gt;
&lt;li&gt;List item 3&lt;/li&gt;
&lt;/ul&gt;

</pre>
</td>
  </tr>
</table>

![unordered-lists-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/yht3d1z3f1g5019jsu2l.png)

---

### Ordered Lists

To create ordered lists, prefix the list items with numbers followed by periods. The labels do not even need to be in the correct numerical order - markdown does that for you automatically!

<table width="100%">
  <tr>
    <th>Markdown</th>
    <th>Equivalent HTML</th>
  </tr>
  <tr>
    <td>
      <pre>
1. First list item
1. Second list item
1. Third list item

a. List item 1
b. List item 2
c. List item 3

</pre>  
 </td>
<td>
<pre>
&lt;ol&gt;
&lt;li&gt;First list item&lt;/li&gt;
&lt;li&gt;Second list item&lt;/li&gt;
&lt;li&gt;Third list item&lt;/li&gt;
&lt;li&gt;List item 4&lt;/li&gt;
&lt;li&gt;List item 5&lt;/li&gt;
&lt;/ol&gt;
</pre>
</td>
  </tr>
</table>

![ordered-lists-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/oqiyrfj0shxxmijox8q8.png)

**Pro-tip**: You can also create nested lists (sublists) made up of both ordered and unordered lists by simply indenting the nested list items.

<table width="100%">
  <tr>
    <th>Markdown</th>
    <th>Equivalent HTML</th>
  </tr>
  <tr>
    <td>
      <pre>
1. Parent list item 1
1. Parent list item 2
 a. Child list item a
 b. Child list item b
1. Parent list item 3
    * Child item 1 
    * Child item 2
</pre>  
    </td>
    <td>
      <pre>
&lt;ol&gt;
  &lt;li&gt;Parent list item 1&lt;/li&gt;
  &lt;li&gt;Parent list item 2&lt;/li&gt;
  &lt;ol&gt;
    &lt;li&gt;Child list item a&lt;/li&gt;
    &lt;li&gt;Child list item b&lt;/li&gt;
  &lt;/ol&gt;
  &lt;li&gt;Parent list item 3&lt;/li&gt;
  &lt;ul&gt;
    &lt;li&gt;Child item 1&lt;/li&gt;
    &lt;li&gt;Child item 2&lt;/li&gt;
  &lt;/ul&gt;
&lt;/ol&gt;
</pre>
    </td>
  </tr>
</table>

![nested-lists-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/u90p213sms6anzv69lcw.png)

---

## Links

Links in markdown can be created in the following ways:

1. **Inline-style links** - Wrap the link text in brackets `[]` followed by the link URL in parenthesis `()`. To add an optional tooltip, enclose the title within quotes and add it right after the URL.
2. **reference-style links** - Instead of inserting the URL inside the parenthesis, a reference to the link can also be made. Create such a link by enclosing the reference inside square brackets `[]` and linking it to the URL from anywhere in the document.

**Pro-tip**: To quickly add a clickable URL or email address, enclose the link inside a pair of angle brackets `<>`

**Markdown:**

```
[An inline-style Link](http://example.com/)

[A reference-style link][Example Reference]
[Example Reference]: http://example.com/

<http://example.com/>
```

**Equivalent HTML:**

```
<a href="http://example.com/">Links in HTML</a>

<a href="http://example.com/" title="Tooltip">
Links in HTML with an optional title
</a>
```

![links-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/qbq4hnahkvqk67smqo26.png)

---

## Images

Images can be created the same way as links - the only thing that needs to be added is an exclamation mark ! before the link syntax.

1. **Inline-style images** - `![alt text](image URL)`
2. **Reference-style images** - `![alt text][reference]`
   `[reference]: image URL`

**Pro-tip**: Images can also be used as links themselves. Simply enclose the markdown syntax for the image in brackets and append the link URL in parenthesis -
`[![alt text](image URL)](link URL)`

**Markdown:**

```
![Markdown-mark](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
```

**Equivalent HTML:**

```
<img src="https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg" alt="Markdown-mark">
```

![images-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/j5x66nsligj3stgmakds.png)
