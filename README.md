# CheatsheetsGenerator
>Disclaimer : this repository is a project proposal, no code have been done so far.

The **Online Cheatsheets Generator** would be a website where you can enter vocabulary, images and code samples in order to create elegant, efficient and powerful cheatsheets about a given topic.

**Problem statment:** given a course or topic studied where its core vocabulary and illustrations have been gathered, allow the student.s to easily put this gist knowledge into a digital and sharable form to maximize learning and retention.

### Install
...

### Stack
We recommend a Minimal Valuable Product approach. First a working local project, then an online CRUD API-based project.

1. JSON data, JS, HTML, CSS.
2. + Online CRUD & API. Open anonymous contributions without password.
3. Account manager.

### Structure
Version 1.x.x :
- repository
  - index.html
  - data/
  - js/ : jquery, bootstrap
  - css/

### Data sample
Common cheatsheets are composed of `word + minimal definition` pairs, `image`, `code` sample, `section title (h3)`, `section footnote`, grouped by category, creating semantic `block`. The document has an header containing the topic's `title`. Each of these elements has specific styles and color, while bottom level row can alternate in background-color to increase readability.

```
{ section: "MacroStructure", class: "row h2", item: "Page's structure", definition:"basic structural blocks"},
{ section: "MacroStructure", class: "row image def-hidden", item: "./img/page_structure.png", definition: "classic structure of a page with body containing topbar, content, footer"},
{ section: "MacroStructure", class: "row def-display", item: "<head>"   , definition:"contains meta data about page & call for resources"},
{ section: "MacroStructure", class: "row def-display", item: "<body>"   , definition:"top semantic block, contains whole page"},
{ section: "MacroStructure", class: "row def-display", item: "<header>" , definition:"or <i>topbar</i>, identifies top of page"},
{ section: "MacroStructure", class: "row def-display", item: "<sider>"  , definition:"identifies left or right of page"},
{ section: "MacroStructure", class: "row def-display", item: "<content>", definition:"identifies core content of page"},
{ section: "MacroStructure", class: "row def-display", item: "<footer>" , definition:"identifies bottom of page"},
{ section: "Blocks", class: "row  h2", item: "HTML block elements", definition:"basic structural blocks in html"},
{ section: "Blocks", class: "row def-display", item: "<div>", definition:"division, basic structural block"},
{ section: "Blocks", class: "row def-display", item: "<p>", definition:"paragraph"},
{ section: "Blocks", class: "row def-display", item: "<span>", definition:"span"},
{ section: "Blocks", class: "row def-display", item: "<text>", definition:"text element"},
{ section: "MinimalHTML5", class: "row h2", item: "HTML5 template", definition:"the shortest valid HTML5 code" },
{ section: "MinimalHTML5", class: "row code def-hidden", item: `
    <html>
      <head><meta charset="utf-8">
      <title>Page's Title !</title>
      <script src="/js/jquery.min.js"></script>
      <link rel="stylesheet" href="/css/styles.css">
      </head>
    <body>
      <div id="header">Topbar</div>
      <div id="main">
          <div id="siderLeft">Left menu !</div>
          <div id="content">Content !</div>
      </div>
      <div id="footer">Footer !</div>
    </body>
    </html>
  `, definition:"To use: copy and paste" },

```

### Annotated example

![Cheatsheets_principles_renewed](https://raw.githubusercontent.com/cricodeclub/CheatsheetsGenerator/master/img/cheatsheet-principles-reviewed.png)

### Contributors
- You !?
