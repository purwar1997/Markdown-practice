# Markdown

![static-badge](https://img.shields.io/badge/syntax-markdown-red?style=flat)
![static-badge](https://img.shields.io/badge/version-1.0.0-blue?style=flat)
![static-badge](https://img.shields.io/badge/status-success-limegreen?style=flat)

## Table of contents

1.  [Headings](#headings)
2.  [Paragraphs](#paragraphs)
3.  [Text Formatting](#text-formatting)
    - [Italic text](#italic-text)
    - [Bold text](#bold-text)
    - [Bold and Italic text](#bold-and-italic-text)
    - [Strikethrough text](#strikethrough-text)
    - [Underlined text](#underlined-text)
    - [Smaller text](#smaller-text)
    - [Superscript and Subscript](#superscript-and-subscript)
    - [Highlighted text](#highlighted-text)
4.  [Emojis](#emojis)
5.  [Inline Code](#inline-code)
6.  [Code blocks](#code-blocks)
7.  [Links](#links)
    - [Links with text](#links-with-text)
    - [Links without text](#links-without-text)
    - [Image as a link](#image-as-a-link)
    - [Links within document](#links-within-document)
8.  [Images](#images)
9.  [Blockquotes](#blockquotes)
10. [Horizontal rule](#horizontal-rule)
11. [Lists](#lists)
    - [Ordered list](#ordered-list)
    - [Unordered list](#unordered-list)
12. [Tables](#tables)

## Headings

### Heading 1

#### Heading 2

Headings can also be created using HTML tags

<h5>Heading 3</h5>
<h6>Heading 4</h6>

## Paragraphs

This is first paragraph.

Another paragraph on a second line.

HERE  
comes a new line within the third paragraph  
because of double spaces.  
This is a multiline paragraph.

<p>Paragraphs can also be created using HTML tags</p>

## Text Formatting

### Italic Text

_This is an italicized text_

<i>Text italicized using HTML tags</i>

_Use as**teris**ks for mid w**or**d b**oldin**g_

### Bold text

**This is a bold text**

<b>Text made bold using HTML tags</b>

**Use a*sterisk*s for mid w*or*d i*talic*s**

### Bold and Italic text

**_This is a bold italicized text_**

<b><i>Text made bold and italicized using HTML tags</i></b>

### Strikethrough text

~~Crossed off text~~

~~Deleted text~~

Text <del>strikethrough</del> using HTML tags

### Underlined text

<ins>Text underlined using HTML tags</ins>

### Smaller text

This text is <small>smaller</small> in size than normal text

### Superscript and Subscript

This is a <sup>superscript</sup> text

This is a <sub>subscript</sub> text

### Highlighted text

<mark>Text highlighted using HTML tags</mark>

## Emojis

To add an emoji in Markdown, just copy and paste it - 😊 ❤️ 😻

## Inline Code

`Text highlighted using backticks`

`Can also be used for inline code`

To create variables in JavaScript language, we can use keywords like `var`, `let` and `const`.

To assign a value in variable, use expression `var x = 10`.

## Code Blocks

```html
<!-- This is HTML code -->

<h1>Large heading</h1>
<p>This is a paragraph</p>
<b>Bold text</b>
```

```css
/* This is CSS code */

* {
  margin: 0;
  padding: 0;
  outline: 0;
}

body {
  width: 100vw;
  height: 100vh;
  background-color: black;
}

.link {
  text-decoration: none;
}
```

```js
// This is JavaScript code

const value1 = 23;
const value2 = 4;
const sum = value1 + value2;

console.log(sum);
```

## Links

### Links with text

[This is a Youtube link](https://www.youtube.com/)

[Visit my GitHub profile](https://github.com/purwar1997)

[Python course](/2024-09-02/python-course/loops.py)

[Markdown course](/2024-09-02/markdown-course/example.md)

To vist zomato, <a href="https://www.zomato.com/">click here</a>.

### Links without text

<https://github.com/purwar1997/shopify-website-clone>

https://chatgpt.com

### Image as a link

<a href="https://www.swiggy.com"><img src="https://res.cloudinary.com/dlqnx5pot/image/upload/v1725280341/images_jpyctl.png" width="170px" /></a>

<a href="http://shopease.shubhampurwar.in"><img src="https://res.cloudinary.com/dlqnx5pot/image/upload/v1724768982/shopease-logo-white_jz62c3.svg" width="170"></a>

### Links within document

[Go to Headings](#headings)

[Go to Paragraphs](#paragraphs)

## Images

![Shopease logo](https://res.cloudinary.com/dlqnx5pot/image/upload/v1724768966/shopease-logo_a9ayl7.svg)

![Google logo](/logos/google.png)

Images can also be added using HTML tags

<img src="https://res.cloudinary.com/dlqnx5pot/image/upload/v1724768982/shopease-logo-white_jz62c3.svg" width="200">

## Blockquotes

> This is a blockquote
>
> > This is a nested blockquote
> >
> > > This is a doubly nested blockquote

<br>

> What is markdown?
>
> > Markdown files ends with .md extension. Markdown syntax is used to create README files of projects. In markdown files, we can use HTML tags to define content like headings and paragraphs.

## Horizontal Rule

Above horizontal rule

---

Between horizontal rules

---

Between horizontal rules

---

Below horizontal rule

## Lists

### Ordered List

- HTML
- CSS
- JavaScript
- DOM Manipulation
- Frameworks
  - React
    - Components
    - JSX
    - Hooks
    - State management
    - Routing
  - Angular
  - Vue
  - Svelte
  - Quik
- Version control

  - Git
  - Bitbucket

### Unordered List

Backend technologies -

1. Databases

   1. MySQL
   2. PostgreSQL
   3. Clickhouse

2. Runtime environments

   1. Node.js
   2. Deno.js
   3. Bun.js
      1. New kid in the town
      2. Faster than alternatives

3. Frameworks

   1. Express.js
      1. Easy to use
      2. Supports all HTTP methods
      3. Comes with middleware support
      4. Able to parse JSON payload
      5. Able to parse urlencoded data
   2. Hapi.js
   3. Nest.js

## Tables

| ID  | Username       | Email                    | Phone      |
| --- | -------------- | ------------------------ | ---------- |
| 1   | Shubham Purwar | shubhampurwar35@gmail.com | 9897887871 |
| 2   | Kunal Shah     | kunalcred20@gmail.com    | 8171617090 |
| 3   | Kailash Nadh   | nadh0dha_cto@gmail.com   | 7890987871 |

<br>

| Left                |        Center         |                Right |
| :------------------ | :-------------------: | -------------------: |
| First item on left  | First item in center  |  First item on right |
| Second item on left | Second item in center | Second item on right |

<br>

|   Name   | Age | Vaccinated |
| :------: | :-: | :--------: |
| Shubham  | 26  |    Yes     |
|  Suyash  | 21  |     No     |
| Sandeep  | 57  |    Yes     |
| Sangeeta | 52  |     No     |

## Checklist

- [X] Checked
- [ ] Unchecked

<br>

- [X] Male
- [ ] Female
- [ ] Other