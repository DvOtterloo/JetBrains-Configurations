# JetBrains Configurations

Some settings are exclusively for **Intellij** or *Webstorm*

## Custom Keymap

| Key binding                   | Action                        |
| :---------------------------- | :---------------------------- |
| `F1`                          | Refactor this...              |
| `F2`                          | Rename                        |
| `SHIFT + F2`                  | Change Signature...           |
| `F3`                          | Generate...                   |
| `F4`                          | Switch Case                   |
| `F5`                          | **Debug** / *Run*             |
| `SHIFT + F5`                  | **Debug...** / *Run...*       |
| `Alt + SHIFT + F5`            | Stop                          |
| `F6`                          | Reformat Code                 |
| `SHIFT F6`                    | **Rearrange Methods**         |
| `F7`                          | Previouos Highlighted Error   |
| `F8`                          | Previous Occurence            |
| `F9`                          | Next Occurence                |
| `F10`                         | Next Highlighted Error        |
| `F11`                         | Toggle Fullscreen             |
| `F12`                         | Quick Definition              |
| `SHIFT + F12`                 | Quick Documentation           |
| `F13`                         | Toggle Bookmark with Mnemonic |
| `SHIFT + F13`                 | Show Bookmarks                |
| `F17`                         | Back                          |
| `F18`                         | Previous Change               |
| `F19`                         | Next Change                   |
| `F20`                         | Forward                       |
| `Ctrl + J`                    | Select Previous Tab           |
| `Ctrl + ;`                    | Select Next Tab               |
| `Ctrl + K`                    | Move Line Up                  |
| `Ctrl + L`                    | Move Line Down                |
| `Ctrl + W`                    | Close                         |
| `Ctrl + SHIFT + W`            | Close other tabs              |
| `Ctrl + Y`                    | Redo                          |
| `Ctrl + Shift + Y`            | Delete Line                   |
| `Ctrl + [1-9]`                | Go to Bookmark [1-9]          |
| `Ctrl + Shift + Middle click` | Open in terminal              |
| `Ctrl + Middle click`         | Show in explorer              |
| `Ctrl + Tab`                  | Switcher                      |
| `SHIFT + Escape`              | Hide active window            |


## Plugins

- CheckStyle-IDEA
- Rainbow Brackets
- **Clean Code Method Rearranger**
- CodeGlance2
- **Cursive**
- Nyan Progress Bar
- SonarLint
- String Manipulation
- Statistic
- **Ideolog**

## Editor

* Editor > Inlay Hints > Show Hints for: `FALSE`

## Appearance

* Theme: One Dark Vivid Italic
  * Editor > Color Scheme > Language Defaults> Block-, Doc- and Line comment > Foreground color: `#00FFD9`
* Font
  * Font: Fira Code
  * Size: 14
  * Line spacing: 1.25
  * Enable font Ligatures: `TRUE`

## Live templates

| Abbr     | Template text                                                |
| -------- | ------------------------------------------------------------ |
| `pf`     | `private final`                                              |
| `pv`     | `private void`                                               |
| `logger` | `private static final org.slf4j.Logger logger = org.slf4j.LoggerFactory.getLogger($CLASS$.class);` |
| `sb`     | `var sb = new StringBuilder();`                              |



## Inspections

uncheck `Actual method parameter is the same constant`

uncheck `Result of method call returning a promise is ignored`

Change `Optional.get is called without isPresent() check` Severity level to `Weak Warning` and Highlighting in Editor to `Text style warning`

