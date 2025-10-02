# Three Musketeers Language Extension for VS Code

This is the Visual Studio Code extension providing syntax highlighting and basic language support for the **Three Musketeers** programming language.

## 🚀 Installation (Local)

### Prerequisites

You need to have **Visual Studio Code** installed and the extension's VSIX file (`three-musketeers-language-0.0.1.vsix`).

### Steps

1.  **Package the Extension:**
    If you haven't already packaged the extension, run this command in the root directory of this repository:
    ```bash
    vsce package
    ```
    This command will generate the file: `three-musketeers-language-0.0.1.vsix`

2.  **Install via Command Line:**
    Open your terminal and run the following command, making sure to replace the filename with the correct version if needed:
    ```bash
    code --install-extension three-musketeers-language-0.0.1.vsix
    ```

3.  **Reload VS Code:**
    Restart Visual Studio Code to ensure the extension is fully loaded.

## ✨ Features

* **Syntax Highlighting:** Properly colors keywords, comments, strings, and identifiers in `.3m` (or whatever extension you chose) files.
* **Language Identification:** Recognizes files with the configured extension as **Three Musketeers** language files.

## 🤝 Contributing

Contributions are welcome! If you find any issues with the syntax highlighting or want to suggest improvements:

1.  Fork this repository.
2.  Create your feature branch (`git checkout -b feature/amazing-feature`).
3.  Commit your changes (`git commit -m 'feat: add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/amazing-feature`).
5.  Open a Pull Request.

---

*Enjoy coding in Three Musketeers!*
