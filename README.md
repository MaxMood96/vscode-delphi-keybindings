[![](https://vsmarketplacebadges.dev/version-short/alefragnani.delphi-keybindings.svg)](https://marketplace.visualstudio.com/items?itemName=alefragnani.delphi-keybindings)
[![](https://vsmarketplacebadges.dev/downloads-short/alefragnani.delphi-keybindings.svg)](https://marketplace.visualstudio.com/items?itemName=alefragnani.delphi-keybindings)
[![](https://vsmarketplacebadges.dev/rating-short/alefragnani.delphi-keybindings.svg)](https://marketplace.visualstudio.com/items?itemName=alefragnani.delphi-keybindings)
[![](https://img.shields.io/github/actions/workflow/status/alefragnani/vscode-delphi-keybindings/main.yml?branch=master)](https://github.com/alefragnani/vscode-delphi-keybindings/actions?query=workflow%3ACI)

<p align="center">
  <br />
  <a title="Learn more about Delphi Keymap" href="http://github.com/alefragnani/vscode-delphi-keybindings"><img src="https://raw.githubusercontent.com/alefragnani/vscode-delphi-keybindings/master/images/vscode-delphi-keybindings-logo-readme.png" alt="Delphi Keymap Logo" width="60%" /></a>
</p>

# What's new in Delphi Keymap 9.8

* Published to **Open VSX**
* Adds **Localization** support
* Adds new setting to choose Delphi release for `DocWiki`
* Adds **Web** support

# Support

**Delphi Keymap** is an open source extension created for **Visual Studio Code**. While being free and open source, if you find it useful, please consider supporting it.

<table align="center" width="60%" border="0">
  <tr>
    <td>
      <a title="Paypal" href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=EP57F3B6FXKTU&lc=US&item_name=Alessandro%20Fragnani&item_number=vscode%20extensions&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif"/></a>
    </td>
    <td>
      <a title="GitHub Sponsors" href="https://github.com/sponsors/alefragnani"><img src="https://raw.githubusercontent.com/alefragnani/oss-resources/master/images/button-become-a-sponsor-rounded-small.png"/></a>
    </td>
    <td>
      <a title="Patreon" href="https://www.patreon.com/alefragnani"><img src="https://raw.githubusercontent.com/alefragnani/oss-resources/master/images/button-become-a-patron-rounded-small.png"/></a>
    </td>
  </tr>
</table>

# Delphi Keymap

This extension ports popular **Delphi** keyboard shortcuts to **Visual Studio Code**.

# Features

## Shortcuts included

You can see all the keyboard shortcuts in the extension's contribution list. Check some of them:

Command | Keyboard Shortcut |   |  Command | Keyboard Shortcut
------- | ----------------- | - |------- | -----------------
Save All | Ctrl + Shift + S |  | Find / Replace | Ctrl + H
Format | Ctrl + D | | Go To Line | Alt + G
IDE Insight | Ctrl + . | | Find Local References | Shift + Ctrl + Enter
Refactor / Rename | Ctrl + Shift + E | | Find Original Symbol | Ctrl + G
Comment Line | Ctrl + ; | | Compile | Ctrl + F9
Redo | Alt + Shift + Backspace | | Run | F9 |
Delete Line | Ctrl + Y | | Step Over | F8
Show Snippets | Ctrl + J | | Step Into | F7
Help Insight | Ctrl + Shift + H | | Toggle Breakpoint | F5
Help | F1 | | Evaluate/Modify | Ctrl + F7

## Available Settings

* Choose the Delphi version to be used in DocWiki (`Alexandria` by default)
```json
    "delphiKeybindings.delphiVersionInDocWiki": "Tokyo"
```

## Bookmarks

If you are looking for the same **Bookmarks** experience from **Delphi**, try out my [Numbered Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.numbered-bookmarks) extension :wink: 

## License

[GPL-3.0](LICENSE.md) &copy; Alessandro Fragnani