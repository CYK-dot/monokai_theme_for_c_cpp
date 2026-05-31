# monokai-nextcode README
前置条件：双下划线注释有bug用不了，要在tasks.json中自己补一下下面的内容
```json
"editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "scope": "comment.line.double-slash.c",
            "settings": {
                "foreground": "#75715E"
            }
        }
    ]
}
```
