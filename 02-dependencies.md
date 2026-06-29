# 01b - Dependencies

## Backend (npm)

**express 4.18.2** - Web framework
**marked 9.1.6** - Markdown parser  
**highlight.js 11.9.0** - Syntax highlighting  
**dotenv 17.4.2** - Environment config  
**nodemon 3.1.0** - Dev auto-restart (devDependency)

---

## Frontend (CDN)

**DO NOT CHANGE URLS**

```html
<!-- CSS -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/easymde/dist/easymde.min.css">

<!-- JavaScript -->
<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/easymde/dist/easymde.min.js"></script>
```

---

## Why These

**express:** Industry standard, simple, mature  
**marked:** Fast, GFM support, 50KB  
**highlight.js:** Auto-detect, many themes  
**EasyMDE:** Markdown-focused, CodeMirror  
**CDN:** No build step, browser caching

---

## Alternatives Rejected

❌ React/Vue - Too heavy, build step  
❌ TypeScript - Compilation required  
❌ Webpack - No build step goal  
❌ markdown-it - Heavier than marked  
❌ Monaco - VS Code editor, too large

---

## Installation

```bash
npm install
```

Downloads ~2,500 files, ~50MB to node_modules/

---

## When to Read

- Setting up environment
- Upgrading dependencies  
- Understanding choices
- Evaluating alternatives

**Next:** 01c-installation.md
