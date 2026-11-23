# 官方语言

出厂中文/English 语言包——可卸载，卸载后 t(key) 返回 key 原文

![官方语言](../../resources/cover.svg)

## What it does

- 2 language packs.

## Applying it

- Language: Settings → Language.

## Install

Open the Plugin Store, find this plugin, and click Install. For offline use, install the `.linkdesk-plugin` package from disk.

## Development

```bash
npm install
npm run dev      # preview in the dev host
npm run lint     # eslint + manifest i18n completeness
npm run verify   # full repository gate
npm run build    # produce the .linkdesk-plugin package
npm run publish  # GitHub Release + catalog entry
```

See the repository root `README.md` for the Chinese documentation and the full directory contract.
