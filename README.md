![](https://raw.githubusercontent.com/victoreduardobarreto/star-night/master/images/background.png)


# Previews
#### style colors
![](https://raw.githubusercontent.com/victoreduardobarreto/star-night/master/images/preview7.png)

#### java script
![](https://raw.githubusercontent.com/victoreduardobarreto/star-night/master/images/preview1.png)

#### css
![](https://raw.githubusercontent.com/victoreduardobarreto/star-night/master/images/preview2.png)

#### php
![](https://raw.githubusercontent.com/victoreduardobarreto/star-night/master/images/preview4.png)

#### html
![](https://raw.githubusercontent.com/victoreduardobarreto/star-night/master/images/preview5.png)

#### terminal
![](https://raw.githubusercontent.com/victoreduardobarreto/star-night/master/images/preview3.png)

---

_For the screenshots, I'm using:_

- [Roboto Mono Light](https://fonts.google.com/specimen/Roboto+Mono)
- [File-icons](https://marketplace.visualstudio.com/items?itemName=file-icons.file-icons)
- [Indenticator](https://marketplace.visualstudio.com/items?itemName=SirTori.indenticator)
- [BreadCrumb in StatusBar](https://marketplace.visualstudio.com/items?itemName=danields761.status-bar-breadcrumb)

```json
// StatusBar configuration | put this code on your settings.json
"breadcrumbs.enabled": false,
```

- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)

```json
// bracker Pair colorizer configuration | put this code on your settings.json

"bracketPairColorizer.showBracketsInGutter": true,
    "bracketPairColorizer.consecutivePairColors": [
        "()",
        "[]",
        "{}",
        ["#b1b1b3"],
        "grey",
    ],
```

- [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) to this plugin special details below

### Blur and Gradient
To enable the special effects you must download the additional code [here](https://raw.githubusercontent.com/victoreduardobarreto/star-night/master/style_extra.css) and setup downloaded file on settings.json with the code below.


![](https://raw.githubusercontent.com/victoreduardobarreto/star-night/master/images/preview6.png)

```json
// custom CSS and JS Loader configuration | put this code on your settings.json
    "vscode_custom_css.imports": [
        "file:////home/youruser/Downloads/style_extra.css"
    ],
    "vscode_custom_css.policy": true,
```
After configuration you must run the command: CTRL+SHIFT+P and type "Enable Custom CSS and JS".

Enjoy!

---