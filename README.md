
# .dotfiles for IGO-Data Team Development


## Web Development
- ESLint for linting, prettier as a formatter too make linting less painfull


### React
`$ npm install eslint prettier eslint-config-prettier eslint-plugin-prettier eslint-config-react-app babel-eslint`
- if you see some peer dependency warnings, make sure they're satisfied
- If you used `create-react-app` you will have redundant rules in package.json to use react-app for linting, this won't cause compatibility issues
  
  
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
