# Whisper

Go theme, elegant and implicit

![alt text](image.png)

Add below setting to `settings.json` for best color

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
