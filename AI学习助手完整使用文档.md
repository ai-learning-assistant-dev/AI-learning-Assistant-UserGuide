# AI学习助手完整使用文档

## 目录

```table-of-contents
```

# 第一部分：基础功能 (V1.01)

## 1 简介
AI学习助手是一款集AI问答、阅读、笔记于一体的学习辅助软件，目前已更新至1.1版本。有了AI帮忙，加上一个简单好用的书籍、笔记系统，对于学习晦涩复杂的知识体系，比如哲学、政治经济学、精神分析、计算机原理、包括AI技术本身会更直白、高效、成体系。

AI学习助手的主要功能是基于一款笔记软件，Obsidian。AI学习助手集成了学习资料、笔记功能、AI功能等。

## 2 下载与安装
通过百度云盘下载AI学习助手1.0
链接: https://pan.bAIdu.com/s/1qaMruokoMFrY7vjlzlBIVA?pwd=7exm 
提取码: 7exm
![百度网盘.png](./images/百度网盘.png)

打开下载好的文件夹，双击进入相关软件安装包
![打开相关软件安装包.png](./images/打开相关软件安装包.png)

双击运行Obsidian-1.8.10.exe，安装软件,
![运行Obsidian-1.8.19.exe.png](./images/运行Obsidian-1.8.19.exe.png)

安装Obsidian笔记软件，建议不要安装在C盘
![确定Obsidian安装路径.png](./images/确定Obsidian安装路径.png)

>[!info] 如果你已经安装Obsidian，请跳过安装步骤。打开你的Obsidian，在<font color="#92d050">设置-关于</font>页面，确保你安装的是v1.8.10最新版本：
>![确认Obsidian版本.png](./images/确认Obsidian版本.png)

## 3 初步配置AI学习助手

>[!tip] AI学习助手软件设置参考视频：[【录播剪辑】AI学习助手1.0-软件设置_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1xbLizPEh3/?spm_id_from=333.337.search-card.all.click&vd_source=9de7c3a67fd42814f6579e0482d4d3ad)

### 3.1 配置文件仓库
安装好Obsidian后，接下来我们要配置好Obsidian仓库。首先，新建一个空的文件夹作为，文件夹名不限（示例为Obsidian vaults），该文件夹主要用于放置AI学习助手相关文件，建议不要放置在C盘。
![创建Obsidian_vaults文件夹.png](./images/创建Obsidian_vaults文件夹.png)

接下来，回到下载好的AI学习助手文件夹，蒋该文件夹整个文件夹拷贝到刚才创建的空的文件夹（示例为Obsidian vaults）中。
![复制AI学习助手文件夹.png](./images/复制ai学习助手文件夹.png)
![把AI学习助手文件夹粘贴.png](./images/把ai学习助手文件夹粘贴.png)

接下来，就可以打开Obsidian软件，在软件内配置AI学习助手，打开Obsidian并选择语言。
>[!info] 注意：由于大量第三方插件未进行本地化，因此改语言选项仅能改变Obsidian的语言设置以及自带本地化的插件。

![打开Obsidian并选择语言.png](./images/打开obsidian并选择语言.png)

选择语言后，点击打开本地仓库（示例为Obsidian vaults）中的AI学习助手-1.0.1文件夹，加载AI学习助手。
![选中AI学习助手并点击选择文件夹.png](./images/选中ai学习助手并点击选择文件夹.png)

### 3.2 加载AI学习助手
首次加载AI学习助时，软件会弹出信任仓库作者按钮，请点击信任
![点击信任作者.png](./images/点击信任作者.png)

接下来，AI学习助手的相关内容会显示在Obsidian的左边栏
![左边栏.png](./images/左边栏.png)

之后要选择、添加、删除、重命名仓库，点击左下方红框里面的按钮即可
![添加删除重命名仓库.png](./images/添加删除重命名仓库.png)

至此，AI学习助手的本体已经安装好了。你现在已经可以阅读学习资料文件夹里面的哲学、历史、政治经济学教材和书籍，后续还会添加精神分析基础、数学物理、AI辅助编程、AI与计算机技术等资料。

## 4 Obsidian使用指南
Obsidian本体的功能很多，对于AI学习助手的使用无需再进行手动配置，直接开始上手摸索即可。

>[!info] Obsidian软件的使用手册可以参照以下链接：
>[由此开始 - Obsidian 中文帮助 - Obsidian Publish](https://publish.obsidian.md/help-zh/%E7%94%B1%E6%AD%A4%E5%BC%80%E5%A7%8B)

Obsidian主界面主要分左边栏，主体，右边栏：
![Obsidian界面.png](./images/Obsidian界面.png)
最左边一列是插件栏。
插件栏的右侧是仓库的文件浏览器。
主体部分即打开后文件显示的位置，即看书、写笔记的位置。
右边栏则是大纲、AI对话框等功能。

### 4.1 自带功能
#### 4.1.1 基础设置
点击Obsidian左下角的<font color="#92d050">齿轮按钮</font>打开设置页面，其左边栏最上方为Obsidian基础设置项：
![基础设置页面.png](./images/基础设置页面.png)

以下是一些比较重要的基础设置：

##### 4.1.1.1 关于
用于检查更新、调整语言等功能

##### 4.1.1.2 编辑器
用于编写文档的设定。Obsidian标准格式叫markdown（.md）格式，特点是用代码表达格式。*比如给一句话加斜体，只要在句子两端加一个星号。* 

打开文件窗口的右上角的三点，再点击源码模式，就可以查看markdown格式的源代码。
![查看md源码.png](./images/查看md源码.png)

源码示例：
![源码示例.png](./images/源码示例.png)

用Obsidian写笔记需要使用markdown语言，对于格式的调整需要通过源码的方式进行设置，对于初学者不太友好，因此，AI学习助手默认添加了第三方插件Editing Toolbar，可以像编辑word文档一样修改、添加格式了。
![editing_toolbar.png](./images/editing_toolbar.png)
关于Editing Toolbar，请参考：[[#4.2.1 Editing Toolbar 格式工具栏]]。
学习更多markdown语法，请参考：[Markdown 链接语法 | Markdown 教程](https://markdown.com.cn/basic-syntax/links.html)

##### 4.1.1.3 外观
该页面可以Obsidian外观，点击外观-管理，进行修改。
![外观.png](./images/外观.png)

进入外观下载界面：选择所需外观，下载即可。
![外观下载界面.png](./images/外观下载界面.png)

##### 4.1.1.4 文件与链接
该页面主要设置新建或删除文档位置。

比较重要的是：
（1）新建笔记的默认位置为<font color="#92d050">随笔·白板</font>文件夹。
![新建笔记.png](./images/新建笔记.png)

点击左上角按钮X，可以退出设置。在AI学习助手仓库里面，就可以看到<font color="#92d050">随笔·白板</font>文件夹。所有新创建的笔记、白板都放在这里。
![随笔白板.png](./images/随笔白板.png)

在系统文件浏览器里面，也可以找到<font color="#92d050">随笔·白板</font>文件夹。
![随笔白板文件浏览器.png](./images/随笔白板文件浏览器.png)

（2）除了笔记，创建的其他所有文件，比如画图、录音，会自动存到<font color="#92d050">Z-附件资料夹/附件材料</font>文件夹中。
![附件.png](./images/附件.png)
和<font color="#92d050">随笔·白板</font>一样，在AI学习助手侧边栏，与文件浏览器里，都可以找到<font color="#92d050">Z-附件资料夹/附件材料</font>文件夹。

##### 4.1.1.5 快捷键
快捷键一栏可自行设定Obsidian软件的快捷键。

#### 4.1.2 核心插件
核心插件是Obsidian自带的一些功能，可以在核心插件页面选择打开或关闭
![核心插件.png](./images/核心插件.png)

>[!tip] 上手即用
>AI学习助手1.01已经帮大家打开实用的核心插件，无需自己设置

核心插件标签下面，就是已经打开的每一项核心插件的设置。
![核心插件设置.png](./images/核心插件设置.png)

##### 4.1.2.1 白板
白板是一个无限大的平面，可以把你的笔记、PDF拖到里面，帮你构建关系图。
![白板演示.png](./images/白板演示.png)

点击左边栏的四个小方框按钮创建白板。
![创建白板.png](./images/创建白板.png)
白板默认储存位置是<font color="#92d050">随笔·白板</font>文件夹。

##### 4.1.2.2 模板
模板插件可以帮你快速插入模板里面的文本。模板都储存在<font color="#92d050">Z-附件资料夹/模板</font>里面。
在特定笔记中，光标点击想添加模板的位置，然后点左边栏<font color="#92d050">插入模板</font>按钮，即可添加模板：
![插入模板.png](./images/插入模板.png)
插入后如下：![模板已插入.png](./images/模板已插入.png)

##### 4.1.2.3 文件恢复
Obsidian会即时储存你的修改，但如果想恢复文件到之前状态，可点击<font color="#92d050">文件恢复-浏览</font>按钮：
![文件恢复.png](./images/文件恢复.png)

选择需要恢复的笔记：
![点击选择要恢复的文件.png](./images/点击选择要恢复的文件.png)

选择需要恢复的时间点：
![选择要恢复的版本.png](./images/选择要恢复的版本.png)

### 4.2 第三方插件
第三方插件是社区爱好者编写的功能，
启用第三方插件，首先要<font color="#92d050">关闭安全模式</font>。点击<font color="#92d050">设置-第三方插件-关闭安全模式</font>：
![关闭安全模式.png](./images/关闭安全模式.png)

之后，关闭或开启个别第三方插件设置-第三方标签页面右下角的按钮。
![第三方插件.png](./images/第三方插件.png)

>[!tip] 开箱即用
>第三方插件中，除了copilot比较特殊，需要用户自行加载AI模型，其他都基本设置好了，开箱即用。

每个第三方插件的具体选项，在设置左下方灰色字体<font color="#646a73">第三方插件</font>下面：
![每个第三方插件设置.png](./images/每个第三方插件设置.png)

>[!attention] 只有在<font color="#92d050">第三方插件</font>标签页中打开的插件才会显示到<font color="#92d050">设置页左下方</font>和<font color="#92d050">左边栏</font>里面：
><font color="#92d050">第三方插件</font>页面：![第三方插件打开状态.png](./images/第三方插件打开状态.png)

下面是一些第三方插件功能简单介绍。

#### 4.2.1 Editing Toolbar 格式工具栏

<font color="#92d050">Editing Toolbar</font>可以让用户像编辑word文档那样修改文字的格式。
![editing_toolbar.png](./images/editing_toolbar.png)

#### 4.2.2 Floating Toc 悬浮目录
悬浮目录会自动读取当前文档的标题，在右边生成一个<font color="#92d050">大纲</font>的悬浮窗：
![floating_toc.png](./images/floating_toc.png)

主要功能：
1）<font color="#92d050">展开收起大纲</font>：浮动大纲右上角小箭头，可收起大纲：
![TOC展开收起大纲.png](./images/TOC展开收起大纲.png)

收起后大纲：
![收起后大纲.png](./images/收起后大纲.png)

2）<font color="#92d050">复制大纲</font>：点击复制按钮可以复制大纲：
![TOC复制大纲.png](./images/TOC复制大纲.png)

关掉floating toc后，如需打开大纲，需要点击<font color="#92d050">右边栏</font>按钮-<font color="#92d050">大纲</font>按钮：
![正常打开大纲.png](./images/正常打开大纲.png)

#### 4.2.3 Minimal Theme Settings 极简外观设定
该插件是Obsidian的极简外观<font color="#92d050">改变字体颜色</font>的插件，打开之后，文档的<font color="#92d050">不同级别标题会自动变色</font>，方便阅读：
![min_theme_set_on.png](./images/min_theme_set_on.png)

关闭Minimal Theme Setting，标题全部变成白色：
![min_theme_set_off.png](./images/min_theme_set_off.png)

>[!attention] 注意：这个插件只对Minimal外观有作用。更换成其他外观，插件会失效。

#### 4.2.4 Excalidraw 手绘板
Excalidraw是一款<font color="#92d050">白板绘图工具</font>，支持手绘板笔记等功能，有手绘板且喜欢手写笔记的朋友可以使。点击左边栏<font color="#92d050">钢笔</font>按钮打开：
![Excalidraw.png](./images/Excalidraw.png)

>[!tip] 配合手写板，体验更佳。

#### 4.2.5 Media Extended 多媒体浏览
Media Extended插件可以直接<font color="#92d050">用Obsidian</font><font color="#92d050">浏览</font>网络或本地的<font color="#92d050">视频</font>。比如，我想看b站的[【官方双语】GPT是什么？直观解释Transformer | 深度学习第5章_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV13z421U7cs/?spm_id_from=333.337.search-card.all.click&vd_source=1dfee8e518fd6ba5fdb2287bbadc1674)这个视频，可以点击左边栏播放按钮，输入视频网址：
![Media_Extended.png](./images/Media_Extended.png)

然后，就可以直接在Obsidian里面看视频了：
![内嵌视频.png](./images/内嵌视频.png)

#### 4.2.6 PDF ++ 
PDF++插件可以帮助给PDF文件写笔记，提升阅读体验。
打开一个PDF文件后，PDF ++ 的主要功能集中在上方<font color="#92d050">工具栏</font>和<font color="#92d050">鼠标右键</font>选项：
![PDF++.png](./images/PDF++.png)

使用方法：打开PDF书籍和对应的笔记，选中要翻译、关键点、灵感或者其他段落，选择你要粘贴的方法，我这里选择了复制原文和页码：
![pdf++复制.png](./images/pdf++复制.png)

点击page，这段话就会被粘贴到对应的笔记中，并附带生成页码的链接，点击页码可以直接打开对应书籍的指定页：
![pdf++粘贴.png](./images/pdf++粘贴.png)

#### 4.2.7 Commander 添加命令
可以让自定义命令与按钮。例如，下图右上角的按钮，为命令<font color="#92d050">PDF++：create new note for auto-focus or auto-paste</font>，通过commander插件定义为快捷按钮使用，其功能为，当阅读PDF书籍时，在<font color="#92d050">随笔·白板</font>文件夹创建一个跟当前书籍相关联的笔记文件。
![commander.png](./images/commander.png)

## 5 AI学习助手使用指南（基础版）

### 5.1 copilot插件介绍

> [!note] 
> AI学习助手的AI部分，主要通过Obsidian软件里面的第三方插件<font color="#92d050">copilot</font>实现。copilot的主要功能有：1）支持多种AI模型； 2）搜索仓库里面笔记，通过"Vault QA"功能整合分散内容，快速生成总结或回答复杂问题； 3）提供一键翻译、润色、生成表格等功能，用户可自定义常用指令模板（如"专业润色"），并储存快速调用，提升操作效率。
> 
> 视频参考：[【录播剪辑】AI学习助手1.0-原理及概念介绍_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1R6L8zhEuf/?spm_id_from=333.337.search-card.all.click&vd_source=9de7c3a67fd42814f6579e0482d4d3ad)

插件已经安装好了，我们需要加载模型。我们在设置里面打开<font color="#92d050">copilot</font>，点击copilot页面中的<font color="#92d050">model</font>标签：
![copilot_model.png](./images/copilot_model.png)

AI学习助手的正常使用需要配置两种模型，<font color="#92d050">对话模型（Chat Model)</font>和<font color="#92d050">嵌入模型（Embedding Model）</font>。上述两种模型的具体功能，请参考：[[#5.2 AI基本问答流程]]。

加载的模型可以用网上运营商提供的api，也可以用下载到本地的。考虑到大部分朋友电脑配置不好，<font color="#92d050">本使用手册采用网上运营商API完成模型加载</font>。

> [!note] 使用网络运营商的优缺点
> 优点：1、对电脑硬件要求低；2、运算速度快
缺点：1、收费，deepseek R1每个问题需要4分钱左右；2、隐私安全问题，嵌入模型会搜索AI学习助手仓库里面的所有文件，包括所有的笔记、心得。

若要使用本地模型，推荐使用LM Studio下载和管理本地模型的使用和加载，详细请参考：[[#6.1 LM Studio]]

#### 5.1.1 添加Chat Model
首先添加对话模型。在Model标签页Chat Model下面，点击Add Custom Model按钮。
![添加chat_model.png](./images/添加chat_model.png)

弹出的模型配置窗口如下：
![AddCustomChatModel.png](./images/AddCustomChatModel.png)

配置以硅基流动API为例，请参考：[[#6.2 硅基流动]]

模型名字（<font color="#92d050">Model Name</font>）：在硅基流动的模型广场选择并复制要使用的大模型名字，如deepseek-AI/DeepSeek-R1
![model_name.png](./images/model_name.png)

展示名（<font color="#92d050">Display Name</font>）：向用户展示的名字，可自行设置，例如Siliconflow_deepseek-AI/DeepSeek-R1

供应商（<font color="#92d050">Provider</font>）：由于不同的软件，模型提供商所要求的访问模型的API不同，因此需要针对模型具体采用的API模式选择提供商，例如，若采用OpenAI的API则可以选择OpenAI Format。
![OpenAI_Format.png](./images/OpenAI_Format.png)

基础地址（<font color="#92d050">Base URL</font>）：访问模型功能的基础网址，例如https://api.siliconflow.cn/v1。
![硅基流动base url.png](./images/硅基流动base url.png)

API密钥（<font color="#92d050">API key</font>）：当你注册并在模型提供商申请API后，模型提供商会生成API密钥，只有带有有效密钥的模型使用请求才会被处理并返回模型结果。
![新建API密钥.png](./images/新建API密钥.png)

将新建好的API密钥复制粘贴到模型配置窗口中。
![复制API密钥.png](./images/复制API密钥.png)
![粘贴API密钥.png](./images/粘贴API密钥.png)

接下来，勾选<font color="#92d050">Reasoning</font>和<font color="#92d050">Enable CORS</font>两个选项。
>[!note]
Reasoning是表示添加的模型具有推理能力，即具有文字问答的能力。CORS是允许跨域资源共享（Cross-Origin Resource Sharing），即允许外部API访问。

![勾选reasoning和cors.png](./images/勾选reasoning和cors.png)

完成上面，点击verify验证：
![verify.png](./images/verify.png)

验证成功的话，Obsidian右上角会弹出Model verification successful（模型验证成功）字样：
![verify_successful.png](./images/verify_successful.png)

然后再点击Add Model添加模型：
![add model.png](./images/add model.png)

模型就添加到Chat Model列表中，若要激活该模型需要勾选Enable和CORS选项：
![勾选enable和cors.png](./images/勾选enable和cors.png)

添加好了对话模型后，可以配置模型参数，通常保持默认即可。
![temp_etc.png](./images/temp_etc.png)

>[!note]
><font color="#92d050">Temperature</font>指的是模型的温度，温度越高，模型创造力越强，缺点是容易瞎编。反之，模型越严谨，缺点是发散性较弱。
><font color="#92d050">Token Limit</font>指的是模型每次回答的最大字数。
><font color="#92d050">Conversation turns in context</font>指的是模型会记住多少前面的问答。15 turns就是15个用户提问和15个模型回答。

#### 5.1.2 添加Embedding Model
除了Chat Model，还需要添加Embedding Model嵌入模型。

>[!note]
嵌入模型的主要功能是搜索仓库里面的文本，把同跟提问相关文本提交给对话模型。深入了解嵌入模型，请参考： [[#5.2 AI基本问答流程]]
如果注重隐私，可以加载本地嵌入模型，如需使用LM Studio软件，请参考： [[#6.1 LM Studio]]]

添加Embedding Model的方法与添加Chat Model基本一致，只是模型功能不同。同样以硅基流动为例，点击展开筛选器，点击嵌入模型。
![展开筛选器.png](./images/展开筛选器.png)
![搜索嵌入模型.png](./images/搜索嵌入模型.png)

推荐选择第一个：
![选择BAAI.png](./images/选择BAAI.png)

之后的步骤基本一致，不在赘述。由于Embedding Model不具备Reasoning等功能，因此选项框只需要勾选<font color="#92d050">Enable CORS</font>：
![嵌入模型enable_CORS.png](./images/嵌入模型enable_CORS.png)

添加后的Embedding Model如下图所示。
![嵌入模型列表勾选cors.png](./images/嵌入模型列表勾选cors.png)

#### 5.1.3 Basic标签页设置

模型加载完成后，在Basic标签页选择刚刚加载完成的两种模型，就可以开始使用AI学习助手了
![选择你的模型.png](./images/选择你的模型.png)

选择你的Embedding Model后，一个重建检索库的弹窗会弹出来，我们点击<font color="#92d050">Continue</font>：
![rebuild_index.png](./images/rebuild_index.png)

检索建立成功，Obsidian右上角会弹出Index completed successfully!
![rebuild_index_suc.png](./images/rebuild_index_suc.png)

<font color="#92d050">这个步骤相当于Embedding Model把学习助手仓库里的所有文本（PDF除外）贴了标签，后续就可以通过标签和提问的相似度向对话模型提供相关文本。</font>

>[!tip] 快速使用
>点击左边栏或右边栏的<font color="#92d050">Open Copilot Chat</font>按钮以打开AI对话框
>![open_copilot_chat左.png](./images/open_copilot_chat左.png)![copilot右.png](./images/copilot右.png)
>
>每次有新笔记或笔记更新，点击对话框右上方的<font color="#92d050">Reindex Current Note</font>，帮助这篇笔记建立一个索引，相当于给图书馆新书贴标签：
>![reindex_current_note.png](./images/reindex_current_note.png)
>
>AI助手会自动推荐一些仓库里可能相关的文件，我另外创建了一个叫<font color="#92d050">学习助手使用</font>的测试笔记，内容就一句话："AI学习助手1.01这样安装最好"。嵌入模型通过搜索笔记后，认为这个文件和本文相似度最高，所以在AI对话框<font color="#92d050">Relevant Notes</font>（相关笔记）栏，<font color="#92d050">学习使用指南</font>排在第一位：
>![relevant_note.png](./images/relevant_note.png)
>
>点击左边的小按钮，可以看到嵌入模型估算的相关度：
>![相关度.png](./images/相关度.png)
>
>点击右边的<font color="#92d050">Add to Chat</font>按钮，可以把这篇笔记添加到对话框里面，作为问题一部分提交给AI：
>![add_to_chat.png](./images/add_to_chat.png)
>
>点击后，这个文件就会添加到下放的对话框里，文件名放在两个中括号里面是嵌入该文件的markdown语法。
>接下来，提问框左上角可以选择<font color="#92d050">chat</font>模式，也就是单纯用对话模型。或v<font color="#92d050">ault QA</font>模式，也就是利用嵌入模型搜索仓库里相关的文本，提交给对话模型：
>![chat_or_VaultQA.png](./images/chat_or_VaultQA.png)
>
>用了VaultQA模式，AI会搜索你的仓库，在回答里面包含你笔记的内容，甚至使用你的图片:
>![VaultQA_modelans.png](./images/VaultQA_modelans.png)
>
>可以选择不同的对话模型：
>![选择对话模型.png](./images/选择对话模型.png)
>
>最后，对话可以保存在本地，默认保存路径是<font color="#92d050">AI对话自动存档</font>文件夹：
>![AI对话自动存档.png](./images/AI对话自动存档.png)

#### 5.1.4 其他设置
<font color="#92d050">Default Mode</font>：AI聊天的默认对话模式。参数示例：Chat（对话模式） / Vault QA（仓库检索模式）

<font color="#92d050">Open Plugin In</font>：用侧边栏或者用编辑器打开AI聊天对话框

<font color="#92d050">Default Conversation Folder Name</font>：AI对话存档的文件夹，默认文件夹是<font color="#92d050">AI对话自动存档</font>

<font color="#92d050">Custom Prompts Folder Name</font>：保存提示词prompts的路径。默认文件夹是<font color="#92d050">AI快捷指令</font>

>[!tip] 提示词就是用户向AI的提问。
>有一些提问技巧，可以提升AI回答的准确性。
>一些重复好用的提示词可以保存到<font color="#92d050">AI快捷指令</font>文件夹里，方便复用。

<font color="#92d050">Default Conversation Tag</font>：保存AI对话的默认标题。默认值：AI-conversations

<font color="#92d050">Conversation Filename Template</font>：保存的AI问答文件的开头格式。默认格式：话题-日期-时间

<font color="#92d050">Autosave Chat</font>：聊天记录自动储存，打开的话每次新建对话都会自动储存之前的话题。新建对话按

<font color="#92d050">New Chat</font>按钮：
![New_chat.png](./images/New_chat.png)

<font color="#92d050">Suggested Prompts</font>：是否显示copilot推荐的提示词。

<font color="#92d050">Relevant Notes</font>：是否显示相关笔记。

#### 5.1.5 QA标签页设置
QA标签页是帮助设置嵌入模型搜索本地文件的。这一页比较重要。

<font color="#92d050">Max Sources</font>：最大文本数。这个数字决定嵌入模型会把几段相关文本投喂给对话模型。

<font color="#92d050">Requests per Minute</font>：每分钟请求数。决定每分钟向AI服务商发送的最大请求次数

<font color="#92d050">Embedding Batch Size</font>：一次性发送给嵌入模型处理的文本块数量。数量越大，单次处理的文本块越多，整体处理速度越快，增加显存、内存占用（如果你的嵌入模型放在本地）

<font color="#92d050">Number of Partitions</font>
Number of partitions for Copilot index. Default is 1. Increase if you have issues indexing large vaults. Warning: Changes require clearing and rebuilding the index!

<font color="#92d050">Exclusions</font>：嵌入模型不可访问的文件夹。

<font color="#92d050">Inclusions</font>：嵌入模型可访问的文件夹。

<font color="#92d050">Enable Obsidian Sync for Copilot index</font>：如果打开，索引文件（相当于图书馆标签系统）文件会储存在 .Obsidian 文件夹

![Obsidian文件夹.png](./images/obsidian文件夹.png)

<font color="#92d050">Disable index loading on mobile</font>：打开此项，索引文件会同步到手机Obsidian上

#### 5.1.6 Command标签页设置
command栏是一些右键快捷AI指令:
![Copilot_command.png](./images/Copilot_command.png)

选择文字-点击鼠标右键，点击你想要的指令：
|Fix grammar and spelling||| 改语法拼写错误
||Translate to Chinese||| 翻译成中文
||Summarize||| 总结
||Simplify||| 简化
||Emojify||| 转换成emoji
||Make shorter||| 缩短
||Make longer| 扩写

比如，修改语法试一下你这句话把：
![Copilot_command_FixGram.png](./images/Copilot_command_FixGram.png)

结果如下：
![Copilot_command_FixGram_res.png](./images/Copilot_command_FixGram_res.png)

这些指令可以自行修改、编写，打开Copilot <font color="#92d050">Command</font>标签页，点击第一项：<font color="#92d050">Fix grammer and spelling</font>旁边的钢笔按钮：
![Copilot_command_check_format.png](./images/Copilot_command_check_format.png)

![Copilot_command_check_format2.png](./images/Copilot_command_check_format2.png)

复制上面指令的格式，然后回到<font color="#92d050">Command</font>页面，点击<font color="#92d050">Add Command</font>：
![Copilot_command_AddCommand.png](./images/Copilot_command_AddCommand.png)

粘贴刚才复制的指令格式，改成自己的指令并保持：
![新增copilot_command.png](./images/新增copilot_command.png)

试一下新指令：
![copilot_试一下新command.png](./images/copilot_试一下新command.png)

结果如下：
![新command_res.png](./images/新command_res.png)

#### 5.1.7 Advanced设置

<font color="#92d050">User System Prompt</font>：添加到所有用户提问中的提示词，例如，你想让AI扮演什么角色，或者回答要包含哪些内容。

添加一段人设：
![system prompt.png](./images/system prompt.png)

用两个中括号引用了AI快捷指令里面的[[回顾笔记内容]]：
![问御姐.png](./images/问御姐.png)

回答如下：
>[!example] 
（指尖轻敲桌面三下）仔细听好：先在Copilot设置中启用"Relevant Notes"并选择`BGE-M3`模型，就像打开自动关联的神经突触。撰写笔记时用`$关键概念$`标注术语，插入`[[双链]]`关联已有知识节点。执行`@vault 生成复习卡片`指令，系统会自动提取[[英语词根表]]等关联内容，按以下结构输出...
>......
>...最后点击![reindex_current_note.png](./images/reindex_current_note.png)重建索引，让新卡片融入知识网络。需要具体案例参考[[哲学复习卡片范例]]第7节。（眼尾微挑）这种信息密度——跟得上么？

### 5.2 AI基本问答流程

本节内容主要通过流程图帮助用户了解从提问，到获得AI回答，中间发生的具体过程。
第一个流程图显示的是deepseek R1的流程。
第二个流程图显示的是AI学习助手增强了哪些部分。

>[!note] 对话模型和嵌入模型
><font color="#92d050">对话模型</font>（Chat Model）就是大语言型（LLM，large language model）也叫推理模型（Reasoning Model），解码模型（Decoder Model）。它的主要功能是分析<font color="#92d050">用户文字提问，生成文字答案。</font>一般来说，对话模型参数越多，对话能力越强。Deepseek R1满血版有6710亿个参数，要1300多G的显存才能加载完成。
><font color="#92d050">嵌入模型</font>（Embedding Model）是一个编码模型（Encoder model），其主要作用是将文本向量化，从而可以计算文本之间的相似度等。嵌入模型一般只有100-300M大小，非常适合下载到本地使用。
>本地下载使用AI模型，请参考[[#6.1 LM Studio]]部分。

#### 5.2.1 deepseek R1工作流程
使用大语言模型时，如deepseek R1，用户和AI的问答流程如下：
```mermaid
%%{init: {"theme": "default", "themeVariables": { "fontSize": "14px"}}}%%
flowchart TD
    A[用户提问] --> C{对话模型<br>Chat Model}
    B[过往对话] --> C
    C -->|深度思考| D[改写提问<br>Rewritten Querry]
    A --> H{对话模型<br>Chat Model}
    B --> H
    D --> H
    H --> I[生成答案]
```
上图可以看到，用户提问和过往对话会输入给对话模型（也就是大语言模型），生成一个改写过的问题。这个改写问题就是R1<font color="#92d050">深度思考</font>产生的提示词或背景描述。然后，<font color="#92d050">原来提问、过往对话、和改写提问三部分</font>会再次输入给对话模型，最后生成回答。

#### 5.2.2 学习助手增强问答流程
大语言模型有几个缺点：第一，容易产生幻觉，也就是生成虚假数据或者细节；第二，信息可能过时；第三，容易忘记用户持续统一的要求（比如希望AI扮演某角色）。通过检索增强生成（Retrival-augmented Generation或RAG）的技术，可以有有效的减少大语言模型的幻觉问题，该技术流程如下：
```mermaid
%%{init: {"theme": "default", "themeVariables": { "fontSize": "14px", "nodeWidth": "30px" }}}%%
flowchart TD
    A[用户提问<br>Query] --> C{对话模型<br>Chat Model}
    B[过往对话] --> C
    C -->|深度思考| D[改写提问<br>Rewritten Querry]
    D --> E{嵌入模型<br>Embedding Model}
    E -->|搜索仓库| F[相关文本块]
    A --> H{对话模型<br>Chat Model}
    B --> H
    D --> H
    F --> H
    G[系统提示词<br>System Prompt] --> H
    H --> I[生成答案]
```
相对于一般问答，增强问答还包含了两部分内容，第一，用户可以写一个<font color="#92d050">系统提示词</font>，该提示词每次提问都会自动添加到问题中，不断提醒AI。第二，可以使用<font color="#92d050">嵌入模型</font>（Embedding Model），辅助搜索<font color="#92d050">搜索本地仓库</font>，把跟提问<font color="#92d050">相关的文本</font>找出来，当作提问的一部分输入对话模型。

>[!note] 嵌入模型如何查找相关文本块？
>**​一、预处理阶段​​**（Rebuild Index)
​​<font color="#92d050">分块​​</font>
>将笔记内容切割为多个文本块（Chunks），便于后续处理。
​​<font color="#92d050">向量化​​</font>
>用嵌入模型将每个文本块转换为语义向量，捕捉文本含义。
><font color="#92d050">​​存储​​</font>
所有语义向量存入数据库，按语义关联性分类存储。
​​
**二、检索阶段​​**
​​<font color="#92d050">提问转换</font>​​
>将用户提问转化为语义向量，与数据库向量统一维度。
 ><font color="#92d050">语义匹配​​</font>
> 从数据库中快速筛选与提问向量最相似的文本块。
><font color="#92d050">​​生成答案​​</font>
>将匹配的文本块作为上下文，输入大模型生成最终回答。

# 第二部分：新增功能(V1.2)

## **零、版本情况**
### **1.2 版本功能特性**
- **AI学习助手界面** - 提供直观的操作界面，一键管理Obsidian软件和语音功能。
- **Obsidian插件语音功能** - 在Obsidian Copilot插件中新增语音功能，包括录音转文字、音视频转文字，以及文字转语音，支持自动播放和更自然的对话方式，模拟真实交流。
- **更多AI学习角色** - 提供多样化的AI学习助手角色，并支持问题延伸功能，AI会主动提出相关学习问题，帮助用户深入学习。
- **语音功能优化** -** 为CUDA用户升级至更高品质的TTS模型，生成音色更生动自然，支持音色克隆功能。语音服务可根据用户设备性能自动适配最优模型，确保流畅体验。

### **1.1 版本功能特性**
- 通过自定义标签设计，实现定制不同的AI人设，满足对话需求
- 支持引用不同文档内的多段文本内容与AI进行交互
- 支持对本地音视频进行语音识别，并可在windows上通过CPU/CUDA上一键部署
- 支持对选中文本进行文字转语音，并可在windows上通过CPU/CUDA上一键部署


## **一、启动器使用**
### **1.1 启动器解压与启动**
首先，下载学习助手软件包“AI-Learning-Assistant-V1.2.0-Launcher-win32-x64-1.0.0.zip”，并解压到指定文件夹(解压路径尽量选择英文路径)，点击其中的学习助手图标的程序启动，如下图：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.001.png)

点击后会启动学习助手界面，目前主要有两块内容，分别是：

1. 学习助手阅读器：用于对obsidian阅读器进行管理，支持多仓库管理、开发插件本地一键更新，后续版本会在其中逐步支持学习资料管理、AI人设管理等内容(暂未支持，敬请期待~)
1. 学习助手工具箱：用于集成管理与使用各种AI工具，目前支持文字转语音(TTS)与语音转文字(ASR)一键部署，后续版本会在其中逐步支持AI跑团、本地语言模型部署、AI绘图等工具(暂未支持，敬请期待~)

### **1.2 学习助手阅读器使用说明**
在学习助手阅读器界面，如果未安装obsidian软件，请点击“安装阅读器”按钮进行安装，会跳出obsidian软件安装程序，请按照指示完成安装。

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.002.png)

安装好obsidian软件后，则需要点击“定位阅读器”，点击后会跳出一个选择文件框，用于选择obsidian软件运行程序。

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.003.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.004.png)



我们可以通过已下方法得知obsidian软件运行程序的具体地址，通过windows搜索栏按照序号顺序输入与点击内容，最后复制此软件的绝对路径，粘贴至定位阅读器的选择框中，最后点击“打开”确认：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.005.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.006.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.007.png)

确定好obsidian位置后，点击需要使用的obsidian仓库的“插件情况”进行插件更新，目前支持对二次开发插件进行更新：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.008.png)

安装好指定插件后，请在obsidian的插件管理页面启动这两个插件：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.009.png)

若你先前安装了原版的aloud/copilot插件，由于插件兼容冲突的原因，需要首先关闭原先插件，再启动新版插件，才能正常使用。

相关新版obsidian插件新功能的使用说明请跳转至“第二部分”。

### **1.3 学习助手工具箱使用说明**
工具箱主要提供各种AI增强服务功能，当前版本支持语音转文字、文字转语音功能，后续功能会逐步添加其他功能。
#### **1.3.1 服务初始化**
首先使用工具箱相关功能，需要在Windows上启动WSL功能,请点击按钮进行启动：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.010.png)

启动后需要安装一些程序，安装好后会提示需要重新启动电脑：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.011.png)

重新启动好后，接下来开始正常开始使用相关功能了。


#### **1.3.2 语音服务使用**
对于TTS/ASR功能，我们提供了"AI-Learning-Assistant-V1.2.0-Voice-v1.1.tar"安装包，其点击其中一个功能的安装按钮，选中指定tar包进行导入与安装，初始安装可能需要耗费比较长的时间(10分钟左右)，请耐心等待：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.012.png)



![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.013.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.014.png)



##### **1.3.2.1 语音转文字**
**基础使用：**

安装完毕后，请点击“启动”，可以在设置页面查看启动情况，当看到最终提示9000端口的相关信息时，可知服务启动成功。接着，我们可在“2.3”部分配置obsidian插件相关参数(注意，请使用本地地址的 URL进行配置，例如 '[http://127.0.0.1:9000](http://127.0.0.1:9000/)'。如果使用全局地址 '[http://0.0.0.0:9000](http://0.0.0.0:9000/)'，由于相关网络参数未正确配置，可能无法正常使用服务。)来使用ASR服务。

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.015.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.016.png)

注意：

1. 请在不需要使用时即时关闭相关服务，以免内存/显存占用

##### **1.3.2.2 文字转语音**
**基础使用：**

安装完毕后，请点击“启动”，可以在设置页面查看启动情况，当看到最终提示8000端口的相关信息时，可知服务启动成功。接着，我们可在“2.2”部分配置obsidian插件相关参数(注意，请使用本地地址的 URL进行配置，例如 '[http://127.0.0.1:8000](http://127.0.0.1:9000/)'。如果使用全局地址 '[http://0.0.0.0:8000](http://0.0.0.0:9000/)'，由于相关网络参数未正确配置，可能无法正常使用服务。)来使用TTS服务。

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.017.png)


![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.018.png)



另外要注意的是，在设置中我们可以强制指定N卡或cpu的运行条件，这样的区别是强制N卡使用index-tts模型，而强制cpu使用kokoro模型。而在默认不强制情况下，程序会根据当前设备的硬件状况运行指定模型(若无N卡以及cuda驱动，则运行kokoro模型；若有则默认运行index-tts模型)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.019.png)



这里展示下当前可用的文本转语音模型总体情况：

|模型|运行速度|语音质量|
| - | - | - |
|kokoro(A卡或cpu默认运行)|cpu/gpu可用，运行速度快|中规中矩，发挥稳定，语气清晰感偏弱|
|index-tts(N卡默认运行)|gpu速度较快，cpu非常慢，不建议在只有cpu上使用该模型|语音质量较高，发声自然，带一定的情绪，且支持音色克隆|


**音色克隆：**

以下介绍音色克隆的方法：点击“添加语音”，选择一段比较干净无噪声的说话人音频文件(7s~20s即可)，确认后会在语音配置管理界面出现一个新增卡片：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.020.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.021.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.022.png)


接下来我们需要编辑新增音色的相关配置，尤其是“语音对应文本”即需要填写上传音频对应的文本内容，当各种参数配置好后，我们点击"保存语音配置"：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.023.png)

配置好后，若文本转语音服务正在运行，则需要停止服务重新启动，新增音色才能正常使用。

注意：

1. 本团队提供此项功能主要是为了方便学习的目的，请不要滥用或不正当使用他人音色
1. 请在不需要使用时即时关闭相关服务，以免显存占用


## **二、obsidian阅读器新特性使用**
本部分主要介绍1.2 版本与1.1 版本新增功能的教程说明，更基础的obsidian插件说明请参考其他教程视频与学习手册。

### **2.1 copilot 基础功能使用**
为方便使用，我们在2.1.1与2.1.2中收录了相关1.1的开发功能。
#### **2.1.1 多文本内容引用**
通过"copliot + commander"插件的组合，我们可以将命令面板的"Copilot:Add paragraphs to reference"命令加入到文件右键命令当中：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.024.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.025.png)


通过上述方法，我们就可以实现将选中文本添加到copliot的对话框内，并且支持索引语法进行简洁引用，不直接粘贴文本，方便进一步的提示词书写与整理：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.026.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.027.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.028.png)

我们可以对多个文档的指定文段进行引用：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.029.png)




#### **2.1.2 人设自定义**
打开obsidian 的设置界面，找到copliot插件：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.030.png)

目前copilot 插件设置页面新增"捏人设"功能，通过"人设调试版"可以组合出各种人设：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.031.png)

我们可以在选中区域内新增标签，并填写相应的标签内容(注意如果新加的标签与已有的标签重名，则无法成功添加)：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.032.png)

对于已有标签，它会匹配多个标签条目，用于存储这个标签下的各种设定，比如说关于”角色“这个标签，我们可以设置“哲学家”、“科技史研究者”、“欧洲历史研究者”等多个标签条目，但每次一个标签只能选中一个条目。我们可以修改当前选中的标签条目的内容，或者新增/删除对应的标签条目，如下所示：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.033.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.034.png)

关于调整不同标签之间的位置，可以通过最左侧的上下箭头实现：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.035.png)

当我们设置好了人设的各种所需要的标签，我们可以在红框处输入名称比如"科技史研究者"，接着点击"添加人设"，即可添加相应人设：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.036.png)

添加好后，可以发现所定义人设出现在了"人设列表"中，且还可以在编辑面板中调整我们人设设定：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.037.png)

最后说明下如何使用，我们可以点击指定人设的左侧按钮，即可切换到想要的人设配置上，后续AI助手就会以这个身份来与我们对话。

当然，你也可以在AI助手的对话框上方切换人设，如下图：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.038.png)

接下来我们就可以根据我们自己设定的人设与AI更加"亲密"地互动了！

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.039.png)

#### **2.1.3 自动衍生问题**
copilot的1.2版本主要新增自动衍生问题、自动语音播放两个功能，下面主要说明自动衍生问题的原理和使用方法，自动语音播放功能说明请看2.2章节。
##### **2.1.3.1 自动衍生问题原理说明**
自动衍生问题主要采取提示词控制大模型输出特定格式的方式实现，也就是说使用特定提示词，使得大模型按照提示词的要求进行输出。如目前插件中默认的提示词，截图如下：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.040.png)

在对话界面中启动自动衍生问题开关后，向大模型提问"你有什么功能"，返回的内容最后就会带上衍生的问题。

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.041.png)

大模型回复截图如下：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.042.png)

当我们继续向大模型提问"请回答问题2”，copilot本身会将对话的上下文一起发送给大模型，那么就会回答之前衍生出来的问题，从而实现自动问题的衍生与答复。

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.043.png)
##### **2.1.3.2 自动衍生问题提示词与系统提示词关系的详细说明(可跳过)**
开启自动衍生问题开关后，就会将相应的提示词拼接到系统提示词上，如果有选择人设或开启口语化功能，会按照"默认系统提示词" + "人设提示词" + "自动衍生问题提示词" + "口语化提示词"的顺序拼接文本，形成系统提示词。如果某项功能没有开启或没有设置，则忽略不进行拼接。

自动衍生问题提示词可以在设置界面中进行修改，如果修改成其它提示词的要求，也是没有可以的。目前的功能本质上只是**将相应的文本拼接起来作为系统提示词发送给大模型**，前端的开关按钮只是用于控制是否将相应的文本拼接在一起。所以自动衍生问题的提示词，包括2.2章节的口语化提示词功能，都是可以修改成自己需要的提示词，同样也可以把相应的提示词写到人设提示词中，只要确保自己配置的提示词会发送给大模型即可。目前自动衍生问题、口语化等功能的提示词是针对特定场景而进行配置的。

可以在设置界面中查看copilot默认系统提示词，并可通过开关进行控制。截图如下：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.044.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.045.png)

### **2.2 copilot 语音播放服务接入**
#### **2.2.1 aloud基础配置** 
在AI学习助手启动器上更新aloud插件到最新版本（更新方式参考启动器使用“1.2”部分），并启动文本转语音服务。

接下来要在aloud插件中配置连接本地文本转语音的服务，配置方法如下：进入obsidian 的配置页面，将"Model Provider"切换至"OpenAI Compatible(Advanced)",接下来填写其他参数。本地部署的话"API key"填写任意字符串或者为空都可以，"API URL"一般填写为本地主机的8000端口，也就是填写"[http://localhost:8000](http://localhost:8000/)"（注意,"http://0.0.0.0:8000"可能无法成功访问，请填写"localhost"格式）,“Model"中填写当前已经部署的模型 kokoro或者index-tts模型，填写好后如下图所示:

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.046.png)

如果之前已配置aloud插件，只要保证更新aloud插件版本后能正常在笔记中使用文本转语音即可。

接下来，我们可以在obsidian中的任意文档内右键选中指定文本进行语音播放，如下图：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.047.png)


我们也可以右键选中指定文本，导出这些文本的音频文件，进行播放：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.048.png)

另外，对于音频存储功能，aloud支持对于过去播放过的文字进行缓存，以及设置多长时间缓存自动清除；对于导出的音频文件，aloud也支持指定存放音频文件的地址。如下图：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.049.png)


#### **2.2.2 语音播放功能说明**
copilot插件目前支持语音播放相关功能（注意使用前需要配置好aloud插件以及文本转语音服务），如下图：

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.050.png)

开启自动语音播放开关，当大模型返回结果后就会自动播放语音。

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.051.png)

我们也可以点击AI消息框下的语音播放按钮进行播放。

#### **2.2.3 口语化提示词说明**
设置口语化提示词的目的是通过控制提示词要求大模型输出的文本尽量短，如果返回的文本过长，自动语音播放就会等到结果完全返回后才进行播放，时间较长。这种长文本情况似乎就没有必要进行语音播放，所以添加口语化提示词的方式控制大模型输出。当然不启动口语化开关也是可以进行自动语音播放的。

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.052.png)

也可以通过设置界面修改口语化提示词，使大模型返回的结果符合自己的设置，类似自动衍生问题的提示词。

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.053.png)

### **2.3 copilot 语音识别功能使用**
#### **2.3.1 ASR基础配置**
1,打开Copilot插件设置页面,点到ASR

2,看图红色框框可以切换openai服务或者本地服务

3,默认使用本地ASR服务,端口是9000,如果自己想改动,请保持前后端的端口相同。另外请务必开启encode与VAD,这是确保本地服务正常运作的条件

4,如果切换使用openai服务,请在API Setting中填写API Key

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.054.png)

5,File Saving Settings服务于语音识别功能,设置Recordings folder后录音会存入指定位置

6,设置Transcriptions folder后,(在没有指定笔记时)语音识别生成的笔记会存入指定位置

8,General Settings暂时是没有用处的,不必配置

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.055.png)

#### **2.3.2 录制语音后转文字**
1,如图点击Open recording controls或者在笔记右键后选择语音输入文字

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.056.png)

2,点击后会弹出录音器,Record为开启录音,Pause暂停,Stop结束录音并转文字

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.057.png)


3,**在copilot 对话框中识别语音识别**：在chat对话框使用语音输入,点击voice按钮,再点Record然后说话

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.058.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.059.png)

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.060.png)



#### **2.3.3 音视频转文字**
1,使用ctrl+p打开命令行, 手打transcri,以下命令都可以对应实现功能

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.061.png)

2,或者选择任意音频或者视频右键,在菜单中选择🎧Transcribe 稍等推理完成,就会根据语音生成文字

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.062.png)

3,注意：在插件配置中如图开启时间标注(Enable timestamps)暂时无法使用，不需要开启

![descript](./images/Aspose.Words.3ce157ed-4731-4541-a350-b2980939925f.063.png)



## **三、使用反馈**
在使用软件时遇到任何问题，欢迎加入QQ群807831970进行交流和咨询！



# 第三部分：其他功能

## 6.1 LM Studio

LM Studio 是一个本地化的大语言模型运行与开发平台，它允许用户在个人电脑上轻松加载、测试和使用各种开源大语言模型。无需联网、无需云服务费用，所有数据处理均在本地完成，保护隐私的同时提供高效的推理能力。
LM Studio 是一款让你在电脑本地免费运行AI聊天机器人（类似ChatGPT）的软件，无需联网，完全离线使用！  

核心功能
   - 本地运行AI模型：直接在电脑上运行各类AI大模型（如Llama、Mistral等），无需注册账号或付费。  
   - 隐私安全：所有对话内容仅保存在你的电脑，不上传网络。   
   - 简单易用：无需编程知识，界面像聊天软件一样直观。  
适合谁用？  
   - 想体验AI但不想付费/注册账号的用户  
   - 注重隐私、希望离线使用AI的人
   - 对科技感兴趣的小白或开发者

### 6.1.1 下载、安装LM Studio
在百度云盘分享的AI学习助手1.01资料分享的相关软件安装包文件夹中找到相应软件运行安装。

![百度网盘.png](./images/百度网盘.png)
![LMStudio安装.png](./images/LMStudio安装.png)

安装完成后，打开软件后先点击右上角skip onbording
![LMStudio主界面.png](./images/LMStudio主界面.png)

在右下角设置中设置软件为中文
![LMSsudio设置.png](./images/LMSsudio设置.png)
![LMStudio设置中文.png](./images/LMStudio设置中文.png)

### 6.1.2 LM Studio功能介绍
>[!info] LM Studio官方文档： https://lm-studio.cn/docs/basics

软件主要有四个模块：聊天（Chat）、开发者（Developer）、我的模型 （My Models）、发现 （Discover）
1. **<font color="#92d050">聊天（Chat）</font>**：顾名思义就是和AI聊天的地方；
2. **<font color="#92d050">开发者（Developer）</font>**：这个板块是为懂点技术的人或者想让其他软件也能用你本地AI的人准备的，它把你的LMStudio变成一个本地AI服务，单纯聊天的话用不到；
3. **<font color="#92d050">我的模型（My Models）</font>**：管理现在手上有的所有模型，从"发现"板块下载下来的模型，或者你自己想办法弄到并存放到特定文件夹的模型，都会显示在这里；
4. **<font color="#92d050">发现（Discover）</font>**：可以调整运行环境，相当于一个"AI模型商店"或"模型图书馆"。这里展示了大量别人训练好的、可以下载使用的AI模型。

![LMStudio主要模块.png](./images/LMStudio主要模块.png)

1. 我们先从<font color="#92d050">发现（Discover）</font>**开始介绍软件的使用
Model Search中可以搜索并一键下载匹配电脑配置的模型，另外建议在设置中将模型加载保护调整为宽松或平衡

![LMStudio搜索模型.png](./images/LMStudio搜索模型.png)
![LMStudio模型加载.png](./images/LMStudio模型加载.png)

模型名称后面的4B、8B等为模型参数量，模型参数量越大，模型越聪明；但模型越大运算占的显存越大，速度越慢。另外带有<font color="#ff0000">CORS</font>**功能的模型会显示视觉功能启用

![LMStudio模型参数量选择.png](./images/LMStudio模型参数量选择.png)
![LMStudio带有cors的模型.png](./images/LMStudio带有cors的模型.png)

Runtime中配置你的模型运行环境，分为三种模式CPU、CUDA、Vulkan，下载相应模型并启用
- CPU：使用CPU运行模型，电脑没有好显卡或兼容性出现问题时可以使用，但速度最慢，适合临时使用
- CUDA：电脑中的显卡是英伟达的显卡且不存在其他品牌显卡时使用，效果最佳
- Vulkan：显卡不是英伟达显卡，或英伟达显卡与其他显卡混搭时使用，速度快，通用性强

![LMStudi_ runtime.png](./images/LMStudi_ runtime.png)

2. **<font color="#92d050">我的模型 （My Models）</font>**
存放着已经下好的模型，模型目录可以自行设置下载模型的存放位置

![LMStudio我的模型.png](./images/LMStudio我的模型.png)

3. **<font color="#92d050">开发者（Developer）</font>**
开发者模块，可以在左侧启用端口，端口未开启的话只能在LM Studio内部使用模型，打开之后可其他软件可以通过AIP调用的方式使用加载的模型。
![LMStudio开发者.png](./images/LMStudio开发者.png)

在设置中可以启用"在网络中提供服务"，这可以使同一局域网下的其他设备使用本机上的模型，比如手机或同一网络下的其他电脑等，CORS启用后可以上传图片、音频等格式给模型进行处理（当然，需要先配置好具有CORS功能的模型）

![LMStudio模型设置.png](./images/LMStudio模型设置.png)

选取要加载的模型

![LMStudio选择要加载的模型.png](./images/LMStudio选择要加载的模型.png)

>开启"手动选择模型加载参数"选项后，点击相应模型修改参数，**<font color="#ff0000">设置完成后,勾选Remember settings for "xxxx"，然后加载模型</font>**，主要设置如下：
>- Auto Unload If Idle (TTL)：模型闲置 Xmin后自动卸载，释放显存/内存
>- 上下文长度：模型能"记住"的对话字数上限
>- GPU卸载：将模型拆分部分到显卡运行（显存不足时用CPU辅助）
>- CPU Thread Pool Size：调用 CPU 核心数 处理计算
>- 评估批处理大小：单次处理文本片段数量（越大越快，但更吃显存）
>- <font color="#ff0000">保持模型在内存中</font>：将模型预存在内存中，会长期占用内存，默认是开启的，但是建议关掉，除非你的模型相对你的电脑来说很小，没有太大影响
>- <font color="#ff0000">尝试mmap（）</font>：用内存映射加载模型，默认开启，同样建议关掉

![LMStudio调整模型参数.png](./images/LMStudio调整模型参数.png)
![LMStudio加载模型2.png](./images/LMStudio加载模型2.png)

加载模型后可以在任务管理器的性能界面看到当前占用的显存大小

![任务管理器.png](./images/任务管理器.png)

4. **<font color="#92d050">聊天（Chat）</font>**
模型部署好了之后，就可以在聊天界面使用，使用方法和市面上的AI是相同的，点击右上角的小按钮可以进行对话设置
>1. 系统提示：设定AI的风格，例如"你是个幽默的助手"、"你是个温柔的..."
>2. 温度：低温（0.1~0.5），保守输出，答案稳定如教科书；高温（0.7~1.0）：创意放飞，可能胡说八道但更有趣

![LMStudi聊天界面.png](./images/LMStudi聊天界面.png)

## 6.2 硅基流动

硅基流动（SiliconFlow）是一个专注于生成式人工智能（AIGC）的云服务平台，旨在为开发者、企业及个人提供"低成本、高效率的AI模型调用服务"。你可以将它理解为"AI模型的云端超市"，无需自己搭建复杂的服务器，通过简单的API即可调用各类先进的大模型15。

 核心特点：

1. 模型丰富：集成50+主流开源模型，涵盖文本生成（如DeepSeek R1）、图像生成（如Stable Diffusion）、代码生成（如Qwen-Coder）等多领域17。
    
2. 高性价比：部分小模型（如9B参数以下）永久免费，新用户注册赠送2000万Tokens（相当于生成约400万汉字），大幅降低使用门槛15。
    
3. 简单易用：提供统一API接口和在线调试工具（Playground），无需代码基础也能快速上手57。

### 6.2.1 如何在Obsidian中接入硅基流动？

### 6.2.2 步骤1：注册并获取API密钥

1. 注册账号：访问[硅基流动官网](https://cloud.siliconflow.cn/)，使用手机号或邮箱注册（邀请码可额外获得免费额度）。
    
2. 创建API密钥：登录后进入【API密钥】页面，点击"新建密钥"生成唯一的密钥（类似密码），妥善保存备用。
    ![新建API密钥 1.png](./images/新建API密钥 1.png)

### 6.2.3 步骤2：配置Obsidian Copilot插件

需要安装Copilot插件，打开Copilot插件，找到Model下的"add Custom Model"![copilot添加模型.png](./images/copilot添加模型.png)

在硅基流动官网找到要使用的模型，复制模型名称，输入base URL（例如https://api.siliconflow.cn/v1），填入API KEY ，最后勾选下方Enable CORS，点击Verify验证成功后，即可点击Add Model添加硅基流动提供的模型。
![输入模型名称和API.png](./images/输入模型名称和API.png)

## 感谢

感谢所有为项目付出的朋友们，因为你们才让我们的开源项目得以一步步落地！以下是贡献者及内容：

### 1.1 版本 贡献名单

| 贡献者 | 贡献内容 |
|--------|---------|
| 柯南 | obsidian插件开发、TTS多平台整合包制作 |
| 罗鉴 | ASR后端开发、ASR多平台整合包制作、使用文档编辑 |
| 南云 | TTS后端开发 |
| 生年不满百 | obsidian插件开发 |
| 岂能 | obsidian插件开发、学习助手整合、使用文档编辑 |
| 教你说再见 | obsidian 插件开发、使用文档编辑 |
| 简单（康） | obsidian插件开发 |
