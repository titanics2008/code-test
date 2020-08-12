## Bigfish 中台最佳实践脚手架

技术栈：Bigfish 3.0 + TechUI + Ant Design + 中台最佳实践

## 准备工作

- 安装 [nodejs](https://nodejs.org/en/)
- 使用最新版本的 [tnpm](http://web.npm.alibaba-inc.com/)

## 开发

### 通过 Bigfish UI 开发（推荐）

```bash
$ tnpm install @alipay/bigfish -g // 安装 Bigfish 到全局
$ bigfish ui // 启动 Bigfish UI，接下来就可以在 UI 里面通过可视化页面操作了
```

### 命令行开发

```bash
$ tnpm install // 安装依赖
$ tnpm run dev // 本地开发
$ tnpm run devs // 联调模式
$ tnpm run oneapi // 更新 OneAPI 信息（services 和 mock）
```

## 文档

- Bigfish 官网：[https://bigfish.antfin-inc.com/](https://bigfish.antfin-inc.com/)
- 关于中台最佳实践：[https://bigfish.antfin-inc.com/doc/console-intro](https://bigfish.antfin-inc.com/doc/console-intro)
- 关于 TechUI：[https://techui.alipay.com/](https://techui.alipay.com/)
