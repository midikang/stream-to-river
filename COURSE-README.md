# Stream to River Interactive Course

## 🎓 What This Is

An interactive, single-page HTML course that teaches how the **Stream to River** codebase works—designed for "vibe coders" who build with AI tools but want to understand what's happening under the hood.

## 🚀 How to Use

Simply open **`streams-to-river-course.html`** in any modern web browser:

```bash
# From the repository root
open streams-to-river-course.html

# Or on Linux
xdg-open streams-to-river-course.html

# Or just double-click the file in your file explorer
```

The course is **completely self-contained**—no server, no dependencies, works offline. Just open and learn!

## 📚 What You'll Learn

The course has **6 interactive modules** that take you from "what does this app do?" to "how does it actually work?":

### Module 1: What Stream to River Does & Your First Word Journey
- What the app does (English learning with spaced repetition)
- Trace adding a word end-to-end from user click to database
- See real code from `word.go` translated to plain English

### Module 2: Meet the Cast - API Service, RPC Service & Frontend
- The three main actors and their responsibilities
- Watch them "chat" in a group conversation (iMessage-style animation)
- Understand the library metaphor (catalog desk, back rooms, reading area)

### Module 3: The Data Highway - How Requests Flow
- Complete HTTP → RPC → Database flow visualization
- Animated message flow showing a review list request
- Real code showing Fisher-Yates shuffle for quiz questions

### Module 4: The Memory System - Spaced Repetition That Works
- Visual Ebbinghaus forgetting curve
- Bitmask scoring system (see bits flip in real-time!)
- Code from `submit_answer.go` showing level progression

### Module 5: AI Superpowers - Chat, Speech & Vision
- How LLM streaming works with Server-Sent Events (SSE)
- Parallel goroutine processing (orchestra conductor metaphor)
- Real code from `chat.go` showing concurrent patterns

### Module 6: The Big Picture - What You Learned
- Full architecture diagram
- Key takeaways for steering AI coding tools
- Practical prompting examples for each concept

## ✨ Interactive Features

Every module includes:

- **Code ↔ English Translations**: Real code from the project on the left, plain English explanation on the right
- **Animated Visualizations**: Data flows, component conversations, architecture diagrams
- **Interactive Quizzes**: Test your understanding with scenario-based questions
- **Glossary Tooltips**: Hover or tap any technical term for a plain-English definition (no need to Google anything!)
- **Scroll-Based Navigation**: Use arrow keys, navigation dots, or just scroll through

## 🎯 Who This Is For

**"Vibe coders"**—people who build software by instructing AI coding tools in natural language, without a traditional CS education.

**Your goals are practical:**
- Steer AI coding tools better (make smarter architectural decisions)
- Detect when AI is wrong (spot hallucinations, catch bad patterns)
- Debug when AI gets stuck (break out of bug loops)
- Talk to engineers without feeling lost

You're **not** trying to become a software engineer. You want coding as a superpower that amplifies what you're already good at.

## 🎨 Design Philosophy

This course inverts traditional CS education:

**Old way:** Memorize concepts for years → eventually build something → finally see the point

**This way:** Build something first → experience it working → **now** understand how it works

Every concept is:
- Explained with a metaphor from everyday life (no recycled "restaurant" clichés!)
- Illustrated with real code from the actual codebase (never modified or simplified)
- Connected to a practical skill (steering AI, debugging, making decisions)

## 🛠️ Technical Details

The course is a single HTML file (72KB) that includes:
- Complete CSS design system (warm palette, beautiful typography)
- All JavaScript for interactive elements (animations, quizzes, tooltips)
- Real code snippets from the Stream to River codebase
- Works on desktop and mobile (fully responsive)

**No dependencies** except Google Fonts (loaded from CDN).

## 📖 Based On

This course was created using the [codebase-to-course](https://github.com/zarazhangrui/codebase-to-course) skill for Claude Code.

---

**Ready to learn?** Open `streams-to-river-course.html` and start exploring! 🚀
