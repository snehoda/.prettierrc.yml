https://www.jetbrains.com/help/idea/prettier.html#ws_prettier_install
 
Can be added to any project to package.json
 
 "scripts": {
    "cy:open": "cypress open",
    "Lint": "prettier cypress/ --check",
    "format": "prettier cypress/ --write --list-different"
  },


Next data must be added to .prettierrc.yml

printWidth: 100
tabWidth: 2
useTabs: false
semi: false
singleQuote: true
quoteProps: "as-needed"
jsxSingleQuote: false
trailingComma: "es5"
bracketSpacing: false
bracketSameLine: false
arrowParens: "avoid"
endOfLine: "auto"
