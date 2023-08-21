# @yafh/tsconfig

**Requires TypeScript >= 5.0**

## Install

```bash
npm i -D @yafh/tsconfig

# or used yarn
yarn add -D @yafh/tsconfig

# or use pnpm
pnpm i -D @yafh/tsconfig
```

## Usage

In your `tsconfig.json`

```jsonc
{
  "extends": "@yafh/tsconfig.json" // <-- add this
}
```

or

```jsonc
{
  "extends": ["@yafh/tsconfig.json", "@vue/tsconfig/tsconfig.json"],
  "compilerOptions": {
    // your options
  }
}
```

## Supported scene presets

|          scene          |              file name              |
| :---------------------: | :---------------------------------: |
|         nodejs          | `@yafh/tsconfig/tsconfig.node.json` |
|           vue           | `@yafh/tsconfig/tsconfig.vue.json`  |
|           lib           | `@yafh/tsconfig/tsconfig.lib.json`  |
|         custom          |   `@yafh/tsconfig/tsconfig.json`    |
| experimental decorators | `@yafh/tsconfig/tsconfig.dec.json`  |
| incremental compilation | `@yafh/tsconfig/tsconfig.inc.json`  |
