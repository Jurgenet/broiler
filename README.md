# vue-broiler
> vue boilerplate

## Available Scripts

```bash
# install
yarn
# run dev mode
yarn serve
# lint
yarn lint
# test
yarn test # test:unit
# build
yarn build
```

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

</details>

## License

*MIT*

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.