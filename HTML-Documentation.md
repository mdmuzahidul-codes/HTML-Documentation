# 🌐 Introduction to HTML

## 📌 What is HTML?
**HTML (HyperText Markup Language)** is the standard markup language used to create web pages.  
It defines the **structure** of a webpage and is the backbone of web development.  

💡 *HTML was invented by **Tim Berners-Lee**, the father of the World Wide Web (WWW).*  

---

## ✨ Key Points
- 📝 **HTML stands for HyperText Markup Language**  
- 📄 It is the **standard markup language** for creating web pages  
- 🏗️ HTML **describes the structure** of a web page  
- 🔖 It consists of a **series of elements**  
- 🌍 HTML elements tell the browser **how to display the content**  
- 👨‍💻 **Invented by Tim Berners-Lee in 1991**  

---

# 🌐 HTML Elements

## Definition
An **HTML element** is a building block of a webpage.  
It consists of a **start tag**, **content**, and an **end tag**.  
Some elements are **self-closing**, meaning they don’t have content.

## Syntax
```html
<tagname>Content goes here</tagname>
```
# 🌐 HTML Attributes

## 📌 What is an Attribute in HTML?
An **HTML attribute** is additional information that provides more details about an HTML element.  
- Attributes are always **specified in the start tag** of an element.  
- They usually come in **name/value pairs** like: name="value"

---

## 🔗 Example: `href` Attribute
The `<a>` tag defines a **hyperlink**.  
The `href` attribute specifies the **URL of the page** the link goes to.

```html
<a href="https://www.example.com">Visit Example</a>
```

# 🌐 HTML Paths

## 📌 What is a Path in HTML?
A **path** tells the browser **where to find a file**, like an image, CSS, or another page.  
There are two types of paths in HTML:

---

## 1. Absolute Path
An **absolute path** specifies the **full URL** or **full location** of a file.  
It always starts from the root or includes the domain name.

### Example
```html
<img src="https://www.example.com/images/logo.png" alt="Logo">
```

## 2. Relative Path
A **relative path** specifies the location of a file **relative to the current HTML file**.  
It does **not** include the full URL. The browser looks for the file starting from the location of the current page.

### Example
```html
<img src="images/logo.png" alt="Logo">
```
# 🌐 HTML Headings

## 📌 What are Headings?
Headings in HTML are used to define **titles and subtitles** on a webpage.  
They range from `<h1>` to `<h6>`, where `<h1>` is the **largest and most important**, and `<h6>` is the **smallest**.

---

## ✅ Headings Examples

### Example: `<h1>` to `<h6>`
```html
<h1>This is Heading 1</h1>
<h2>This is Heading 2</h2>
<h3>This is Heading 3</h3>
<h4>This is Heading 4</h4>
<h5>This is Heading 5</h5>
<h6>This is Heading 6</h6>
```
# 🌐 HTML Paragraph, Preformatted,Line break and Horizontal Rule Elements

---

## 1. Paragraph (`<p>`)

The `<p>` element defines a **paragraph** in HTML.  

### Example
```html
<p>This is a paragraph of text.</p>
```

# 🌐 HTML `<pre>` Elements

---

## 2. Preformatted Text (`<pre>`)

The `<pre>` element defines **preformatted text**.  
Text inside `<pre>` **preserves spaces, line breaks, and indentation**.

### Example
```html
<pre>
  This is preformatted text.
      It preserves spaces and line breaks.
</pre>
```
# 🌐 HTML `<hr>` Element

---
## 3. Horizontal Line (`<hr>`)

The `<hr>` element defines a **horizontal line** (divider) in an HTML page.  
It is a **self-closing tag** and does not require an end tag.

---

## Example
```html
<hr>
```
# 🌐 HTML `<br>` Element

---
## 4. Line Break (`<br>`)

The `<br>` element defines a **line break** in HTML.  
- It is a **self-closing tag** and does not require an end tag.  
- Used to **start a new line** without creating a new paragraph.

---

## Example
```html
<p>This is line one.<br>This is line two.</p>
```
# 🌐 HTML Text Formatting Tags

HTML provides several tags to format text in different ways.

| Tag       | Meaning             |
|-----------|-------------------|
| `<b>`     | Bold text          |
| `<strong>`| Important text     |
| `<i>`     | Italic text        |
| `<em>`    | Emphasized text    |
| `<mark>`  | Marked/Highlighted text |
| `<small>` | Smaller text       |
| `<del>`   | Deleted text       |
| `<ins>`   | Inserted text      |
| `<sub>`   | Subscript text     |
| `<sup>`   | Superscript text   |

---

## Examples

### Bold Text
```html
<p>This is <b>bold</b> text.</p>
```
### Important Text
```html
<p>This is <strong>important</strong> text.</p>
```
### Italic Text
```html
<p>This is <i>italic</i> text.</p>
```
### Emphasized Text
```html
<p>This is <em>emphasized</em> text.</p>
```
### Marked/Highlighted Text
```html
<p>This is <mark>highlighted</mark> text.</p>
```
### Smaller Text
```html
<p>This is <small>smaller</small> text.</p>
```
### Deleted Text
```html
<p>This is <del>deleted</del> text.</p>
```
### Inserted Text
```html
<p>This is <ins>inserted</ins> text.</p>
```
### Subscript Text
```html
<p>H<sub>2</sub>O is water.</p>
```
### Superscript Text
```html
<p>2<sup>5</sup> = 32</p>
```
### Subscript Text
```html
<p>H<sub>2</sub>O is water.</p>
```
### Underline Text
```html
<p><u>My name is Muzahid.</u></p>
```

# 🌐 HTML Quotations

HTML provides tags to define quotations and cited text.

---

## 1. Blockquote (`<blockquote>`)

The `<blockquote>` element is used for **long quotations**.  
It usually displays as an **indented block**.

### Example
```html
<blockquote>
  "The only limit to our realization of tomorrow is our doubts of today."
</blockquote>
```
# 🌐 HTML `<q>` Element

---
## 2. Inline Quotations (`<q>`)

The `<q>` element is used for **short, inline quotations**.  
Browsers usually add **quotation marks automatically** around the content.

---

## Example
```html
<p>Albert Einstein said, <q>Imagination is more important than knowledge.</q></p>
```
# 🌐 HTML `<abbr>` Element

---
## 3. Abbreviation (`<abbr>`)

The `<abbr>` element is used to represent an **abbreviation or acronym**.  
- You can provide the **full form** using the `title` attribute.  
- When hovered over in a browser, the full form is usually displayed as a tooltip.

---

## Example
```html
<p>The <abbr title="HyperText Markup Language">HTML</abbr> tutorial is very helpful.</p>
```
# 🌐 HTML `<cite>` Element

---
## 4. itle of a creative work (`<cite>`)

The `<cite>` element is used to define the **title of a creative work**, such as:  
- A book  
- A poem  
- A song  
- A movie  
- A painting, etc.  

It usually appears in *italic* style by default in browsers.  

---

## Example
```html
<p><cite>The Mona Lisa</cite> was painted by Leonardo da Vinci.</p>
```
# 🌐 HTML `<address>` Element

---
## 5. Contact Information (`<address>`)

The `<address>` element is used to define **contact information** for a person, company, or organization.  
- It usually displays the content in **italic** by default.  
- Often used for email, physical address, phone numbers, or author info.  

---

## Example
```html
<address>
  John Doe<br>
  123 Main Street<br>
  New York, NY 10001<br>
  Email: <a href="mailto:johndoe@example.com">johndoe@example.com</a>
</address>
```
# 🌐 HTML `<bdo>` Element

---
## 7. Override the current text direction (`<bdo>`)

The `<bdo>` (Bi-Directional Override) element is used to **override the current text direction**.  
- By default, text direction is **left-to-right (LTR)**.  
- You can change it to **right-to-left (RTL)** using the `dir` attribute.  

---

## Example
```html
<p>Default text direction:</p>
<p>This text goes left to right.</p>

<p>Using BDO to change direction:</p>
<bdo dir="rtl">This text will go right to left.</bdo>
```

# 🌐 HTML Comments

HTML comments are used to **add notes or explanations** in the code.  
- Comments are **not displayed** in the browser.  
- Useful for documentation, reminders, or temporarily disabling code.

---

## Syntax
```html
<!-- This is a comment -->
```
# 🌐 HTML Colors

HTML allows you to set colors for text, backgrounds, borders, and more using different methods.

---

## 1. Color Names
You can use predefined color names like `red`, `blue`, `green`, etc.

### Example
```html
<p style="color: red;">This text is red.</p>
<p style="background-color: yellow;">This background is yellow.</p>
```
# 🎨 Hexadecimal Colors in HTML

Hexadecimal (Hex) colors are widely used in HTML and CSS to represent colors.  
A hex color code starts with **`#`** followed by **six hexadecimal digits**.

---

## 🔹 Structure
- **RR** = Red (00 to FF)  
- **GG** = Green (00 to FF)  
- **BB** = Blue (00 to FF)  

Each pair ranges from **00 (0)** to **FF (255 in decimal)**.

---

## 🔹 Examples

### Example 1: Red
```html
<p style="color: #FF0000;">This text is red.</p>
```
# 🎨 RGB Colors in HTML

RGB stands for **Red, Green, Blue**.  
You can define colors by specifying the intensity of each color using numbers from **0 to 255**.

---

## 🔹 Syntax
```css
rgb(red, green, blue)
```
<p style="color: rgba(255, 0, 0, 0.5);">This text is semi-transparent red.</p>
<p style="background-color: rgba(0, 255, 0, 0.3);">This background is semi-transparent green.</p>
```
# 🎨 RGBA Colors in HTML

RGBA is an extension of RGB that includes an **Alpha** channel for **opacity**.  
- **R** → Red (0–255)  
- **G** → Green (0–255)  
- **B** → Blue (0–255)  
- **A** → Alpha (0.0–1.0) → determines transparency  

---

## 🔹 Syntax
```css
rgba(red, green, blue, alpha)
```
# 🎨 HSL Colors in HTML

HSL stands for **Hue, Saturation, Lightness**.  
- **Hue (H)** → color type (0–360 degrees on the color wheel)  
- **Saturation (S)** → intensity of the color (0% = gray, 100% = full color)  
- **Lightness (L)** → brightness (0% = black, 50% = normal, 100% = white)  

---

## 🔹 Syntax
```css
hsl(hue, saturation%, lightness%)
```
# 🎨 HSLA Colors in HTML

HSLA is an extension of HSL that includes an **Alpha** channel for **opacity**.  
- **H** → Hue (0–360 degrees)  
- **S** → Saturation (0%–100%)  
- **L** → Lightness (0%–100%)  
- **A** → Alpha (0.0–1.0) → determines transparency  

---

## 🔹 Syntax
```css
hsla(hue, saturation%, lightness%, alpha)
```
# 🌐 HTML Links (`<a>`)

The `<a>` element defines a **hyperlink**, which allows users to navigate to another page, a different section of the same page, or an external website.

---

## 🔹 Syntax
```html
<a href="URL">Link Text</a>
```
# 🌐 HTML `target` Attribute

The `target` attribute specifies **where to open the linked document**.  
It is used inside the `<a>` (anchor) tag.

---

## 🔹 Common Values

| Value          | Description                                  |
|----------------|----------------------------------------------|
| `_self`        | Opens the link in the **same tab** (default) |
| `_blank`       | Opens the link in a **new tab**              |
| `_parent`      | Opens the link in the **parent frame**       |
| `_top`         | Opens the link in the **full body of the window** |

---

## 🔹 Examples

### Open in a New Tab
```html
<a href="https://www.example.com" target="_blank">Open Example in New Tab</a>
```
# 🌐 HTML `<img>` Element

The `<img>` element is used to **embed images** in an HTML page.  
- It is a **self-closing tag** and does not require an end tag.  
- The `src` attribute specifies the **path to the image**.  
- The `alt` attribute provides **alternative text** if the image cannot be displayed.  

---

## 🔹 Syntax
```html
<img src="image.jpg" alt="Description of image">
```
