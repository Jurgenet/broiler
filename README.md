# broiler
> vue boilerplate

## Project setup

<details><summary>Scripts</summary>

| `Yarn run <script>`  | Description                                        |
| -------------------- | -------------------------------------------------- |
| `yarn install`       | install                                            |
| `yarn run serve`     | Compiles and hot-reloads for development           |
| `yarn run build`     | Compiles and minifies for production               |
| `yarn run test`      | Run your tests                                     |
| `yarn run lint`      | Lints and fixes files                              |
| `yarn run test:unit` | Run your unit tests                                |

</details>

## Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

## Details

<details><summary>Structure</summary>

```
.
├── config                        #
|   └── storybook                 # storybook settings
|       ├── addons.js             #
|       └── config.js             #
├── node_modules/**               #
├── public/**                     # builded project   
├── src                           # app source code (js|jsx source)
|   ├── assets/**                 #
|   ├── components/**             # reusable components
|   ├── plugins                   #
|   |   └── firebase.js           #
|   ├── store                     #
|   |   ├── modules/**            # 
|   |   ├── index.js              #
|   |   └── mutation-types.js     #
|   ├── stories/**                #
|   ├── views                     # pages
|   ├── App.vue                   #
|   ├── main.js                   #
|   └── router.js                 #
├── tests/**                      #
├── .gitignore                    #
├── .prettierrc                   #
├── babel.config.js               #
├── package.json                  # package.json
├── README.md                     # README file
└── yarn.lock                     # yarn lock file
```

<details><summary>Powered by</summary>

* [vue2](https://vuejs.org)  
* [webpack4](https://github.com/webpack/webpack)  
* [babel6](https://babeljs.io)  
* [pug](https://pugjs.org/api/getting-started.html)  
* [scss](https://sass-scss.ru)  
* [storybook](https://storybook.js.org/basics/guide-vue/)  
* [firebase](https://firebase.google.com)  

</details>

## License

**MIT**