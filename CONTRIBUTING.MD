## How to contribute translations (Crowdin)

Translations are managed via Crowdin.  
Please **do not open pull requests that directly edit locale JSON files** unless you are working on the English source strings.

- To contribute translations, join the Crowdin project (link here when available).
- Use Crowdin’s interface to add or improve translations.
- Keep placeholders (for example `{player}`, `{count}`, `%s`, etc.) exactly as in the source text.
- Approved translations in Crowdin will be synced back to this repository.

If you need to add a **new key** (for a new feature), update the English JSON file in this repo; the new key will then appear in Crowdin for all languages.