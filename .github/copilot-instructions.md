# GitHub Copilot Instructions

This repository is a CSS and HTML learning project (CSS-AIML1).

## How to Switch to GitHub Copilot Pro Model

GitHub Copilot Pro gives access to more powerful models such as **GPT-4o** and **Claude Sonnet**.  
Follow the steps below to switch to a Pro model:

### In Visual Studio Code

1. Open the **Copilot Chat** panel (`Ctrl+Alt+I` / `Cmd+Alt+I`).
2. Click the **model picker** dropdown at the top of the Chat panel (shows the current model name, e.g. "GPT-4o").
3. Select your preferred Pro model from the list (e.g. **GPT-4o**, **Claude 3.5 Sonnet**, or **o3-mini**).

> **Note:** Pro models are only available if your GitHub account has an active **GitHub Copilot Pro** or **Copilot Business/Enterprise** subscription.

### Via VS Code Settings (persistent per-workspace)

A `.vscode/settings.json` file is already included in this repository that sets the default Copilot model to `gpt-4o`:

```json
{
  "github.copilot.advanced": {
    "model": "gpt-4o"
  }
}
```

You can change the value to any model identifier supported by your Copilot plan:
- `"gpt-4o"` – GPT-4o (default Pro model)
- `"claude-3.5-sonnet"` – Claude 3.5 Sonnet
- `"o3-mini"` – OpenAI o3-mini

### On GitHub.com (Copilot Chat in the browser)

1. Open [github.com/copilot](https://github.com/copilot).
2. Click the **model** dropdown in the top-right corner of the chat window.
3. Select the desired Pro model.

## Project Context

- All files use plain HTML and CSS (no frameworks).
- Prefer suggestions that follow modern CSS best practices (Flexbox / Grid).
- Keep code beginner-friendly and well-commented.
