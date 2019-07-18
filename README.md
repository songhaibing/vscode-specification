# vscode-specification
vscode协作规范



{
  "window.zoomLevel": 0,
  "editor.fontSize": 16,
  "editor.snippetSuggestions": "top",
  "editor.minimap.maxColumn": 100,
  "editor.fontWeight": "600",
  "[vue]": {
    "editor.formatOnSave": true
  },
  "[scss]": {
    "editor.formatOnSave": true
  },
  "[less]": {
    "editor.formatOnSave": true
  },
  "[css]": {
    "editor.formatOnSave": true
  },
  "[html]": {
    "editor.formatOnSave": true
  },
  "[javascript]": {
    "editor.formatOnSave": true
  },
  "[json]": {
    "editor.formatOnSave": true
  },

  "emmet.syntaxProfiles": {
    "vue":"html"
  },
  
  "vetur.format.defaultFormatter.html": "prettyhtml",
  "vetur.format.defaultFormatterOptions": {
    "js-beautify-html": {
      "wrap_attributes": "force-aligned"
    },
    "prettyhtml": {
      "printWidth": 120,
      "singleQuote": false,
      "wrapAttributes": false,
      "sortAttributes": true,
      "tabWidth":2
    }
  },
  "vetur.format.styleInitialIndent": true,
  "vetur.format.scriptInitialIndent": true,
  "vetur.format.defaultFormatter.js": "prettier-eslint",
  "vetur.format.defaultFormatter.scss": "prettier",
  "vetur.format.defaultFormatter.less": "prettier",
  "vetur.format.defaultFormatter.css": "prettier",
  "vetur.format.defaultFormatter.postcss": "prettier",

  "prettier.eslintIntegration": true,
  "prettier.stylelintIntegration": true,
  "prettier.arrowParens": "avoid",
  "prettier.bracketSpacing": true,
  "prettier.jsxBracketSameLine": true,
  "prettier.parser": "babylon",
  "prettier.printWidth":120,
  "prettier.tabWidth": 2,
  "prettier.useTabs":true,
  "prettier.semi": true,
  "prettier.singleQuote": false,
  "prettier.htmlWhitespaceSensitivity": "strict",
  "prettier.proseWrap": "preserve",
  "prettier.trailingComma": "none",
  "prettier.endOfLine": "lf",
  "prettier.requireConfig": false,
  "prettier.jsxSingleQuote": false,

  "css.validate": false,
  "scss.validate": false,

  "eslint.autoFixOnSave": true,
  "eslint.validate": [
      "javascript",
      "javascriptreact",
      {
          "language": "vue",
          "autoFix": true
      },
      {
          "language": "html",
          "autoFix": true
      }
  ],

  "postcssSorting.showErrorMessages": true,

  "javascript.updateImportsOnFileMove.enabled": "always",
  
  "breadcrumbs.enabled": true,

  "npm.enableScriptExplorer": true,

  "todo-tree.defaultHighlight": {
    "foreground": "green",
    "type": "none"
  },
  "todo-tree.customHighlight": {
    "TODO": {},
    "FIXME": {}
  },
  "terminal.integrated.fontWeight": "600",
  "terminal.integrated.fontWeightBold": "600",
  "javascript.suggestionActions.enabled": false,
  "workbench.iconTheme": "vscode-icons",
  "workbench.colorTheme": "Solarized Light"
}
