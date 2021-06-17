## Vutify form generator base on a schema

-   This repo clone from [Vuetify-form-base](https://github.com/wotamann/vuetify-form)
-   This Repo solve the SSR issue of this package [Github issue](https://github.com/wotamann/vuetify-form-base/issues/50)

---

## Why I refactor and make a single file component for this package?

-   Reduce size
-   Resolved SSR issue in Nuxt.js
-   Add all dependencies in component

### Install for Vue.js and Nuxt.js

You should install this package with the below command:

-   NPM ` npm i vuetify-form-base-ssr --save`
-   YARN ` yarn add vuetify-form-base-ssr --save`

## How to use this package?

For general registration in Nuxt.js, you must add this package in plugin folder and add the file to `Nuxt.config.js` in the plugin section

`Vue.component('VuetifyFormBaseSsr', () => import('vuetify-form-base-ssr'))`

Or you can import this component to your desire components like as below

`import VuetifyFormBaseSsr from 'vuetify-form-base-ssr' `

## Documentation

[Link to main site documentation](https://wotamann.github.io/simple)
