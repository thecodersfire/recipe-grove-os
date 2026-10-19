# Built-in features for recipe-grove-os

Purpose: cooking and meal planning

1. **organize work and records** — run recipe-grove-os-workspace. It creates ~/Documents/recipe-grove-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run recipe-grove-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/recipe-grove-os-session-plans/.
3. **check records and task readiness** — run recipe-grove-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/recipe-grove-os-workspace features/recipe-grove-os-plan features/recipe-grove-os-check "$HOME/.local/bin/"
