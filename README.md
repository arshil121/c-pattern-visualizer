# Pattern → C Code Visualizer

Type a pattern (like a star triangle) and get the **C code** for it. Then click **Next** to watch the program run step by step and see how the variables change.

**Live demo:** [https://arshil121.github.io/pattern-visualizer-c/](https://arshil121.github.io/c-pattern-visualizer/)

## What it does

- Turns a pattern you type into C code
- Shows each step of the program, one click at a time
- Highlights the current line of code
- Shows the values of `n`, `i`, `s` and `j` as they change
- Builds the output character by character

## How to use

1. Open the live demo (or `index.html` in your browser).
2. Pick an example pattern or type your own. Spaces matter.
3. Click **Generate C code**.
4. Click **Next** to go step by step, or **Play** to run it automatically.
5. Click **Copy** to take the code and run it yourself:

```bash
gcc pattern.c -o pattern
./pattern
```

## Patterns it understands

Triangles, pyramids, diamonds, hollow shapes, number patterns (`1 12 123`) and alphabet patterns (`A AB ABC`).

## Run it on your computer

Download `index.html` and double-click it. No installation needed.

## Files

- `index.html`: the whole website
- `README.md`: this file
