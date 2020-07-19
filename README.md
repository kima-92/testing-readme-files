# testing-readme-files
Personal repo to test Markdown features

* This is meant to be an Example
* Markdown is really fast
* Cool, right?

## Link example
Inline-style link
[One quick cheatsheet from GitHub](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

1. Item One
2. Item two
3. Item Three

<!-- This is how you commentout something -->

<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## _Italic_

<!-- Normal Italics -->
*Using stars* to make italic text

_Using underscore_ to make italic text

<!-- Strong (bold) Italics -->
**Using double stars** to make italic text

__Using double underscore__ to make italic text

## Strikethrough

<!-- Strikethrough -->
~~Using double tilde~~ to make strikethrogh text

## Horizontal Rule

<!-- Horizontal Lines/Separators -->
Using triple hyphens

---
or

Triple underscores
___

## Escape characters with the backslash

<!-- If you actually need to display the special characters like *, _ or ~. -->
<!-- Use the backslash before each character you want to display -->
\*Using text and the stars\* without making it italic text

\~~Using the tilde\~~ without making it strike the text

## Blockquote
<!-- Using one greater-than sign -->
> This is a quote, using one greater than simbol.
This quote continues at the second line too.

## Links

<!-- The text you want for the link has to be in brakets [] -->
<!-- The URL goes in the parenthesis -->

Simple link :

[Google](https://www.google.com/)

<!-- If I want a title to be displayed when the mouse hovers over the link, that goes inside the parenthesis, WITH A SPACE after the URL, in between double quotes -->

Link with a title :

Link to the [tutorial video](https://www.youtube.com/watch?v=HUBNt18RFbo "Markdown Crash Course") I followed while learning Markdown

## Lists

### Unordered List
<!-- For nested items, use the tap then the start again -->
Using the star

* Item 1
* Item 2
* Item 3
    * Nested Item 3.1
    * Nested Item 3.2
    * Nested Item 3.3

### Ordered List
<!--- You can list them as 1. 1. 1. .. or 1. 2. 3. .. -->
Using 1.

1. Item 1
1. Item 2
1. Item 3

## Inline Code Block

<!-- Using backticks -->
`<p> This is a paraghraph <p>`

`var person: Person()`

## Images

<!-- Like making a link, but using the ! before it -->
Add an image using !, [] and ()

![Markdown Logo](https://markdown-here.com/img/icon256.png)


# GitHub Markdown

## Code Blocks

<!-- Using triple backticks -->

```
Small block of code, no specifications
```

```bash
# Telling the block of code, this is in bash

npm install
npm start
```

```swift
//Telling the block of code, this is in Swift
var a = "Some string"
```

```javascript
// Telling this block of code, this is in javascript
function add(num1, num2) {
    return num1 + num2;
}
```

```python
# Telling this block of code, this is in javascript
def add(num1, num2):
    return num1 + num2
```

## Tables
<!-- Use the vertical bar and the dashes/hyphens, to separate and specify where the different components of the table should be -->

| Name     | Email             |
| -------- | ----------------- |
| John Doe | johndoe@gmail.com |
| Jane Doe | janedoe@gmail.com |

## Task List
<!-- Use the stars to list them -->
<!-- Then the square brakets with an x or a space, to mark them as completed or not -->

* [x] Task 1 Done
* [x] Task 2 Done
* [ ] Task 3 Not Done

## Images from inside this repo

Inside this same repo

![](GUEST_9dd6d425-5711-478d-8aa6-7fecf18e7c18.jpg)

Inside the imagesFolder, in this repo

![](imagesFolder/GWC_SEO_Logo.png)

### Images with specified size
<!-- This does the same as above, but in HTML -->
<!-- Which allows you to specify a width and/or hight -->

<!-- If you specify both, it won't respect the original aspect ratio of the image. If you only specify width OR height, it will maintain it's aspect ratio -->

With a specified width of 200

<img src="GUEST_9dd6d425-5711-478d-8aa6-7fecf18e7c18.jpg" width=200>

### Images with a link
<!-- Make sure it's inside [], followed by the link inside a parenthesis. No spaces -->

[<img src="imagesFolder/GWC_SEO_Logo.png" width=200>](https://girlswhocode.com/)