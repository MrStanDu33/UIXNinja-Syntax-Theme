# UIXNinja Syntax Theme, for Visual Studio Code

Look on Visual Studio Code's [Marketplace](https://marketplace.visualstudio.com/items?itemName=danielsrothstan.uixninja-theme)

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.png?style=flat)](https://github.com/MrStanDu33/UIXNinja-Syntax-Theme/issues)
[![GitHub release](https://img.shields.io/github/release/MrStanDu33/UIXNinja-Syntax-Theme.png)](https://GitHub.com/MrStanDu33/UIXNinja-Syntax-Theme/releases/)

[![GitHub license](https://img.shields.io/github/license/MrStanDu33/UIXNinja-Syntax-Theme.png)](https://github.com/MrStanDu33/UIXNinja-Syntax-Theme/blob/master/LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.png)](https://github.com/MrStanDu33/UIXNinja-Syntax-Theme/graphs/commit-activity)

[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.png)](https://code.visualstudio.com/)
[![Badge for installs for Visual Studio Code extension danielsrothstan.uixninja-theme](https://vsmarketplacebadge.apphb.com/installs/danielsrothstan.uixninja-theme.png)](https://marketplace.visualstudio.com/items?itemName=danielsrothstan.uixninja-theme)

Handmade syntax theme for Visual Studio Code inspired by
[this Dribbble shot](https://dribbble.com/shots/2932388-code-editor-redesign)
by
[uixninja](https://dribbble.com/uixninja),
based on
[this Atom theme](https://github.com/licatajustin/ninja-ui-syntax)

![Banner DANIELS-ROTH Stan x UIXNinja](https://raw.githubusercontent.com/MrStanDu33/UIXNinja-Syntax-Theme/master/assets/banner.png)

## Installation

Launch *Quick Open*:
-   <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
-   <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
-   <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:

```shell
ext install uixninja-theme
```

And pick the one by **Daniels-Roth Stan** (me) as author.

## GitHub Repository Clone

Change to your `.vscode/extensions` [VS Code extensions directory](https://code.visualstudio.com/docs/extensions/install-extension#_side-loading).
Depending on your platform it is located in the following folders:

-   <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> **Linux** `~/.vscode/extensions`
-   <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> **macOs** `~/.vscode/extensions`
-   <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> **Windows** `%USERPROFILE%\.vscode\extensions`

Clone the Material Theme repository as `danielsrothstan.uixninja-theme`:

```shell
git clone https://github.com/MrStanDu33/UIXNinja-Syntax-Theme.git danielsrothstan.uixninja-theme
```

## Activate theme

Launch *Quick Open*:

-   <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl + Shift + P`
-   <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘ + Shift + P`
-   <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl + Shift + P`

Type `theme`, choose `Preferences: Color Theme`, and select Ninja-UI Syntax Theme from the list.

## Screenshots

*JavaScript*
![Screenshot of JavaScript](https://raw.githubusercontent.com/MrStanDu33/UIXNinja-Syntax-Theme/master/assets/vue.js.png)

*PHP*
![Screenshot of PHP](https://raw.githubusercontent.com/MrStanDu33/UIXNinja-Syntax-Theme/master/assets/laravel.php.png)

*HTML5*
![Screenshot of HTML5](https://raw.githubusercontent.com/MrStanDu33/UIXNinja-Syntax-Theme/master/assets/angular.js.html.png)

*CSS3*
![Screenshot of CSS3](https://raw.githubusercontent.com/MrStanDu33/UIXNinja-Syntax-Theme/master/assets/font-awesome.css.png)

*C*
![Screenshot of C](https://raw.githubusercontent.com/MrStanDu33/UIXNinja-Syntax-Theme/master/assets/git.c.png)

*Ruby*
![Screenshot of Ruby](https://raw.githubusercontent.com/MrStanDu33/UIXNinja-Syntax-Theme/master/assets/ruby.rb.png)

## Recommended settings for a better experience

I usually use this theme with theses settings :
```js
{
    "editor.fontFamily": "museo sans, Consolas, 'Courier New', monospace",
    "editor.fontLigatures": true,
    "editor.fontSize": 16,
    "vscode_custom_css.imports": ["URL_TO_StyleVSCode.css"],
    "background.customImages": ["URL_TO_Background.png"],
    "background.useDefault": false,
    "background.useFront": false,
    "workbench.colorTheme": "Ninja-UI Syntax Theme",
    "editor.fontWeight": "500",
    "vscode_custom_css.policy": true,
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "comment",
                "settings": {
                    "fontStyle": "italic"
                }
            }
        ]
    },
}
```

If you want to install my custom Background and my custom stylesheet in your Visual Studio Code for a better experience, follow theses steps:

First, install [this extension](https://marketplace.visualstudio.com/items?itemName=shalldie.background) to add a custom background and [this extension](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) to load a custom CSS file (to change fonts).

*It seems that background extension is causing Visual Studio Code to detect a sort of corruption. Don't mind the warning message and close it, or uninstall the background extension.*

Then, you will find in this repository a folder named `addons` containing two files: `StyleVSCode.css` and `Background.png`.

Place them somewhere on your computer (or inside this theme folder), and then add theses lines in your `settings.json` :

*for Background.png :*
```js
{
    "background.customImages": ["URL_TO_Background.png"],
    "background.useDefault": false,
    "background.useFront": false,
}
```

*for StyleVSCode.css :*
```js
{
    "vscode_custom_css.imports": ["URL_TO_StyleVSCode.css"],
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "comment",
                "settings": {
                    "fontStyle": "italic"
                }
            }
        ]
    },
}
```

Finally, restart Visual Studio Code and enjoy your new workstation !

As you can see, I am using [Museo Sans font](https://www.dafontfree.net/freefonts-museo-sans-f95072.htm) and [Operator Mono font](https://www.typography.com/fonts/operator/styles/), both can be found on those websites, but you can change for any other fonts.

## License

MIT @ [Daniels-Roth Stan](https://daniels-roth-stan.fr)
