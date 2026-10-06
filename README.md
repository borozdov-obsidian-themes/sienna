# Borozdov Sienna

A theme from the Borozdov collection. Two faces — light **Blush**, serif headlines on white
paper with one peach card, and dark **Cocoa**, the same page by lamplight. A quiet grey
system, soft 20px cards, pill buttons, and one pair of colours — peach and sienna — for
what you act on.

![Borozdov Sienna in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/sienna/main/screenshots/light.png)

![Borozdov Sienna in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/sienna/main/screenshots/dark.png)

## Principles

- **A serif that whispers.** Old Standard at weight 400 for the title and the two largest
  headings, tracked in a little as it grows; the serif never goes bold. Everything else is
  the platform's own sans.
- **Ink on kraft paper.** The page is achromatic — white, mist, fog and ink. Colour is one
  pair: a peach wash for the note callout, tags, the highlighter and the open file, and
  sienna ink for links, the caret, a checked task, a toggle and the main button.
- **Flat cards, floating panels.** Callouts, code and embeds are flat mist cards with 20px
  corners and no shadow; only menus, popovers and modals earn a faint lift.
- **Pills for actions.** Buttons and tags are pills; plain buttons are ghosts with a rim,
  and the one that matters is filled sienna with peach text.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as flat cards with the title in the type's colour; the plain note in peach
- Pull quotes in the serif, a size up, behind a sienna rule
- Tables as white cards with a hairline frame, a mist header band and tabular figures
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Ember**. Install Borozdov Ember under Settings → Appearance → Themes → Manage, then the
[Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and choose
**Sienna** under Style Settings → Borozdov Ember → Variant. The variant brings this
theme's palette, type and corners; its own layout, and its embedded font if it has one,
come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/sienna/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Sienna/`, then choose Borozdov Sienna under
Settings → Appearance → Themes.

## Font

Old Standard Regular (© 2006–2011 Alexey Kryukov, 2019–2023 Robert Alessi, 2023 Antonis
Tsolomitis) is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License 1.1 —
see [`fonts/OFL.txt`](fonts/OFL.txt). One weight, Latin and Cyrillic, for the title, the two
largest headings and pull quotes only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Румянец» — заголовки с
засечками на белой бумаге и одна персиковая карточка, и тёмный «Какао» — та же страница при
свете лампы. Тихая серая система, мягкие карточки 20px, кнопки-пилюли и одна пара цветов,
персиковый и сиена, для того, что вы делаете. В каталоге тема живёт вариантом Borozdov Ember: установите Borozdov Ember и плагин Style Settings, затем выберите Sienna в Style Settings → Borozdov Ember → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
