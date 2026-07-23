# Rules

Personal proxy rules for Surge.

## Structure

```
rules/
└── Surge/
    ├── Gemini/
    │   └── Gemini.list
    └── Notion/
        └── Notion.list
```

## Usage (Surge)

```ini
RULE-SET,https://raw.githubusercontent.com/aydengen/rules/refs/heads/main/Surge/Gemini/Gemini.list,PROXY
RULE-SET,https://raw.githubusercontent.com/aydengen/rules/refs/heads/main/Surge/Notion/Notion.list,PROXY
```
