# markdown-scrimba
This is a repo for the Markdown course on Scrimba to share the articles created by students.

--- 
  ![GitHub contributors](https://img.shields.io/github/contributors/PizzaPokerGuy/markdown-scrimba)
  ![Twitter Follow](https://img.shields.io/twitter/follow/pizzapokerguy?label=Follow&style=social) 

- Dylan C. Israel | [Markdown Course LIVE on Scrimba](https://dev.to/pizzapokerguy/markdown-course-live-on-scrimba-3pjk-temp-slug-6044007?preview=3854bc764872c3c488aa78590956f09f402bfb4f255fd9affdf4a8656157c047bafdbca55aaad311437edbdd74592bea3d5eaef7700239f591068b90)
- Dave Collison | [My first markdown post on dev.to](https://dev.to/thebigdavec/just-getting-started-4ekn "Dave Collison's Markdown Post")
- Jason Schwarz | [My first markdown post on dev.to](https://dev.to/passandscore/blockchain-is-changing-our-world-one-block-at-a-time-4h4b "Jason Schwarz's First Markdown Post About Blockchain")

# How JSX works in ReactJS? 🤗

---

React uses JSX to make developer experience better than other environments. JSX is just an HTML like syntax, but not HTML in Javascript. The Browser can't understand JSX code on it's own. It needs transpilers like **Babel** to *convert* JSX code to **React.createElement()** code, **React.createElement()** are nothing but **JavaScript Objects** and then those **objects** are *converted* to **DOM**.

So the flow goes like:
_JSX_ **=>** _Babel_ **=>** _React.createElement_ **=>** _Obj_ **=>** _HTML code(DOM)_

---

>"Babel is a Beast."

---

Before compiling React JSX code, we need Babel to transpile it to the React API format.

JSX Element

```js
const reactElement = <h1>Hello World</h1>
```

Babel transpiled react version

```js
const reactElement = /*#__PURE__*/React.createElement("h1", null, "Hello World");
```

![Reactlogo](https://www.iconfinder.com/icons/1174949/download/png/48)

---

###Conclusion
- JSX is HTML-like syntax, but not actual HTML in JS file.
- Babel is a Beast.

---
[YouTube Link](https://www.youtube.com/channel/UCyjSE3te6b_--hn_Mvxs5ew "Jyotis Channel")
<jyotisemail@gmail.com>