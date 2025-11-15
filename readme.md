# Ways to Inject / Insert / Embed CSS into HTML

There are several ways to include CSS inside an HTML document.  
This guide summarizes all common methods, when to use them, and sample code.

---

## 1. External Stylesheet

**Best for:** Large projects, reusability, clean separation of concerns.

**Usage:**
```html
<link rel="stylesheet" href="styles.css">


2 Internal (Embedded) Stylesheet
<style>
  body {
    background-color: lightblue;
  }
</style>

3 Inline Styles
<p style="color: red; font-weight: bold;">Hello world!</p>


4 CSS Injection via JavaScript

document.getElementById("myDiv").style.backgroundColor = "yellow";
