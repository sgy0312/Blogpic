# Blogpic

用于保存博客、技术文档和 Markdown 页面引用的图片及附件资源。

## 使用原则

- 现有文件名和根目录路径保持不变，避免历史文章中的图片链接失效。
- 新增资源建议使用日期前缀或独立目录，减少重名和用途混淆。
- 不提交账号凭据、访问令牌、系统配置、客户数据或其他敏感信息。
- 上传前压缩大尺寸图片；动态图只在确有必要时使用 GIF。

## 引用方式

Markdown 中可以使用 GitHub Raw 地址引用资源：

```text
https://raw.githubusercontent.com/sgy0312/Blogpic/main/<文件路径>
```

示例：

```markdown
![说明](https://raw.githubusercontent.com/sgy0312/Blogpic/main/example.png)
```

## 目录策略

仓库目前包含大量按时间命名的历史资源。为了保证外部链接稳定，本次整理只增加说明和文件类型设置，不移动或重命名已有文件。

建议后续新增内容使用以下结构：

```text
YYYY/
  MM/
    article-name/
      image-01.png
```
