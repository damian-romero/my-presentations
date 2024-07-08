---
marp: true
theme: damian-romero
paginate: true
size: 16:9
header: 'Damian Romero Marp theme tour'
footer: '© Damian Romero | [GitHub](https://github.com/damian-romero) | [LinkedIn](https://www.linkedin.com/in/damian-romero/) | [Website](https://www.d-romero.com)'
---

# Damian Romero Custom Theme
### A Visual Guide

Welcome to the visual guide for the Damian Romero custom theme. This presentation will showcase various features and custom directives of the theme.

---

<!-- _class: title -->

# Title Slide Example

## This is a title slide with the custom background color and text styling.

---

# Basic Slide
This is a basic slide with default styling.

---

## Normal Slide

---

## Slide with List

- Bullet point 1
- Bullet point 2
- Bullet point 3

---

### Numbered List

1. First item
2. Second item
3. Third item

---

#### Markdown Table

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1    | Data 1   | Data 1   |
| Row 2    | Data 2   | Data 2   |
| Row 3    | Data 3   | Data 3   |

This slide showcases a markdown table.

---

##### Code Block

```python
def hello_world():
    print("Hello, world!")
```

---

###### Math Typesetting

Inline math: \( E = mc^2 \)

Display math:
$$
\int_{a}^{b} x^2 dx
$$

---

<!-- _backgroundColor: #732124 -->
<!-- _color: #fef8f8 -->

# Custom Background and Text Color

This slide uses custom background and text colors.

---

<!-- _class: invert -->

# Inverted slide

This slide has inverted colors using the `invert` directive.

*Note: The inverted class has not yet been implemented. This slide is a 
placeholder.*

---

<!-- _paginate: false -->

# No Pagination

This slide has pagination disabled using the `_paginate` directive.

---

# Custom Footer

<footer>
  <a href="https://github.com/damian-romero/" class="github">GitHub</a>
  <a href="https://www.linkedin.com/in/damian-romero/" class="linkedin">LinkedIn</a>
  <a href="https://www.d-romero.com" class="website">Website</a>
</footer>

---

# Iframe example

<iframe src="https:www.d-romero.com" width="100%" height="500"></iframe>

---

<!-- _class: lead -->

<!-- _footer: -->

# Background Image

![bg left:33%](https://via.placeholder.com/800x600)

This slide has a background image using the `![bg]` syntax.

---

# Fragmented Lists

* Item 1
* Item 2
* Item 3

---

# Incremental Text

This text will appear incrementally.

---

# C'est fini

Thank you for viewing the visual guide of the Damian Romero custom theme. We hope this guide helps you understand how to use the various features and custom directives available.

---

# Instructions

```
1. Save the Enhanced Markdown File

2. Ensure the Theme File is Saved

3. Compile the Presentation

`marp --html --theme-set damian-romero-marp.css --output presentation.html slides.md`

4. Preview or Convert Your Presentation

`marp --html --theme-set damian-romero-marp.css --preview slides.md`

5. Export to PDF
`marp --html --theme-set damian-romero-marp.css --pdf slides.md`
```
