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


