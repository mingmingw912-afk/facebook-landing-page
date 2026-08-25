# 出海增长实验室

面向中国工厂、外贸公司和出口企业的 B2B Facebook 广告获客落地页，使用原生 HTML、CSS 和 JavaScript 构建。

## 运行

无需安装依赖，直接用浏览器打开 `index.html` 即可预览。

也可以在项目目录执行：

```bash
python3 -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 配置

- 将 `index.html` 和 `script.js` 中的 `https://wa.me/8613800000000` 替换为实际 WhatsApp 号码。
- 当前表单为前端演示提交，会显示成功反馈；接入生产环境时，将 `script.js` 的提交逻辑连接到 CRM、邮件或后端接口。