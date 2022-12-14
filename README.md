# 全て完了後、この Todo リストを削除する
- [ ] package.json の `name` を設定する。
- [ ] manifest.json の `name` を設定する（Safari-Extension は __MSG_extension_name__）。
- [ ] manifest.json の `description` を設定する（Safari-Extension は __MSG_extension_description__）。

# 環境
```md
# typescript
4.9.4

# webpack
5.75.0
```

## eslint
8.23.1
```json
{
  // typescript
  "@typescript-eslint/eslint-plugin": "^5.37.0",
  "@typescript-eslint/parser": "^5.37.0",
  // import 順の整理
  "eslint-plugin-import": "^2.22.0",
  // unused-import の削除
  "eslint-plugin-unused-imports": "^2.0.0",
  // prettier
  "eslint-plugin-prettier": "^4.2.1"
}
```

## types
```json
{
  // chrome api
  "@types/chrome": "^0.0.204",
  // web api
  "@types/web": "^0.0.84",
  // browser extension api
  "@types/webextension-polyfill": "^0.9.2"
}
```