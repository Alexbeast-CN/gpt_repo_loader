# GPT 仓库加载器

将任何 GitHub 仓库转换为适用于 GPT 的文本知识库。

## 特点

- 🚀 一键将 GitHub 仓库转换为文本格式
- 💡 支持指定分支和子目录
- 🎯 智能文件过滤系统
- 📝 生成标准化的文本输出
- ⚡️ 无需任何配置，即开即用

## 使用方法

1. 访问 [GPT 仓库加载器](https://your-deployment-url.com)
2. 输入 GitHub 仓库 URL
   - 支持完整 URL：`https://github.com/用户名/仓库名/tree/分支名`
   - 或简单格式：`https://github.com/用户名/仓库名`（默认 main 分支）
3. 点击"处理仓库"按钮
4. 等待处理完成后复制或下载生成的文本

## 文件过滤

系统默认会过滤以下类型文件：
- 二进制文件（.pyc, .whl 等）
- 图片文件（.png, .jpg, .gif 等）
- 系统文件（.git/, __pycache__/ 等）
- 配置文件（.gitignore, .env 等）

您可以在界面上的忽略列表中添加更多需要过滤的文件类型。

## 注意事项

- 处理大型仓库可能需要较长时间
- 生成的文本可直接用于 GPT 对话
- 如遇到问题，可以点击"取消"按钮终止处理

## 致谢

本项目受 [mpoon/gpt-repository-loader](https://github.com/mpoon/gpt-repository-loader) 启发。

## 许可证

MIT License
