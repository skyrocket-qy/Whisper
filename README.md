<div align="center">

# Whisper

An elegant and implicit theme for Visual Studio Code, designed for a focused and enjoyable coding experience.

<p>
    <a href="https://marketplace.visualstudio.com/items?itemName=skyrocket-qy.whisper">
        <img src="https://img.shields.io/visual-studio-marketplace/v/skyrocket-qy.whisper?style=for-the-badge&label=Version&color=CBA6F7" alt="VS Code Marketplace Version" />
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=skyrocket-qy.whisper">
        <img src="https://img.shields.io/visual-studio-marketplace/i/skyrocket-qy.whisper?style=for-the-badge&label=Installs&color=CBA6F7" alt="VS Code Marketplace Installs" />
    </a>
    <a href="https://github.com/skyrocket-qy/Whisper/blob/main/LICENSE">
        <img src="https://img.shields.io/github/license/skyrocket-qy/Whisper?style=for-the-badge&label=License&color=CBA6F7" alt="License" />
    </a>
</p>

</div>

![Whisper Theme Preview](image.png)

## 🌟 Overview

Whisper is a dark theme that combines subtlety with clarity. Its carefully selected color palette, based on the popular [Catppuccin Mocha](https://github.com/catppuccin/catppuccin), reduces visual noise and helps you focus on what matters most: your code.

While the theme is designed to be aesthetically pleasing for any language, it includes specific optimizations for Go, providing enhanced semantic highlighting for a more intuitive development workflow.

## ✨ Features

- **Minimalist Design**: A clean and unobtrusive interface that stays out of your way.
- **Soothing Colors**: A harmonious color scheme that is easy on the eyes, perfect for long coding sessions.
- **Optimized for Go**: Fine-tuned syntax highlighting for the Go programming language.
- **Semantic Highlighting**: Leverages semantic tokens to provide richer and more meaningful code coloration.

## 🚀 Installation

1.  Open **Visual Studio Code**.
2.  Go to the **Extensions** view (`Ctrl+Shift+X`).
3.  Search for "Whisper" and click **Install**.
4.  Go to **File > Preferences > Color Theme** and select **Whisper**.

Alternatively, you can install it directly from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=skyrocket-qy.whisper).

## 🔧 Recommended Settings

For the best experience, especially for Go development, add the following to your `settings.json` file:

<details>
<summary>Click to expand settings.json</summary>

```json
"editor.semanticHighlighting.enabled": true,
"editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "name": "Go type names (fallback)",
            "scope": [
                "entity.name.import.go",
            ],
            "settings": { "foreground": "#CBA6F7" }
        },
        {
            "name": "go.mod",
            "scope": [
                "string.unquoted.go.mod"
            ],
            "settings": { "foreground": "#D6D6D6" }
        },
    ]
},
"gopls": {
    "ui.semanticTokens": true
}
```

</details>

## 📄 License

This theme is released under the [MIT License](LICENSE).
