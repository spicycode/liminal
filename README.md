# Liminal

**Liminal** is an opinionated minimalistic VS Code theme based on Subliminal that is based on [Subliminal](https://github.com/gaearon/subliminal). See [Credits](#credits) for a detailed lineage.

## Disclaimer

This theme is intentionally focused on a small subset of VS Code features that I use (basic editing, file tree, and debugger) and may not work well in other scenarios. However, I’ll happily take changes that respect the design intention but fix rough edges in parts I didn’t polish (e.g. viewing diffs, terminal, or search).

The theme is intentionally [very opinionated](https://mobile.twitter.com/dan_abramov/status/990768800717996032) and we may disagree about some of its choices. Philosophically, it owes some inspiration to [Alabaster](https://github.com/tonsky/vscode-theme-alabaster) and [White](https://github.com/arthurwhite/white-theme-vscode). I love colors though.

The config is pretty hacky and was only tested with [Sublime Babel](https://github.com/joshpeng/Sublime-Babel-VSCode) syntax. The theme is probably horribly broken with other languages (even JSON or CSS). Pull requests to fix this that adhere to the theme’s JS look and feel are welcome.

## More Than a Theme

To me, this isn’t just a theme, but an attempt to recreate a more minimalistic experience that I’m used to from Sublime Text. I suggest using these settings for the intended effect:

```js
{
    // ...
    "editor.fontSize": 18,
    "editor.folding": false,
    "editor.hideCursorInOverviewRuler": true,
    "editor.lineHeight": 26,
    "editor.lineNumbers": "off",
    "editor.matchBrackets": false,
    "editor.minimap.enabled": false,
    "editor.occurrencesHighlight": false,
    "editor.overviewRulerBorder": false,
    "editor.renderIndentGuides": false,
    "editor.renderLineHighlight": "none",
    "editor.scrollbar.horizontal": "hidden",
    "explorer.openEditors.visible": 0,
    "window.zoomLevel": 0,
    "workbench.activityBar.visible": false,
    "workbench.colorTheme": "Subliminal",
    "workbench.iconTheme": null,
    "workbench.editor.showIcons": false,
    "workbench.statusBar.visible": false,
}
```

## Credits

Forked from [this theme](https://github.com/marioterron/one-dark-bimbo-theme) which is itself based on [these](https://github.com/pawelgrzybek/bimbo-theme) [two](https://github.com/Binaryify/OneDark-Pro) themes. Most of the original credit goes to the [Oceanic Next](https://github.com/voronianski/oceanic-next-color-scheme) color scheme by [Dmitri Voronianski](https://github.com/voronianski). I ended up changing most colors and their mappings quite significantly though.

Philosophically, it owes some inspiration to [Alabaster](https://github.com/tonsky/vscode-theme-alabaster) and [White](https://github.com/arthurwhite/white-theme-vscode). I love colors though.

The UI chrome styling is inspired by [Spacegray](https://github.com/kkga/spacegray) by [Gadzhi Kharkharov](https://github.com/kkga) although my theme is much more sloppy. If you can make it less sloppy and more in the spirit of the original, send a PR.

## License

MIT
