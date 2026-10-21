# JS & TS Interview Lab

A free, single-page site for preparing for JavaScript and TypeScript interviews.

**Live site:** https://narmieu.github.io/js-ts-interview-lab/

## What's inside

- **Learn**: 36 plain-language lessons, from the event loop, closures and `this` to promises from the inside, generics and conditional types. Each lesson has code examples, common mistakes, key terms and self-check questions.
- **Code challenges**: 90 LeetCode-style problems with hidden tests and full walkthroughs:
  - JavaScript fundamentals, async JavaScript (your own Promise, concurrency pools, schedulers) and advanced JavaScript (Proxy, generators, parsers)
  - TypeScript type challenges (MyPick, DeepReadonly, Paths, IsUnion and more), checked by the real TypeScript compiler in your browser
  - Typed TypeScript functions that must pass both type tests and runtime tests
- **Output quiz**: 76 "what does this print?" snippets about the event loop, hoisting, `this`, coercion, objects and arrays.
- **Interview questions**: 112 questions with model answers, key points to cover, likely follow-ups and a mock interview mode.

## The code editor

The challenges use a real code editor (CodeMirror 5) with the TypeScript language service behind it, so it behaves like a small VS Code:

- Syntax highlighting, smart indentation, auto-closing brackets and quotes, bracket matching
- Autocomplete, parameter hints, hover info and live error underlines for both JavaScript and TypeScript
- Format with Prettier (`Shift+Alt+F`), find and replace (`Ctrl+F`, `Ctrl+H`), multi-cursor (`Ctrl+D`, `Alt+click`)
- Line commands: move (`Alt+Up/Down`), copy (`Shift+Alt+Up/Down`), delete (`Ctrl+Shift+K`), comment (`Ctrl+/`)
- Run (`Ctrl+Enter`) and submit (`Ctrl+Shift+Enter`), your own test cases checked against the reference solution, a console tab for calling your code with anything, and a history of your submissions
- Settings for font size, indentation, word wrap and suggestions, plus a focus mode

## How it works

Everything runs in your browser. JavaScript solutions run in an isolated Web Worker with a time limit. The TypeScript 6.0.2 compiler (used for type checking and editor IntelliSense) and Prettier 3.8.1 (for formatting) load from jsDelivr the first time they are needed. Your code, progress and answers are saved in your browser's local storage only.

## Run it locally

Open `index.html` in a browser, or serve the folder with any static server, for example `npx serve .`.
