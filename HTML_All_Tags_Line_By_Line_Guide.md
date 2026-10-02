# 📚 Master Guide: Complete HTML Tags Reference & Line-by-Line Analysis

> **Workspace**: `Apna College / Html`  
> **Total Files Analyzed**: 109 HTML files  
> **Coverage**: Complete line-by-line breakdown for every HTML file in this repository.


## 📋 Table of Contents

- [1. Document Structure & Core Metadata](#1-document-structure--core-metadata)
- [2. Semantic Layout & Sections](#2-semantic-layout--sections)
- [3. Typography, Headings & Text Formatting](#3-typography-headings--text-formatting)
- [4. Lists & Navigation](#4-lists--navigation)
- [5. Tables & Tabular Data](#5-tables--tabular-data)
- [6. Forms & User Inputs](#6-forms--user-inputs)
- [7. Multimedia, Images & Graphics](#7-multimedia-images--graphics)
- [8. Interactive Dialogs & Disclosures](#8-interactive-dialogs--disclosures)

---


## <a id="1-document-structure--core-metadata"></a>1. Document Structure & Core Metadata

*Essential root elements, document structure, metadata, links, and styling configurations.*


### 📄 [`1.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/1.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<title>Title of the document</title>
</head>

<body>
The content of the document......
</body>

</html>

```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<title>Title of the document</title>` | Sets the document title rendered in the browser tab and bookmarks bar: **"Title of the document"**. |
| **Line 5** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 8** | `The content of the document......` | Renders markup / text content: `The content of the document......` |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |

---

### 📄 [`base10.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/base10.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
  <base href="https://www.w3schools.com/" target="_blank">
</head>
<body>

<h1>The base element</h1>

<p><img src="images/stickman.gif" width="24" height="39" alt="Stickman"> - Notice that we have only specified a relative address for the image. Since we have specified a base URL in the head section, the browser will look for the image at "https://www.w3schools.com/images/stickman.gif".</p>

<p><a href="tags/tag_base.asp">HTML base tag</a> - Notice that the link opens in a new window, even if it has no target="_blank" attribute. This is because the target attribute of the base element is set to "_blank".</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<base href="https://www.w3schools.com/" target="_blank">` | Renders markup / text content: `<base href="https://www.w3schools.com/" target="_blank">` |
| **Line 5** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 6** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 7** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 8** | `<h1>The base element</h1>` | Defines a **H1** heading element with text: *"The base element"*. |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `<p><img src="images/stickman.gif" width="24" height="39...` | Defines a paragraph (`<p>`) element displaying text: *"<img src="images/stickman.gif" width="24" height="39" alt="Stickman"> - Notice that we have only specified a relative address for the image. Since we have specified a base URL in the head section, the browser will look for the image at "https://www.w3schools.com/images/stickman.gif"."*. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<p><a href="tags/tag_base.asp">HTML base tag</a> - Noti...` | Defines a paragraph (`<p>`) element displaying text: *"<a href="tags/tag_base.asp">HTML base tag</a> - Notice that the link opens in a new window, even if it has no target="_blank" attribute. This is because the target attribute of the base element is set to "_blank"."*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `</body>` | Closes the document `<body>` section. |
| **Line 15** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`bdi-11.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/bdi-11.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The bdi element</h1>

<p>In the example below, usernames are shown along with the number of points in a contest. If the bdi element is not supported in the browser, the username of the Arabic user would confuse the text (the bidirectional algorithm would put the colon and the number "90" next to the word "User" rather than next to the word "points").</p>

<ul>
 <li>User <bdi>hrefs</bdi>: 60 points</li>
 <li>User <bdi>jdoe</bdi>: 80 points</li>
 <li>User <bdi>إيان</bdi>: 90 points</li>
</ul>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The bdi element</h1>` | Defines a **H1** heading element with text: *"The bdi element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>In the example below, usernames are shown along with...` | Defines a paragraph (`<p>`) element displaying text: *"In the example below, usernames are shown along with the number of points in a contest. If the bdi element is not supported in the browser, the username of the Arabic user would confuse the text (the bidirectional algorithm would put the colon and the number "90" next to the word "User" rather than next to the word "points")."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<ul>` | Opens an unordered bulleted list (`<ul>`). |
| **Line 10** | `<li>User <bdi>hrefs</bdi>: 60 points</li>` | Defines an individual list item (`<li>`): `<li>User <bdi>hrefs</bdi>: 60 points</li>`. |
| **Line 11** | `<li>User <bdi>jdoe</bdi>: 80 points</li>` | Defines an individual list item (`<li>`): `<li>User <bdi>jdoe</bdi>: 80 points</li>`. |
| **Line 12** | `<li>User <bdi>إيان</bdi>: 90 points</li>` | Defines an individual list item (`<li>`): `<li>User <bdi>إيان</bdi>: 90 points</li>`. |
| **Line 13** | `</ul>` | Closes the unordered bulleted list (`<ul>`). |
| **Line 14** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 15** | `</body>` | Closes the document `<body>` section. |
| **Line 16** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`body-14.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/body-14.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
  <title>Title of the document</title>
</head>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>
</body>

</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<title>Title of the document</title>` | Sets the document title rendered in the browser tab and bookmarks bar: **"Title of the document"**. |
| **Line 5** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 8** | `<h1>This is a heading</h1>` | Defines a **H1** heading element with text: *"This is a heading"*. |
| **Line 9** | `<p>This is a paragraph.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is a paragraph."*. |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`col-21.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/col-21.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<h1>The col element</h1>

<table>
  <colgroup>
    <col span="2" style="background-color:red">
    <col style="background-color:yellow">
  </colgroup>
  <tr>
    <th>ISBN</th>
    <th>Title</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>3476896</td>
    <td>My first HTML</td>
    <td>$53</td>
  </tr>
  <tr>
    <td>5869207</td>
    <td>My first CSS</td>
    <td>$49</td>
  </tr>
</table>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `table, th, td {` | Renders markup / text content: `table, th, td {` |
| **Line 6** | `border: 1px solid black;` | Renders markup / text content: `border: 1px solid black;` |
| **Line 7** | `}` | Renders markup / text content: `}` |
| **Line 8** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 9** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 10** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<h1>The col element</h1>` | Defines a **H1** heading element with text: *"The col element"*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<table>` | Opens a `<table>` container with structure/styling: `<table>`. |
| **Line 15** | `<colgroup>` | Renders markup / text content: `<colgroup>` |
| **Line 16** | `<col span="2" style="background-color:red">` | Renders markup / text content: `<col span="2" style="background-color:red">` |
| **Line 17** | `<col style="background-color:yellow">` | Renders markup / text content: `<col style="background-color:yellow">` |
| **Line 18** | `</colgroup>` | Renders markup / text content: `</colgroup>` |
| **Line 19** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 20** | `<th>ISBN</th>` | Defines a table header cell (`<th>`): `<th>ISBN</th>`. |
| **Line 21** | `<th>Title</th>` | Defines a table header cell (`<th>`): `<th>Title</th>`. |
| **Line 22** | `<th>Price</th>` | Defines a table header cell (`<th>`): `<th>Price</th>`. |
| **Line 23** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 24** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 25** | `<td>3476896</td>` | Defines a standard table data cell (`<td>`): `<td>3476896</td>`. |
| **Line 26** | `<td>My first HTML</td>` | Defines a standard table data cell (`<td>`): `<td>My first HTML</td>`. |
| **Line 27** | `<td>$53</td>` | Defines a standard table data cell (`<td>`): `<td>$53</td>`. |
| **Line 28** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 29** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 30** | `<td>5869207</td>` | Defines a standard table data cell (`<td>`): `<td>5869207</td>`. |
| **Line 31** | `<td>My first CSS</td>` | Defines a standard table data cell (`<td>`): `<td>My first CSS</td>`. |
| **Line 32** | `<td>$49</td>` | Defines a standard table data cell (`<td>`): `<td>$49</td>`. |
| **Line 33** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 34** | `</table>` | Closes the `<table>` element. |
| **Line 35** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 36** | `</body>` | Closes the document `<body>` section. |
| **Line 37** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`dl-31.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/dl-31.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The dl, dd, and dt elements</h1>

<p>These three elements are used to create a description list:</p>

<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The dl, dd, and dt elements</h1>` | Defines a **H1** heading element with text: *"The dl, dd, and dt elements"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>These three elements are used to create a descriptio...` | Defines a paragraph (`<p>`) element displaying text: *"These three elements are used to create a description list:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<dl>` | Renders markup / text content: `<dl>` |
| **Line 10** | `<dt>Coffee</dt>` | Renders markup / text content: `<dt>Coffee</dt>` |
| **Line 11** | `<dd>Black hot drink</dd>` | Renders markup / text content: `<dd>Black hot drink</dd>` |
| **Line 12** | `<dt>Milk</dt>` | Renders markup / text content: `<dt>Milk</dt>` |
| **Line 13** | `<dd>White cold drink</dd>` | Renders markup / text content: `<dd>White cold drink</dd>` |
| **Line 14** | `</dl>` | Renders markup / text content: `</dl>` |
| **Line 15** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 16** | `</body>` | Closes the document `<body>` section. |
| **Line 17** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`head-41.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/head-41.html)

**Source Code:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Title of the document</title>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html lang="en">` | Opening root tag of the HTML document with primary language set to `en` for browser rendering and screen readers. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<title>Title of the document</title>` | Sets the document title rendered in the browser tab and bookmarks bar: **"Title of the document"**. |
| **Line 5** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 6** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 7** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 8** | `<h1>This is a heading</h1>` | Defines a **H1** heading element with text: *"This is a heading"*. |
| **Line 9** | `<p>This is a paragraph.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is a paragraph."*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`html-45.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/html-45.html)

**Source Code:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Title of the document</title>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html lang="en">` | Opening root tag of the HTML document with primary language set to `en` for browser rendering and screen readers. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<title>Title of the document</title>` | Sets the document title rendered in the browser tab and bookmarks bar: **"Title of the document"**. |
| **Line 5** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 6** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 7** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 8** | `<h1>This is a heading</h1>` | Defines a **H1** heading element with text: *"This is a heading"*. |
| **Line 9** | `<p>This is a paragraph.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is a paragraph."*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`kbd-51.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/kbd-51.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The kbd element</h1>

<p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text (Windows).</p>

<p>Press <kbd>Cmd</kbd> + <kbd>C</kbd> to copy text (Mac OS).</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The kbd element</h1>` | Defines a **H1** heading element with text: *"The kbd element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text (W...` | Defines a paragraph (`<p>`) element displaying text: *"Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text (Windows)."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<p>Press <kbd>Cmd</kbd> + <kbd>C</kbd> to copy text (Ma...` | Defines a paragraph (`<p>`) element displaying text: *"Press <kbd>Cmd</kbd> + <kbd>C</kbd> to copy text (Mac OS)."*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`link-55.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/link-55.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>Hello World!</h1>

<h2>I am formatted with a linked style sheet.</h2>

<p>Me too!</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<link rel="stylesheet" href="styles.css">` | Renders markup / text content: `<link rel="stylesheet" href="styles.css">` |
| **Line 5** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 6** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 7** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 8** | `<h1>Hello World!</h1>` | Defines a **H1** heading element with text: *"Hello World!"*. |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `<h2>I am formatted with a linked style sheet.</h2>` | Defines a **H2** heading element with text: *"I am formatted with a linked style sheet."*. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<p>Me too!</p>` | Defines a paragraph (`<p>`) element displaying text: *"Me too!"*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `</body>` | Closes the document `<body>` section. |
| **Line 15** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`meta-60.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/meta-60.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML,CSS,XML,JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<p>All meta information goes in the head section...</p>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML,CSS,XML,JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<p>All meta information goes in the head section...</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<meta charset="UTF-8">` | Sets the document character encoding to **UTF-8**, ensuring universal support for characters, symbols, and emojis. |
| **Line 5** | `<meta name="description" content="Free Web tutorials">` | Renders markup / text content: `<meta name="description" content="Free Web tutorials">` |
| **Line 6** | `<meta name="keywords" content="HTML,CSS,XML,JavaScript">` | Renders markup / text content: `<meta name="keywords" content="HTML,CSS,XML,JavaScript">` |
| **Line 7** | `<meta name="author" content="John Doe">` | Renders markup / text content: `<meta name="author" content="John Doe">` |
| **Line 8** | `<meta name="viewport" content="width=device-width, init...` | Configures responsive viewport scaling so the page adjusts cleanly across mobile, tablet, and desktop screens. |
| **Line 9** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 10** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<p>All meta information goes in the head section...</p>` | Defines a paragraph (`<p>`) element displaying text: *"All meta information goes in the head section..."*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `</body>` | Closes the document `<body>` section. |
| **Line 15** | `</html>` | Closing root tag that marks the end of the HTML document. |
| **Line 16** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 17** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 18** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 19** | `<meta charset="UTF-8">` | Sets the document character encoding to **UTF-8**, ensuring universal support for characters, symbols, and emojis. |
| **Line 20** | `<meta name="description" content="Free Web tutorials">` | Renders markup / text content: `<meta name="description" content="Free Web tutorials">` |
| **Line 21** | `<meta name="keywords" content="HTML,CSS,XML,JavaScript">` | Renders markup / text content: `<meta name="keywords" content="HTML,CSS,XML,JavaScript">` |
| **Line 22** | `<meta name="author" content="John Doe">` | Renders markup / text content: `<meta name="author" content="John Doe">` |
| **Line 23** | `<meta name="viewport" content="width=device-width, init...` | Configures responsive viewport scaling so the page adjusts cleanly across mobile, tablet, and desktop screens. |
| **Line 24** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 25** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 26** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 27** | `<p>All meta information goes in the head section...</p>` | Defines a paragraph (`<p>`) element displaying text: *"All meta information goes in the head section..."*. |
| **Line 28** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 29** | `</body>` | Closes the document `<body>` section. |
| **Line 30** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`meter-61.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/meter-61.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The meter element</h1>

<p>The meter element is used to display a gauge:</p>

<label for="disk_c">Disk usage C:</label>
<meter id="disk_c" value="2" min="0" max="10">2 out of 10</meter><br>

<label for="disk_d">Disk usage D:</label>
<meter id="disk_d" value="0.6">60%</meter>

<p><strong>Note:</strong> The meter tag is not supported in Edge 12 (or earlier).</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The meter element</h1>` | Defines a **H1** heading element with text: *"The meter element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>The meter element is used to display a gauge:</p>` | Defines a paragraph (`<p>`) element displaying text: *"The meter element is used to display a gauge:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<label for="disk_c">Disk usage C:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="disk_c">Disk usage C:</label>`. |
| **Line 10** | `<meter id="disk_c" value="2" min="0" max="10">2 out of ...` | Renders a gauge/meter showing scalar measurement within a range (`<meter>`): `<meter id="disk_c" value="2" min="0" max="10">2 out of 10</meter><br>`. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<label for="disk_d">Disk usage D:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="disk_d">Disk usage D:</label>`. |
| **Line 13** | `<meter id="disk_d" value="0.6">60%</meter>` | Renders a gauge/meter showing scalar measurement within a range (`<meter>`): `<meter id="disk_d" value="0.6">60%</meter>`. |
| **Line 14** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 15** | `<p><strong>Note:</strong> The meter tag is not supporte...` | Defines a paragraph (`<p>`) element displaying text: *"<strong>Note:</strong> The meter tag is not supported in Edge 12 (or earlier)."*. |
| **Line 16** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 17** | `</body>` | Closes the document `<body>` section. |
| **Line 18** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`noscript-63.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/noscript-63.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The noscript element</h1>

<p>A browser with JavaScript disabled will show the text inside the noscript element ("Hello World!" will not be displayed).</p>

<script>
document.write("Hello World!")
</script>
<noscript>Sorry, your browser does not support JavaScript!</noscript>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The noscript element</h1>` | Defines a **H1** heading element with text: *"The noscript element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>A browser with JavaScript disabled will show the tex...` | Defines a paragraph (`<p>`) element displaying text: *"A browser with JavaScript disabled will show the text inside the noscript element ("Hello World!" will not be displayed)."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<script>` | Opens a JavaScript `<script>` block for interactive client-side logic. |
| **Line 10** | `document.write("Hello World!")` | Renders markup / text content: `document.write("Hello World!")` |
| **Line 11** | `</script>` | Closes the JavaScript `<script>` block. |
| **Line 12** | `<noscript>Sorry, your browser does not support JavaScri...` | Renders markup / text content: `<noscript>Sorry, your browser does not support JavaScript!</noscript>` |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `</body>` | Closes the document `<body>` section. |
| **Line 15** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`picture-71.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/picture-71.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>The picture element</h1>

<p>Resize the browser window to load different images.</p>

<picture>
  <source media="(min-width:550px)" srcset="https://th.bing.com/th/id/R.020ddb3d2087436a7b843e314f344040?rik=%2bYUH7A9UT3XK9A&riu=http%3a%2f%2fwallup.net%2fwp-content%2fuploads%2f2016%2f02%2f198449-nature-orange-flowers.jpg&ehk=%2f%2bPdWGASr2X%2b2Vt1YgdoS7tw2o9T3MNcEESY3ID2Ukk%3d&risl=&pid=ImgRaw&r=0">
  <source media="(min-width:365px)" srcset="https://th.bing.com/th/id/R.020ddb3d2087436a7b843e314f344040?rik=%2bYUH7A9UT3XK9A&riu=http%3a%2f%2fwallup.net%2fwp-content%2fuploads%2f2016%2f02%2f198449-nature-orange-flowers.jpg&ehk=%2f%2bPdWGASr2X%2b2Vt1YgdoS7tw2o9T3MNcEESY3ID2Ukk%3d&risl=&pid=ImgRaw&r=0">
  <img src="https://th.bing.com/th/id/R.020ddb3d2087436a7b843e314f344040?rik=%2bYUH7A9UT3XK9A&riu=http%3a%2f%2fwallup.net%2fwp-content%2fuploads%2f2016%2f0２%２f198449-nature-orange-flowers.jpg&ehk=%２f%２bPdWGASr２X%２b２Vt1YgdoS7tw２o9T３MNcEESY３ID２Ukk%３d&risl=&pid=ImgRaw&r=0" alt="Flowers" style="width:auto;">
</picture>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<meta name="viewport" content="width=device-width, init...` | Configures responsive viewport scaling so the page adjusts cleanly across mobile, tablet, and desktop screens. |
| **Line 5** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 6** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 7** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 8** | `<h1>The picture element</h1>` | Defines a **H1** heading element with text: *"The picture element"*. |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `<p>Resize the browser window to load different images.</p>` | Defines a paragraph (`<p>`) element displaying text: *"Resize the browser window to load different images."*. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<picture>` | Opens a responsive image `<picture>` container. |
| **Line 13** | `<source media="(min-width:550px)" srcset="https://th.bi...` | Specifies an alternative media source and MIME type (`<source>`): `<source media="(min-width:550px)" srcset="https://th.bing.com/th/id/R.020ddb3d2087436a7b843e314f344040?rik=%2bYUH7A9UT3XK9A&riu=http%3a%2f%2fwallup.net%2fwp-content%2fuploads%2f2016%2f02%2f198449-nature-orange-flowers.jpg&ehk=%2f%2bPdWGASr2X%2b2Vt1YgdoS7tw2o9T3MNcEESY3ID2Ukk%3d&risl=&pid=ImgRaw&r=0">`. |
| **Line 14** | `<source media="(min-width:365px)" srcset="https://th.bi...` | Specifies an alternative media source and MIME type (`<source>`): `<source media="(min-width:365px)" srcset="https://th.bing.com/th/id/R.020ddb3d2087436a7b843e314f344040?rik=%2bYUH7A9UT3XK9A&riu=http%3a%2f%2fwallup.net%2fwp-content%2fuploads%2f2016%2f02%2f198449-nature-orange-flowers.jpg&ehk=%2f%2bPdWGASr2X%2b2Vt1YgdoS7tw2o9T3MNcEESY3ID2Ukk%3d&risl=&pid=ImgRaw&r=0">`. |
| **Line 15** | `<img src="https://th.bing.com/th/id/R.020ddb3d2087436a7...` | Renders markup / text content: `<img src="https://th.bing.com/th/id/R.020ddb3d2087436a7b843e314f344040?rik=%2bYU` |
| **Line 16** | `</picture>` | Closes the `<picture>` container. |
| **Line 17** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 18** | `</body>` | Closes the document `<body>` section. |
| **Line 19** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`script-80.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/script-80.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The script element</h1>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script> 

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The script element</h1>` | Defines a **H1** heading element with text: *"The script element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p id="demo"></p>` | Renders markup / text content: `<p id="demo"></p>` |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<script>` | Opens a JavaScript `<script>` block for interactive client-side logic. |
| **Line 10** | `document.getElementById("demo").innerHTML = "Hello Java...` | Renders markup / text content: `document.getElementById("demo").innerHTML = "Hello JavaScript!";` |
| **Line 11** | `</script>` | Closes the JavaScript `<script>` block. |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 13** | `</body>` | Closes the document `<body>` section. |
| **Line 14** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`search-81.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/search-81.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The search Element</h1>

<search>
  <form>
    <input name="fsrch" id="fsrch" placeholder="Search W3Schools">
  </form>
</search>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The search Element</h1>` | Defines a **H1** heading element with text: *"The search Element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<search>` | Defines a semantic `<search>` landmark section for search and filtering controls. |
| **Line 8** | `<form>` | Opens a `<form>` container with attributes: `<form>` for user data input and submission. |
| **Line 9** | `<input name="fsrch" id="fsrch" placeholder="Search W3Sc...` | Specifies an interactive form input field (`<input>`): `<input name="fsrch" id="fsrch" placeholder="Search W3Schools">`. |
| **Line 10** | `</form>` | Closes the `<form>` element. |
| **Line 11** | `</search>` | Closes the `<search>` landmark element. |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 13** | `</body>` | Closes the document `<body>` section. |
| **Line 14** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`style-88.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/style-88.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
h1 {color:red;}
p {color:blue;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `h1 {color:red;}` | Renders markup / text content: `h1 {color:red;}` |
| **Line 6** | `p {color:blue;}` | Renders markup / text content: `p {color:blue;}` |
| **Line 7** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 8** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 9** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `<h1>This is a heading</h1>` | Defines a **H1** heading element with text: *"This is a heading"*. |
| **Line 12** | `<p>This is a paragraph.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is a paragraph."*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `</body>` | Closes the document `<body>` section. |
| **Line 15** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`sup-91.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/sup-91.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The sub and sup elements</h1>

<p>This text contains <sub>subscript</sub> text.</p>
<p>This text contains <sup>superscript</sup> text.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The sub and sup elements</h1>` | Defines a **H1** heading element with text: *"The sub and sup elements"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>This text contains <sub>subscript</sub> text.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This text contains <sub>subscript</sub> text."*. |
| **Line 8** | `<p>This text contains <sup>superscript</sup> text.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This text contains <sup>superscript</sup> text."*. |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`template-96.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/template-96.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The template Element</h1>

<p>Click the button below to display the hidden content from the template element.</p>

<button onclick="showContent()">Show hidden content</button>

<template>
  <h2>Flower</h2>
  <img src="img_white_flower.jpg" width="214" height="204">
</template>

<script>
function showContent() {
  let temp = document.getElementsByTagName("template")[0];
  let clon = temp.content.cloneNode(true);
  document.body.appendChild(clon);
}
</script>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The template Element</h1>` | Defines a **H1** heading element with text: *"The template Element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Click the button below to display the hidden content...` | Defines a paragraph (`<p>`) element displaying text: *"Click the button below to display the hidden content from the template element."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<button onclick="showContent()">Show hidden content</button>` | Defines a clickable button element (`<button>`): `<button onclick="showContent()">Show hidden content</button>`. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `<template>` | Opens a `<template>` container holding client-side HTML markup not rendered until cloned via JavaScript. |
| **Line 12** | `<h2>Flower</h2>` | Defines a **H2** heading element with text: *"Flower"*. |
| **Line 13** | `<img src="img_white_flower.jpg" width="214" height="204">` | Renders markup / text content: `<img src="img_white_flower.jpg" width="214" height="204">` |
| **Line 14** | `</template>` | Closes the `<template>` container. |
| **Line 15** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 16** | `<script>` | Opens a JavaScript `<script>` block for interactive client-side logic. |
| **Line 17** | `function showContent() {` | Renders markup / text content: `function showContent() {` |
| **Line 18** | `let temp = document.getElementsByTagName("template")[0];` | Renders markup / text content: `let temp = document.getElementsByTagName("template")[0];` |
| **Line 19** | `let clon = temp.content.cloneNode(true);` | Renders markup / text content: `let clon = temp.content.cloneNode(true);` |
| **Line 20** | `document.body.appendChild(clon);` | Renders markup / text content: `document.body.appendChild(clon);` |
| **Line 21** | `}` | Renders markup / text content: `}` |
| **Line 22** | `</script>` | Closes the JavaScript `<script>` block. |
| **Line 23** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 24** | `</body>` | Closes the document `<body>` section. |
| **Line 25** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`time-101.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/time-101.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The time element</h1>

<p>Open from <time>10:00</time> to <time>21:00</time> every weekday.</p>

<p>I have a date on <time datetime="2008-02-14 20:00">Valentines day</time>.</p>

<p><b>Note:</b> The time element does not render as anything special in any of the major browsers.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The time element</h1>` | Defines a **H1** heading element with text: *"The time element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Open from <time>10:00</time> to <time>21:00</time> e...` | Defines a paragraph (`<p>`) element displaying text: *"Open from <time>10:00</time> to <time>21:00</time> every weekday."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<p>I have a date on <time datetime="2008-02-14 20:00">V...` | Defines a paragraph (`<p>`) element displaying text: *"I have a date on <time datetime="2008-02-14 20:00">Valentines day</time>."*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `<p><b>Note:</b> The time element does not render as any...` | Defines a paragraph (`<p>`) element displaying text: *"<b>Note:</b> The time element does not render as anything special in any of the major browsers."*. |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 13** | `</body>` | Closes the document `<body>` section. |
| **Line 14** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`title-102.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/title-102.html)

**Source Code:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>HTML Elements Reference</title>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html lang="en">` | Opening root tag of the HTML document with primary language set to `en` for browser rendering and screen readers. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<title>HTML Elements Reference</title>` | Sets the document title rendered in the browser tab and bookmarks bar: **"HTML Elements Reference"**. |
| **Line 5** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 6** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 7** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 8** | `<h1>This is a heading</h1>` | Defines a **H1** heading element with text: *"This is a heading"*. |
| **Line 9** | `<p>This is a paragraph.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is a paragraph."*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---


## <a id="2-semantic-layout--sections"></a>2. Semantic Layout & Sections

*HTML5 semantic containers for structuring pages logically and improving accessibility/SEO.*


### 📄 [`article6.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/article6.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The article element</h1>

<article>
  <h2>Google Chrome</h2>
  <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
</article>

<article>
  <h2>Mozilla Firefox</h2>
  <p>Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018.</p>
</article>

<article>
  <h2>Microsoft Edge</h2>
  <p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
</article>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The article element</h1>` | Defines a **H1** heading element with text: *"The article element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<article>` | Opens a self-contained, independent syndicatable `<article>` container. |
| **Line 8** | `<h2>Google Chrome</h2>` | Defines a **H2** heading element with text: *"Google Chrome"*. |
| **Line 9** | `<p>Google Chrome is a web browser developed by Google, ...` | Defines a paragraph (`<p>`) element displaying text: *"Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!"*. |
| **Line 10** | `</article>` | Closes the `<article>` container. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<article>` | Opens a self-contained, independent syndicatable `<article>` container. |
| **Line 13** | `<h2>Mozilla Firefox</h2>` | Defines a **H2** heading element with text: *"Mozilla Firefox"*. |
| **Line 14** | `<p>Mozilla Firefox is an open-source web browser develo...` | Defines a paragraph (`<p>`) element displaying text: *"Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018."*. |
| **Line 15** | `</article>` | Closes the `<article>` container. |
| **Line 16** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 17** | `<article>` | Opens a self-contained, independent syndicatable `<article>` container. |
| **Line 18** | `<h2>Microsoft Edge</h2>` | Defines a **H2** heading element with text: *"Microsoft Edge"*. |
| **Line 19** | `<p>Microsoft Edge is a web browser developed by Microso...` | Defines a paragraph (`<p>`) element displaying text: *"Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer."*. |
| **Line 20** | `</article>` | Closes the `<article>` container. |
| **Line 21** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 22** | `</body>` | Closes the document `<body>` section. |
| **Line 23** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`aside7.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/aside7.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The aside element</h1>

<p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!</p>

<aside>
  <h4>Epcot Center</h4>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</aside>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The aside element</h1>` | Defines a **H1** heading element with text: *"The aside element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>My family and I visited The Epcot center this summer...` | Defines a paragraph (`<p>`) element displaying text: *"My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<aside>` | Opens an `<aside>` element for secondary sidebar/callout content tangentially related to the main content. |
| **Line 10** | `<h4>Epcot Center</h4>` | Defines a **H4** heading element with text: *"Epcot Center"*. |
| **Line 11** | `<p>Epcot is a theme park at Walt Disney World Resort fe...` | Defines a paragraph (`<p>`) element displaying text: *"Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events."*. |
| **Line 12** | `</aside>` | Closes the `<aside>` element. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `</body>` | Closes the document `<body>` section. |
| **Line 15** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`div-30.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/div-30.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
.myDiv {
  border: 5px outset red;
  background-color: lightblue;    
  text-align: center;
}
</style>
</head>
<body>

<h1>The div element</h1>

<div class="myDiv">
  <h2>This is a heading in a div element</h2>
  <p>This is some text in a div element.</p>
</div>

<p>This is some text outside the div element.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `.myDiv {` | Renders markup / text content: `.myDiv {` |
| **Line 6** | `border: 5px outset red;` | Renders markup / text content: `border: 5px outset red;` |
| **Line 7** | `background-color: lightblue;` | Renders markup / text content: `background-color: lightblue;` |
| **Line 8** | `text-align: center;` | Renders markup / text content: `text-align: center;` |
| **Line 9** | `}` | Renders markup / text content: `}` |
| **Line 10** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 11** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 12** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<h1>The div element</h1>` | Defines a **H1** heading element with text: *"The div element"*. |
| **Line 15** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 16** | `<div class="myDiv">` | Renders markup / text content: `<div class="myDiv">` |
| **Line 17** | `<h2>This is a heading in a div element</h2>` | Defines a **H2** heading element with text: *"This is a heading in a div element"*. |
| **Line 18** | `<p>This is some text in a div element.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is some text in a div element."*. |
| **Line 19** | `</div>` | Renders markup / text content: `</div>` |
| **Line 20** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 21** | `<p>This is some text outside the div element.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is some text outside the div element."*. |
| **Line 22** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 23** | `</body>` | Closes the document `<body>` section. |
| **Line 24** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`footer-38.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/footer-38.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The footer element</h1>

<footer>
  <p>Author: Rahul Gupta<br>
  <a href="mailto:rahul@example.com">rahul@example.com</a></p>
</footer>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The footer element</h1>` | Defines a **H1** heading element with text: *"The footer element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<footer>` | Opens a `<footer>` element for copyright notices, authorship details, or contact information. |
| **Line 8** | `<p>Author: Rahul Gupta<br>` | Renders markup / text content: `<p>Author: Rahul Gupta<br>` |
| **Line 9** | `<a href="mailto:rahul@example.com">rahul@example.com</a></p>` | Renders markup / text content: `<a href="mailto:rahul@example.com">rahul@example.com</a></p>` |
| **Line 10** | `</footer>` | Closes the `<footer>` element. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `</body>` | Closes the document `<body>` section. |
| **Line 13** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`header-42.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/header-42.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<article>
  <header>
    <h1>A heading here</h1>
    <p>Posted by John Doe</p>
    <p>Some additional information here</p>
  </header>
  <p>Lorem Ipsum dolor set amet....</p>
</article>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<article>` | Opens a self-contained, independent syndicatable `<article>` container. |
| **Line 6** | `<header>` | Opens a `<header>` element containing introductory content, headings, or navigation. |
| **Line 7** | `<h1>A heading here</h1>` | Defines a **H1** heading element with text: *"A heading here"*. |
| **Line 8** | `<p>Posted by John Doe</p>` | Defines a paragraph (`<p>`) element displaying text: *"Posted by John Doe"*. |
| **Line 9** | `<p>Some additional information here</p>` | Defines a paragraph (`<p>`) element displaying text: *"Some additional information here"*. |
| **Line 10** | `</header>` | Closes the `<header>` element. |
| **Line 11** | `<p>Lorem Ipsum dolor set amet....</p>` | Defines a paragraph (`<p>`) element displaying text: *"Lorem Ipsum dolor set amet...."*. |
| **Line 12** | `</article>` | Closes the `<article>` container. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `</body>` | Closes the document `<body>` section. |
| **Line 15** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`hgroup-43.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/hgroup-43.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<hgroup>
  <h2>Norway</h2>
  <p>The land with the midnight sun.</p>
</hgroup>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<hgroup>` | Renders markup / text content: `<hgroup>` |
| **Line 6** | `<h2>Norway</h2>` | Defines a **H2** heading element with text: *"Norway"*. |
| **Line 7** | `<p>The land with the midnight sun.</p>` | Defines a paragraph (`<p>`) element displaying text: *"The land with the midnight sun."*. |
| **Line 8** | `</hgroup>` | Renders markup / text content: `</hgroup>` |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`main-56.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/main-56.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
  <title>My Web Page</title>
</head>
<body>

<h1>The main element</h1>

<main>
  <h1>Most Popular Browsers</h1>
  <p>Chrome, Firefox, and Edge are the most used browsers today.</p>

  <article>
    <h2>Google Chrome</h2>
    <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
  </article>

  <article>
    <h2>Mozilla Firefox</h2>
    <p>Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018.</p>
  </article>

  <article>
    <h2>Microsoft Edge</h2>
    <p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
  </article>
</main>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<title>My Web Page</title>` | Sets the document title rendered in the browser tab and bookmarks bar: **"My Web Page"**. |
| **Line 5** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 6** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 7** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 8** | `<h1>The main element</h1>` | Defines a **H1** heading element with text: *"The main element"*. |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `<main>` | Opens the `<main>` container representing the dominant, unique central content of the document. |
| **Line 11** | `<h1>Most Popular Browsers</h1>` | Defines a **H1** heading element with text: *"Most Popular Browsers"*. |
| **Line 12** | `<p>Chrome, Firefox, and Edge are the most used browsers...` | Defines a paragraph (`<p>`) element displaying text: *"Chrome, Firefox, and Edge are the most used browsers today."*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<article>` | Opens a self-contained, independent syndicatable `<article>` container. |
| **Line 15** | `<h2>Google Chrome</h2>` | Defines a **H2** heading element with text: *"Google Chrome"*. |
| **Line 16** | `<p>Google Chrome is a web browser developed by Google, ...` | Defines a paragraph (`<p>`) element displaying text: *"Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!"*. |
| **Line 17** | `</article>` | Closes the `<article>` container. |
| **Line 18** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 19** | `<article>` | Opens a self-contained, independent syndicatable `<article>` container. |
| **Line 20** | `<h2>Mozilla Firefox</h2>` | Defines a **H2** heading element with text: *"Mozilla Firefox"*. |
| **Line 21** | `<p>Mozilla Firefox is an open-source web browser develo...` | Defines a paragraph (`<p>`) element displaying text: *"Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018."*. |
| **Line 22** | `</article>` | Closes the `<article>` container. |
| **Line 23** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 24** | `<article>` | Opens a self-contained, independent syndicatable `<article>` container. |
| **Line 25** | `<h2>Microsoft Edge</h2>` | Defines a **H2** heading element with text: *"Microsoft Edge"*. |
| **Line 26** | `<p>Microsoft Edge is a web browser developed by Microso...` | Defines a paragraph (`<p>`) element displaying text: *"Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer."*. |
| **Line 27** | `</article>` | Closes the `<article>` container. |
| **Line 28** | `</main>` | Closes the `<main>` container. |
| **Line 29** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 30** | `</body>` | Closes the document `<body>` section. |
| **Line 31** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`nav-62.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/nav-62.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The nav element</h1>

<p>The nav element defines a set of navigation links:</p>

<nav>
<a href="/html/">HTML</a> |
<a href="/css/">CSS</a> |
<a href="/js/">JavaScript</a> |
<a href="/python/">Python</a>
</nav>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The nav element</h1>` | Defines a **H1** heading element with text: *"The nav element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>The nav element defines a set of navigation links:</p>` | Defines a paragraph (`<p>`) element displaying text: *"The nav element defines a set of navigation links:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<nav>` | Opens a `<nav>` container specifically intended for major site navigation links. |
| **Line 10** | `<a href="/html/">HTML</a> \|` | Renders markup / text content: `<a href="/html/">HTML</a> |` |
| **Line 11** | `<a href="/css/">CSS</a> \|` | Renders markup / text content: `<a href="/css/">CSS</a> |` |
| **Line 12** | `<a href="/js/">JavaScript</a> \|` | Renders markup / text content: `<a href="/js/">JavaScript</a> |` |
| **Line 13** | `<a href="/python/">Python</a>` | Renders markup / text content: `<a href="/python/">Python</a>` |
| **Line 14** | `</nav>` | Closes the `<nav>` navigation container. |
| **Line 15** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 16** | `</body>` | Closes the document `<body>` section. |
| **Line 17** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`section-82.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/section-82.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The section element</h1>

<section>
  <h2>WWF History</h2>
  <p>The World Wide Fund for Nature (WWF) is an international organization working on issues regarding the conservation, research and restoration of the environment, formerly named the World Wildlife Fund. WWF was founded in 1961.</p>
</section>

<section>
  <h2>WWF's Symbol</h2>
  <p>The Panda has become the symbol of WWF. The well-known panda logo of WWF originated from a panda named Chi Chi that was transferred from the Beijing Zoo to the London Zoo in the same year of the establishment of WWF.</p>
</section>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The section element</h1>` | Defines a **H1** heading element with text: *"The section element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<section>` | Opens a standalone thematic `<section>` grouping related content together. |
| **Line 8** | `<h2>WWF History</h2>` | Defines a **H2** heading element with text: *"WWF History"*. |
| **Line 9** | `<p>The World Wide Fund for Nature (WWF) is an internati...` | Defines a paragraph (`<p>`) element displaying text: *"The World Wide Fund for Nature (WWF) is an international organization working on issues regarding the conservation, research and restoration of the environment, formerly named the World Wildlife Fund. WWF was founded in 1961."*. |
| **Line 10** | `</section>` | Closes the `<section>` element. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<section>` | Opens a standalone thematic `<section>` grouping related content together. |
| **Line 13** | `<h2>WWF's Symbol</h2>` | Defines a **H2** heading element with text: *"WWF's Symbol"*. |
| **Line 14** | `<p>The Panda has become the symbol of WWF. The well-kno...` | Defines a paragraph (`<p>`) element displaying text: *"The Panda has become the symbol of WWF. The well-known panda logo of WWF originated from a panda named Chi Chi that was transferred from the Beijing Zoo to the London Zoo in the same year of the establishment of WWF."*. |
| **Line 15** | `</section>` | Closes the `<section>` element. |
| **Line 16** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 17** | `</body>` | Closes the document `<body>` section. |
| **Line 18** | `</html>` | Closing root tag that marks the end of the HTML document. |

---


## <a id="3-typography-headings--text-formatting"></a>3. Typography, Headings & Text Formatting

*Text styling, emphasis, quotations, citations, ruby annotations, and code formatting tags.*


### 📄 [`3.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/3.html)

**Source Code:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.
  <p><dfn><abbr title="Cascading Style Sheets">CSS</abbr>
</dfn> is a language that describes the style of an HTML document.</p>
</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html lang="en">` | Opening root tag of the HTML document with primary language set to `en` for browser rendering and screen readers. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<meta charset="UTF-8">` | Sets the document character encoding to **UTF-8**, ensuring universal support for characters, symbols, and emojis. |
| **Line 5** | `<meta name="viewport" content="width=device-width, init...` | Configures responsive viewport scaling so the page adjusts cleanly across mobile, tablet, and desktop screens. |
| **Line 6** | `<title>Document</title>` | Sets the document title rendered in the browser tab and bookmarks bar: **"Document"**. |
| **Line 7** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 8** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 9** | `The <abbr title="World Health Organization">WHO</abbr> ...` | Renders markup / text content: `The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.` |
| **Line 10** | `<p><dfn><abbr title="Cascading Style Sheets">CSS</abbr>` | Renders markup / text content: `<p><dfn><abbr title="Cascading Style Sheets">CSS</abbr>` |
| **Line 11** | `</dfn> is a language that describes the style of an HTM...` | Renders markup / text content: `</dfn> is a language that describes the style of an HTML document.</p>` |
| **Line 12** | `</body>` | Closes the document `<body>` section. |
| **Line 13** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`b-9.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/b-9.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The br element</h1>

<p>To force<br> line breaks<br> in a text,<br> use the br<br> element.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The br element</h1>` | Defines a **H1** heading element with text: *"The br element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>To force<br> line breaks<br> in a text,<br> use the ...` | Defines a paragraph (`<p>`) element displaying text: *"To force<br> line breaks<br> in a text,<br> use the br<br> element."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`bdo-12.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/bdo-12.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The bdo element</h1>

<p>This paragraph will go left-to-right.</p>  
<p><bdo dir="rtl">This paragraph will go right-to-left.</bdo></p>  

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The bdo element</h1>` | Defines a **H1** heading element with text: *"The bdo element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>This paragraph will go left-to-right.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This paragraph will go left-to-right."*. |
| **Line 8** | `<p><bdo dir="rtl">This paragraph will go right-to-left....` | Defines a paragraph (`<p>`) element displaying text: *"<bdo dir="rtl">This paragraph will go right-to-left.</bdo>"*. |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`blockquote-13.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/blockquote-13.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The blockquote element</h1>

<p>Here is a quote from WWF's website:</p>

<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally.
</blockquote>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The blockquote element</h1>` | Defines a **H1** heading element with text: *"The blockquote element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Here is a quote from WWF's website:</p>` | Defines a paragraph (`<p>`) element displaying text: *"Here is a quote from WWF's website:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<blockquote cite="http://www.worldwildlife.org/who/inde...` | Renders markup / text content: `<blockquote cite="http://www.worldwildlife.org/who/index.html">` |
| **Line 10** | `For 50 years, WWF has been protecting the future of nat...` | Renders markup / text content: `For 50 years, WWF has been protecting the future of nature. The world's leading ` |
| **Line 11** | `</blockquote>` | Renders markup / text content: `</blockquote>` |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 13** | `</body>` | Closes the document `<body>` section. |
| **Line 14** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`br-15.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/br-15.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The br element</h1>

<p>To force<br> line breaks<br> in a text,<br> use the br<br> element.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The br element</h1>` | Defines a **H1** heading element with text: *"The br element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>To force<br> line breaks<br> in a text,<br> use the ...` | Defines a paragraph (`<p>`) element displaying text: *"To force<br> line breaks<br> in a text,<br> use the br<br> element."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`cite-19.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/cite-19.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The cite element</h1>

<img src="img_the_scream.jpg" width="220" height="277" alt="The Scream">
<p><cite>The Scream</cite> by Edward Munch. Painted in 1893.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The cite element</h1>` | Defines a **H1** heading element with text: *"The cite element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<img src="img_the_scream.jpg" width="220" height="277" ...` | Renders markup / text content: `<img src="img_the_scream.jpg" width="220" height="277" alt="The Scream">` |
| **Line 8** | `<p><cite>The Scream</cite> by Edward Munch. Painted in ...` | Defines a paragraph (`<p>`) element displaying text: *"<cite>The Scream</cite> by Edward Munch. Painted in 1893."*. |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`code-20.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/code-20.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The code element</h1>

<p>The HTML <code>button</code> tag defines a clickable button.</p>

<p>The CSS <code>background-color</code> property defines the background color of an element.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The code element</h1>` | Defines a **H1** heading element with text: *"The code element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>The HTML <code>button</code> tag defines a clickable...` | Defines a paragraph (`<p>`) element displaying text: *"The HTML <code>button</code> tag defines a clickable button."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<p>The CSS <code>background-color</code> property defin...` | Defines a paragraph (`<p>`) element displaying text: *"The CSS <code>background-color</code> property defines the background color of an element."*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`data-23.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/data-23.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The data element</h1>

<p>The following example displays product names but also associates each name with a product number:</p>

<ul>
  <li><data value="21053">Cherry Tomato</data></li>
  <li><data value="21054">Beef Tomato</data></li>
  <li><data value="21055">Snack Tomato</data></li>
</ul>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The data element</h1>` | Defines a **H1** heading element with text: *"The data element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>The following example displays product names but als...` | Defines a paragraph (`<p>`) element displaying text: *"The following example displays product names but also associates each name with a product number:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<ul>` | Opens an unordered bulleted list (`<ul>`). |
| **Line 10** | `<li><data value="21053">Cherry Tomato</data></li>` | Defines an individual list item (`<li>`): `<li><data value="21053">Cherry Tomato</data></li>`. |
| **Line 11** | `<li><data value="21054">Beef Tomato</data></li>` | Defines an individual list item (`<li>`): `<li><data value="21054">Beef Tomato</data></li>`. |
| **Line 12** | `<li><data value="21055">Snack Tomato</data></li>` | Defines an individual list item (`<li>`): `<li><data value="21055">Snack Tomato</data></li>`. |
| **Line 13** | `</ul>` | Closes the unordered bulleted list (`<ul>`). |
| **Line 14** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 15** | `</body>` | Closes the document `<body>` section. |
| **Line 16** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`del-26.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/del-26.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The del element</h1>

<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The del element</h1>` | Defines a **H1** heading element with text: *"The del element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>` | Defines a paragraph (`<p>`) element displaying text: *"My favorite color is <del>blue</del> <ins>red</ins>!"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`dfn-28.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/dfn-28.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The dfn element</h1>

<p><dfn>HTML</dfn> is the standard markup language for creating web pages.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The dfn element</h1>` | Defines a **H1** heading element with text: *"The dfn element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p><dfn>HTML</dfn> is the standard markup language for ...` | Defines a paragraph (`<p>`) element displaying text: *"<dfn>HTML</dfn> is the standard markup language for creating web pages."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`em-33.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/em-33.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The em element</h1>

<p>You <em>have</em> to hurry up!</p>

<p>We <em>cannot</em> live like this.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The em element</h1>` | Defines a **H1** heading element with text: *"The em element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>You <em>have</em> to hurry up!</p>` | Defines a paragraph (`<p>`) element displaying text: *"You <em>have</em> to hurry up!"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<p>We <em>cannot</em> live like this.</p>` | Defines a paragraph (`<p>`) element displaying text: *"We <em>cannot</em> live like this."*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`h1 to h6-40.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/h1 to h6-40.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>

<p><b>Tip:</b> Use h1 to h6 elements only for headings. Do not use them just to make text bold or big. Use other tags for that.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>This is heading 1</h1>` | Defines a **H1** heading element with text: *"This is heading 1"*. |
| **Line 6** | `<h2>This is heading 2</h2>` | Defines a **H2** heading element with text: *"This is heading 2"*. |
| **Line 7** | `<h3>This is heading 3</h3>` | Defines a **H3** heading element with text: *"This is heading 3"*. |
| **Line 8** | `<h4>This is heading 4</h4>` | Defines a **H4** heading element with text: *"This is heading 4"*. |
| **Line 9** | `<h5>This is heading 5</h5>` | Defines a **H5** heading element with text: *"This is heading 5"*. |
| **Line 10** | `<h6>This is heading 6</h6>` | Defines a **H6** heading element with text: *"This is heading 6"*. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<p><b>Tip:</b> Use h1 to h6 elements only for headings....` | Defines a paragraph (`<p>`) element displaying text: *"<b>Tip:</b> Use h1 to h6 elements only for headings. Do not use them just to make text bold or big. Use other tags for that."*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `</body>` | Closes the document `<body>` section. |
| **Line 15** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`hr-44.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/hr-44.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The Main Languages of the Web</h1>

<p>HTML is the standard markup language for creating Web pages. HTML describes the structure of a Web page, and consists of a series of elements. HTML elements tell the browser how to display the content.</p>

<hr>

<p>CSS is a language that describes how HTML elements are to be displayed on screen, paper, or in other media. CSS saves a lot of work, because it can control the layout of multiple web pages all at once.</p>

<hr>

<p>JavaScript is the programming language of HTML and the Web. JavaScript can change HTML content and attribute values. JavaScript can change CSS. JavaScript can hide and show HTML elements, and more.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The Main Languages of the Web</h1>` | Defines a **H1** heading element with text: *"The Main Languages of the Web"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>HTML is the standard markup language for creating We...` | Defines a paragraph (`<p>`) element displaying text: *"HTML is the standard markup language for creating Web pages. HTML describes the structure of a Web page, and consists of a series of elements. HTML elements tell the browser how to display the content."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<hr>` | Renders markup / text content: `<hr>` |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `<p>CSS is a language that describes how HTML elements a...` | Defines a paragraph (`<p>`) element displaying text: *"CSS is a language that describes how HTML elements are to be displayed on screen, paper, or in other media. CSS saves a lot of work, because it can control the layout of multiple web pages all at once."*. |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 13** | `<hr>` | Renders markup / text content: `<hr>` |
| **Line 14** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 15** | `<p>JavaScript is the programming language of HTML and t...` | Defines a paragraph (`<p>`) element displaying text: *"JavaScript is the programming language of HTML and the Web. JavaScript can change HTML content and attribute values. JavaScript can change CSS. JavaScript can hide and show HTML elements, and more."*. |
| **Line 16** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 17** | `</body>` | Closes the document `<body>` section. |
| **Line 18** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`i-46.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/i-46.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The i element</h1>

<p><i>Lorem ipsum</i> is the most popular filler text in history.</p>

<p>The <i>RMS Titanic</i>, a luxury steamship, sank on April 15, 1912 after striking an iceberg.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The i element</h1>` | Defines a **H1** heading element with text: *"The i element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p><i>Lorem ipsum</i> is the most popular filler text i...` | Defines a paragraph (`<p>`) element displaying text: *"<i>Lorem ipsum</i> is the most popular filler text in history."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<p>The <i>RMS Titanic</i>, a luxury steamship, sank on ...` | Defines a paragraph (`<p>`) element displaying text: *"The <i>RMS Titanic</i>, a luxury steamship, sank on April 15, 1912 after striking an iceberg."*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`ins-50.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/ins-50.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The ins element</h1>

<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The ins element</h1>` | Defines a **H1** heading element with text: *"The ins element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>` | Defines a paragraph (`<p>`) element displaying text: *"My favorite color is <del>blue</del> <ins>red</ins>!"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`legend-53.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/legend-53.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The legend element</h1>

<form action="/action_page.php">
 <fieldset>
  <legend>Personalia:</legend>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  <label for="birthday">Birthday:</label>
  <input type="date" id="birthday" name="birthday"><br><br>
  <input type="submit" value="Submit">
 </fieldset>
</form>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The legend element</h1>` | Defines a **H1** heading element with text: *"The legend element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<form action="/action_page.php">` | Opens a `<form>` container with attributes: `<form action="/action_page.php">` for user data input and submission. |
| **Line 8** | `<fieldset>` | Opens a `<fieldset>` element grouping related input controls within a border. |
| **Line 9** | `<legend>Personalia:</legend>` | Defines the caption/title for the `<fieldset>`: `<legend>Personalia:</legend>`. |
| **Line 10** | `<label for="fname">First name:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="fname">First name:</label>`. |
| **Line 11** | `<input type="text" id="fname" name="fname"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="text" id="fname" name="fname"><br><br>`. |
| **Line 12** | `<label for="lname">Last name:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="lname">Last name:</label>`. |
| **Line 13** | `<input type="text" id="lname" name="lname"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="text" id="lname" name="lname"><br><br>`. |
| **Line 14** | `<label for="email">Email:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="email">Email:</label>`. |
| **Line 15** | `<input type="email" id="email" name="email"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="email" id="email" name="email"><br><br>`. |
| **Line 16** | `<label for="birthday">Birthday:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="birthday">Birthday:</label>`. |
| **Line 17** | `<input type="date" id="birthday" name="birthday"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="date" id="birthday" name="birthday"><br><br>`. |
| **Line 18** | `<input type="submit" value="Submit">` | Specifies an interactive form input field (`<input>`): `<input type="submit" value="Submit">`. |
| **Line 19** | `</fieldset>` | Closes the `<fieldset>` element. |
| **Line 20** | `</form>` | Closes the `<form>` element. |
| **Line 21** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 22** | `</body>` | Closes the document `<body>` section. |
| **Line 23** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`mark-58.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/mark-58.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The mark element</h1>

<p>Do not forget to buy <mark>milk</mark> today.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The mark element</h1>` | Defines a **H1** heading element with text: *"The mark element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Do not forget to buy <mark>milk</mark> today.</p>` | Defines a paragraph (`<p>`) element displaying text: *"Do not forget to buy <mark>milk</mark> today."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`p-69.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/p-69.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The p element</h1>

<p>This is a paragraph.</p>
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The p element</h1>` | Defines a **H1** heading element with text: *"The p element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>This is a paragraph.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is a paragraph."*. |
| **Line 8** | `<p>This is a paragraph.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is a paragraph."*. |
| **Line 9** | `<p>This is a paragraph.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is a paragraph."*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`pre-72.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/pre-72.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The pre element</h1>

<pre>
Text in a pre element
is displayed in a fixed-width
font, and it preserves
both      spaces and
line breaks
</pre>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The pre element</h1>` | Defines a **H1** heading element with text: *"The pre element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<pre>` | Renders markup / text content: `<pre>` |
| **Line 8** | `Text in a pre element` | Renders markup / text content: `Text in a pre element` |
| **Line 9** | `is displayed in a fixed-width` | Renders markup / text content: `is displayed in a fixed-width` |
| **Line 10** | `font, and it preserves` | Renders markup / text content: `font, and it preserves` |
| **Line 11** | `both      spaces and` | Renders markup / text content: `both      spaces and` |
| **Line 12** | `line breaks` | Renders markup / text content: `line breaks` |
| **Line 13** | `</pre>` | Renders markup / text content: `</pre>` |
| **Line 14** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 15** | `</body>` | Closes the document `<body>` section. |
| **Line 16** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`progress-73.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/progress-73.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The progress element</h1>

<label for="file">Downloading progress:</label>
<progress id="file" value="32" max="100"> 32% </progress>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The progress element</h1>` | Defines a **H1** heading element with text: *"The progress element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<label for="file">Downloading progress:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="file">Downloading progress:</label>`. |
| **Line 8** | `<progress id="file" value="32" max="100"> 32% </progress>` | Renders a progress bar indicating completion percentage (`<progress>`): `<progress id="file" value="32" max="100"> 32% </progress>`. |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`q-74.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/q-74.html)

*Note: `q-74.html` is currently an empty file representing the `<q>` tag.*


**Standard Tag Usage:**
```html
<p>Short quote: <q>Knowledge is power.</q></p>
```


### 📄 [`rp-75.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/rp-75.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The rp element</h1>

<ruby>
漢 <rp>(</rp><rt>ㄏㄢˋ</rt><rp>)</rp>
</ruby>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The rp element</h1>` | Defines a **H1** heading element with text: *"The rp element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<ruby>` | Renders markup / text content: `<ruby>` |
| **Line 8** | `漢 <rp>(</rp><rt>ㄏㄢˋ</rt><rp>)</rp>` | Renders markup / text content: `漢 <rp>(</rp><rt>ㄏㄢˋ</rt><rp>)</rp>` |
| **Line 9** | `</ruby>` | Renders markup / text content: `</ruby>` |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`rt-76.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/rt-76.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The ruby and rt elements</h1>

<ruby>
 漢 <rt> ㄏㄢˋ </rt>
</ruby>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The ruby and rt elements</h1>` | Defines a **H1** heading element with text: *"The ruby and rt elements"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<ruby>` | Renders markup / text content: `<ruby>` |
| **Line 8** | `漢 <rt> ㄏㄢˋ </rt>` | Renders markup / text content: `漢 <rt> ㄏㄢˋ </rt>` |
| **Line 9** | `</ruby>` | Renders markup / text content: `</ruby>` |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`ruby-77.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/ruby-77.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The ruby and rt elements</h1>

<ruby>
 漢 <rt> ㄏㄢˋ </rt>
</ruby>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The ruby and rt elements</h1>` | Defines a **H1** heading element with text: *"The ruby and rt elements"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<ruby>` | Renders markup / text content: `<ruby>` |
| **Line 8** | `漢 <rt> ㄏㄢˋ </rt>` | Renders markup / text content: `漢 <rt> ㄏㄢˋ </rt>` |
| **Line 9** | `</ruby>` | Renders markup / text content: `</ruby>` |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`s-78.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/s-78.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The s element</h1>

<p><s>Only 50 tickets left!</s></p>
<p>SOLD OUT!</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The s element</h1>` | Defines a **H1** heading element with text: *"The s element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p><s>Only 50 tickets left!</s></p>` | Defines a paragraph (`<p>`) element displaying text: *"<s>Only 50 tickets left!</s>"*. |
| **Line 8** | `<p>SOLD OUT!</p>` | Defines a paragraph (`<p>`) element displaying text: *"SOLD OUT!"*. |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`samp-79.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/samp-79.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The samp element</h1>

<p>Message from my computer:</p>

<p><samp>File not found.<br>Press F1 to continue</samp></p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The samp element</h1>` | Defines a **H1** heading element with text: *"The samp element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Message from my computer:</p>` | Defines a paragraph (`<p>`) element displaying text: *"Message from my computer:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<p><samp>File not found.<br>Press F1 to continue</samp></p>` | Defines a paragraph (`<p>`) element displaying text: *"<samp>File not found.<br>Press F1 to continue</samp>"*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`select-83.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/select-83.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The select element</h1>

<p>The select element is used to create a drop-down list.</p>

<form action="/action_page.php">
  <label for="cars">Choose a car:</label>
  <select name="cars" id="cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="opel">Opel</option>
    <option value="audi">Audi</option>
  </select>
  <br><br>
  <input type="submit" value="Submit">
</form>

<p>Click the "Submit" button and the form-data will be sent to a page on the 
server called "action_page.php".</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The select element</h1>` | Defines a **H1** heading element with text: *"The select element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>The select element is used to create a drop-down lis...` | Defines a paragraph (`<p>`) element displaying text: *"The select element is used to create a drop-down list."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<form action="/action_page.php">` | Opens a `<form>` container with attributes: `<form action="/action_page.php">` for user data input and submission. |
| **Line 10** | `<label for="cars">Choose a car:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="cars">Choose a car:</label>`. |
| **Line 11** | `<select name="cars" id="cars">` | Opens a dropdown selection menu (`<select>`): `<select name="cars" id="cars">`. |
| **Line 12** | `<option value="volvo">Volvo</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="volvo">Volvo</option>`. |
| **Line 13** | `<option value="saab">Saab</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="saab">Saab</option>`. |
| **Line 14** | `<option value="opel">Opel</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="opel">Opel</option>`. |
| **Line 15** | `<option value="audi">Audi</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="audi">Audi</option>`. |
| **Line 16** | `</select>` | Closes the dropdown selection menu (`<select>`). |
| **Line 17** | `<br><br>` | Renders markup / text content: `<br><br>` |
| **Line 18** | `<input type="submit" value="Submit">` | Specifies an interactive form input field (`<input>`): `<input type="submit" value="Submit">`. |
| **Line 19** | `</form>` | Closes the `<form>` element. |
| **Line 20** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 21** | `<p>Click the "Submit" button and the form-data will be ...` | Renders markup / text content: `<p>Click the "Submit" button and the form-data will be sent to a page on the` |
| **Line 22** | `server called "action_page.php".</p>` | Renders markup / text content: `server called "action_page.php".</p>` |
| **Line 23** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 24** | `</body>` | Closes the document `<body>` section. |
| **Line 25** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`small-84.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/small-84.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The small element</h1>

<p>This is some normal text.</p>
<p><small>This is some smaller text.</small></p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The small element</h1>` | Defines a **H1** heading element with text: *"The small element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>This is some normal text.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is some normal text."*. |
| **Line 8** | `<p><small>This is some smaller text.</small></p>` | Defines a paragraph (`<p>`) element displaying text: *"<small>This is some smaller text.</small>"*. |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`span-86.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/span-86.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The span element</h1>

<p>My mother has <span style="color:blue;font-weight:bold">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold">dark green</span> eyes.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The span element</h1>` | Defines a **H1** heading element with text: *"The span element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>My mother has <span style="color:blue;font-weight:bo...` | Defines a paragraph (`<p>`) element displaying text: *"My mother has <span style="color:blue;font-weight:bold">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold">dark green</span> eyes."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`strong-87.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/strong-87.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The strong element</h1>

<p>This text is normal.</p>

<p><strong>This text is important!</strong></p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The strong element</h1>` | Defines a **H1** heading element with text: *"The strong element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>This text is normal.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This text is normal."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<p><strong>This text is important!</strong></p>` | Defines a paragraph (`<p>`) element displaying text: *"<strong>This text is important!</strong>"*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`sub-89.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/sub-89.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The sub and sup elements</h1>

<p>This text contains <sub>subscript</sub> text.</p>
<p>This text contains <sup>superscript</sup> text.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The sub and sup elements</h1>` | Defines a **H1** heading element with text: *"The sub and sup elements"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>This text contains <sub>subscript</sub> text.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This text contains <sub>subscript</sub> text."*. |
| **Line 8** | `<p>This text contains <sup>superscript</sup> text.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This text contains <sup>superscript</sup> text."*. |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`table-93.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/table-93.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<h1>The table element</h1>

<table>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$80</td>
  </tr>
</table>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `table, th, td {` | Renders markup / text content: `table, th, td {` |
| **Line 6** | `border: 1px solid black;` | Renders markup / text content: `border: 1px solid black;` |
| **Line 7** | `}` | Renders markup / text content: `}` |
| **Line 8** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 9** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 10** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<h1>The table element</h1>` | Defines a **H1** heading element with text: *"The table element"*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<table>` | Opens a `<table>` container with structure/styling: `<table>`. |
| **Line 15** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 16** | `<th>Month</th>` | Defines a table header cell (`<th>`): `<th>Month</th>`. |
| **Line 17** | `<th>Savings</th>` | Defines a table header cell (`<th>`): `<th>Savings</th>`. |
| **Line 18** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 19** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 20** | `<td>January</td>` | Defines a standard table data cell (`<td>`): `<td>January</td>`. |
| **Line 21** | `<td>$100</td>` | Defines a standard table data cell (`<td>`): `<td>$100</td>`. |
| **Line 22** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 23** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 24** | `<td>February</td>` | Defines a standard table data cell (`<td>`): `<td>February</td>`. |
| **Line 25** | `<td>$80</td>` | Defines a standard table data cell (`<td>`): `<td>$80</td>`. |
| **Line 26** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 27** | `</table>` | Closes the `<table>` element. |
| **Line 28** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 29** | `</body>` | Closes the document `<body>` section. |
| **Line 30** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`tr-103.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/tr-103.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<h1>The tr element</h1>

<p>The tr element defines a row in a table:</p>

<table>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$80</td>
  </tr>
</table>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `table, th, td {` | Renders markup / text content: `table, th, td {` |
| **Line 6** | `border: 1px solid black;` | Renders markup / text content: `border: 1px solid black;` |
| **Line 7** | `}` | Renders markup / text content: `}` |
| **Line 8** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 9** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 10** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<h1>The tr element</h1>` | Defines a **H1** heading element with text: *"The tr element"*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<p>The tr element defines a row in a table:</p>` | Defines a paragraph (`<p>`) element displaying text: *"The tr element defines a row in a table:"*. |
| **Line 15** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 16** | `<table>` | Opens a `<table>` container with structure/styling: `<table>`. |
| **Line 17** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 18** | `<th>Month</th>` | Defines a table header cell (`<th>`): `<th>Month</th>`. |
| **Line 19** | `<th>Savings</th>` | Defines a table header cell (`<th>`): `<th>Savings</th>`. |
| **Line 20** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 21** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 22** | `<td>January</td>` | Defines a standard table data cell (`<td>`): `<td>January</td>`. |
| **Line 23** | `<td>$100</td>` | Defines a standard table data cell (`<td>`): `<td>$100</td>`. |
| **Line 24** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 25** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 26** | `<td>February</td>` | Defines a standard table data cell (`<td>`): `<td>February</td>`. |
| **Line 27** | `<td>$80</td>` | Defines a standard table data cell (`<td>`): `<td>$80</td>`. |
| **Line 28** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 29** | `</table>` | Closes the `<table>` element. |
| **Line 30** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 31** | `</body>` | Closes the document `<body>` section. |
| **Line 32** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`u-105.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/u-105.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The u element</h1>

<p>This is some <u>mispeled</u> text.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The u element</h1>` | Defines a **H1** heading element with text: *"The u element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>This is some <u>mispeled</u> text.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is some <u>mispeled</u> text."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`var-107.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/var-107.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The var element</h1>

<p>The area of a triangle is: 1/2 x <var>b</var> x <var>h</var>, where <var>b</var> is the base, and <var>h</var> is the vertical height.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The var element</h1>` | Defines a **H1** heading element with text: *"The var element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>The area of a triangle is: 1/2 x <var>b</var> x <var...` | Defines a paragraph (`<p>`) element displaying text: *"The area of a triangle is: 1/2 x <var>b</var> x <var>h</var>, where <var>b</var> is the base, and <var>h</var> is the vertical height."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`wbr-109.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/wbr-109.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The wbr element</h1>

<p>Try to shrink the browser window, to view how the very long word in 
the paragraph below will break:</p>

<p>This is a veryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryvery<wbr>longwordthatwillbreakatspecific<wbr>placeswhenthebrowserwindowisresized.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The wbr element</h1>` | Defines a **H1** heading element with text: *"The wbr element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Try to shrink the browser window, to view how the ve...` | Renders markup / text content: `<p>Try to shrink the browser window, to view how the very long word in` |
| **Line 8** | `the paragraph below will break:</p>` | Renders markup / text content: `the paragraph below will break:</p>` |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `<p>This is a veryveryveryveryveryveryveryveryveryveryve...` | Defines a paragraph (`<p>`) element displaying text: *"This is a veryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryvery<wbr>longwordthatwillbreakatspecific<wbr>placeswhenthebrowserwindowisresized."*. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `</body>` | Closes the document `<body>` section. |
| **Line 13** | `</html>` | Closing root tag that marks the end of the HTML document. |

---


## <a id="4-lists--navigation"></a>4. Lists & Navigation

*Ordered, unordered, and descriptive definition lists for organizing hierarchical items.*


### 📄 [`2.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/2.html)

**Source Code:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <a href="https://www.w3schools.com">Visit W3Schools.com!</a>
</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html lang="en">` | Opening root tag of the HTML document with primary language set to `en` for browser rendering and screen readers. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<meta charset="UTF-8">` | Sets the document character encoding to **UTF-8**, ensuring universal support for characters, symbols, and emojis. |
| **Line 5** | `<meta name="viewport" content="width=device-width, init...` | Configures responsive viewport scaling so the page adjusts cleanly across mobile, tablet, and desktop screens. |
| **Line 6** | `<title>Document</title>` | Sets the document title rendered in the browser tab and bookmarks bar: **"Document"**. |
| **Line 7** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 8** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 9** | `<a href="https://www.w3schools.com">Visit W3Schools.com!</a>` | Renders markup / text content: `<a href="https://www.w3schools.com">Visit W3Schools.com!</a>` |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`colgroup-22.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/colgroup-22.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<h1>The colgroup element</h1>

<table>
  <colgroup>
    <col span="2" style="background-color:red">
    <col style="background-color:yellow">
  </colgroup>
  <tr>
    <th>ISBN</th>
    <th>Title</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>3476896</td>
    <td>My first HTML</td>
    <td>$53</td>
  </tr>
  <tr>
    <td>5869207</td>
    <td>My first CSS</td>
    <td>$49</td>
  </tr>
</table>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `table, th, td {` | Renders markup / text content: `table, th, td {` |
| **Line 6** | `border: 1px solid black;` | Renders markup / text content: `border: 1px solid black;` |
| **Line 7** | `}` | Renders markup / text content: `}` |
| **Line 8** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 9** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 10** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<h1>The colgroup element</h1>` | Defines a **H1** heading element with text: *"The colgroup element"*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<table>` | Opens a `<table>` container with structure/styling: `<table>`. |
| **Line 15** | `<colgroup>` | Renders markup / text content: `<colgroup>` |
| **Line 16** | `<col span="2" style="background-color:red">` | Renders markup / text content: `<col span="2" style="background-color:red">` |
| **Line 17** | `<col style="background-color:yellow">` | Renders markup / text content: `<col style="background-color:yellow">` |
| **Line 18** | `</colgroup>` | Renders markup / text content: `</colgroup>` |
| **Line 19** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 20** | `<th>ISBN</th>` | Defines a table header cell (`<th>`): `<th>ISBN</th>`. |
| **Line 21** | `<th>Title</th>` | Defines a table header cell (`<th>`): `<th>Title</th>`. |
| **Line 22** | `<th>Price</th>` | Defines a table header cell (`<th>`): `<th>Price</th>`. |
| **Line 23** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 24** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 25** | `<td>3476896</td>` | Defines a standard table data cell (`<td>`): `<td>3476896</td>`. |
| **Line 26** | `<td>My first HTML</td>` | Defines a standard table data cell (`<td>`): `<td>My first HTML</td>`. |
| **Line 27** | `<td>$53</td>` | Defines a standard table data cell (`<td>`): `<td>$53</td>`. |
| **Line 28** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 29** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 30** | `<td>5869207</td>` | Defines a standard table data cell (`<td>`): `<td>5869207</td>`. |
| **Line 31** | `<td>My first CSS</td>` | Defines a standard table data cell (`<td>`): `<td>My first CSS</td>`. |
| **Line 32** | `<td>$49</td>` | Defines a standard table data cell (`<td>`): `<td>$49</td>`. |
| **Line 33** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 34** | `</table>` | Closes the `<table>` element. |
| **Line 35** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 36** | `</body>` | Closes the document `<body>` section. |
| **Line 37** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`dd-25.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/dd-25.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The dl, dd, and dt elements</h1>

<p>These three elements are used to create a description list:</p>

<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The dl, dd, and dt elements</h1>` | Defines a **H1** heading element with text: *"The dl, dd, and dt elements"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>These three elements are used to create a descriptio...` | Defines a paragraph (`<p>`) element displaying text: *"These three elements are used to create a description list:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<dl>` | Renders markup / text content: `<dl>` |
| **Line 10** | `<dt>Coffee</dt>` | Renders markup / text content: `<dt>Coffee</dt>` |
| **Line 11** | `<dd>Black hot drink</dd>` | Renders markup / text content: `<dd>Black hot drink</dd>` |
| **Line 12** | `<dt>Milk</dt>` | Renders markup / text content: `<dt>Milk</dt>` |
| **Line 13** | `<dd>White cold drink</dd>` | Renders markup / text content: `<dd>White cold drink</dd>` |
| **Line 14** | `</dl>` | Renders markup / text content: `</dl>` |
| **Line 15** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 16** | `</body>` | Closes the document `<body>` section. |
| **Line 17** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`dt-32.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/dt-32.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The dl, dd, and dt elements</h1>

<p>These three elements are used to create a description list:</p>

<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The dl, dd, and dt elements</h1>` | Defines a **H1** heading element with text: *"The dl, dd, and dt elements"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>These three elements are used to create a descriptio...` | Defines a paragraph (`<p>`) element displaying text: *"These three elements are used to create a description list:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<dl>` | Renders markup / text content: `<dl>` |
| **Line 10** | `<dt>Coffee</dt>` | Renders markup / text content: `<dt>Coffee</dt>` |
| **Line 11** | `<dd>Black hot drink</dd>` | Renders markup / text content: `<dd>Black hot drink</dd>` |
| **Line 12** | `<dt>Milk</dt>` | Renders markup / text content: `<dt>Milk</dt>` |
| **Line 13** | `<dd>White cold drink</dd>` | Renders markup / text content: `<dd>White cold drink</dd>` |
| **Line 14** | `</dl>` | Renders markup / text content: `</dl>` |
| **Line 15** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 16** | `</body>` | Closes the document `<body>` section. |
| **Line 17** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`label-52.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/label-52.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The label element</h1>

<p>Click on one of the text labels to toggle the related radio button:</p>

<form action="/action_page.php">
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label><br><br>
  <input type="submit" value="Submit">
</form>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The label element</h1>` | Defines a **H1** heading element with text: *"The label element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Click on one of the text labels to toggle the relate...` | Defines a paragraph (`<p>`) element displaying text: *"Click on one of the text labels to toggle the related radio button:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<form action="/action_page.php">` | Opens a `<form>` container with attributes: `<form action="/action_page.php">` for user data input and submission. |
| **Line 10** | `<input type="radio" id="html" name="fav_language" value...` | Specifies an interactive form input field (`<input>`): `<input type="radio" id="html" name="fav_language" value="HTML">`. |
| **Line 11** | `<label for="html">HTML</label><br>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="html">HTML</label><br>`. |
| **Line 12** | `<input type="radio" id="css" name="fav_language" value=...` | Specifies an interactive form input field (`<input>`): `<input type="radio" id="css" name="fav_language" value="CSS">`. |
| **Line 13** | `<label for="css">CSS</label><br>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="css">CSS</label><br>`. |
| **Line 14** | `<input type="radio" id="javascript" name="fav_language"...` | Specifies an interactive form input field (`<input>`): `<input type="radio" id="javascript" name="fav_language" value="JavaScript">`. |
| **Line 15** | `<label for="javascript">JavaScript</label><br><br>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="javascript">JavaScript</label><br><br>`. |
| **Line 16** | `<input type="submit" value="Submit">` | Specifies an interactive form input field (`<input>`): `<input type="submit" value="Submit">`. |
| **Line 17** | `</form>` | Closes the `<form>` element. |
| **Line 18** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 19** | `</body>` | Closes the document `<body>` section. |
| **Line 20** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`li-54.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/li-54.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The ol and ul elements</h1>

<p>The ol element defines an ordered list:</p>
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<p>The ul element defines an unordered list:</p>
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The ol and ul elements</h1>` | Defines a **H1** heading element with text: *"The ol and ul elements"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>The ol element defines an ordered list:</p>` | Defines a paragraph (`<p>`) element displaying text: *"The ol element defines an ordered list:"*. |
| **Line 8** | `<ol>` | Opens an ordered numbered list (`<ol>`). |
| **Line 9** | `<li>Coffee</li>` | Defines an individual list item (`<li>`): `<li>Coffee</li>`. |
| **Line 10** | `<li>Tea</li>` | Defines an individual list item (`<li>`): `<li>Tea</li>`. |
| **Line 11** | `<li>Milk</li>` | Defines an individual list item (`<li>`): `<li>Milk</li>`. |
| **Line 12** | `</ol>` | Closes the ordered numbered list (`<ol>`). |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<p>The ul element defines an unordered list:</p>` | Defines a paragraph (`<p>`) element displaying text: *"The ul element defines an unordered list:"*. |
| **Line 15** | `<ul>` | Opens an unordered bulleted list (`<ul>`). |
| **Line 16** | `<li>Coffee</li>` | Defines an individual list item (`<li>`): `<li>Coffee</li>`. |
| **Line 17** | `<li>Tea</li>` | Defines an individual list item (`<li>`): `<li>Tea</li>`. |
| **Line 18** | `<li>Milk</li>` | Defines an individual list item (`<li>`): `<li>Milk</li>`. |
| **Line 19** | `</ul>` | Closes the unordered bulleted list (`<ul>`). |
| **Line 20** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 21** | `</body>` | Closes the document `<body>` section. |
| **Line 22** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`menu-59.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/menu-59.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The menu element</h1>

<menu>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</menu>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The menu element</h1>` | Defines a **H1** heading element with text: *"The menu element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<menu>` | Renders markup / text content: `<menu>` |
| **Line 8** | `<li>Coffee</li>` | Defines an individual list item (`<li>`): `<li>Coffee</li>`. |
| **Line 9** | `<li>Tea</li>` | Defines an individual list item (`<li>`): `<li>Tea</li>`. |
| **Line 10** | `<li>Milk</li>` | Defines an individual list item (`<li>`): `<li>Milk</li>`. |
| **Line 11** | `</menu>` | Renders markup / text content: `</menu>` |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 13** | `</body>` | Closes the document `<body>` section. |
| **Line 14** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`ol-65.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/ol-65.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The ol element</h1>

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<ol start="50">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
 
</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The ol element</h1>` | Defines a **H1** heading element with text: *"The ol element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<ol>` | Opens an ordered numbered list (`<ol>`). |
| **Line 8** | `<li>Coffee</li>` | Defines an individual list item (`<li>`): `<li>Coffee</li>`. |
| **Line 9** | `<li>Tea</li>` | Defines an individual list item (`<li>`): `<li>Tea</li>`. |
| **Line 10** | `<li>Milk</li>` | Defines an individual list item (`<li>`): `<li>Milk</li>`. |
| **Line 11** | `</ol>` | Closes the ordered numbered list (`<ol>`). |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 13** | `<ol start="50">` | Opens an ordered numbered list (`<ol>`). |
| **Line 14** | `<li>Coffee</li>` | Defines an individual list item (`<li>`): `<li>Coffee</li>`. |
| **Line 15** | `<li>Tea</li>` | Defines an individual list item (`<li>`): `<li>Tea</li>`. |
| **Line 16** | `<li>Milk</li>` | Defines an individual list item (`<li>`): `<li>Milk</li>`. |
| **Line 17** | `</ol>` | Closes the ordered numbered list (`<ol>`). |
| **Line 18** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 19** | `</body>` | Closes the document `<body>` section. |
| **Line 20** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`svg-92.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/svg-92.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The svg element</h1>

<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
  Sorry, your browser does not support inline SVG.
</svg>
 
</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The svg element</h1>` | Defines a **H1** heading element with text: *"The svg element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<svg width="100" height="100">` | Opens an SVG (Scalable Vector Graphics) container (`<svg>`): `<svg width="100" height="100">`. |
| **Line 8** | `<circle cx="50" cy="50" r="40" stroke="green" stroke-wi...` | Renders markup / text content: `<circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />` |
| **Line 9** | `Sorry, your browser does not support inline SVG.` | Renders markup / text content: `Sorry, your browser does not support inline SVG.` |
| **Line 10** | `</svg>` | Closes the `<svg>` graphics container. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `</body>` | Closes the document `<body>` section. |
| **Line 13** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`ul-106.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/ul-106.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The ul element</h1>

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The ul element</h1>` | Defines a **H1** heading element with text: *"The ul element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<ul>` | Opens an unordered bulleted list (`<ul>`). |
| **Line 8** | `<li>Coffee</li>` | Defines an individual list item (`<li>`): `<li>Coffee</li>`. |
| **Line 9** | `<li>Tea</li>` | Defines an individual list item (`<li>`): `<li>Tea</li>`. |
| **Line 10** | `<li>Milk</li>` | Defines an individual list item (`<li>`): `<li>Milk</li>`. |
| **Line 11** | `</ul>` | Closes the unordered bulleted list (`<ul>`). |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 13** | `</body>` | Closes the document `<body>` section. |
| **Line 14** | `</html>` | Closing root tag that marks the end of the HTML document. |

---


## <a id="5-tables--tabular-data"></a>5. Tables & Tabular Data

*Table elements, headers, columns, row structures, summaries, and captions for structured data.*


### 📄 [`caption -18.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/caption -18.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<h1>The caption element</h1>

<table>
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$50</td>
  </tr>
</table>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `table, th, td {` | Renders markup / text content: `table, th, td {` |
| **Line 6** | `border: 1px solid black;` | Renders markup / text content: `border: 1px solid black;` |
| **Line 7** | `}` | Renders markup / text content: `}` |
| **Line 8** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 9** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 10** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<h1>The caption element</h1>` | Defines a **H1** heading element with text: *"The caption element"*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<table>` | Opens a `<table>` container with structure/styling: `<table>`. |
| **Line 15** | `<caption>Monthly savings</caption>` | Renders markup / text content: `<caption>Monthly savings</caption>` |
| **Line 16** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 17** | `<th>Month</th>` | Defines a table header cell (`<th>`): `<th>Month</th>`. |
| **Line 18** | `<th>Savings</th>` | Defines a table header cell (`<th>`): `<th>Savings</th>`. |
| **Line 19** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 20** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 21** | `<td>January</td>` | Defines a standard table data cell (`<td>`): `<td>January</td>`. |
| **Line 22** | `<td>$100</td>` | Defines a standard table data cell (`<td>`): `<td>$100</td>`. |
| **Line 23** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 24** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 25** | `<td>February</td>` | Defines a standard table data cell (`<td>`): `<td>February</td>`. |
| **Line 26** | `<td>$50</td>` | Defines a standard table data cell (`<td>`): `<td>$50</td>`. |
| **Line 27** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 28** | `</table>` | Closes the `<table>` element. |
| **Line 29** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 30** | `</body>` | Closes the document `<body>` section. |
| **Line 31** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`tbody-94.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/tbody-94.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<h1>The thead, tbody, and tfoot elements</h1>

<table>
  <thead>
    <tr>
      <th>Month</th>
      <th>Savings</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>January</td>
      <td>$100</td>
    </tr>
    <tr>
      <td>February</td>
      <td>$80</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Sum</td>
      <td>$180</td>
    </tr>
  </tfoot>
</table>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `table, th, td {` | Renders markup / text content: `table, th, td {` |
| **Line 6** | `border: 1px solid black;` | Renders markup / text content: `border: 1px solid black;` |
| **Line 7** | `}` | Renders markup / text content: `}` |
| **Line 8** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 9** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 10** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<h1>The thead, tbody, and tfoot elements</h1>` | Defines a **H1** heading element with text: *"The thead, tbody, and tfoot elements"*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<table>` | Opens a `<table>` container with structure/styling: `<table>`. |
| **Line 15** | `<thead>` | Defines a table header cell (`<th>`): `<thead>`. |
| **Line 16** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 17** | `<th>Month</th>` | Defines a table header cell (`<th>`): `<th>Month</th>`. |
| **Line 18** | `<th>Savings</th>` | Defines a table header cell (`<th>`): `<th>Savings</th>`. |
| **Line 19** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 20** | `</thead>` | Renders markup / text content: `</thead>` |
| **Line 21** | `<tbody>` | Renders markup / text content: `<tbody>` |
| **Line 22** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 23** | `<td>January</td>` | Defines a standard table data cell (`<td>`): `<td>January</td>`. |
| **Line 24** | `<td>$100</td>` | Defines a standard table data cell (`<td>`): `<td>$100</td>`. |
| **Line 25** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 26** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 27** | `<td>February</td>` | Defines a standard table data cell (`<td>`): `<td>February</td>`. |
| **Line 28** | `<td>$80</td>` | Defines a standard table data cell (`<td>`): `<td>$80</td>`. |
| **Line 29** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 30** | `</tbody>` | Renders markup / text content: `</tbody>` |
| **Line 31** | `<tfoot>` | Renders markup / text content: `<tfoot>` |
| **Line 32** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 33** | `<td>Sum</td>` | Defines a standard table data cell (`<td>`): `<td>Sum</td>`. |
| **Line 34** | `<td>$180</td>` | Defines a standard table data cell (`<td>`): `<td>$180</td>`. |
| **Line 35** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 36** | `</tfoot>` | Renders markup / text content: `</tfoot>` |
| **Line 37** | `</table>` | Closes the `<table>` element. |
| **Line 38** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 39** | `</body>` | Closes the document `<body>` section. |
| **Line 40** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`td-95.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/td-95.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<h1>The td element</h1>

<p>The td element defines a cell in a table:</p>

<table>
  <tr>
    <td>Cell A</td>
    <td>Cell B</td>
  </tr>
  <tr>
    <td>Cell C</td>
    <td>Cell D</td>
  </tr>
</table>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `table, th, td {` | Renders markup / text content: `table, th, td {` |
| **Line 6** | `border: 1px solid black;` | Renders markup / text content: `border: 1px solid black;` |
| **Line 7** | `}` | Renders markup / text content: `}` |
| **Line 8** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 9** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 10** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<h1>The td element</h1>` | Defines a **H1** heading element with text: *"The td element"*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<p>The td element defines a cell in a table:</p>` | Defines a paragraph (`<p>`) element displaying text: *"The td element defines a cell in a table:"*. |
| **Line 15** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 16** | `<table>` | Opens a `<table>` container with structure/styling: `<table>`. |
| **Line 17** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 18** | `<td>Cell A</td>` | Defines a standard table data cell (`<td>`): `<td>Cell A</td>`. |
| **Line 19** | `<td>Cell B</td>` | Defines a standard table data cell (`<td>`): `<td>Cell B</td>`. |
| **Line 20** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 21** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 22** | `<td>Cell C</td>` | Defines a standard table data cell (`<td>`): `<td>Cell C</td>`. |
| **Line 23** | `<td>Cell D</td>` | Defines a standard table data cell (`<td>`): `<td>Cell D</td>`. |
| **Line 24** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 25** | `</table>` | Closes the `<table>` element. |
| **Line 26** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 27** | `</body>` | Closes the document `<body>` section. |
| **Line 28** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`tfoot-98.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/tfoot-98.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<h1>The thead, tbody, and tfoot elements</h1>

<table>
  <thead>
    <tr>
      <th>Month</th>
      <th>Savings</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>January</td>
      <td>$100</td>
    </tr>
    <tr>
      <td>February</td>
      <td>$80</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Sum</td>
      <td>$180</td>
    </tr>
  </tfoot>
</table>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `table, th, td {` | Renders markup / text content: `table, th, td {` |
| **Line 6** | `border: 1px solid black;` | Renders markup / text content: `border: 1px solid black;` |
| **Line 7** | `}` | Renders markup / text content: `}` |
| **Line 8** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 9** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 10** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<h1>The thead, tbody, and tfoot elements</h1>` | Defines a **H1** heading element with text: *"The thead, tbody, and tfoot elements"*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<table>` | Opens a `<table>` container with structure/styling: `<table>`. |
| **Line 15** | `<thead>` | Defines a table header cell (`<th>`): `<thead>`. |
| **Line 16** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 17** | `<th>Month</th>` | Defines a table header cell (`<th>`): `<th>Month</th>`. |
| **Line 18** | `<th>Savings</th>` | Defines a table header cell (`<th>`): `<th>Savings</th>`. |
| **Line 19** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 20** | `</thead>` | Renders markup / text content: `</thead>` |
| **Line 21** | `<tbody>` | Renders markup / text content: `<tbody>` |
| **Line 22** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 23** | `<td>January</td>` | Defines a standard table data cell (`<td>`): `<td>January</td>`. |
| **Line 24** | `<td>$100</td>` | Defines a standard table data cell (`<td>`): `<td>$100</td>`. |
| **Line 25** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 26** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 27** | `<td>February</td>` | Defines a standard table data cell (`<td>`): `<td>February</td>`. |
| **Line 28** | `<td>$80</td>` | Defines a standard table data cell (`<td>`): `<td>$80</td>`. |
| **Line 29** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 30** | `</tbody>` | Renders markup / text content: `</tbody>` |
| **Line 31** | `<tfoot>` | Renders markup / text content: `<tfoot>` |
| **Line 32** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 33** | `<td>Sum</td>` | Defines a standard table data cell (`<td>`): `<td>Sum</td>`. |
| **Line 34** | `<td>$180</td>` | Defines a standard table data cell (`<td>`): `<td>$180</td>`. |
| **Line 35** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 36** | `</tfoot>` | Renders markup / text content: `</tfoot>` |
| **Line 37** | `</table>` | Closes the `<table>` element. |
| **Line 38** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 39** | `</body>` | Closes the document `<body>` section. |
| **Line 40** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`th-99.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/th-99.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<h1>The th element</h1>

<p>The th element defines a header cell in a table:</p>

<table>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$80</td>
  </tr>
</table>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `table, th, td {` | Renders markup / text content: `table, th, td {` |
| **Line 6** | `border: 1px solid black;` | Renders markup / text content: `border: 1px solid black;` |
| **Line 7** | `}` | Renders markup / text content: `}` |
| **Line 8** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 9** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 10** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<h1>The th element</h1>` | Defines a **H1** heading element with text: *"The th element"*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<p>The th element defines a header cell in a table:</p>` | Defines a paragraph (`<p>`) element displaying text: *"The th element defines a header cell in a table:"*. |
| **Line 15** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 16** | `<table>` | Opens a `<table>` container with structure/styling: `<table>`. |
| **Line 17** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 18** | `<th>Month</th>` | Defines a table header cell (`<th>`): `<th>Month</th>`. |
| **Line 19** | `<th>Savings</th>` | Defines a table header cell (`<th>`): `<th>Savings</th>`. |
| **Line 20** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 21** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 22** | `<td>January</td>` | Defines a standard table data cell (`<td>`): `<td>January</td>`. |
| **Line 23** | `<td>$100</td>` | Defines a standard table data cell (`<td>`): `<td>$100</td>`. |
| **Line 24** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 25** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 26** | `<td>February</td>` | Defines a standard table data cell (`<td>`): `<td>February</td>`. |
| **Line 27** | `<td>$80</td>` | Defines a standard table data cell (`<td>`): `<td>$80</td>`. |
| **Line 28** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 29** | `</table>` | Closes the `<table>` element. |
| **Line 30** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 31** | `</body>` | Closes the document `<body>` section. |
| **Line 32** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`thead-100.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/thead-100.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<h1>The thead, tbody, and tfoot elements</h1>

<table>
  <thead>
    <tr>
      <th>Month</th>
      <th>Savings</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>January</td>
      <td>$100</td>
    </tr>
    <tr>
      <td>February</td>
      <td>$80</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Sum</td>
      <td>$180</td>
    </tr>
  </tfoot>
</table>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<style>` | Opens an embedded CSS `<style>` block for defining styling rules. |
| **Line 5** | `table, th, td {` | Renders markup / text content: `table, th, td {` |
| **Line 6** | `border: 1px solid black;` | Renders markup / text content: `border: 1px solid black;` |
| **Line 7** | `}` | Renders markup / text content: `}` |
| **Line 8** | `</style>` | Closes the embedded CSS `<style>` block. |
| **Line 9** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 10** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `<h1>The thead, tbody, and tfoot elements</h1>` | Defines a **H1** heading element with text: *"The thead, tbody, and tfoot elements"*. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<table>` | Opens a `<table>` container with structure/styling: `<table>`. |
| **Line 15** | `<thead>` | Defines a table header cell (`<th>`): `<thead>`. |
| **Line 16** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 17** | `<th>Month</th>` | Defines a table header cell (`<th>`): `<th>Month</th>`. |
| **Line 18** | `<th>Savings</th>` | Defines a table header cell (`<th>`): `<th>Savings</th>`. |
| **Line 19** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 20** | `</thead>` | Renders markup / text content: `</thead>` |
| **Line 21** | `<tbody>` | Renders markup / text content: `<tbody>` |
| **Line 22** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 23** | `<td>January</td>` | Defines a standard table data cell (`<td>`): `<td>January</td>`. |
| **Line 24** | `<td>$100</td>` | Defines a standard table data cell (`<td>`): `<td>$100</td>`. |
| **Line 25** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 26** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 27** | `<td>February</td>` | Defines a standard table data cell (`<td>`): `<td>February</td>`. |
| **Line 28** | `<td>$80</td>` | Defines a standard table data cell (`<td>`): `<td>$80</td>`. |
| **Line 29** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 30** | `</tbody>` | Renders markup / text content: `</tbody>` |
| **Line 31** | `<tfoot>` | Renders markup / text content: `<tfoot>` |
| **Line 32** | `<tr>` | Opens a table row (`<tr>`) container. |
| **Line 33** | `<td>Sum</td>` | Defines a standard table data cell (`<td>`): `<td>Sum</td>`. |
| **Line 34** | `<td>$180</td>` | Defines a standard table data cell (`<td>`): `<td>$180</td>`. |
| **Line 35** | `</tr>` | Closes the table row (`<tr>`). |
| **Line 36** | `</tfoot>` | Renders markup / text content: `</tfoot>` |
| **Line 37** | `</table>` | Closes the `<table>` element. |
| **Line 38** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 39** | `</body>` | Closes the document `<body>` section. |
| **Line 40** | `</html>` | Closing root tag that marks the end of the HTML document. |

---


## <a id="6-forms--user-inputs"></a>6. Forms & User Inputs

*Interactive form controls, labels, buttons, selection lists, grouped inputs, and output results.*


### 📄 [`button-16.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/button-16.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The button Element</h1>

<button type="button" onclick="alert('Hello world!')">Click Me!</button>
 
</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The button Element</h1>` | Defines a **H1** heading element with text: *"The button Element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<button type="button" onclick="alert('Hello world!')">C...` | Defines a clickable button element (`<button>`): `<button type="button" onclick="alert('Hello world!')">Click Me!</button>`. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`datalist-24.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/datalist-24.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The datalist element</h1>

<form action="/action_page.php" method="get">
  <label for="browser">Choose your browser from the list:</label>
  <input list="browsers" name="browser" id="browser">
  <datalist id="browsers">
    <option value="Edge">
    <option value="Firefox">
    <option value="Chrome">
    <option value="Opera">
    <option value="Safari">
  </datalist>
  <input type="submit">
</form>

<p><strong>Note:</strong> The datalist tag is not supported in Safari 12.0 (or earlier).</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The datalist element</h1>` | Defines a **H1** heading element with text: *"The datalist element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<form action="/action_page.php" method="get">` | Opens a `<form>` container with attributes: `<form action="/action_page.php" method="get">` for user data input and submission. |
| **Line 8** | `<label for="browser">Choose your browser from the list:...` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="browser">Choose your browser from the list:</label>`. |
| **Line 9** | `<input list="browsers" name="browser" id="browser">` | Specifies an interactive form input field (`<input>`): `<input list="browsers" name="browser" id="browser">`. |
| **Line 10** | `<datalist id="browsers">` | Renders markup / text content: `<datalist id="browsers">` |
| **Line 11** | `<option value="Edge">` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="Edge">`. |
| **Line 12** | `<option value="Firefox">` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="Firefox">`. |
| **Line 13** | `<option value="Chrome">` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="Chrome">`. |
| **Line 14** | `<option value="Opera">` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="Opera">`. |
| **Line 15** | `<option value="Safari">` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="Safari">`. |
| **Line 16** | `</datalist>` | Renders markup / text content: `</datalist>` |
| **Line 17** | `<input type="submit">` | Specifies an interactive form input field (`<input>`): `<input type="submit">`. |
| **Line 18** | `</form>` | Closes the `<form>` element. |
| **Line 19** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 20** | `<p><strong>Note:</strong> The datalist tag is not suppo...` | Defines a paragraph (`<p>`) element displaying text: *"<strong>Note:</strong> The datalist tag is not supported in Safari 12.0 (or earlier)."*. |
| **Line 21** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 22** | `</body>` | Closes the document `<body>` section. |
| **Line 23** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`fieldset-35.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/fieldset-35.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The fieldset element</h1>

<form action="/action_page.php">
 <fieldset>
  <legend>Personalia:</legend>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  <label for="birthday">Birthday:</label>
  <input type="date" id="birthday" name="birthday"><br><br>
  <input type="submit" value="Submit">
 </fieldset>
</form>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The fieldset element</h1>` | Defines a **H1** heading element with text: *"The fieldset element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<form action="/action_page.php">` | Opens a `<form>` container with attributes: `<form action="/action_page.php">` for user data input and submission. |
| **Line 8** | `<fieldset>` | Opens a `<fieldset>` element grouping related input controls within a border. |
| **Line 9** | `<legend>Personalia:</legend>` | Defines the caption/title for the `<fieldset>`: `<legend>Personalia:</legend>`. |
| **Line 10** | `<label for="fname">First name:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="fname">First name:</label>`. |
| **Line 11** | `<input type="text" id="fname" name="fname"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="text" id="fname" name="fname"><br><br>`. |
| **Line 12** | `<label for="lname">Last name:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="lname">Last name:</label>`. |
| **Line 13** | `<input type="text" id="lname" name="lname"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="text" id="lname" name="lname"><br><br>`. |
| **Line 14** | `<label for="email">Email:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="email">Email:</label>`. |
| **Line 15** | `<input type="email" id="email" name="email"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="email" id="email" name="email"><br><br>`. |
| **Line 16** | `<label for="birthday">Birthday:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="birthday">Birthday:</label>`. |
| **Line 17** | `<input type="date" id="birthday" name="birthday"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="date" id="birthday" name="birthday"><br><br>`. |
| **Line 18** | `<input type="submit" value="Submit">` | Specifies an interactive form input field (`<input>`): `<input type="submit" value="Submit">`. |
| **Line 19** | `</fieldset>` | Closes the `<fieldset>` element. |
| **Line 20** | `</form>` | Closes the `<form>` element. |
| **Line 21** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 22** | `</body>` | Closes the document `<body>` section. |
| **Line 23** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`form-39.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/form-39.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The form element</h1>

<form action="/action_page.php">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <input type="submit" value="Submit">
</form>

<p>Click the "Submit" button and the form-data will be sent to a page on the 
server called "action_page.php".</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The form element</h1>` | Defines a **H1** heading element with text: *"The form element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<form action="/action_page.php">` | Opens a `<form>` container with attributes: `<form action="/action_page.php">` for user data input and submission. |
| **Line 8** | `<label for="fname">First name:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="fname">First name:</label>`. |
| **Line 9** | `<input type="text" id="fname" name="fname"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="text" id="fname" name="fname"><br><br>`. |
| **Line 10** | `<label for="lname">Last name:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="lname">Last name:</label>`. |
| **Line 11** | `<input type="text" id="lname" name="lname"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="text" id="lname" name="lname"><br><br>`. |
| **Line 12** | `<input type="submit" value="Submit">` | Specifies an interactive form input field (`<input>`): `<input type="submit" value="Submit">`. |
| **Line 13** | `</form>` | Closes the `<form>` element. |
| **Line 14** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 15** | `<p>Click the "Submit" button and the form-data will be ...` | Renders markup / text content: `<p>Click the "Submit" button and the form-data will be sent to a page on the` |
| **Line 16** | `server called "action_page.php".</p>` | Renders markup / text content: `server called "action_page.php".</p>` |
| **Line 17** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 18** | `</body>` | Closes the document `<body>` section. |
| **Line 19** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`input-49.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/input-49.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The input element</h1>

<form action="/action_page.php">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <input type="submit" value="Submit">
</form>

<p>Click the "Submit" button and the form-data will be sent to a page on the 
server called "action_page.php".</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The input element</h1>` | Defines a **H1** heading element with text: *"The input element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<form action="/action_page.php">` | Opens a `<form>` container with attributes: `<form action="/action_page.php">` for user data input and submission. |
| **Line 8** | `<label for="fname">First name:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="fname">First name:</label>`. |
| **Line 9** | `<input type="text" id="fname" name="fname"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="text" id="fname" name="fname"><br><br>`. |
| **Line 10** | `<label for="lname">Last name:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="lname">Last name:</label>`. |
| **Line 11** | `<input type="text" id="lname" name="lname"><br><br>` | Specifies an interactive form input field (`<input>`): `<input type="text" id="lname" name="lname"><br><br>`. |
| **Line 12** | `<input type="submit" value="Submit">` | Specifies an interactive form input field (`<input>`): `<input type="submit" value="Submit">`. |
| **Line 13** | `</form>` | Closes the `<form>` element. |
| **Line 14** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 15** | `<p>Click the "Submit" button and the form-data will be ...` | Renders markup / text content: `<p>Click the "Submit" button and the form-data will be sent to a page on the` |
| **Line 16** | `server called "action_page.php".</p>` | Renders markup / text content: `server called "action_page.php".</p>` |
| **Line 17** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 18** | `</body>` | Closes the document `<body>` section. |
| **Line 19** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`optgroup-66.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/optgroup-66.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The optgroup element</h1>

<p>The optgroup tag is used to group related options in a drop-down list:</p>

<form action="/action_page.php">
  <label for="cars">Choose a car:</label>
  <select name="cars" id="cars">
    <optgroup label="Swedish Cars">
      <option value="volvo">Volvo</option>
      <option value="saab">Saab</option>
    </optgroup>
    <optgroup label="German Cars">
      <option value="mercedes">Mercedes</option>
      <option value="audi">Audi</option>
    </optgroup>
  </select>
  <br><br>
  <input type="submit" value="Submit">
</form>
 
</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The optgroup element</h1>` | Defines a **H1** heading element with text: *"The optgroup element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>The optgroup tag is used to group related options in...` | Defines a paragraph (`<p>`) element displaying text: *"The optgroup tag is used to group related options in a drop-down list:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<form action="/action_page.php">` | Opens a `<form>` container with attributes: `<form action="/action_page.php">` for user data input and submission. |
| **Line 10** | `<label for="cars">Choose a car:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="cars">Choose a car:</label>`. |
| **Line 11** | `<select name="cars" id="cars">` | Opens a dropdown selection menu (`<select>`): `<select name="cars" id="cars">`. |
| **Line 12** | `<optgroup label="Swedish Cars">` | Groups related dropdown options with a label (`<optgroup>`): `<optgroup label="Swedish Cars">`. |
| **Line 13** | `<option value="volvo">Volvo</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="volvo">Volvo</option>`. |
| **Line 14** | `<option value="saab">Saab</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="saab">Saab</option>`. |
| **Line 15** | `</optgroup>` | Closes the `<optgroup>` element. |
| **Line 16** | `<optgroup label="German Cars">` | Groups related dropdown options with a label (`<optgroup>`): `<optgroup label="German Cars">`. |
| **Line 17** | `<option value="mercedes">Mercedes</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="mercedes">Mercedes</option>`. |
| **Line 18** | `<option value="audi">Audi</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="audi">Audi</option>`. |
| **Line 19** | `</optgroup>` | Closes the `<optgroup>` element. |
| **Line 20** | `</select>` | Closes the dropdown selection menu (`<select>`). |
| **Line 21** | `<br><br>` | Renders markup / text content: `<br><br>` |
| **Line 22** | `<input type="submit" value="Submit">` | Specifies an interactive form input field (`<input>`): `<input type="submit" value="Submit">`. |
| **Line 23** | `</form>` | Closes the `<form>` element. |
| **Line 24** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 25** | `</body>` | Closes the document `<body>` section. |
| **Line 26** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`option-67.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/option-67.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The option element</h1>

<label for="cars">Choose a car:</label>

<select id="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="opel">Opel</option>
  <option value="audi">Audi</option>
</select>
  
</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The option element</h1>` | Defines a **H1** heading element with text: *"The option element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<label for="cars">Choose a car:</label>` | Provides an accessible descriptive label (`<label>`) bound to a form control: `<label for="cars">Choose a car:</label>`. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<select id="cars">` | Opens a dropdown selection menu (`<select>`): `<select id="cars">`. |
| **Line 10** | `<option value="volvo">Volvo</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="volvo">Volvo</option>`. |
| **Line 11** | `<option value="saab">Saab</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="saab">Saab</option>`. |
| **Line 12** | `<option value="opel">Opel</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="opel">Opel</option>`. |
| **Line 13** | `<option value="audi">Audi</option>` | Defines a selectable item within a dropdown menu (`<option>`): `<option value="audi">Audi</option>`. |
| **Line 14** | `</select>` | Closes the dropdown selection menu (`<select>`). |
| **Line 15** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 16** | `</body>` | Closes the document `<body>` section. |
| **Line 17** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`output-68.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/output-68.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The output element</h1>

<form oninput="x.value=parseInt(a.value)+parseInt(b.value)">
<input type="range" id="a" value="50">
+<input type="number" id="b" value="25">
=<output name="x" for="a b"></output>
</form>

<p><strong>Note:</strong> The output element is not supported in Edge 12 (or earlier).</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The output element</h1>` | Defines a **H1** heading element with text: *"The output element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<form oninput="x.value=parseInt(a.value)+parseInt(b.value)">` | Opens a `<form>` container with attributes: `<form oninput="x.value=parseInt(a.value)+parseInt(b.value)">` for user data input and submission. |
| **Line 8** | `<input type="range" id="a" value="50">` | Specifies an interactive form input field (`<input>`): `<input type="range" id="a" value="50">`. |
| **Line 9** | `+<input type="number" id="b" value="25">` | Renders markup / text content: `+<input type="number" id="b" value="25">` |
| **Line 10** | `=<output name="x" for="a b"></output>` | Renders markup / text content: `=<output name="x" for="a b"></output>` |
| **Line 11** | `</form>` | Closes the `<form>` element. |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 13** | `<p><strong>Note:</strong> The output element is not sup...` | Defines a paragraph (`<p>`) element displaying text: *"<strong>Note:</strong> The output element is not supported in Edge 12 (or earlier)."*. |
| **Line 14** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 15** | `</body>` | Closes the document `<body>` section. |
| **Line 16** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`textarea-97.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/textarea-97.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The textarea element</h1>

<form action="/action_page.php">
  <p><label for="w3review">Review of W3Schools:</label></p>
  <textarea id="w3review" name="w3review" rows="4" cols="50">At w3schools.com you will learn how to make a website. They offer free tutorials in all web development technologies.</textarea>
  <br>
  <input type="submit" value="Submit">
</form>

<p>Click the "Submit" button and the form-data will be sent to a page on the 
server called "action_page.php".</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The textarea element</h1>` | Defines a **H1** heading element with text: *"The textarea element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<form action="/action_page.php">` | Opens a `<form>` container with attributes: `<form action="/action_page.php">` for user data input and submission. |
| **Line 8** | `<p><label for="w3review">Review of W3Schools:</label></p>` | Defines a paragraph (`<p>`) element displaying text: *"<label for="w3review">Review of W3Schools:</label>"*. |
| **Line 9** | `<textarea id="w3review" name="w3review" rows="4" cols="...` | Defines a multi-line text input field (`<textarea>`): `<textarea id="w3review" name="w3review" rows="4" cols="50">At w3schools.com you will learn how to make a website. They offer free tutorials in all web development technologies.</textarea>`. |
| **Line 10** | `<br>` | Renders markup / text content: `<br>` |
| **Line 11** | `<input type="submit" value="Submit">` | Specifies an interactive form input field (`<input>`): `<input type="submit" value="Submit">`. |
| **Line 12** | `</form>` | Closes the `<form>` element. |
| **Line 13** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 14** | `<p>Click the "Submit" button and the form-data will be ...` | Renders markup / text content: `<p>Click the "Submit" button and the form-data will be sent to a page on the` |
| **Line 15** | `server called "action_page.php".</p>` | Renders markup / text content: `server called "action_page.php".</p>` |
| **Line 16** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 17** | `</body>` | Closes the document `<body>` section. |
| **Line 18** | `</html>` | Closing root tag that marks the end of the HTML document. |

---


## <a id="7-multimedia-images--graphics"></a>7. Multimedia, Images & Graphics

*Embedded media players, responsive graphics, image maps, vector art, and inline frames.*


### 📄 [`4.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/4.html)

**Source Code:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <address>
Written by <a href="mailto:webmaster@example.com">Jon Doe</a>.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html lang="en">` | Opening root tag of the HTML document with primary language set to `en` for browser rendering and screen readers. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<meta charset="UTF-8">` | Sets the document character encoding to **UTF-8**, ensuring universal support for characters, symbols, and emojis. |
| **Line 5** | `<meta name="viewport" content="width=device-width, init...` | Configures responsive viewport scaling so the page adjusts cleanly across mobile, tablet, and desktop screens. |
| **Line 6** | `<title>Document</title>` | Sets the document title rendered in the browser tab and bookmarks bar: **"Document"**. |
| **Line 7** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 8** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 9** | `<address>` | Renders markup / text content: `<address>` |
| **Line 10** | `Written by <a href="mailto:webmaster@example.com">Jon D...` | Renders markup / text content: `Written by <a href="mailto:webmaster@example.com">Jon Doe</a>.<br>` |
| **Line 11** | `Visit us at:<br>` | Renders markup / text content: `Visit us at:<br>` |
| **Line 12** | `Example.com<br>` | Renders markup / text content: `Example.com<br>` |
| **Line 13** | `Box 564, Disneyland<br>` | Renders markup / text content: `Box 564, Disneyland<br>` |
| **Line 14** | `USA` | Renders markup / text content: `USA` |
| **Line 15** | `</address>` | Renders markup / text content: `</address>` |
| **Line 16** | `</body>` | Closes the document `<body>` section. |
| **Line 17** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`5.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/5.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The map and area elements</h1>

<p>Click on the computer, the phone, or the cup of coffee to go to a new page and read more about the topic:</p>

<img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBwgHBgkIBwgKCgkLDRYPDQwMDRsUFRAWIB0iIiAdHx8kKDQsJCYxJx8fLT0tMTU3Ojo6Iys/RD84QzQ5OjcBCgoKDQwNGg8PGjclHyU3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3N//AABEIAJQA6AMBEQACEQEDEQH/xAAcAAEAAgMBAQEAAAAAAAAAAAAABAUDBgcBAgj/xABIEAABAwMBBAcEBAsFCQEAAAABAAIDBAURIQYSMVETIkFhcYGRBxQyoVKTsdEVFiMzNEJTVWKS8FSCosHSNkNFcnOElOHxJP/EABoBAQACAwEAAAAAAAAAAAAAAAADBAECBQb/xAA1EQACAgECBQEGBAYDAQEAAAAAAQIDEQQSBRMhMVFBFCIyYZHRcYHB8AYVI0KhsTNS4fEk/9oADAMBAAIRAxEAPwDpatHNCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCA+m/C7wQz6HyhgIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCGT1vB3gg9DxDAQBAEAQBAEAwTnAzhDJ7unkmQN13JANx30T6JlDDG47kfQplDDG47kfQplDDG47kfQplDDG47kfQplDDG47kfQplDDG47kfQplDDG47kfQplDDG47kfQplDDPdx30T6IMM83TyKDA3TyTIG6eSZGBunkmRg8QwEAKArrzeqS0RNfUOLnvHUibxd3+CjstVfchuvhUuvc1V+3FbvO6Gmgaw9jsk+qqvUyz2KL4hL0Rb2Xa2mr5mQVjRTTO0ac5Y48s9h8VNXqFJ4aLFOsjZ0fRmyKwXAgCAIAgCAzU5+JYZvEyrU2CAkRnLAVqSrsfSAIAgCAIAgCAIB2FDJGPFbER4hgIAeBWQRDx8VuRBYA1/wDqA1C57KV9xrZaqevg3nnQbpw1vYFUnppylnJz7dHKctzkYG7AVTgD+EIBn+AqP2aXkx/LZP8AuPh2wtUHEe/wnn1CsvSy8mP5fJf3G322Kpgo44ayZs8rBumVoxvAcM96uQTUcNl+uMoxSZKWxuEAQBAEBlp/1lhm8TMtTYICRF8AWpJE+kNggCAIAgCAIAgHNARjxWxCeIAgB4HwQETkpCILAPCMoD1AehxHaUMnnblZMBDIWDAQBAEBDul1oLTTiouVXHTxk4BkOMnkB2+SxKSj3JIVzn8Kya3Ue02wwUlU6jfLUVLWZhifE9gkdy3saeeFXnqa8dGW4aG3d73RfkZPZ/ttU7TVlVR1tJDFLDGJGvhJwRnGCCTr3rFN3MM6jTqtJxZu6nKhIi+ALUkifSGwQBAEAQBAEAQDmgI362MZytiI0faj2k26zTz0VFA+urYXGN41YyN47CSNfJQ2XxgW6tHKfV9EYLD7UrdXzQU1wo5qOeV7Ig5pEke87TJOhAz3Faw1EZdGZs0UorMXk353AqwUyJyUhCFgBAEAQDxWTJX3G92u1EC5V1PTOPBssgDvRaOcV3ZvCqc/hRYLYjCAIAgNM28pRdYqq3Rs6SpbA2aNu8Oqdd3tyMlpHquFrpOGqUn26I9Lw2KlpNqXU41IyRr3RhpMgcWbg163DHqt11Zt0R+idlbBQWO3sFJRsgqJo2OncCS5zsa6nsznRdSEFFdDh3Wysl1fQuluQkiL4AtSSJ9IbBAEAQBAEAQBAOaAg1bpm00xpmh84Y7omOduhz8HAJ5Zwsvt0I136n5fe+R7i6Zz3SEnec/4ie3PeuVJvLyehSS6LsbRs/ZKB93tkFyDzG+cCbD91p7vDOFrVNOa8E19G2ltfFjJ3WrnjoqaSaQ7sEMZe/Tg1o1XXlJQjlnmYwlZNQXdvBBo6+nrYhJA7IGhB4/1otoWRn2NbqZ0PE0SuxbkQWDAQBABxCyDgN2t1fPdK2atqY5KkVD2Svy7UhxBxpw5Li2W5m0z01VP9NOPbC/0d5NRTg4M8Wf+cLsb4+Tzyotf9j+jHvFP+3i/nCb4+TPIt/6P6M+2PY8ZY5rhzacrKafYjlGUXiSwfSGpT19BM+sdPEWdGWdcEak+PLux5rh67Q2SslOHZ9e/7/I9Fw/iFcao1z7rp27/AL9Sn2f2PsQvXv3uruli/KsaZHFm/njgla8NtdlmJPsiXikeVVmC7vqb2u2edCAkRfAFqSRPpDYIAgCAIAgCAIBzQEbOq2ITlW32wtLBUz3qGtkAqJ8yU7mji76J7B4hUNVBQjvR2OH2O2aqkuyPNk7FLd7hDUB8YpqadrpWnGXNHWxjHA4wq2mp5ks+i7nS4hq40wcPWXbH0N027jadnKiYvcx0RbukH4w47paeYIcVe1izS34OPwttamKxnP6dTFsfRMpLHC8avn/KPJ468At9HBQqT89SHilzt1LXouiLtWjnBAEAQAcUMnLtorDUW2tllkZ0lPJKXNncM5yc6/xfcuHfTOuTz2/fQ9NpNTVdBY6Px+Brl1J/CdSGuAJmfj+Yq3pqa5w3SXqyzxTX6qi9QqscUox6J/I+HMb0Tjh+8Bn4grHs9OfhX0Oa+La7vzpfU6j7Pf8AZxn/AFH/AGrGj6Qa+bMfxBJy1MHJ9XCP+jZlbOEVO090baLPLUbrXSEhkbCficf6J8lmNHPzX6NPJNRJwsUl6Gh2naerdtDQSS7scAlDDEzhh2mvM6qWjhFGlrls6yx3f6F/VauzUrEux11VTnhASI/gC1ZJE+kNjQdvfaGdnK4W220sVRWhgfI+UncjzwGBqT3ZCgst2dEWadPzFl9iv2P9qj7lcobdfKKGEzvEcdRT7wYHHQBzSSQDwzk8UhdnozNmmSWYvsdO4aKcqhAEAQBAOaAjHitiE0vbqqopqqGhq6qaIRt3yyODfBzoNd4KlqWm9rKl+o5Vi2zcWvH7/wAFRYrxbbBJNJSy1NSJg1ronRiPgeIO8eaiplGl5Rvbxiy9KNkt2Pkk+v4EjbHaSku1pggoXvH5XflY5uCMDQep+S01WpjZXiJ6nh2hsotc7FjphfmbNbJIaOzUfvEscQ6Jgy9waM4zjVdSpYrRwtU9182vLJkFTT1O97vPFLu/F0bw7HopCu00ZUMH10b8A7jiDyBTKNtrHRyfs3/ylMobX4Pl+WAlw3cDPWCenQw/d7lPeaCK+UnQOqX07GP3g4N3t7APZoo9TpubHambaHXKixzxlYwaDW7G3qetmkbSjdc9zgS8agknmqlPNrjt2ZPT62Wh1U1Zz1F7YrGH6I9pti7s12KmiD4znJbIAW944rNktQ1mMPmUfYtFOeXqvomv9o3XZuOKz2/3OSVzt17iHOaRkEqrpOIVQjtt6PLLPFNJbqrI2VJPEUu/hYLxk8T25bIwjxXThfVNboyTRwZ6a+t4lBnPfaLVvrbnRUNO/eY1hLQOBe44z6D5lXtBqKpVTtXaLxn8slj2SyqUYSXvS64NYrrZXW2Nk9TH0fXwwgg9Ya/5KxptfptVJwqllpG9umtqipTWMncqOb3ikp5hwkia71AK5sliWCm+5m4rUwfTZHY0KwZye9I7xWcGcnINsNmpJdsa2tneQyaWKaMbuWvaGtDmnv6vzXJ1tjrn27o7nDoRtry/Qw2ayW2W9UUbqNoJqWbzmbzcDOhADsDXu7VVqtm7IrPqXb64cubx1wzti7x5lBDIQBAEA5oCMeK2ITmu19dVwX6pawUbmadHvUkErsYGhLmk8c8Sufe3zH1/19jkauycLcYTz8l9iqgr6monZA0UALzu5NDTNB/vbmniqkZ5lj7fY7MuD6qvSq/C3d2tq6L6d16m2XTZ7ZW0RxT1ss1PE9wDAZiQSBnGdSupXw6E37qOl/NtVLOGm/kiq20uthvNhNLTXCETQvbLC05wS3I3fMEhdD2W3GEjnQjNTyzF7N/c4SWOqYPfZ3l4hY3r7rWkYJ9T6clq6JwWZIXNs6DpgAjmNFGVy5tchfSgE5LNFBYveLtLzEkh2SRqtSTJUbRNLYOlbx+Eqal9cFLWrEclFA7QsA0w93+Eq1LGcnKrl6fj/osfJQM6K6DA7QgZ8yRxyjEjGuHeFpZVXYsTWUS13WVS3VywyDNbGk/kH45hwz81ybuERbzW/r9zs0cakli6Ofw+xoO3DBR7QUeX6tiY4n++V3uGaPlaOdXdvP8Aogt1b1FysSwlgzbbuDqGkGnWmyP5SuR/Dcf/ANE0/H6nS4u/6UPm/wBGb9slJ0uy9qc45d7pHk9+6upesWSPOPuWyiMGaFoMb9NQFhm8VlANHu7j254rHqFjZk1fa6SOeha2FpkfG/Jc0fCMa/13KpxCmUqspFzhOqrjqNkpYz9GyBsdR0Ym98meekDyGNfndaeYJVbh2n3LnNduhb4trOXJUZxnqb3nv7MrqHLCAIAgCAc0BGPFbEJzLamS1Nvtayopap0weMubUNaMloI03Vz7Wt7Ryrra67t2Hn5M1uplpnPPu8b42Y1EkgJz44Cpzq9YnqOH/wAR12NV39Pn9zbqO83mutsNI6xiuDG4bPIwjOO8jGcDmrdGq1Cwowzgsarh+ilmTt2p9emCXT0F0lG8+zW6Lue8Z+TV0I6jVPvFL8zkT0eij0V0n+X/AKXFutfQhss0NPFOCcCFnAeOPFTq2xxxIq2UwUvck8fMtPkqtmpjCW1ot16WU47kSqGpFK52+CWu5f14qCeqhL0J69NOHdk78JRdkb/Rae0RJuSyLXVFPXQGGQSNBIORxW0NUovJHbpObDayAyipG5LXzE4IwQO0YUr16fRoqLhWOqkeq0VwgCAkUMDaiYscXABudCtZywiWqCm+pCumwtvulY6qqaip3nADdDhgAclUnDfLczWzh9djy2yti2ZpbvVTUVVJK1lK7qFmMnsXL0VbV1kU8YO7xWmN+nqy3+0ZNlpWwOuFmD3P/B1Q5kZdxMZOnpgj0XXonlNM85Q1Fyq77WXynLBngPUk5rDN4vCKu61RETYIzgO6zu8clNXDrllLU2tRUEVPgpyhg+oo3SyMijGXOcAARosZUVkyoucserNktlHVwROjn3C0fAQ7OO5VLLIyeUdjT02wjtmTPd393qo9yLGxkeaeCB5ZNUQsdjOHSAH5puRo2o9GzH77R/2un+tb96zuXkxvj5HvtH/a6f61v3puXkb4+R77Sa4qqf65v3puXkb4+SMaylz+lU/1rfvW25eSJyicz20v1wpdo54qG5VTINxhaIap4bw1wGnCs1aCu+O9yZryd7c1Nr8GUTtpby4AG6Vx/wC6k/1KT+VVf9n9TK0zX98vqdT2Mubrns3TTPkc6ZgMcpLsneB4lQXVcqWz0N8YLEk54rBCO3KwF0JFAxslUxrhka/Yo7IRxnBNTKSljJWXmuZarfVVkhO7CxzgOZ4AeuFnZDHYwpzcu7+pxaS73Nz3PNzrwXHJDaqQAeABWm2PguZfkC83X97XL/zJP9SbY+Bl+S0t22N4pHATVDqmPtEztf5hr65Wy2r0X0RBZS59pNP8X9zsCkKoQBATbR+kOP8AAR8wo7OxPQ/ewW+ThQlspLTJG6/XHo3A5xjxHH5lc/TuPtNmPkdDUqXstefmaJQ1nuntDr2kndmqJYyPPI+xWaXi1nj1Zs1015N46fXRpXQ2nR3HnTYB6p8im0bsrBqNzvhZc6oOiBijeWjBwdND8wVzHxV1WuDXup4/f5nTnwSN1CujJqTWfJNgkEzctXbhJTSkux5iyEq5Ykmn81guNnoekry88Im549p0+9RXyxHBZ0EN1mX6Gzv0bkcVUR2Wej4clYBwvauu/CW0NdVDBZ0hY0ka4boFTk9zZ5TW28y6TKnyHotcFQeXyTojPQvrJY6e5UDp5JXxvEhYN0DHAferlGmhbXuz1J4VqUcszv2Qfru1bMfxM/8AakegfozPI+ZrF/oHW24e7vfvno2u3mjA1yu1oa3XThnc0K20JPyVZdh7RwBB1Vrd720t5N69mFz6Cvqrc8kioZ0kYz+s3j8j8lT1kMpSNLPJ0Jc8gCGCVbP0xnn9i1n8JLT8aOb+1O6YMFqjJJJ6eYDlkhg9cnyR+hJTHu2apftm6yzUVDVVOralv5QAfmn8d0+WPPK1awSRnueDJaLJJdYS6ippah0bQZRGfhyq8pWp9EULbdVGbwuhM/FKuP8Aw6q+Sxm7wRe06rwdZV0nCA80WQahtVtFW2y7RxWyfonxRESEAHO8Qca+AVHUWvdtRR1OqnVNKDwVR212gIIdcdCMfm2/cqznJruQR4lqU85MEG1F1pXl1NMyJ5GC5rQT88qGqqNUnKOclvU8e1d8FBtJfJEGKumku8ddO/fmdMJHu06xzqpov3snLjbKVu+T65OtA5Hjqusux3jzw49iDJom1r4KC5viijcXyjpc7+mSTlcfVaWtWNp9y0/4hv0iVe1PCRGo71s5Tw//AK5681Om8KZmA3mMnC2hw6uKUoyefl/4X4cWt1EFzK1j6r/JbWX2gbPWeOQQU9yf0rt4mTdJ4eKs1afl5w28+TS7Uc3GVjHgsx7WLKNPc630b96m2MhyiPcvarbZLdUx0dLViodE4RF4bgOI0zqigxlHMKCod+akcXciTqob6kusTicR0vTmwX4/cm8OKq+pxiLVSuEhY04A4rucN0sXXzZLLfY7fDtPDl8yS6syWy61dsnE1PI4tBy6Iu6rvELrSrjJdjoTpjNYwdRjc18bJGfC9ocPAjK5zRxWsPBoO3Ld2+Ndgawsx6uVzT/AdTRf8f5/YpOi36NzmjLmu3gOfNUdRqOVq4eMf7ILr+Vq4p9vuZrRWut90paxn+6kDvFp0I9CQunOKnBx8nQksrB2xj2yNa9h3muG80jtB4Li4x0Kx9LBglW39MZ5/YtZ/CS0/Gcx2fon7R7XV94rWE09NUHAOgLxo1o8AAViPvdSWb5ccG9XSghudBPR1P5uUbu92g9h8it2ivGWHk1PYKEbOQ3+W5gxOilhpS/s6x0cO7UHwKiaxJFtvdDobrz7dFMU30PVgwEB44gNJPDtRtJdTKTbSRr74WVtaT0bCXu4loOnP0XlN1mq1Huvu/3/AIPXOnT6XTZnFPC8L99y5ZRUjGBopoSAMZMYXqIVQhFRS7HkZtWScmu5Audtj/PRwRhv6zQweq5HEtLL/mr7eq/U7XCr6X/Qsis+jwvoYaSstcckFDVNpm1EziIWGMZfjy/rRS8Mt5tbjNdV6kXFtHCuxTglh+n6/v8AUvcrqnJCA577QH7l3jcc4FO37SqOqzvOTrlm1JGjVQBmc9pJB1UtMk44Ovobd1Sh6oxAOOoClckl1ZalZCHVtI+ujLWZe7HILRWKTxEijqY2S21rPl+iMWMOAUjeFlk7aSy+x9glrg5p1BWGk0Ye2ccejLNlUxzQXZyOPcufODhLB5nUaaVVjiu3oYZy2R+8zOvNdPRa6NNfLs9C7o9Sqq9lh8wxxSTMbO8tiJ65aMnCuvidGOmS3LXV46G+M2utLGta0VIa0YA6IaD1VP2utvonk5udz/E1DaC5G63N87QRGOpGCMHdHafXK7NUXGODtUV8uCRggmZHGGuznwXnNfYrb249uiOJrXzbW49uxhmj3HYHwnh4LuaC/m0pvuujOvo7ubUn6rudV2GuHv8As9AHOzJT/kneXD5YVXUw2WP5mZrEi0uzq9tC/wDBUMctWdGCR2Gt5k/coq9u73uxqsZ6lfstTbUi+08t3qqV1IGu3oonak4ONN3h5rbUOhw9zOSzVKG7ESzt9J7lRx05wXNyXEDALidSoYqMViPYhtm7JuTJKyRlJt7QT1exk7KSIySunY57WjrOa3sHPGToo5dZFqppR6jZC4SXCwUslS4GpjHRy65JxoCfEYKzXNTWUyO+qVcsSRdrchCA0j2oXMw0FPbonYfO8SyY4hrTkf4sHyWJdsE9K67jN7OH3CooZ6mtIdCCGQPf8bscdeX3KCnTVVzc4rGSfU6q2yCrk846m4qwUhx0QLuce2xtNwtd5dPUyvkZK7egqRpwOg7iOXmo41xrW2Kwi5zec90nlnQ9j782+2pr5CBWQ9Sdo7T9Idx+3KkTK1kdrL5CM577QADeIs/sG/aVR1PxnJ17xYvwNXEMf0VXyUt8jx8cLGF7m9UcUWW8IkrVlklGPdlZK/fkyBhn6oHYuhCG1YPT0UqmG36sm0lKGt35tSewdiq3W7ntXY4+v1jnLl19l/kx11OGjpYxj6QW9Fn9rJuG6vP9GX5fYw0jmdKA/wCE6KS+GVkta+l2Vbo90WPQR9oVLJ53fIdBH9FMjfIwVQZGA1g6x+S6vDNPvlzZdkdTh1Lm3ZLsjymg3uu4dXsCs8S1fLXKj3ff8CfiGq5a5ce7/wAEjoI+S4OTh75FnHavftna6oibmeje2TA7WY6w9NfJdThdmybXk7HDJdJEz2a3D3e7zULz1aqPLNdN9v3je9F1dZWnBPwdO1HS+Gi5hASbZ+mM8/sWs/hJKfjRHf8AG7xK2XYjZ4hgrtrai+wW+ip7BbpamWZri6Zgz0Woxx0yc9umi3ojU5Sdjwi0o5jEhbJ7JVdmD6msMslZO3EgbktaOPme9ZstrwoQWIoxdKy15kv34L1Rlc+ekYASXtwOOSmRg5NcBNtbtk6GmcRGZNxrjwbE3Qu+31C17llYhE6tSU0NHTRU1MzchiaGsbyC2KzeTKgPUBFuNvp7nRSUlYwPhkHmDzHencJtPKOX5qthtpRvP6WAjJLT+diJ5fS8e0ctVjsyz0nE6tBLHPDHNAd6KVjXsdzBGR9qyVvXBoPtAIbd43HgIG/aVR1PxnI1ybtSXg1fp4/pfJV8FPlyJlsq6SKpa6rp46unILXxPHYe0d605zpmpY6HoOB6Oq5y3TxZ/b9/n+ncwXKktsFeX26aV1IQCxsrTlruXfhWZauNixA24p7Vp48uUej9fJiE8f0vkocM87y5DpojoTkdowUWV2MwjNSyi0skmz1LSPNXbp6qpcCN8vG6OWOXjgqSWtjBbZReT1mh089fS5uSj6P7kF74wSR1W9gc7UKhzZt9ImZ8C4dGO6V+PzRhfURtaS12T4KzDc/iWDz2p0tMbVCme6L9X0IvSRSnfc8Md+sCu3Xq5UVbEso7M/6FP9NZwSemiYMB2g7iuPKUptyl1bPOS5k5OUu7Peni+l8ljBpskbz7PQHU1bkZa5zQQeWCrej6JnT4f8MvxNTuFJLs3tQ0RNO7BK2WHTiwnh6ZC9ArI2Ve8zsJqUTpFTtJZKUfl7lTMcRnc6QF3oNVysoh2SfoWOy92orvN01vkfJEx26XuiewE47N4DPktJ/Cb1xasWTK/wCN3it12ImfKyYJle90cjI2PcAxgGATqo4JYbZNa3F4T9CN0sn7R5/vLfC8Ee5+T6fTCRpZIGuY4EOB7QsZM7WaRU+zOGWoc+G6SxwEkthLN4t7t7PDyWMkqmWux2yb9n46jp5oZp5nAdLG0jDB2a9+T6ckTNZtyNj6B3MLOTTax0DuYTI2sdA7mEyNrMNXTVT6Z7aOWGOc/A+Vhe0eIBCZCj5NZtuxU8lzqLltJUwV08mAyNjTuNAxg4I7uCxkkb6YibZ0B5juCzkj2sorls064X6mrZ/d5KSOPcfE/JLtD2YxxI7VBKvdYpPsVp6ZzuU32RK/Fez/ALtpPq1Jsh4JfZ4eEBsxaAdLbSfVrDrrfoZVMV2RTV+wrXVfvFvmgY3Ofd5495nh4eSpS0WJ76ng6/tsLaeVqYbl59f/AKW8Wy9rMbTNbaLpN0b25H1c92VdUI4WUciWnqy9q6H1+K9oHC20n1azsh4Mezw8I9/Fi0Yx+DqT6tNkPBnkxxhdjz8V7R+7qT6tNkPBjkQ8IfixaP3bR/Vpsh4HIh/1RUbQbBUVyhb7h0NDOw6FkfVcO8f5rOETw93p6Gax7JCCndFeKS1VD2/BLFEd5w/iyFrsh4Ip0Vvsix/Fez9ttpPq1nZDwa+zw8GDZ3Z+a0PrN6SExzSb0bWA9UZOAfktKYOtv5kdGnlW5Z9WYtrdmJb9T04p6qOmnifq9zC4FhGox447ezvUrZcg9pFtvs8tFL0b6kOq5WjrGRxDXHnuosIOc2bbb4m0kke61rY2DDWRjACxLqsGIe7LLPh0Li4nI1K2yabWGwkOBOMZGUbG3qZKppmndI3AB4Z8FiPRYNprdJsxdC7mFnJrtZnWpuEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAeID1AEAQBAEAQBAEAQH/2Q==" alt="Workplace" usemap="#workmap" width="400" height="379">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
</map>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The map and area elements</h1>` | Defines a **H1** heading element with text: *"The map and area elements"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Click on the computer, the phone, or the cup of coff...` | Defines a paragraph (`<p>`) element displaying text: *"Click on the computer, the phone, or the cup of coffee to go to a new page and read more about the topic:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<img src="data:image/jpeg;base64,/9...[base64 image data truncated]...width="400" height="379">` | Embeds an image using inline Base64 data URI along with attributes `usemap` linking to the `<map>` definition and dimensions. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `<map name="workmap">` | Defines an image map linking clickable areas (`<map>`): `<map name="workmap">`. |
| **Line 12** | `<area shape="rect" coords="34,44,270,350" alt="Computer...` | Defines a clickable hotspot shape, coordinates, and hyperlink target (`<area>`): `<area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">`. |
| **Line 13** | `<area shape="rect" coords="290,172,333,250" alt="Phone"...` | Defines a clickable hotspot shape, coordinates, and hyperlink target (`<area>`): `<area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">`. |
| **Line 14** | `<area shape="circle" coords="337,300,44" alt="Cup of co...` | Defines a clickable hotspot shape, coordinates, and hyperlink target (`<area>`): `<area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">`. |
| **Line 15** | `</map>` | Closes the `<map>` element. |
| **Line 16** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 17** | `</body>` | Closes the document `<body>` section. |
| **Line 18** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`audio8.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/audio8.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The audio element</h1>

<p>Click on the play button to play a sound:</p>

<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The audio element</h1>` | Defines a **H1** heading element with text: *"The audio element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Click on the play button to play a sound:</p>` | Defines a paragraph (`<p>`) element displaying text: *"Click on the play button to play a sound:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<audio controls>` | Embeds an audio player with playback attributes: `<audio controls>`. |
| **Line 10** | `<source src="horse.ogg" type="audio/ogg">` | Specifies an alternative media source and MIME type (`<source>`): `<source src="horse.ogg" type="audio/ogg">`. |
| **Line 11** | `<source src="horse.mp3" type="audio/mpeg">` | Specifies an alternative media source and MIME type (`<source>`): `<source src="horse.mp3" type="audio/mpeg">`. |
| **Line 12** | `Your browser does not support the audio element.` | Renders markup / text content: `Your browser does not support the audio element.` |
| **Line 13** | `</audio>` | Closes the `<audio>` player element. |
| **Line 14** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 15** | `</body>` | Closes the document `<body>` section. |
| **Line 16** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`canvas-17.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/canvas-17.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>
<h1>HTML5 Canvas</h1>

<canvas id="myCanvas" width="300" height="150" style="border:1px solid grey"></canvas>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `<h1>HTML5 Canvas</h1>` | Defines a **H1** heading element with text: *"HTML5 Canvas"*. |
| **Line 5** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 6** | `<canvas id="myCanvas" width="300" height="150" style="b...` | Creates an HTML5 drawing canvas surface for dynamic graphics via JavaScript (`<canvas>`): `<canvas id="myCanvas" width="300" height="150" style="border:1px solid grey"></canvas>`. |
| **Line 7** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 8** | `</body>` | Closes the document `<body>` section. |
| **Line 9** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`embed-34.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/embed-34.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The embed element</h1>

<embed type="image/jpg" src="https://www.bing.com/th/id/OIP.fV-OZpn6Jtc6NUpSIqRwxQHaE7?w=193&h=135&c=8&rs=1&qlt=90&o=6&dpr=1.3&pid=ImgAns&rm=2" width="300" height="200">

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The embed element</h1>` | Defines a **H1** heading element with text: *"The embed element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<embed type="image/jpg" src="https://www.bing.com/th/id...` | Renders markup / text content: `<embed type="image/jpg" src="https://www.bing.com/th/id/OIP.fV-OZpn6Jtc6NUpSIqRw` |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`figcaption-36.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/figcaption-36.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The figure and figcaption element</h1>

<figure>
  <img src="https://www.bing.com/th/id/OIP.HyPO0GQqnsGoMcauAHz_MQHaE7?w=193&h=135&c=8&rs=1&qlt=90&o=6&dpr=1.3&pid=ImgAns&rm=2" alt="Trulli" style="width:100%">
  <figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>
</figure>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The figure and figcaption element</h1>` | Defines a **H1** heading element with text: *"The figure and figcaption element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<figure>` | Renders markup / text content: `<figure>` |
| **Line 8** | `<img src="https://www.bing.com/th/id/OIP.HyPO0GQqnsGoMc...` | Renders markup / text content: `<img src="https://www.bing.com/th/id/OIP.HyPO0GQqnsGoMcauAHz_MQHaE7?w=193&h=135&` |
| **Line 9** | `<figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>` | Renders markup / text content: `<figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>` |
| **Line 10** | `</figure>` | Renders markup / text content: `</figure>` |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `</body>` | Closes the document `<body>` section. |
| **Line 13** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`figure-37.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/figure-37.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The figure and figcaption element</h1>

<figure>
  <img src="https://www.bing.com/th/id/OIP.HyPO0GQqnsGoMcauAHz_MQHaE7?w=193&h=135&c=8&rs=1&qlt=90&o=6&dpr=1.3&pid=ImgAns&rm=2" alt="Trulli" style="width:100%">
  <figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>
</figure>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The figure and figcaption element</h1>` | Defines a **H1** heading element with text: *"The figure and figcaption element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<figure>` | Renders markup / text content: `<figure>` |
| **Line 8** | `<img src="https://www.bing.com/th/id/OIP.HyPO0GQqnsGoMc...` | Renders markup / text content: `<img src="https://www.bing.com/th/id/OIP.HyPO0GQqnsGoMcauAHz_MQHaE7?w=193&h=135&` |
| **Line 9** | `<figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>` | Renders markup / text content: `<figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>` |
| **Line 10** | `</figure>` | Renders markup / text content: `</figure>` |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `</body>` | Closes the document `<body>` section. |
| **Line 13** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`iframe-47.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/iframe-47.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The iframe element</h1>

<iframe src="https://www.w3schools.com" title="W3Schools Free Online Web Tutorials">
</iframe>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The iframe element</h1>` | Defines a **H1** heading element with text: *"The iframe element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<iframe src="https://www.w3schools.com" title="W3School...` | Renders markup / text content: `<iframe src="https://www.w3schools.com" title="W3Schools Free Online Web Tutoria` |
| **Line 8** | `</iframe>` | Renders markup / text content: `</iframe>` |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`img-48.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/img-48.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The img element</h1>

<img src="https://www.bing.com/th/id/OIP.fw03Y9du809equXr34YdyQHaLH?w=193&h=290&c=8&rs=1&qlt=90&o=6&dpr=1.3&pid=ImgAns&rm=2
" alt="Girl in a jacket" width="500" height="600">

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The img element</h1>` | Defines a **H1** heading element with text: *"The img element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<img src="https://www.bing.com/th/id/OIP.fw03Y9du809equ...` | Renders markup / text content: `<img src="https://www.bing.com/th/id/OIP.fw03Y9du809equXr34YdyQHaLH?w=193&h=290&` |
| **Line 8** | `" alt="Girl in a jacket" width="500" height="600">` | Renders markup / text content: `" alt="Girl in a jacket" width="500" height="600">` |
| **Line 9** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 10** | `</body>` | Closes the document `<body>` section. |
| **Line 11** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`map-57.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/map-57.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The map and area elements</h1>

<p>Click on the computer, the phone, or the cup of coffee to go to a new page and read more about the topic:</p>

<img src="https://img.freepik.com/premium-photo/modern-office-design-with-flexible-workspaces-bright-colors-visualization-flexible-workspace-that-can-easily-transition-inperson-virtual-collaboration_538213-79473.jpg" alt="Workplace" usemap="#workmap" width="700" height="400">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
</map>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The map and area elements</h1>` | Defines a **H1** heading element with text: *"The map and area elements"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Click on the computer, the phone, or the cup of coff...` | Defines a paragraph (`<p>`) element displaying text: *"Click on the computer, the phone, or the cup of coffee to go to a new page and read more about the topic:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<img src="https://img.freepik.com/premium-photo/modern-...` | Renders markup / text content: `<img src="https://img.freepik.com/premium-photo/modern-office-design-with-flexib` |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `<map name="workmap">` | Defines an image map linking clickable areas (`<map>`): `<map name="workmap">`. |
| **Line 12** | `<area shape="rect" coords="34,44,270,350" alt="Computer...` | Defines a clickable hotspot shape, coordinates, and hyperlink target (`<area>`): `<area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">`. |
| **Line 13** | `<area shape="rect" coords="290,172,333,250" alt="Phone"...` | Defines a clickable hotspot shape, coordinates, and hyperlink target (`<area>`): `<area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">`. |
| **Line 14** | `<area shape="circle" coords="337,300,44" alt="Cup of co...` | Defines a clickable hotspot shape, coordinates, and hyperlink target (`<area>`): `<area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">`. |
| **Line 15** | `</map>` | Closes the `<map>` element. |
| **Line 16** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 17** | `</body>` | Closes the document `<body>` section. |
| **Line 18** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`object-64.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/object-64.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The object element</h1>

<object data="https://wallpaperaccess.com/full/2056415.jpg" width="300" height="200"></object>
 
</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The object element</h1>` | Defines a **H1** heading element with text: *"The object element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<object data="https://wallpaperaccess.com/full/2056415....` | Renders markup / text content: `<object data="https://wallpaperaccess.com/full/2056415.jpg" width="300" height="` |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `</body>` | Closes the document `<body>` section. |
| **Line 10** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`param-70.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/param-70.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The param element</h1>

<object data="horse.wav">
<param name="autoplay" value="true">
</object>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The param element</h1>` | Defines a **H1** heading element with text: *"The param element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<object data="horse.wav">` | Renders markup / text content: `<object data="horse.wav">` |
| **Line 8** | `<param name="autoplay" value="true">` | Renders markup / text content: `<param name="autoplay" value="true">` |
| **Line 9** | `</object>` | Renders markup / text content: `</object>` |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `</body>` | Closes the document `<body>` section. |
| **Line 12** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`source-85.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/source-85.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The source element</h1>

<p>Click on the play button to play a sound:</p>

<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The source element</h1>` | Defines a **H1** heading element with text: *"The source element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>Click on the play button to play a sound:</p>` | Defines a paragraph (`<p>`) element displaying text: *"Click on the play button to play a sound:"*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<audio controls>` | Embeds an audio player with playback attributes: `<audio controls>`. |
| **Line 10** | `<source src="horse.ogg" type="audio/ogg">` | Specifies an alternative media source and MIME type (`<source>`): `<source src="horse.ogg" type="audio/ogg">`. |
| **Line 11** | `<source src="horse.mp3" type="audio/mpeg">` | Specifies an alternative media source and MIME type (`<source>`): `<source src="horse.mp3" type="audio/mpeg">`. |
| **Line 12** | `Your browser does not support the audio element.` | Renders markup / text content: `Your browser does not support the audio element.` |
| **Line 13** | `</audio>` | Closes the `<audio>` player element. |
| **Line 14** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 15** | `</body>` | Closes the document `<body>` section. |
| **Line 16** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`track-104.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/track-104.html)

**Source Code:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <video width="320" height="240" controls>
  <source src="forrest_gump.mp4" type="video/mp4">
  <source src="forrest_gump.ogg" type="video/ogg">
  <track src="fgsubtitles_en.vtt" kind="subtitles" srclang="en" label="English">
  <track src="fgsubtitles_no.vtt" kind="subtitles" srclang="no" label="Norwegian">
</video>
</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html lang="en">` | Opening root tag of the HTML document with primary language set to `en` for browser rendering and screen readers. |
| **Line 3** | `<head>` | Opens the metadata container section holding title, character sets, viewport settings, scripts, and stylesheets. |
| **Line 4** | `<meta charset="UTF-8">` | Sets the document character encoding to **UTF-8**, ensuring universal support for characters, symbols, and emojis. |
| **Line 5** | `<meta name="viewport" content="width=device-width, init...` | Configures responsive viewport scaling so the page adjusts cleanly across mobile, tablet, and desktop screens. |
| **Line 6** | `<title>Document</title>` | Sets the document title rendered in the browser tab and bookmarks bar: **"Document"**. |
| **Line 7** | `</head>` | Closes the document `<head>` metadata container section. |
| **Line 8** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 9** | `<video width="320" height="240" controls>` | Embeds a video player with playback controls and dimensions: `<video width="320" height="240" controls>`. |
| **Line 10** | `<source src="forrest_gump.mp4" type="video/mp4">` | Specifies an alternative media source and MIME type (`<source>`): `<source src="forrest_gump.mp4" type="video/mp4">`. |
| **Line 11** | `<source src="forrest_gump.ogg" type="video/ogg">` | Specifies an alternative media source and MIME type (`<source>`): `<source src="forrest_gump.ogg" type="video/ogg">`. |
| **Line 12** | `<track src="fgsubtitles_en.vtt" kind="subtitles" srclan...` | Renders markup / text content: `<track src="fgsubtitles_en.vtt" kind="subtitles" srclang="en" label="English">` |
| **Line 13** | `<track src="fgsubtitles_no.vtt" kind="subtitles" srclan...` | Renders markup / text content: `<track src="fgsubtitles_no.vtt" kind="subtitles" srclang="no" label="Norwegian">` |
| **Line 14** | `</video>` | Closes the `<video>` player element. |
| **Line 15** | `</body>` | Closes the document `<body>` section. |
| **Line 16** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`video-108.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/video-108.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The video element</h1>

<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The video element</h1>` | Defines a **H1** heading element with text: *"The video element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<video width="320" height="240" controls>` | Embeds a video player with playback controls and dimensions: `<video width="320" height="240" controls>`. |
| **Line 8** | `<source src="movie.mp4" type="video/mp4">` | Specifies an alternative media source and MIME type (`<source>`): `<source src="movie.mp4" type="video/mp4">`. |
| **Line 9** | `<source src="movie.ogg" type="video/ogg">` | Specifies an alternative media source and MIME type (`<source>`): `<source src="movie.ogg" type="video/ogg">`. |
| **Line 10** | `Your browser does not support the video tag.` | Renders markup / text content: `Your browser does not support the video tag.` |
| **Line 11** | `</video>` | Closes the `<video>` player element. |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 13** | `</body>` | Closes the document `<body>` section. |
| **Line 14** | `</html>` | Closing root tag that marks the end of the HTML document. |

---


## <a id="8-interactive-dialogs--disclosures"></a>8. Interactive Dialogs & Disclosures

*Collapsible widgets, popups, and user interaction components.*


### 📄 [`details-27.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/details-27.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The details element</h1>

<details>
  <summary>Epcot Center</summary>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</details>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The details element</h1>` | Defines a **H1** heading element with text: *"The details element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<details>` | Opens an expandable/collapsible disclosure widget (`<details>`). |
| **Line 8** | `<summary>Epcot Center</summary>` | Defines the visible clickable summary label for `<details>`: `<summary>Epcot Center</summary>`. |
| **Line 9** | `<p>Epcot is a theme park at Walt Disney World Resort fe...` | Defines a paragraph (`<p>`) element displaying text: *"Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events."*. |
| **Line 10** | `</details>` | Closes the `<details>` disclosure widget. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `</body>` | Closes the document `<body>` section. |
| **Line 13** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`dialog-29.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/dialog-29.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The dialog element</h1>

<p>This is some text.</p>

<p>This is some text.</p>

<dialog open>This is an open dialog window</dialog>

<p>This is some text.</p>

<p>This is some text.</p>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The dialog element</h1>` | Defines a **H1** heading element with text: *"The dialog element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<p>This is some text.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is some text."*. |
| **Line 8** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 9** | `<p>This is some text.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is some text."*. |
| **Line 10** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 11** | `<dialog open>This is an open dialog window</dialog>` | Defines a modal or popup dialog box (`<dialog>`): `<dialog open>This is an open dialog window</dialog>`. |
| **Line 12** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 13** | `<p>This is some text.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is some text."*. |
| **Line 14** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 15** | `<p>This is some text.</p>` | Defines a paragraph (`<p>`) element displaying text: *"This is some text."*. |
| **Line 16** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 17** | `</body>` | Closes the document `<body>` section. |
| **Line 18** | `</html>` | Closing root tag that marks the end of the HTML document. |

---

### 📄 [`summary-90.html`](file:///c:/Users/vallu/OneDrive/Desktop/Full stack projects/Apna College/Html/summary-90.html)

**Source Code:**
```html
<!DOCTYPE html>
<html>
<body>

<h1>The summary element</h1>

<details>
  <summary>Epcot Center</summary>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</details>

</body>
</html>
```

**Line-by-Line Explanation:**

| Line # | Code | Explanation |
| :--- | :--- | :--- |
| **Line 1** | `<!DOCTYPE html>` | Declares the document type and tells the web browser that this document follows the modern **HTML5** standard. |
| **Line 2** | `<html>` | Opening root tag encapsulating all HTML elements and content on the page. |
| **Line 3** | `<body>` | Opens the document body section containing all visible content (headings, paragraphs, media, forms) rendered on screen. |
| **Line 4** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 5** | `<h1>The summary element</h1>` | Defines a **H1** heading element with text: *"The summary element"*. |
| **Line 6** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 7** | `<details>` | Opens an expandable/collapsible disclosure widget (`<details>`). |
| **Line 8** | `<summary>Epcot Center</summary>` | Defines the visible clickable summary label for `<details>`: `<summary>Epcot Center</summary>`. |
| **Line 9** | `<p>Epcot is a theme park at Walt Disney World Resort fe...` | Defines a paragraph (`<p>`) element displaying text: *"Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events."*. |
| **Line 10** | `</details>` | Closes the `<details>` disclosure widget. |
| **Line 11** | `` | Empty line for readability and clear separation of code blocks. |
| **Line 12** | `</body>` | Closes the document `<body>` section. |
| **Line 13** | `</html>` | Closing root tag that marks the end of the HTML document. |

---
