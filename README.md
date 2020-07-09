
# .dotfiles for IGO-Data Team Development


## Web Development
- ESLint for linting, prettier as a formatter too make linting less painful


### React
```
$ npm install --save-dev eslint prettier eslint-config-prettier eslint-plugin-prettier eslint-config-react-app babel-eslint eslint-plugin-import eslint-plugin-flowtype eslint-plugin-jsx-a11y eslint-plugin-react
```
- if you see some peer dependency warnings, make sure they're satisfied
- If you used `create-react-app` you will have redundant rules in package.json to use react-app for linting, this won't cause compatibility issues

If using react-hooks,
```
$ npm install --save-dev eslint-plugin-react-hooks
```
  
### Node
```
 $ npm install --save-dev eslint eslint-plugin-node
```


### Vue
```
$ npm install --save-dev eslint eslint-plugin-vue@next
```


### Set up Prettier in VSCode
CMD+P and
```
ext install esbenp.prettier-vscode 
```

Add these lines to your settings:
```

    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
```
