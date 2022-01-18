# nav-1
一个简约的前端导航网页

## 开发
1. yarn global add parcel@1.9.7
2. yarn global add parcel@next
- 测试：parcel src/index.html
- 发布： parcel build  src/index.html
- BUG：Error in parsing SVG: Unbound namespace prefix: "xlink"
- 解决：parcel build  src/index.html --no-minify；使用 parcel@next，build命令应当把 --no-minify 选项替换成 --no-optimize

## 构建命令
```
yarn build
```