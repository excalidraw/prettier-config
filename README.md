# @excalidraw/prettier-config

Excalidraw's [Prettier](https://prettier.io) config.

## Usage

### Install

```bash
yarn add --dev @excalidraw/prettier-config prettier
```

### Edit `package.json`

```jsonc
{
  // ...
  "prettier": "@excalidraw/prettier-config"
}
```

## What you get

```json
{
  "proseWrap": "never",
  "trailingComma": "all",
  "overrides": [
    {
      "files": ["*.json"],
      "options": {
        "printWidth": 256
      }
    }
  ]
}
```
