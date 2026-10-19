# Built-in features for recipe-grove-os

Purpose: cooking and meal planning

1. **organize work and records** — run recipe-grove-os-workspace. It creates ~/Documents/recipe-grove-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run recipe-grove-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/recipe-grove-os-session-plans/.
3. **check records and task readiness** — run recipe-grove-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/recipe-grove-os-workspace features/recipe-grove-os-plan features/recipe-grove-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for cooking and meal planning:

1. **GNOME Calendar** — org.gnome.Calendar
2. **GIMP** — org.gimp.GIMP
3. **Audacity** — org.audacityteam.Audacity

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for cooking and meal planning:

1. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
2. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
3. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
4. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
5. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
6. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
7. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
8. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
9. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
10. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
