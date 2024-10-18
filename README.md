# GPT 仓库加载器

将任何 GitHub 仓库转换为 .txt 类型知识库

## 简介

GPT 仓库加载器是一个简单而强大的工具，可以将 GitHub 仓库的内容转换为易于处理的文本格式。这对于将代码库导入到 GPT 或其他 AI 模型中特别有用，使得模型可以更好地理解和处理代码结构。

## 特性

- 支持任何公开的 GitHub 仓库
- 可选的 GitHub 个人访问令牌，用于访问私有仓库或提高 API 速率限制
- 可自定义忽略列表，排除不需要的文件和目录
- 简洁的用户界面，易于使用
- 支持复制输出或保存为文件

## 使用方法

1. 访问 [GPT 仓库加载器网页](https://alexbeast-cn.github.io/gpt_repo_loader/)
2. 输入 GitHub 仓库的 URL，例如：https://github.com/jstmn/ikflow 以访问默认为 main 分支的代码，https://github.com/jstmn/ikflow/tree/master 以访问 master 分支的代码
3. （可选）输入 GitHub 个人访问令牌
4. （可选）自定义忽略列表
5. 点击"处理仓库"按钮
6. 等待处理完成后，可以复制输出或保存为文件

## 注意事项

- 对于大型仓库，处理可能需要一些时间
- 请确保遵守 GitHub 的使用条款和 API 限制
- 如果遇到 API 速率限制，请使用个人访问令牌

## 贡献

欢迎提交 issues 和 pull requests 来改进这个项目。

## 致谢

本项目受 [mpoon/gpt-repository-loader](https://github.com/mpoon/gpt-repository-loader) 启发。

## 许可证

本项目采用 MIT 许可证 - 详情请查看 [LICENSE](LICENSE) 文件。
