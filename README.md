# About

This package provides syntax highlighting for the character sheets created by [npc](https://github.com/aurule/npc). The sheets are mostly markdown files with the addition of tags and special sections.

Each tag appears on its own line and starts with an at (`@`) symbol. Recognized tags will be highlighted differently from free-form tags, but you can tag characters however you want. Section headings must appear on their own line and consist of one or two words wrapped in two hyphens, like `--Section Name--`. The only section that gets special treatment is the Stats section, which has game-specific formatting for certain systems.

The supported file types right now are:

| extension | game                                                       |
|:----------|:-----------------------------------------------------------|
| .dnd3     | Dungeons & Dragons 3.5                                     |
| .nwod     | New World of Darkness 1e (human, changeling, and werewolf) |
| .fate     | FATE Core and Eclipse Phase addon                          |
| .npc      | Generic character info sheet                               |

# Installation

The best way to install NPC Sheets is through [Package Manager](https://packagecontrol.io/).

Alternatively, you can download the latest code into your Sublime Text `Packages` directory, either by cloning the repository or by downloading the [latest release](https://github.com/aurule/npc_sheets/releases).
