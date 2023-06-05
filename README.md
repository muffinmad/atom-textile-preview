[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://stand-with-ukraine.pp.ua)

# Textile preview package

Show the rendered HTML for text marked-up with [Textile](https://github.com/textile)

Based on [markdown-preview](https://github.com/atom/markdown-preview) and [textile-js](https://github.com/borgar/textile-js)

## Keybinding

You can define your own hotkey in your keymap.cson like this:
```
'atom-text-editor':
  'ctrl-shift-t': 'textile-preview:toggle'
```
But <kbd>ctrl</kbd>-<kbd>shit</kbd>-<kbd>t</kbd> is used to reopen closed tab and <kbd>ctrl</kbd>-<kbd>alt</kbd>-<kbd>t</kbd> is for nuclide fuzzy finder. Thats why i don't like making the default hotkey. There are too many hotkeys already.
