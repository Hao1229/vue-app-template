# Vue3 Template

### 專案初始化

```js
pnpm install

pnpm dev
```

### 專案打包

```
pnpm build
```

### Git Commit

commitlint + commitizon + husky + lint-staged

提交需要符合 [@commitlint/config-conventional
](https://github.com/conventional-changelog/commitlint/tree/master/%40commitlint/config-conventional)

Rule: type(scope): subject

Example: `feat(header): add logo in header`、`fix(header): fix header layout in mobile`

commit 時會透過 husky 檢查 commit 格式與 lint，若檢查未過會無法提交
要 commit 時，請用 `pnpm commit` 取代 `git commit`

### Node 版本

```
nvm use
```

see in .nvmrc

### Node 套件管理工具

pnpm

### CSS framework

可以根據專案需求選擇
ex: tailwindcss、Vuetify etc.
