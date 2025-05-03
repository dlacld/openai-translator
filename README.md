# OpenAI-Translator

<p align="center">
    <br> <a href="README.md"> English </a> | 中文
</p>
<p align="center">
    <em>所有的代码和文档完全由 OpenAI 的 GPT-4 模型生成</em>
</p>

## 介绍

OpenAI 翻译器是一个使用 AI 技术将英文 PDF 书籍翻译成中文的工具。这个工具使用了大型语言模型 (LLMs)，如 ChatGLM 和 OpenAI 的 GPT-3 以及 GPT-3.5 Turbo 来进行翻译。它是用 Python 构建的，并且具有灵活、模块化和面向对象的设计。

## 为什么做这个项目

在现今的环境中，缺乏非商业而且有效的 PDF 翻译工具。很多用户有包含敏感数据的 PDF 文件，他们更倾向于不将其上传到公共商业服务网站，以保护隐私。这个项目就是为了解决这个问题，为需要翻译他们的 PDF 文件同时又要保护数据隐私的用户提供解决方案。



## 特性

- [x] 使用大型语言模型 (LLMs) 将英文 PDF 书籍翻译成中文。
- [x] 支持 ChatGLM 和 OpenAI 模型。默认使用智谱LLM  "glm-4"
- [x] 对健壮的翻译操作进行超时和错误处理。
- [x] 通过通过图形化选择将中文PDF 翻译成英文
- [ ] 


## 开始使用

### 环境准备

1.克隆仓库 `git clone `。

2.需要 Python 3.10 或更高版本。使用 `pip install -r requirements.txt` 安装依赖项。

3.需要设置zhipuAI 密钥,默认调用模型采用"glm-4"。

### 使用示例

您可以通过指定配置文件或提供命令行参数来使用 OpenAI-Translator 工具。

命令行直接运行：

```bash
python ai_translator/gradio_server.py
```

## 许可证

该项目采用 GPL-3.0 许可证。有关详细信息，请查看 [LICENSE](LICENSE) 文件。

### 参考

此项目参考https://github.com/DjangoPeng/openai-quickstart





