# React-Router-template

ReactRouterからGitHubPagesにデプロイする開発環境を整えたテンプレートレポジトリ

## 開発

準備
```
npm i
```

起動
```
npm run start
```

## 環境
- node.js
    - vite
    - React-router v7
    - React
    - typescript
    - tailwindcss
    - prettier

`npx create-react-router@latest`コマンドで作成した

## デプロイ

`Master`ブランチにマージすることでGitHubActionsが自動でビルド->デプロイを行う