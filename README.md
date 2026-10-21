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

## How it works

Everything runs in your browser. JavaScript solutions run in an isolated Web Worker with a time limit. TypeScript problems load the TypeScript 6.0.2 compiler from jsDelivr the first time you run one. Your code, progress and answers are saved in your browser's local storage only.

## Run it locally

Open `index.html` in a browser, or serve the folder with any static server, for example `npx serve .`.
