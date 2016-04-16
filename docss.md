# DOCSS

is a tool for generating (s)css documentation.

## How it works

Recursively finds every (s)css file in a folder, and generates a tree and table of contents, like:

```
css/
├── main.css
├── normalize.css
├── print/
│   ├── paper.css
│   └── pdf.css
├── reveal.min.css
├── style.css
└── theme/
    └── default.css
```

### Table of Contents

- [css/](/css)
    - [main.css](css/main.css)
    - normalize.css
    - print/
        - paper.css
        - pdf.css
    - reveal.min.css
    - style.css
    - theme/
        - default.css 
