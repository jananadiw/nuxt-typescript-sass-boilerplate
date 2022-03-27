## Vue Nuxt Typescript and Scss Boilerplate 

>  A Nuxt boilerplate with Typescript installed along with Sass. Type definitions are installed and set up for Nuxt, Jest and Vue.

## Features

- Typescript support
- Installed sass and sass-loader packages 
- Configured Scss style extentions in nuxt config file.
- Easy to scafold custom assets directory

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).


## Directory Structure

```js
.
├── assets
│   └── sass // styles
├── components // all Vue Components can be used in layouts, pages
│   ├── common // shared components in multiple pages
│   │   ├── ui // ui components (Checkbox, NumberInput,...)
│   │   └── ... // other featured common components
│   ├── layout // components to be used in layouts
│   ├── accounts // components grouped by pages
│   └── payee
│       └── PayeeInfo.vue // (Component File Naming: Pascal-Case)
├── layouts // layout components
│   ├── default.vue
│   ├── error.vue // error page
├── middleware
├── mixins
├── pages // route pages
│   ├── ...
│   ├── user // (Page File Naming: kebab-case)
│   └── index.vue
├── plugins
├── services // business logics
├── static // static files(images, ...)
├── store // vuex store
├── test
├── types // all types (interfaces, enums and constants)
└── utils
```
