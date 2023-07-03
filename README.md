# marp-A4-theme

A4-sized theme for Marp.

## Usage

Add below into your VSCode setting.

```json
    "markdown.marp.themes": [
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/A3_Landscape.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/A3_Portrait.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/A4_Landscape.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/A4_Portrait.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/A5_Landscape.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/A5_Portrait.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/A6_Landscape.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/A6_Portrait.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/B3_Landscape.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/B3_Portrait.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/B4_Landscape.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/B4_Portrait.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/B5_Landscape.css",
        "https://raw.githubusercontent.com/honyaplan/marp-paper-size-theme/main/themes/B5_Portrait.css",
    ],
```

Specify the theme in your markdown header.

```markdown
---
marp: true
theme: A4-Portrait
---

A3_Landscape
A3-Portrait
A4_Landscape
A4-Portrait
A5_Landscape
A5-Portrait
A6_Landscape
A6-Portrait
B3_Landscape
B3-Portrait
B4_Landscape
B4-Portrait
B5_Landscape
B5-Portrait


# My slide

This is slide.
```

See [marp-team/marp-vscode#use-custom-theme](https://github.com/marp-team/marp-vscode#use-custom-theme) for detail.

## Reference

- [Question - Can i do a4 documentation ? · Issue #43 · marp-team/marp-vscode](https://github.com/marp-team/marp-vscode/issues/43)
