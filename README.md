# gotoho

```json
// 只允许使用pnpm来开发
// preinstall 在install之前（首次）执行
// postinstall 在install之后（首次）执行
"scripts": {
  "preinstall": "npx only-allow pnpm",
},
// 防止最外层包被发布出去，设为true以后发布时会提醒你
"private": true,
"engines": {
  "node": ">=16.0.0"
}

```
