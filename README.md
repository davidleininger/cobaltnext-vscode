# CobaltNext Theme for VS Code

[![Version](https://vsmarketplacebadge.apphb.com/version/dline.CobaltNext.svg)](https://marketplace.visualstudio.com/items?itemName=dline.CobaltNext)

### Original Version - "Cobalt Next"
![Screenshot Original](https://raw.githubusercontent.com/davidleininger/cobaltnext-vscode/master/images/screenshot.png)

### Dark Version - "Cobalt Next Dark"
![Screenshot Dark](https://raw.githubusercontent.com/davidleininger/cobaltnext-vscode/master/images/screenshot-dark.png)

### Minimal Version - "Cobalt Next Minimal"
![Screenshot Minimal](https://raw.githubusercontent.com/davidleininger/cobaltnext-vscode/master/images/screenshot-minimal.png)
*This one is not super different from `Cobalt Next Dark`, but it has a few extra treats to clean things up a bit. Maximize your expereince by using [Caleb Porzio's](https://twitter.com/calebporzio) [Make VS Code Awesome](https://makevscodeawesome.com/) Course. _Silence the noise and hide all the crap!_

# Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Cobalt Next`.
3. Click **Install** to install it.
4. Click **Reload** to reload the your editor
5. File > Preferences > Color Theme > **Cobalt Next** or change it in User Settings.
  - Try the dark version with **Cobalt Next Dark**.
  - Try the minimal version with **Cobalt Next Minimal**. Spice it up with [Caleb Porzio's](https://twitter.com/calebporzio) [Make VS Code Awesome](https://makevscodeawesome.com/) Course.
6. Optional: Use the recommended settings below for best experience

## Recommended Settings

```js
{
  "editor.bracketPairColorization.enabled": true, // Native bracket matching - colors included in theme
  "color-highlight.markerType": "underline", // requires Color Highlight Extension
  "color-highlight.markRuler": false, // requires Color Highlight Extension
  "editor.colorDecorators": false, // using Color Hightlight instead
  "editor.cursorBlinking": "solid",
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 3,
  "editor.letterSpacing": 0.5,
  "editor.lineHeight": 32,
  "editor.fontFamily": "Operator Mono, Menlo, monospace",
  "editor.fontSize": 16,
  "editor.fontWeight": "300",
  "editor.matchBrackets": "never", // using Subtle Match Brackets instead
  "editor.tabSize": 2,
  "files.trimTrailingWhitespace": true,
  "subtleBrackets.style": { // requires Subtle Match Bracket Extension
    "global": {
      "borderColor": "#fac863",
      "borderWidth": "2px"
    }
  },
  "terminal.integrated.fontFamily": "Inconsolata for Powerline",
  "terminal.integrated.fontSize": 14,
  "window.title": "${dirty} ${activeEditorMedium}${separator}${rootName}",
  "workbench.colorTheme": "Cobalt Next",
  "workbench.editor.tabSizing": "shrink",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "newUntitledFile",
}
```

## Want active and inactive window borders?
Personally, I don't like active window borders, but if you'd like it, here are two examples.Open the Command Palette with Ctrl+Shift+P (Windows) or Cmd+Shift+P (Mac) and select **Preferences: Open Settings (JSON)**.

_subtle_
```js
"workbench.colorCustomizations": {
  "window.activeBorder": "#4f5b66",
  "window.inactiveBorder": "#1b2b34",
}
```

_full color_
```js
"workbench.colorCustomizations": {
  "window.activeBorder": "#5fb3b3",
  "window.inactiveBorder": "#1b2b34",
}
```

### Suggested Extensions For Theme
* [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
* [Subtle Match Brackets](https://marketplace.visualstudio.com/items?itemName=rafamel.subtle-brackets)

### Suggested Terminal Settings

![Terminal Preview](https://github.com/davidleininger/cobaltnext-vscode/blob/master/images/terminal.png?raw=true)

[ZSH](http://ohmyz.sh/) is a great shell and it adds support for git. I would suggest using the [Cobalt2 Theme](https://github.com/wesbos/Cobalt2-iterm) for ZSH. Make sure to get [Inconsolata for Powerline](https://github.com/powerline/fonts/blob/master/Inconsolata/Inconsolata%20for%20Powerline.otf) so that you can get all of the special characters in prompt.

## VS Code Icon

Want to change up your VS Code Icon to match your theme? _Done._

### New Icon
![VS Code Icon Preview](https://github.com/davidleininger/cobaltnext-vscode/blob/master/images/vscode-CobaltNext-New.png?raw=true)

[Download the .icns file.](https://github.com/davidleininger/cobaltnext-vscode/blob/master/images/vscode-CobaltNext-New.icns) (Mac)

[Download the .ico file.](https://github.com/davidleininger/cobaltnext-vscode/blob/master/images/vscode-CobaltNext-New.ico) (Win)

### Old Icon - Incase you miss it
![VS Code Icon Preview](https://github.com/davidleininger/cobaltnext-vscode/blob/master/images/vscode-cobaltnext.png?raw=true)

[Download the .icns file.](https://github.com/davidleininger/cobaltnext-vscode/blob/master/images/vscode-cobaltnext.icns) (Mac)

[Download the .ico file.](https://github.com/davidleininger/cobaltnext-vscode/blob/master/images/vscode-cobaltnext.ico) (Win)

**Enjoy!**
