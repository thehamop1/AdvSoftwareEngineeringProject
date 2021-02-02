class: inverse
layout: true
---
class: center, middle

# Conversational Interfaces / Bots

.foornote[by [Cristian Gutierrez](https://github.com/thehamop1), [Archana Ravi](https://github.com/darshikasondra), [Darshi Kasondra](https://github.com/)]

---
class: middle

# Topics

- What are converational interfaces/bots
- What are the differnet categories of converational interfaces/bots
- What industries are using CI/bots?
- Examples of Successful CI/bots
- What platforms do these belong on?


---
# Write with markdown

## Paragraph

Paragraph with **strong**, *italic*, `code`,
or &lt;strike&gt;inline strike tag&lt;/strike&gt;.

Links as labeled [github](https://github.com/) or direct https://github.com/ .

## Blockquote

> blockquote texts with
"**> quoted texts...**"

## Table

|ID|Name|Value|
|--|----|-----|
| 1|foo |   10|
| 2|bar |   20|


---
# Items of markdown

no bullte paragraph

1. numbered 1
    - bullet 1
    - bullet 2
2. numbered 2
    1. child 1
    2. child 2
3. numbered 3

---
# GFM code block

```js
// remark.js enables highlight.js with GFM code block notation
// Setting the highlight.js theme at last script tag as:
// const slideshow = remark.create({highlightStyle: "github",});

import {Buffer} from "buffer";

const b = Buffer.from("f0f0f0", "hex");

class Target extends EventTarget {
  constructor() {
    //...
  }
  close() {}
}

function isOk() {
  return true
}
console.log(`${Boolean("true")}`);
// here is line 20 ------------------------------------------------------ col 80
```

---
#  Key bindings and Side note

## Key bindings

- Forward: right, down and space keys
- Backward: left, up keys
- Full screen toggle: **F** key
- Cloned Window: **C** key
    - original and cloned synchronizes their page move
- Help: **H** key

## Side note for presentation

`???` as side-note delimiter

- Toggle side note: **P** key

For presentation

- C: open a cloned window to move 2nd screen
- F: make the cloned fullscreen
- P: switch side note view on the original window
- down, down, down: goto to next pages


???

Note here

- you can use same notation includes code blocks and optional latex notations

---

# Other features

Span element with .red[red span] (it should be specified at the style tag).

KaTeX for math representaion:

$$F(x) = \int_{-\infty}^{\infty}{f(x)}dx + C$$

Mermaid for graph:

<div class="mermaid">
graph LR;
  A --> B;
  B --> C;
  C --> A;
  D --> C;
</div>

---
# Convert to PDF

## Set CSS `@media print`

- Fit paper with `top` `left` `width` `height` of `.remark-slide-scaler`

## To PDF file with browser's print

- Preview and save as PDF
- NOTE: render mermail graph once displayed

---
# Indentless textarea edit with
# emacs web-mode

- Install with `M-x package-install` then type `web-mode`
- add customization into `~/.emacs` as:

```lisp
(add-to-list 'auto-mode-alist '("\\.html\\'" . web-mode))
(add-hook 'web-mode-hook (lambda ()
   (setq web-mode-markup-indent-offset 2)
   (setq web-mode-css-indent-offset 2)
   (setq web-mode-code-indent-offset 2)
   (setq web-mode-style-padding nil)
   (setq web-mode-script-padding nil)
   (setq web-mode-indentless-elements
         (append web-mode-indentless-elements '("p" "h1" "h2" "h3" "h4")))
   (setq web-mode-indentless-attributes
         (append web-mode-indentless-attributes '("onload")))
   (custom-set-faces
    '(web-mode-html-tag-face ((t (:foreground "blue"))))
    '(web-mode-html-tag-bracket-face ((t (:foreground "blue")))))))
```
