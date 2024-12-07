# VUE-CLI-MODE-AND-ENV

Vue-CLI build project in multiple environment.


## Project Structure

```plaintext
#vue-cli-mode-and-env
├─public
│  ├─sdk-dev.js            # sdk.js(dev environment)
│  ├─sdk-test.js           # sdk.js(test environment)
│  ├─sdk-prod.js           # sdk.js(production environment)
│  └─index.html
├─src
│  ├─App.vue
│  └─main.vue
├─.env                     # environment variable file(default)
├─.env.development         # environment variable file(dev)
├─.env.test                # environment variable file(test)
├─.env.test-prod           # environment variable file(test)
├─.env.prod                # environment variable file(prod)
├─.gitignore
├─package.json
├─prettier.config.js
├─vue.config.js
└─README.md
```
