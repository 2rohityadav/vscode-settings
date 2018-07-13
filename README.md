# VS Code Settings

# Extensions

## JavaScript

* [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
  * Contains code snippets for JavaScript in ES6 syntax
* [Vue 2 Snippets](https://marketplace.visualstudio.com/items?itemName=hollowtree.vue-snippets)
  * This extension adds Vue 2 Code Snippets and Syntax Highlight into Visual Studio Code.
* [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
  * Provide you Javascript and React/Redux snippets in ES7 with babel plugins features for Vs Code
* [Angular 6 Snippets - TypeScript, Html, Angular Material, ngRx, RxJS & Flex Layout](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
  * TypeScript and Html snippets and code examples for Angular 2,4,5 & 6.
* [Angular v6 Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)
  * Adds snippets for Angular for TypeScript and HTML.
* [ExpressSnippet](https://marketplace.visualstudio.com/items?itemName=vladmrnv.expresssnippet)
  * Collection of snippets for Express
* [FreeMarker](https://marketplace.visualstudio.com/items?itemName=dcortes92.FreeMarker)
  * FreeMarker syntax with square brackets is fully supported
* [tslint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
  * Integrates the tslint linter for the TypeScript language

## HTML Framework

* [Bootstrap 4 & Font awesome snippets](https://marketplace.visualstudio.com/items?itemName=thekalinga.bootstrap4-vscode)
  * Containing Bootstrap 4, Font awesome 4 & Font Awesome 5 Free & Pro snippets

## Workflow

* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * Automatically rename paired HTML/XML tag

## IntelliSense/AutoComplete

* [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  * Provides CSS class name completion for the HTML class attribute based on the definitions found in your workspace or external files referenced through the link element
* [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  * Autocompletes npm modules in import/require statements
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * Autocompletes filenames
* [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
  * Vue tooling

## Style/Formatting

* [Prettier Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * VS Code package to format your JavaScript / TypeScript / CSS
* [Better Comments](https://marketplace.visualstudio.com/items?itemName=OmarRwemi.BetterComments)
  * Help you create more human-friendly comments in your code.
* [language-stylus](https://marketplace.visualstudio.com/items?itemName=sysoev.language-stylus)
  * Adds syntax highlighting and code completion to Stylus files

## Themes/Color

* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=coenraads.bracket-pair-colorizer)
  * Matching parenthesis and curly brackets to with colors
* [highlight-matching-tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)
  * Highlight matching opening or closing tags.
* [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons)
  * Icons for Visual Studio Code
* [Monokai Pro](https://www.monokai.pro/)
* [:emojisense:](https://marketplace.visualstudio.com/items?itemName=bierner.emojisense)
* [Atom One Dark Theme](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)
* [Babel JavaScript](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel)
  * JavaScript syntax highlighting for ES201x, React JSX, Flow and GraphQL.

## Testing

* [Jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest)
  * Highlights the errors next to the expect functions and adds syntax highlighting to snapshot files
* [Jest Snippets](https://marketplace.visualstudio.com/items?itemName=andys8.jest-snippets)
  * Code snippets for testing framework Jest

## Useful/Extra

* [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  * Display inline the size of the required/imported package
* [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  * Evaluate code/logs inline and show results in the editor
* [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Collaborative editing, debugging, and more inside VS Code
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  * Launch a development local Server with live reload feature for static & dynamic pages. 
* [LoremZombie](https://marketplace.visualstudio.com/items?itemName=angelgonzalez.loremzombie)
  * Dummy content

# Settings

```json
{
    "editor.tabCompletion": true,
    "editor.snippetSuggestions": "top",
    "editor.quickSuggestions": {
      "other": true,
      "comments": true,
      "strings": true
    },
      "terminal.integrated.shell.windows": "Path of [base.exe]",
      "editor.wordWrap": "on",
      "emmet.syntaxProfiles": {
          "vue-html": "html",
          "vue": "html"
      },
      "editor.tabSize": 2,
      "editor.detectIndentation": false,
      "window.zoomLevel": 0,
      "workbench.iconTheme": "vscode-icons",
      "vsicons.projectDetection.autoReload": true,

      "git.enabled": true,
      "git.path": "Path of [git.exe]",
  
      "editor.fontFamily": "Fira Code",
      "editor.fontLigatures": true,
      "files.associations": {
        ".eslintrc": "jsonc"
      },
      "editor.formatOnSave": false,

      "[javascript]": {
          "editor.formatOnSave": true
      },
      "emojisense.languages": {
        "markdown": true,
        "git-commit": true,
        "plaintext": false,
        "json": true
    },
      "liveshare.connectionMode": "relay",

      "workbench.colorTheme": "Monokai Pro (Filter Spectrum)",
      "debug.toolBarLocation": "docked",
      "editor.tokenColorCustomizations": {
        "textMateRules": [
          {
            "scope": [
              "comment",
              "comment.block",
              "comment.block.documentation",
              "comment.line",
              "constant",
              "constant.character",
              "constant.character.escape",
              "constant.numeric",
              "constant.numeric.integer",
              "constant.numeric.float",
              "constant.numeric.hex",
              "constant.numeric.octal",
              "constant.other",
              "constant.regexp",
              "constant.rgb-value",
              "emphasis",
              "entity",
              "entity.name",
              "entity.name.class",
              "entity.name.function",
              "entity.name.method",
              "entity.name.section",
              "entity.name.selector",
              "entity.name.tag",
              "entity.name.type",
              "entity.other",
              "entity.other.attribute-name",
              "entity.other.inherited-class",
              "invalid",
              "invalid.deprecated",
              "invalid.illegal",
              "keyword",
              "keyword.control",
              "keyword.operator",
              "keyword.operator.new",
              "keyword.operator.assignment",
              "keyword.operator.arithmetic",
              "keyword.operator.logical",
              "keyword.other",
              "markup",
              "markup.bold",
              "markup.changed",
              "markup.deleted",
              "markup.heading",
              "markup.inline.raw",
              "markup.inserted",
              "markup.italic",
              "markup.list",
              "markup.list.numbered",
              "markup.list.unnumbered",
              "markup.other",
              "markup.quote",
              "markup.raw",
              "markup.underline",
              "markup.underline.link",
              "meta",
              "meta.block",
              "meta.cast",
              "meta.class",
              "meta.function",
              "meta.function-call",
              "meta.preprocessor",
              "meta.return-type",
              "meta.selector",
              "meta.tag",
              "meta.type.annotation",
              "meta.type",
              "punctuation.definition.string.begin",
              "punctuation.definition.string.end",
              "punctuation.separator",
              "punctuation.separator.continuation",
              "punctuation.terminator",
              "storage",
              "storage.modifier",
              "storage.type",
              "string",
              "string.interpolated",
              "string.other",
              "string.quoted",
              "string.quoted.double",
              "string.quoted.other",
              "string.quoted.single",
              "string.quoted.triple",
              "string.regexp",
              "string.unquoted",
              "strong",
              "support",
              "support.class",
              "support.constant",
              "support.function",
              "support.other",
              "support.type",
              "support.type.property-name",
              "support.variable",
              "variable",
              "variable.language",
              "variable.name",
              "variable.other",
              "variable.other.readwrite",
              "variable.parameter"
            ]
          }
        ]
      }
    }
```