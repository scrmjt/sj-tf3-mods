# Contributing

This repository takes issues, feature requests and translations. It holds no source code, so there is nothing else to send a pull request
against: a pull request that touches anything but `translations/` will be closed.

## Translating by pull request

1. Fork this repository.
2. Edit `translations/<language>.json` for your language (`de`, `es`, `fr`, `it`, `ja`, `ko`, `nl`, `pl`, `pt_BR`, `ru`, `zh_CN`, `zh_TW`).
   Fix a wrong text or fill an empty `""`. Do not change the English keys. Read [translations/README.md](translations/README.md) first:
   keep the `{placeholders}`, use the game's own wording, and mind mod.io's word filter.
3. Open a pull request with the template; say which mod's texts you changed, if you know.
4. ScramJet reads the changes, merges them into the mods' source by hand and releases them with the next version of the mod.
   Your name (or the name you want shown) goes into that mod's patch notes and into the translation credits.

You do not have to play-test every line, but the texts end up in narrow windows: if you can, look at yours in the game.

## One text, no pull request

Use the **Translation** issue form: language, mod, the current text, your better text.

## Licence

Everything in this repository is under [CC0 1.0](LICENSE) (public domain): anyone may use the translations for anything. By
opening a pull request you agree that your contribution is under CC0 1.0 too. You are still credited in the mod's patch notes.

## Everyone

Be kind and keep to the point. Disagree about the idea, not the person. Harassment and insults get a comment removed and the person blocked.
