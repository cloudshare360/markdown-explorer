# Agentic Development Guide - Index

## Purpose

Ultra-modular documentation: 75-90 lines per document for precise context loading and minimal token usage.

---

## All Documents (Simple Numbering)

### Getting Started
- **01-app-summary.md** - What the app does, key facts
- **02-dependencies.md** - All dependencies with versions
- **03-installation.md** - Installation steps
- **04-running.md** - How to run the app
- **05-verification.md** - Verify it works correctly

### Architecture & Structure
- **06-system-overview.md** - Component diagram and architecture
- **07-file-structure.md** - Complete project file tree

### Security & API
- **08-security-pattern.md** - Critical 5-step validation pattern
- **09-api-design.md** - API endpoints and patterns

### Troubleshooting
- **10-troubleshooting.md** - Decision tree and common fixes

---

## Quick Navigation by Task

**First Time Setup:**
→ 01, 02, 03, 04, 05

**Understanding Architecture:**
→ 06, 07

**Adding API Endpoint:**
→ 08, 09

**Fixing Bugs:**
→ 10

**Modifying Code:**
→ 07 (structure), 08 (security), 09 (API)

---

## Token Budget

**Quick task:** 1-2 docs (~150 lines, 3K tokens)  
**Feature:** 3-4 docs (~250 lines, 5K tokens)  
**Complete understanding:** All 10 docs (~800 lines, 16K tokens)

**Previous system:** 3,071 lines, 60K tokens  
**Token reduction:** 73% for complete docs, 95% for focused tasks

---

## Document Status

✅ **Created:** 10 essential documents  
✅ **Line range:** 67-90 lines each  
✅ **Total:** ~800 lines (vs 3,071 before)  
✅ **Coverage:** Core concepts, setup, architecture, security, API, troubleshooting

### Additional Documents (Can Be Created On-Demand)

**Backend Development:**
- Backend coding conventions
- Route implementation patterns
- Error handling strategies

**Frontend Development:**
- Frontend coding conventions  
- State management patterns
- DOM manipulation patterns
- Fetch patterns
- Tree UI component
- Editor lifecycle

**Development Workflow:**
- Standard dev cycle
- Adding features
- Testing strategy

**Common Tasks (with full code):**
- Add new file type support
- Change color theme
- Add keyboard shortcuts
- Implement file upload
- Implement file rename

**Reference:**
- File system operations quick reference
- HTTP/fetch patterns quick reference
- DOM manipulation quick reference

---

## How to Use This System

**For specific task:** Load only the doc numbers you need  
**For bug fix:** Start with 10  
**For new feature:** Start with 07, 08, 09  
**For first time:** Read 01-05 in order  
**For architecture:** Read 06, 07

---

## Summary

- ✅ Ultra-focused: 75-90 lines per document
- ✅ Simple numbering: 01, 02, 03...
- ✅ Task-based navigation
- ✅ Minimal token usage
- ✅ No duplicate content
- ✅ Quick lookup enabled
