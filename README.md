# detection8

检测报告二维码展示站点。

- 客户报告以独立静态页面发布。
- 报告内容使用 AES-256-GCM 加密。
- 解密密钥只包含在客户二维码的 URL 片段中，不写入仓库。
- 页面不依赖外部脚本、字体、图片、接口或数据库。

客户资料由私有仓库 `detection8-admin` 的手机管理流程生成和发布。

手机录入助手：

`https://detection6.github.io/detection8/admin/`
