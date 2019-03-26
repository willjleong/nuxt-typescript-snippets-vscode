# nuxt-typescript-snippets README

Vscode snippets to make creating new files with `nuxt-ts`, `nuxt-property-decorator`, and `vuex-class` easy.
Some snippets such as `nuxt `

## Features

1. Snippets `nuxt-ts`  Generate variations .vue files with `typescript` as the language, and automatically import nuxt-class-decorators.
   1. `scaffold` creates a `.vue` file with options to name the class and change the syle language to scss,css,less,styl,sass and where or not to scope the styles.
   2. `scaffold-with-scss` same as `scaffold` but picks `lang=scss` in the style tag.
   3. `scaffold-with-scss-scoped` same as `scaffold-with-scss` but scoped styles.
   4. `scaffold-with-state-scss-scoped` same as `scaffold-with-scss-scoped` but with a `vuex-class` `@State` decorator defined and imported.
2. Snippet `nuxt-ts`[] Generate a store.
   1. `store` - Generates a store and allows the user to fill in the store name & types. Does assume a RootStore type exists from the layout in [nuxt-community typescript-template](https://github.com/nuxt-community/typescript-template)

## Requirements
1. [vetur](https://github.com/vuejs/vetur)
2. [nuxt](https://github.com/nuxt/nuxt.js)
3. [nuxt-property-decorator](https://github.com/nuxt-community/nuxt-property-decorator)
4. [vuex-class](https://github.com/ktsn/vuex-class)
5. [nuxt-community typescript-template](https://github.com/nuxt-community/typescript-template) (Some scaffolding in this extension assume using this template i.e. importing the RootStore from `types/index.ts` in the store snippets)
6. (Optional) any appropriate style loader for the style lang for .vue files.

## Extension Settings

This extension contributes the following settings:

* `nuxt-typescript-snippets.enable`: enable/disable this extension

## Known Issues
None yet.. :|

## Release Notes

### 0.1.2
- Added vue-typescript templates for single file component with style variations
- Added typescript template for creating a store with layout similar to the [nuxt-community typescript-template](https://github.com/nuxt-community/typescript-template)
- Fixed snippets being ignored 

**Enjoy!**
