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

### base

| scene | file name |
| custom | `@yafh/tsconfig/tsconfig.json` |

### web

| scene |              file name               |
| :---: | :----------------------------------: |
|  vue  |  `@yafh/tsconfig/tsconfig.vue.json`  |
| solid | `@yafh/tsconfig/tsconfig.solid.json` |
| react | `@yafh/tsconfig/tsconfig.react.json` |

### nodejs

|          scene          |              file name              |
| :---------------------: | :---------------------------------: |
|         nodejs          | `@yafh/tsconfig/tsconfig.node.json` |
|           lib           | `@yafh/tsconfig/tsconfig.lib.json`  |

### optional scenarios

|          scene          |              file name              |
| :---------------------: | :---------------------------------: |
| experimental decorators | `@yafh/tsconfig/tsconfig.dec.json`  |
| incremental compilation | `@yafh/tsconfig/tsconfig.inc.json`  |
