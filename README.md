# Gh-Mirror

基于 Cloudflare Workers 的 GitHub 镜像站。

## 方法1部署到 Cloudflare Workers

1. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)。
2. 进入 **Workers & Pages** → **创建应用程序** → **创建 Worker**→ **从 Hello World! 开始**。
3. 命名，例如 `gh-mirror`，点击 **部署**。
4. 点击 **编辑代码**，删除默认代码，粘贴本项目Cloudflare Workers/Worker.js源码。
5. 点击 **保存并部署**。
6. 可选：进入 **设置** → **域和路由** → **添加** → **自定义域**，绑定你的域名。
7. 可选：防止举报滥用，进入 **域** → **Worker URL** → **禁用workers.dev的访问**

## 验证

访问：

```text
https://你的域名/
```

返回 `ok` 即部署成功。

## 使用方式

| 功能 | 地址 |
|---|---|
| 仓库页 | `把github域名替换成你的域名` |
| 代码页 | `把github域名替换成你的域名` |
| Raw 文件 | `把github域名替换成你的域名` |
