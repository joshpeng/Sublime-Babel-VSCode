# Sublime Babel [![VS Code marketplace button](http://vsmarketplacebadge.apphb.com/installs/joshpeng.sublime-babel-vscode.svg)](https://marketplace.visualstudio.com/items?itemName=joshpeng.sublime-babel-vscode)
When using your favorite theme, Visual Studio Code doesn't always display syntax highlight colors as expected. This extension tries to mimic Sublime's [babel-sublime](https://packagecontrol.io/packages/Babel) package as much as possible to address poor coloring.

Other JS grammars are currently either incorrect or incomplete.

| Grammar                                  | Description                              |
| ---------------------------------------- | ---------------------------------------- |
| [Sublime Babel](https://marketplace.visualstudio.com/items?itemName=joshpeng.sublime-babel-vscode) | Syntax highlighting working with most preexisting .tmThemes |
| [JavaScript Atom Grammar](https://marketplace.visualstudio.com/items?itemName=ms-vscode.js-atom-grammar) | Immature JSX support                     |
| [Babel ES6/ES7](https://marketplace.visualstudio.com/items?itemName=dzannotti.vscode-babel-coloring) | Incorrect colors in many scenarios due to missing or incorrect scopes |
| [Latest TypeScript and JavaScript Grammar](https://marketplace.visualstudio.com/items?itemName=ms-vscode.typescript-javascript-grammar) | Incorrect colors in many scenarios due to non-standard scoping |

**Note**: VS Code may interpret scopes slightly differently than Sublime so it won't always be 100% the same. You may need to tweak your theme's scoping a little bit to match it exactly. Hopefully it is close enough though out-of-the-box for the majority of preexisting tmThemes.



## Installation

1. Uninstall any preexisting JavaScript grammar extensions (e.g. [Latest TypeScript and JavaScript Grammar](https://marketplace.visualstudio.com/items?itemName=ms-vscode.typescript-javascript-grammar), [Babel ES6/ES7](https://marketplace.visualstudio.com/items?itemName=dzannotti.vscode-babel-coloring)) to prevent conflicts
2. Install Sublime Babel via `ext install sublime-babel-vscode` in Command Palette
3. When opening a `.js` or `.jsx` file, ensure the language mode is set to `JavaScript (Babel)` or `JavaScript React (Babel)`

![statusbar](https://raw.githubusercontent.com/joshpeng/Sublime-Babel-VSCode/master/images/statusbar.png)



## Suggested Color Themes

For best results, please consider using these optimized themes. Other ported themes will work too, but may not necessarily handle the differences between Sublime and VS Code properly.

[One Dark](https://marketplace.visualstudio.com/items?itemName=joshpeng.theme-onedark-sublime)

[Charcoal Oceanic Next](https://marketplace.visualstudio.com/items?itemName=joshpeng.theme-charcoal-oceanicnext)

[Tomorrow Kit](https://marketplace.visualstudio.com/items?itemName=joshpeng.theme-tomorrowkit-sublime)



## Comparisons

Here is a quick example of the improved grammar compared against the popular [Babel ES6/ES7](https://marketplace.visualstudio.com/items?itemName=dzannotti.vscode-babel-coloring) extension on the marketplace. Notice how [Babel ES6/ES7](https://marketplace.visualstudio.com/items?itemName=dzannotti.vscode-babel-coloring) handles comments and strings incorrectly.

![Babel ES6/ES7](https://raw.githubusercontent.com/joshpeng/Sublime-Babel-VSCode/master/images/babel-es6.png)

![Sublime Babel](https://raw.githubusercontent.com/joshpeng/Sublime-Babel-VSCode/master/images/sublime-babel.png)

![React](https://raw.githubusercontent.com/joshpeng/Sublime-Babel-VSCode/master/images/react.png)



## Changelog
Please see [here](https://github.com/joshpeng/Sublime-Babel-VSCode/blob/master/CHANGELOG.md).