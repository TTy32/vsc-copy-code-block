
This is a fork of [dumitory-dev/vsc-copy-code-block](https://github.com/dumitory-dev/vsc-copy-code-block).

Original project appears unmaintained: this fork adds a few features.


# Code Block Copier ✂️

A VS Code extension that lets you copy code blocks with line numbers, file paths, and preserved formatting — perfect for sharing snippets in documentation, chats, or pull requests.

## 🚀 Features

- 🔢 **Adds line Numbers**
- 📄 **File Path** – Relative or otherwise absolute path
- ✂️ **Smart Selection** – If no text is selected, copies the *entire file*
- ➕ **Append Mode** – Add another code block to the clipboard instead of overwriting

## ⚙️ Installation

1. Open **VS Code**
2. Go to **Extensions View** (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for **“Code Block Copier”**
4. Click **Install**

## 🪄 Usage

1. Select the code you want to copy
2. Press F1 and select:
   - ✏️ "Code Block Copier: Copy Code Block"
   - ➕ "Code Block Copier: Copy Code Block (Append)"
3. Paste anywhere you need it

## 🧩 Example Output

```
path: src/example/file.ts
1: function greet(name: string): string {
2:     return `Hello, ${name}!`;
3: }
4:
5: console.log(greet("World"));
```

If you append another block, your clipboard will look like:

```
path: src/another/file.ts
1: export const sum = (a: number, b: number) => a + b;

path: src/example/file.ts
1: function greet(name: string): string {
2:     return `Hello, ${name}!`;
3: }
4:
5: console.log(greet("World"));
```

## 🪪 License

[MIT License](LICENSE)

- Author [**dumitory-dev**](https://github.com/dumitory-dev)
- Additional features by [**TTy32 / Randy Wijnants**](https://github.com/TTy32)

---

**Enjoy coding and sharing!**
