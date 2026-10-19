# Built-in features for ethical-lab-os

Purpose: ethical cybersecurity learning

1. **prepare study and research files** — run ethical-lab-os-workspace. It creates ~/Documents/ethical-lab-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run ethical-lab-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/ethical-lab-os-session-plans/.
3. **check study and source readiness** — run ethical-lab-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/ethical-lab-os-workspace features/ethical-lab-os-plan features/ethical-lab-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for ethical cybersecurity learning:

1. **Zotero** — org.zotero.Zotero
2. **Anki** — net.ankiweb.Anki
3. **Foliate** — com.github.johnfactotum.Foliate

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for ethical cybersecurity learning:

1. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
2. **LibreOffice** — create reports and spreadsheets (org.libreoffice.LibreOffice)
3. **Thonny** — write and debug Python code (org.thonny.Thonny)
4. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
5. **QGIS** — analyze geographic data and make maps (org.qgis.qgis)
6. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
9. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
10. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
