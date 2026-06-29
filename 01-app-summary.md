# 01a - Application Summary

## What It Is

**Name:** Markdown Server Stack Edit  
**Type:** Browser-based markdown file browser and editor  
**Purpose:** Local development tool for managing markdown documentation  
**Users:** Individual developers working on localhost

---

## Core Functionality

**File Browser:**
- Hierarchical tree view of all `.md` files
- Lazy-loading folder expansion
- Search by navigating tree structure
- System folders hidden (node_modules, .git, etc.)

**Markdown Editor:**
- Split-pane: editor left, live preview right
- Powered by EasyMDE (CodeMirror-based)
- Real-time rendering as you type
- Toolbar: bold, italic, headings, lists, links, images

**File Management:**
- Create new files and folders
- Delete files and folders (with confirmation)
- Context-aware creation (create in selected folder)
- Automatic `.md` extension

**Development Mode:**
- Live reload via Server-Sent Events (SSE)
- Auto browser refresh on code changes
- Nodemon integration for hot-reloading

---

## Technical Summary

**Architecture:** Express.js backend + Vanilla JS SPA frontend  
**Source Code:** 678 lines total (170 backend + 489 frontend + 19 utility)  
**Files:** 3 source files (server.js, index.html, find-port.js)  
**Dependencies:** 4 runtime, 1 dev (all via npm)  
**Build:** None - runs directly with `node server.js`

---

## Critical Constraints

- **Single file architecture** - Backend in one file, frontend in one file
- **No build step** - No webpack, TypeScript, SASS, etc.
- **No frameworks** - Vanilla JavaScript only
- **Localhost only** - Not designed for network deployment
- **Markdown only** - Core functionality restricted to `.md` files

---

## Key Facts for Agents

1. **Simple by design** - Complexity is avoided intentionally
2. **Security by path validation** - Every file op checks boundaries
3. **Stateless server** - No sessions, no caching (except SSE clients)
4. **Synchronous I/O** - Acceptable for single-user localhost
5. **Direct file access** - No database, filesystem is the database

---

## When to Use This Document

- First time seeing the codebase
- Need quick overview for new team member
- Explaining the project to someone
- Deciding if architecture fits use case

**Next:** Read `01b-dependencies.md` for dependency details.
