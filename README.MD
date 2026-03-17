# ts-locales

This repository contains the translation files used by my FiveM scripts, Toine Scripts.

All translations for this project are managed through **Crowdin**.

The goal is to:
- centralize all locale files (JSON),
- keep translation keys consistent across scripts,
- use Crowdin for collaborative translation.

## Structure

Example structure:

- `ts-props-system/`
  - `en.json` – English source strings for **ts-props-system**
  - `fr.json` – French translations for **ts-props-system**
  - (other languages may be added: `de.json`, `es.json`, etc.)

Each script has its own folder with one file per language.

## Source of truth

- The **repository** is the source of truth for:
  - file structure,
  - keys,
  - English strings (`en.json`).
- **Crowdin** is the source of truth for:
  - community translations,
  - keeping other languages in sync with English.

Changes to keys or new features start here (in `en.json`), then flow into Crowdin, then back into all languages.

## File format

Translation files use simple JSON with `key: "value"` pairs, for example:

```json
{
  "props_menu_title": "Props menu",
  "props_menu_subtitle": "Manage your props",
  "action_place_prop": "Place prop"
}