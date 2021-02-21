# obsidian-plugin-toc

Create a tables of contents for a note.

This plugin exposes the following commands:

| Action                                          | Hotkey           |
| ----------------------------------------------- | ---------------- |
| Create full table of contents                   | Blank by default |
| Create table of contents for next heading level | Blank by default |

And the following settings:

| Setting              | type                 | Default    |
| -------------------- | -------------------- | ---------- |
| List Style           | 'bullet' or 'number' | 'bullet'   |
| Title                | 'string'             | undefined' |
| Minimum header depth | number               | 2          |
| Maximum header depth | number               | 6          |

## Installing

Unzip the [latest release](https://github.com/hipstersmoothie/obsidian-plugin-toc/releases/latest) into your `<vault>/.obsidian/plugins/` folder.

## Usage

This plugin will create a table of content for the sub-heading of the current heading level.

**Example:**

_Input:_ Run "Table of Contents" under a level 2 heading  
_Output:_ "Table of Contents" only contains subheadings of that level2 heading
