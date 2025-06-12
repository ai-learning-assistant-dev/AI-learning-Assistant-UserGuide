# AI学习助手使用指南

AI学习助手是一款集AI问答、阅读、笔记于一体的学习辅助软件，基于Obsidian平台开发。

## 📚 文档导航

- **[完整使用文档](./AI学习助手完整使用文档.md)** - 包含v1.01基础功能和v1.1新功能的完整指南
- **[更新日志](./CHANGELOG.md)** - 版本更新记录
- **[开发指南](./CLAUDE.md)** - 开发者文档

## ✨ 主要功能

### 基础功能 (V1.01)
- Obsidian笔记软件集成
- AI对话与问答
- 文档管理与阅读
- 插件系统支持

### 新增功能 (V1.1)
- **AI人设自定义** - 通过标签设计定制不同AI角色
- **多文本内容引用** - 支持引用多个文档段落进行AI交互
- **语音识别(ASR)** - 本地音视频转文字，支持CPU/CUDA部署
- **文字转语音(TTS)** - 选中文本语音播放，支持多种音色

## 🚀 快速开始

1. 下载AI学习助手安装包
2. 安装Obsidian软件
3. 配置AI模型（支持本地LM Studio或在线API）
4. 参考[完整使用文档](./AI学习助手完整使用文档.md)进行详细配置

## 💬 技术支持

遇到问题？欢迎加入QQ群：**807831970** 进行交流和咨询！

## 📝 文档贡献指南

### 文档结构
- `AI学习助手完整使用文档.md` - 主要用户文档
- `images/` - 文档截图和图片资源
- `CHANGELOG.md` - 版本更新记录
- `CLAUDE.md` - 项目开发指南

### 如何贡献
1. **更新文档内容**：直接编辑markdown文件，保持格式一致
2. **添加图片**：将截图放入`images/`文件夹，使用描述性中文文件名
3. **版本记录**：重要更新需在`CHANGELOG.md`中记录
4. **格式规范**：使用标准markdown语法，保持目录结构清晰

### Word文档转换
使用pandoc转换Word文档到markdown：
```bash
pandoc "filename.docx" --extract-media=. -o "output.md"
```


## ❕其他注意

### 使用文档目录生成

文档的目录在visual studio code/cursor等工具中无法直接显示，需要用obsidian打开并安装“Automatic Table Of Contents”插件，这样通过其语法(ctrl+p打开指令面板，输入insert，找到insert table of content并回车，即可根据Markdown的#段落自动构建目录)就可以生成文档目录了。


### 使用文档的pdf导出

打开obsidian，安装插件”Better Export PDF“，在待导出的文档上输入ctrl+p打开命令板，搜索命令"Better Export PDF: 导出当前文件为PDF"。它会打开一个窗口，等待其渲染完毕，即可点击"export"导出pdf文件了！。

## 🤝 致谢

感谢所有为项目贡献的开发者们！详见[贡献者名单](./AI学习助手完整使用文档.md#感谢)。
