# First of all
- disable autocrlf on Windows with `git config --global autocrlf false`

## Study notes

### Independent tools
- Codepen
- CodeSandbox
- Stackblitz
- IcoMoon (icons)
- Figma (SVG editor)
- [ScreenToGif](http://www.screentogif.com/)
- OBS Studio (screen recording)
- Cmder (better cmd)
- VS Code
- [Observable](https://beta.observablehq.com/)
- Carbon.now.sh
- [CSV to JSON](https://www.csvjson.com/csv2json)

### Bundlers / automation
- Webpack
- Rollup
- Gulp

### JavaScript resources
- MDN
- JavaScript.info
- https://github.com/Chalarangelo/30-seconds-of-code
- https://github.com/AllThingsSmitty/must-watch-javascript (video)
- https://css-tricks.com/debouncing-throttling-explained-examples/
- https://eu.udacity.com/course/javascript-design-patterns--ud989
- DevDocs



### ES
- import / export
- Promise | async / await
  - https://egghead.io/courses/asynchronous-javascript-with-async-await (video)
- class
- destructuring
- spread operator
- compiler Babel

### Functional programming
- map, reduce, filter
- currying
- pipe
- pure functions
- __reducer pattern__ (Redux)

### Style guide
- https://github.com/ryanmcdermott/clean-code-javascript#clean-code-javascript
- ESlint
- Prettier

### Automation
- [create-react-app](https://github.com/facebook/create-react-app)
- [nwb](https://github.com/insin/nwb)

### RegEx
- https://regexr.com/
- https://regex101.com/#javascript

### Frameworks / libraries
- React, virtual DOM
- state management (Redux, Mobx - especially mobx-state-tree)
- date/time (MomentJS, Date-fns)
- KaTeX (Math)
- d3.js
- Ramda
- Lodash
- Jest, react-testing-library, dom-testing-library
- tape
- math.js

### React environment
- https://react.holiday/
- https://reactpatterns.com
- Redux
- GatsbyJS
- Recompose
- vx (d3.js for React)
- animations: react-spring / pose (popmotion) / react-motion / react-move (in this order)
- svgr - icon builder
- styled-components - CSS
- immer - immutable transforms
- classcat
- normalizr
- react-router
- storybook
- react-redux-form / Formik
- react-jsonschema-form

### VS Code
#### extensions
- Babel JavaScript (still?)
- Debugger for Chrome
- Bracket Pair Colorizer
- ESLint
- Git History
- HTMLHint (still?)
- Import Cost
- Prettier
- SVG Viewer (still?)
- vscode-styled-components
- npm

#### settings
```json
{
  "window.menuBarVisibility": "toggle",
  "workbench.colorTheme": "One Monokai",
  "prettier.eslintIntegration": true,
  "prettier.singleQuote": true,
  "emmet.syntaxProfiles": {
    "javascript": "jsx",
    "typescript": "jsx",
    "latte": "html",
    "php": "html",
    "phtml": "html"
  },
  "files.eol": "\n",
  "emmet.showExpandedAbbreviation": "always",
  "window.zoomLevel": 0,
  "files.defaultLanguage": "javascript",
  "editor.tabSize": 2,
  "eslint.options": {
    "envs": [
      "es6"
    ],
    "parser": "babel-eslint",
    "parserOptions": {
      "ecmaVersion": 2017,
      "sourceType": "module",
      "ecmaFeatures": {
        "experimentalObjectRestSpread": true,
        "jsx": true
      }
    },
    "rules": {
      "linebreak-style": [
        "off"
      ],
      "quotes": [
        "off"
      ]
    }
  },
  "terminal.integrated.shell.windows": "C:\\Windows\\sysnative\\cmd.exe",
  "editor.rulers": [
    80
  ],
  "extensions.ignoreRecommendations": true,
  "prettier.semi": true,
  "editor.minimap.enabled": false,
  "typescript.autoImportSuggestions.enabled": false,
  "explorer.confirmDragAndDrop": false,
  "javascript.implicitProjectConfig.checkJs": false,
  "git.autofetch": true,
  "diffEditor.ignoreTrimWhitespace": false,
  "git.enableSmartCommit": true,
  "editor.snippetSuggestions": "none"
}
```
