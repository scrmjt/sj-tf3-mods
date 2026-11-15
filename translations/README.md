# Translating the SJ mods

Every text the SJ mods show, in the 12 languages besides English, is in one file per language here: `<language>.json`
(`de`, `es`, `fr`, `it`, `ja`, `ko`, `nl`, `pl`, `pt_BR`, `ru`, `zh_CN`, `zh_TW`).

Each file has two parts:

- `strings`: the texts in the game's windows (buttons, column titles, tooltips, settings).
- `description_lines`: the lines of the mods' mod.io descriptions and patch notes.

The key of every entry is the **English** text, the value is the text in the file's language. An empty value `""` means
nobody has translated it yet. Fix a wrong value or fill an empty one. **Do not change a key**: it is how the mods find the text.

## Rules

- **Keep the `{placeholders}` exactly as they are** (`{time}`, `{h}`, `{m}`, `{count}` ...): the mod replaces them with numbers and names.
  You may move them within the sentence.
- **Use the game's own wording** for anything the game itself has: window names, button names, cargo names, "Lines", "Stations".
  Play the game in your language and copy what it says.
- Title Case for controls, window titles, column headings and setting names where your language does that in the game;
  ordinary sentences stay ordinary sentences.
- Keep it short: the windows are narrow, a long text is cut off or pushes a column out of place.
- **mod.io's word filter** stars out some words on the mods' mod.io pages, so it matters in `description_lines` (not in the game's
  windows). In Spanish and Brazilian Portuguese never write the singular "vehículo" or
  "veículo"; write "unidad" (es) or "unidade" (pt_BR). The plurals are fine.
- Save the file as UTF-8, keep the indentation (2 spaces) and the sorted order. Do not reformat the file.

Then open a pull request: see `CONTRIBUTING.md`. These files are generated from the mods' source; a pull request is read, checked and merged
into the source by hand, and you are credited in the mod's patch notes.
