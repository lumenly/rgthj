# rgthj

当前仓库用于存放 PDF 示例文件。

## 文件内容

- `1MBzipFile.zip`：包含两份 PDF 文件：
  - `documents/pdf-sample1.pdf`
  - `documents/pdf-sample3.pdf`

## 使用方法

在仓库根目录运行以下命令解压文件：

```bash
python -m zipfile -e 1MBzipFile.zip extracted
```

解压后的 PDF 位于 `extracted/documents/` 目录，可使用 PDF 阅读器打开。

仓库目前没有应用代码、依赖安装步骤或自动化测试。
