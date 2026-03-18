# 重庆友谊骨科智能客服

## 部署说明

1. 打开 https://vercel.com 登录
2. 点击 "Add New..." → "Project"
3. 选择 "Import Git Repository"
4. 输入仓库地址：https://github.com/shaoxiong365/yyy-bone-chat
5. 点击 Deploy

## 使用方法

部署成功后访问生成的网址即可。

## 修改 API Key

如果需要更换 API Key，编辑 `index.html` 找到：
```js
const DS_KEY = 'sk-xxxxxx';
```
替换为您自己的 DeepSeek API Key
