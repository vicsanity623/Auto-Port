# DevQuest Auto-Port ⚡️🦀

A mobile-first **Progressive Web App (PWA)** that functions as a logic playground. It allows you to write JavaScript and automatically convert ("port") it to Rust, then execute it via the Rust Playground API.

## Features
- 📱 **Mobile Optimized:** Full PWA support with safe-area insets for iOS/Android.
- ⚡ **Auto-Port:** distinct "AI" heuristic engine converts JS syntax (`console.log`, `let`, loops) into valid Rust code.
- 🦀 **Remote Execution:** Runs Rust code using the official Rust Playground API.
- 📂 **Virtual File System:** Create, edit, and save `.js`, `.rs`, `.html`, and `.css` files locally.

## How to use
1. Open the [Live Demo](https://vicsanity623.github.io/Auto-Port/) on your phone.
2. Add to Home Screen to install as an App.
3. Open `script.js` and write some logic.
4. Click **⚡ Auto-Port** to generate a Rust equivalent.
5. Click **Run** to see the output from the remote compiler.

## Tech Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript (Zero Dependencies).
- **Backend:** Relies on the public Rust Playground API.
- **Storage:** Browser LocalStorage for file persistence.

## Examples
Check the `examples/` folder for Rust code snippets compatible with this runner.
