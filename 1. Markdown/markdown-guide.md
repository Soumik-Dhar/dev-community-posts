It's happening again. You stare at your screen, trying to figure out why your write-up looks like an IKEA manual, written using only the stuff that comes after the question mark in an URL. Wouldn't it be great to create content and format it seamlessly without making it less human-readable in the process?

This is where Markdown comes in. Markdown allows you to quickly write and format structured content for the web. It is easy to learn and can be used to create websites, notes, technical documentation, and even books! 

**Fun Fact**: This entire tutorial has been designed and formatted using Markdown itself! Read till the end to find an awesome <u>[cheat sheet](#cheat-sheet)</u> for this tutorial which has also been created using Markdown!

![cheat-sheet](https://dev-to-uploads.s3.amazonaws.com/i/5dujgfm2j742eg6cbmoa.png)

---

# Wait...What's Markdown Again?

Markdown is a lightweight markup language used for formatting plain text documents with a simple, unobtrusive syntax. It was created by [John Gruber](https://en.wikipedia.org/wiki/John_Gruber) with [Aaron Swartz](https://en.wikipedia.org/wiki/Aaron_Swartz) in 2004. From the official documentation at [Daring Fireball](https://daringfireball.net/projects/markdown/), Markdown can be defined as,

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

Here's a small clip of Markdown in action - 

![markdown-in-action](https://dev-to-uploads.s3.amazonaws.com/i/kx1i4ce4hlxmbd6dr87d.gif)

---

# ~~Turn down~~ Markdown For What!?

Due to its highly intuitive and portable nature, Markdown is used in a wide variety of applications. Some of its use cases are -

- **Documents** - While Markdown is not as powerful as Microsoft Word or similar What You See Is What You Get ([WYSIWYG](https://en.wikipedia.org/wiki/WYSIWYG)) editors, it is good enough for lightweight formatting
- **Websites** - Static site generators like [Jekyll](https://jekyllrb.com/) convert Markdown files into static HTML websites that can be hosted for free on platforms like [GitHub Pages](https://pages.github.com/)
- **Documentation** - Markdown offers the ideal syntax for technical documentation and is widely used for writing scientific papers, articles, and even the `README.md` files in GitHub (like the one shown below)

![markdown-in-readme](https://dev-to-uploads.s3.amazonaws.com/i/8g79m7dxbymal6skqxop.png)

---

# How To Get Started

One of the biggest advantages of learning Markdown is that it does not require downloading a whole bunch of applications (paid or otherwise) to create Markdown-formatted documents. Simply choose from a wide array of free online Markdown editors to learn and practice the syntax or, just launch your favorite text editor and you're good to go!

## Markdown Editors

To get started with Markdown, you have the following options (and more) at your disposal -

### Online Markdown Editors -

- <u>[Dillinger](https://dillinger.io/)</u>
- <u>[StackEdit](https://stackedit.io/)</u>
- <u>[Markdown Editor](https://jbt.github.io/markdown-editor/)</u>
- <u>[Markdown Live Preview](https://markdownlivepreview.com/)</u>

### Desktop Applications -

- <u>[Visual Studio Code](https://code.visualstudio.com/)</u>
- <u>[Atom](https://atom.io/)</u>
- <u>[Typora](https://typora.io/)</u>
- <u>[MacDown](https://macdown.uranusjr.com/)</u> (only available for macOS)

---

# How to get the most out of this tutorial?

To follow along with the tutorial, choose an online editor like **Dillinger** and try out the syntax as you learn it. After you get accustomed to the syntax, you can switch to an offline text editor like **VS Code** to create fully-fledged Markdown documents. Just create a plain text file with the `.md` or `.markdown` extension, open it using your editor of choice and you're off to the races!

For this tutorial, I've used <u>[VS Code](https://code.visualstudio.com/)</u> with the extension <u>[Markdown Preview Enhanced](https://shd101wyy.github.io/markdown-preview-enhanced/#/)</u> installed. You can use the Markdown previewer that comes bundled with VS Code as well. Also included at the very end, is a cheat sheet summarizing the entire tutorial. So, without any further ado, let's get started!

<figure>
<img src="https://dev-to-uploads.s3.amazonaws.com/i/jbg87bx3v0xxmtu0qlr3.png" alt="Dillinger">
<figcaption> 
<a href="https://dillinger.io/">Dillinger</a>
</figcaption>
<figure>

---

# Basic Markdown Syntax

Almost all Markdown applications support the basic syntax outlined in John Gruber's original documentation. The most commonly used elements in the basic Markdown syntax are discussed below.

## Headings

Heading elements in Markdown can be created by prepending the number symbol `#` to a word or phrase.
The number of hashes (#) indicates the level of the heading. One hash (#) corresponds to a level 1 heading - all the way up to six hashes (######) for a level 6 heading.

**Pro-tip**: Always add a space between the hash symbol and the heading name for consistent results.

<table width="100%">
  <tr>
    <th><center>Markdown</center></th>
    <th><center>Equivalent HTML</center></th>
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
    <th><center>Markdown</center></th>
    <th><center>Equivalent HTML</center></th>
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
    <th><center>Markdown</center></th>
    <th><center>Equivalent HTML</center></th>
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

Text can be emphasized by making it **bold** or _italicized_.  
To make the text **bold**, add double asterisks `**` or double underscores `__` before and after a word or phrase. To _italicize_ text, wrap the word or phrase inside a pair of a single asterisk `*` or a single underscore `_`.

**Pro-tip**: Use asterisks instead of underscores when formatting words inside of a phrase.

<table width="100%">
  <tr>
    <th><center>Markdown</center></th>
    <th><center>Equivalent HTML</center></th>
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
    <th><center>Markdown</center></th>
    <th><center>Equivalent HTML</center></th>
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

Using Markdown, related items can be grouped in the form of unordered or ordered lists.

### Unordered Lists

To create unordered (bullet) lists, prefix the list items with asterisks `*`, hyphens `-` or plus signs `+`.

<table width="100%">
  <tr>
    <th><center>Markdown</center></th>
    <th><center>Equivalent HTML</center></th>
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

To create ordered lists, prefix the list items with numbers followed by periods. The labels do not even need to be in the correct numerical order - Markdown does that for you automatically!

<table width="100%">
  <tr>
    <th><center>Markdown</center></th>
    <th><center>Equivalent HTML</center></th>
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

**Pro-tip**: You can also create **nested lists** (sublists) made up of both ordered and unordered lists by simply indenting the nested list items.

<table width="100%">
  <tr>
    <th><center>Markdown</center></th>
    <th><center>Equivalent HTML</center></th>
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

Links in Markdown can be created in the following ways:

1. **Inline-style links** - Wrap the link text in brackets `[]` followed by the link URL in parenthesis `()`. To add an optional tooltip, enclose the title within quotes and add it right after the URL. 
2. **reference-style links** - Instead of inserting the URL inside the parenthesis, a reference to the link can also be made. Create such a link by enclosing the reference inside square brackets `[]` and linking it to the URL from anywhere in the document.

**Pro-tip**: To quickly add a clickable URL or email address, enclose the link inside a pair of angle brackets `<>`

**Markdown**:
```
[An inline-style Link](http://example.com/)

[A reference-style link][Reference]
<!-- linking -->[Reference]: http://example.com/

<http://example.com/>
```

**Equivalent HTML**:
```
<a href="http://example.com/">Links in HTML</a>

<a href="http://example.com/" title="Tooltip"> 
Links in HTML with an optional title
</a>
```

![links-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/qbq4hnahkvqk67smqo26.png)

---

## Images

Images can be created the same way as links - the only thing that needs to be added is an exclamation mark `!` before the link syntax.

1. **Inline-style images** - `![alt text](image URL)`
2. **Reference-style images** - `![alt text][reference]`
`[reference]: image URL`

**Pro-tip**: Images can also be used as links themselves. Simply enclose the Markdown syntax for the image in brackets and append the link URL in parenthesis - 
`[![alt text](image URL)](link URL)`

**Markdown**:
```
![Markdown-mark](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
```

**Equivalent HTML**:
```
<img src="https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg" alt="Markdown-mark">
```

![images-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/j5x66nsligj3stgmakds.png)

---

# Extended Markdown Syntax

To overcome the unambiguous specs proposed by John Gruber's Markdown syntax, several individuals and organizations came up with specific implementations - often referred to as _flavors_ of Markdown. These lightweight markup languages provide extended features and improve on some of the drawbacks of the original syntax. Some of these are - 

* <u>[GitHub Flavored Markdown (GFM)](https://github.github.com/gfm/)</u>
* <u>[CommonMark](https://commonmark.org/)</u>
* <u>[Markdown Extra](https://michelf.ca/projects/php-markdown/extra/)</u>

Some of the elements supported by these lightweight markup languages are discussed below.

## Tables

Tables are available in GitHub Flavored Markdown (GFM). To create a table, separate each column with the pipe symbol `|` and use three or more hyphens `---` to indicate the first row (column headers). 

**Pro-tip**: To left, right or center align text in the columns, simply add a colon `:` to the left, right, or both sides of the column header hyphens respectively. 

**Syntax**:
```
| First Name | Last Name | Age |
| :--------- | :-------: | --: |
| John       |    Doe    |  28 |
| Jane       |    Doe    |  52 |
```

![tables-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/1k5majlhkurxf21ulhr2.png)

---

## Extended Text Formatting

Extended Markdown syntax allows text to be struck-through and highlighted. To strikethrough text, wrap the word or phrase inside a pair of double tildes `~~`. To highlight text, use a pair of double equality signs `==` before and after the word or phrase. 

**Syntax**:
```
Strikethrough text ~~like this~~ using a pair of double tildes

Highlight text ==like this== using a pair of double equality signs
```

![extended-text-formatting-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/1d1dvkxki0imjui9hv7b.png)

---

## Task Lists

Task lists are used to provide progress indicators in the form of list items with checkboxes. 
To create a task list, simply add double brackets with a space between them `[ ]`  before the list item in an unordered or ordered list. To check off a list item, add an `x` inside the brackets `[x]`.

**Syntax**:
```
1. [ ] Unchecked list item
1. [x] Checked list item
1. [ ] Another unchecked list item

- [x] Research
- [x] Compose
- [ ] Publish
```

![task-lists-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/ckw3vawjfn40w4v4ya6v.png)

---

## Code

Although inline code and code blocks can be created using the original Markdown syntax, it is convenient to discuss all the various ways to embed code in Markdown in one place.

### Inline Code

To include inline code snippets, enclose the code in a pair of backticks <code>`</code>.

<pre>
Run `npm install` to install all dependencies
</pre>

### Code Blocks

To create a block of code (without using extended syntax), indent each line of code by one or more tabs (at least 4 spaces).

<pre>
      while (--i >= 0) {
         free_page((unsigned long);
      }
      kfree(group_info);
      return NULL;
</pre>

![code-in-blocks](https://dev-to-uploads.s3.amazonaws.com/i/6tuw5bgbdyhtsvwzt0vo.png)

### Fenced Code Blocks

Using the extended Markdown syntax, blocks of code can be created by wrapping the code block inside a pair of triple backticks.

<pre>
```
// function to add two numbers
function add(num1, num2) {
   return num1 + num2
}
```
</pre>

![fenced-code-blocks-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/rkcc2w1yc8m9bxixyl0g.png)

### Syntax Highlighting

To add syntax highlighting to a fenced code block, append the language name after the starting backticks <code>\```</code> before the code block begins.

<pre>
```js
// function to add two numbers using javascript
function add(num1, num2) {
   return num1 + num2
}
```

```c++
// function to add two numbers using c++
double add (double num1, double num2) {
   return (num1 + num2);
}
```
</pre>

![syntax-highlighting-in-markdown](https://dev-to-uploads.s3.amazonaws.com/i/gvnfaa5zauo70f1j6lo1.png)

---

#### Escaping Characters

In case you actually want to use certain literals like `*` and `#` without having them formatted, simply prefix a backslash `\` before the character or wrap it inside a pair of backticks <code>`</code> (similar to inline code). 

<pre>
\# Without the backslash, this would be a level 1 heading!
</pre>
---

# Cheat Sheet

A list of frequently used basic and extended Markdown syntax has been provided in the cheat sheet linked below. Go ahead, fork this gist or bookmark it and use it as a quick reference to take your Markdown skills to the next level!

**Fun fact**: This entire cheat sheet has been created using Markdown itself!

### <center><u> [Markdown Cheat Sheet](https://gist.github.com/Soumik-Dhar/29c9be8431660f16bf1db5248367a23f) </u></center>

---

# Wrapping it up

Now that you know how to use Markdown to format plain text, it's your turn to play around with the syntax, build cool projects with it, and have fun along the way! 

Here's a list of useful resources you can utilize to elevate your Markdown skills - 

* <u>[Daring Fireball](https://daringfireball.net/projects/markdown/)</u> - The official Markdown guide written by John Gruber
* <u>[Markdown Tutorial](https://www.markdowntutorial.com/)</u> - An interactive browser-based markdown tutorial
* <u>[The Markdown Guide](https://www.markdownguide.org/)</u> - A free and open-source Markdown reference guide

Whenever you get stuck over a particular syntax or feel like reviewing some of the concepts, give this tutorial a shot and hold on to that cheat sheet as a handy reference. 

**Final pro-tip**: Never hesitate to use HTML for advanced formatting, as Markdown is more or less a superset of HTML.

If there's any syntax that I missed or anything that I wasn't able to explain clearly, feel free to hit me up in the comments below. Your feedback means a lot to me.

---

___Disclaimer: Markdown is an incredibly powerful tool meant for composing rich content for the web and hence, is widely used across a large number of platforms and applications. This guide has been written in an effort to make Markdown accessible to beginners as well as, to serve as a quick reference for experienced users.___