<h2 align="center">
    <img src="https://gptlesson1.oss-cn-beijing.aliyuncs.com/chatgpt.png" height="64">
    <br>ChatGPT
</h2>
<h3 align="center">
    <a href="https://marketplace.visualstudio.com/items?itemName=zhang-renyang.chat-gpt" alt="Marketplace version">
        <img src="https://img.shields.io/visual-studio-marketplace/v/zhang-renyang.chat-gpt?label=VS%20Code%20Marketplace" />
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=zhang-renyang.chat-gpt" alt="Marketplace download count">
        <img src="https://img.shields.io/visual-studio-marketplace/stars/zhang-renyang.chat-gpt" />
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=zhang-renyang.chat-gpt" alt="Marketplace download count">
        <img src="https://img.shields.io/visual-studio-marketplace/d/zhang-renyang.chat-gpt?label=Downloads" />
    </a>
</h3>
<p align="center">Keyless,Magic-free,Login-free,Support GPT-4</p>
<p align="center" >免Key,免魔法,免登录,支持GPT-4</p>


<div style="display: flex; justify-content: space-between;">
<div style="width: 45%;">

**English**

## Features
- 💻 Copy and insert code into current and new files
- 🚀 Add predefined prompts for quick input during questioning
- 📤 Export code or entire conversations as markdown files
- 💾 Save your conversation history on your local hard drive, replay, continue, and manage at any time
- 🔑 Bind your own API key that supports GPT4 to use the GPT4 model
- 🗣️ Bind your own API key to support streaming context conversation and you can pause the response at any time
- 🌐 Use your own OpenAI server
- 🔒 Privacy secured, all information is saved on your local hard drive, without uploading any information to any server

## Commands
- **ChatGPT:Ask a question❓**: Click on the ChatGPT icon and input your content, then press Enter to get a reply from ChatGPT
- **ChatGPT:Bind your own API key🔀🔑**: Easily bind your own API key using a combination of shortcuts and commands
- **ChatGPT:Validate API key✔️🔑**: Validate your API key to ensure its validity and correct function
- **ChatGPT:Refresh API key🔄🔑**: Refresh the existing API key to obtain a new API key
- **ChatGPT:Why is there a bug in this code?🐛💻**: Use the code error-finding feature to analyze and highlight errors in the code
- **ChatGPT:Help me explain the code?💬📖**: Use the code explanation feature for a better understanding of your code
- **ChatGPT:Refactor this code and tell me what did you change?🔧**: Refactor code and understand clearly what you've changed
- **ChatGPT:Add some test for this code for me➕🧪💻**: Easily add tests for your code
- **ChatGPT:Custom prompt✏️❓**: Generate custom queries for ChatGPT
- **ChatGPT:Add Predefined Prompt➕**: Add predefined prompts through a combination of shortcuts and input
- **ChatGPT:Set language🌍**: Set the language you want with shortcuts and commands. The default is English
- **ChatGPT:Set up a custom proxy server🌐**: Set and use your own proxy server by inputting your proxy server information
- **ChatGPT:Clear list🗑️**: Able to clear the current conversation
- **ChatGPT:Export markdown📤**: Able to export the current conversation as a markdown file

## 📖 Usage
### 🔧 Install the extension
Install the extension from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=zhang-renyang.chat-gpt)

###  Ask question❓
Press the shortcut key `Ctrl+Shift+P`, type `ChatGPT:Ask a question ❓`, press Enter, type your question, press Enter again, and the answer panel will automatically open to provide an answer.

Alternatively, click on the ChatGPT icon on the left, enter what you want to say, press Enter, and wait a few seconds for ChatGPT's reply to appear.

On the answer page, the first small icon is for copying to the clipboard, the second small icon is for inserting the answer at the current cursor position, and the third small icon is for creating and opening a file and inserting the answer at the current cursor position.

### 🔑 API key
###  📚 What is an API key?
An API key from OpenAI is a mechanism for authenticating and authorizing access to OpenAI's API (Application Programming Interface). An API key is like a password, allowing developers to interact with OpenAI's services in a secure manner. The API key is a critical factor in establishing a connection between the server and the client, used to verify the legitimacy of the request. Typically, only users with a valid API key can access a specific API.

Here are the general steps to use the OpenAI API key:

- Create an OpenAI account: You first need to [click here](https://platform.openai.com/signup) to create an OpenAI account, and then generate your API key in that account.

- Generate API key: In the OpenAI dashboard, [click here](https://platform.openai.com/account/api-keys) you can generate a new API key."

###  Bind your own API key🔀🔑
Press the shortcut `Ctrl+Shift+P`, enter `ChatGPT:Bind your own API key🔀🔑`, press Enter, input the API key, press Enter again, and the API key will be updated.

You can also open any file, right-click, select `ChatGPT:Bind your own API key🔀🔑`, input the API key, and press Enter to update the API key. If the update is successful, the balance and expiry date of the API key and supported models will be displayed. If the update fails, you will be prompted to re-enter the API key.


###   Validate API key✔️🔑
Press the shortcut `Ctrl+Shift+P`, enter `ChatGPT:Validate API key ✔️🔑`, press Enter, and the API key will be validated.

You can also open any file, right-click, select `ChatGPT:Validate API key ✔️🔑`, and press Enter to validate the API key. If the validation is successful, the balance and expiry date and supported models of the API key will be displayed. If the validation fails, you will be notified that the API key is invalid.

If you wish to use GPT-4, you need to [click here](https://openai.com/waitlist/gpt-4-api) to apply for GPT-4 API permissions.

###  刷新API key🔀🔑
Press the shortcut `Ctrl+Shift+P`, enter `ChatGPT:Refresh API key 🔄🔑`,You can then obtain a new API key!


###   Why is there a bug in this code?🐛💻
Open any file, select a piece of code (if no code is selected, the whole content of the file will be considered), then right-click and choose `ChatGPT:Why is there a bug in this code? 🐛💻` from the menu. This can help you analyze your code and highlight any errors.


###   Help me explain the code?💬📖
Open any file, select a piece of code (if no code is selected, the whole content of the file will be considered), then right-click and choose `ChatGPT:Help me explain the code? 💬📖` from the menu. This can help explain your code.

###  Refactor this code and tell me what did you change?🔧💻 
Open any file, select a piece of code (if no code is selected, the whole content of the file will be considered), then right-click and choose `ChatGPT:Refactor this code and tell me what did you change? 🔧💻` from the menu. This can help refactor your code.


###   Add some tests for this code for me➕🧪💻
Open any file, select a piece of code (if no code is selected, the whole content of the file will be considered), then right-click and choose `ChatGPT:Add some test for this code for me ➕🧪` from the menu. This can help add tests for your code.


###  Custom prompt✏️❓
Open any file, select a piece of code (if no code is selected, the whole content of the file will be considered), then right-click and choose `ChatGPT:Custom prompt ✏️❓` from the menu. An input box will pop up, type your question, press Enter, and you will get an answer.

### Add predefined prompts➕
Press the shortcut `Ctrl+Shift+P`, enter `ChatGPT:Add Predefined Prompt ➕`, press Enter, and you can enter predefined prompts, which could be a title or content.
After input, in the question input box, you can type / to pop up a predefined selection box, then use the up and down arrow keys to select a predefined prompt. Press Enter or click to confirm and it will be automatically filled into the question input box.


###  Set language🌍
Press the shortcut `Ctrl+Shift+P`, enter `ChatGPT:Set language 🌍`, press Enter, and select the language you want to set. The default is English.

###  Set up a custom proxy server🌐
Press the shortcut `Ctrl+Shift+P`, enter `ChatGPT:Set up a custom proxy server 🌐` ，Then, by entering your own proxy server, you can use your own proxy server.


### Settings❓ 
- [OpenAI Documentation](https://platform.openai.com/docs/)
- [OpenAI API Guide](https://platform.openai.com/docs/api-reference)

#### 🧠Model
The OpenAI API is powered by a diverse set of [models](https://platform.openai.com/docs/models) with different capabilities and price points. You can also make limited customizations to our original base models for your specific use case with fine-tuning.

##### GPT-3.5
GPT-3.5 models can understand and generate natural language or code. Our most capable and cost effective model in the GPT-3.5 family is gpt-3.5-turbo which has been optimized for chat but works well for traditional completions tasks as well.

On June 27th, 2023, gpt-3.5-turbo will be updated to point from gpt-3.5-turbo-0301 to gpt-3.5-turbo-0613.

We recommend using gpt-3.5-turbo over the other GPT-3.5 models because of its lower cost and improved performance.

##### GPT-4
GPT-4 is currently in a limited beta and only accessible to those who have been granted access. Please join the waitlist to get access.

GPT-4 is a large multimodal model (accepting text inputs and emitting text outputs today, with image inputs coming in the future) that can solve difficult problems with greater accuracy than any of our previous models, thanks to its broader general knowledge and advanced reasoning capabilities. Like gpt-3.5-turbo, GPT-4 is optimized for chat but works well for traditional completions tasks both using the Chat Completions API. Learn how to use GPT-4 in our GPT guide.

#### 🌡️Temperature
In the OpenAI API, `temperature` is a parameter that controls the randomness of the generated text. Its value is between 0 and 1, inclusive.

When the `temperature` is close to 1, the text generated by the model will be more random. In other words, when the model chooses the next word, it will make a more uniform selection among all possible words, even if the probabilities of some words are low. This may result in outputs that are more innovative, but it may also lead to reduced coherence and consistency in the outputs.

When the `temperature` is close to 0, the text generated by the model will be more deterministic. That is, the model will be more inclined to choose the word with the highest probability when selecting the next word. This may result in outputs that are more coherent and consistent, but they may lack innovation.

In summary, the `temperature` parameter can help you find a balance between innovation and coherence. If you want the generated text to be more innovative, you can try to increase the value of `temperature`; if you want the generated text to be more coherent, you can try to decrease the value of `temperature`.

## 🗣️ Communication
- You are welcome to join

 the QQ discussion group for discussions
- ChatGPT① group 794147724【Full】
- ChatGPT② group【Not Full】 [Click to join](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=meREBUj-zAqgRqNEAvdDOI-PB4yUIvp_&authKey=CKwikgmiZKyRlxADmsn22nwHQawfTiseShOK2qzfEh5j%2F3eGC3dd70D60ZH0IKE6&noverify=0&group_code=724138520)
- Or join by scanning the QQ QR code<br/>
<img src="https://gptlesson1.oss-cn-beijing.aliyuncs.com/group2.png" height="128">

</div>
<div style="width: 45%;">

**中文**
## 特色

- 💻 可以复制、插入代码到当前文件和新文件中
- 🚀 可以添加预定义提示词以便在提问的时候快速输入
- 📤 可以导出代码或整个会话为markdown文件 
- 💾 可以将你的会话记录保存在本地硬盘，随时回放、继续和管理
- 🔑 绑定自己的支持GPT4的API key之后可以GPT4模型
- 🗣️ 绑定自己的API key之后支持流式上下文对话并且可以随时暂停回答
- 🌐 可以使用你自己的 OpenAI服务器
- 🔒 隐私安全，所有信息都保存在本地硬盘，不会将任何信息上传至任何服务器


## 命令
- **ChatGPT:发起提问❓**: 点击ChatGPT图标并输入内容，然后按Enter键获取ChatGPT的回复
- **ChatGPT:绑定自己的API key🔀🔑**: 通过组合快捷键和命令轻松更新API key
- **ChatGPT:验证API key✔️🔑**: 验证API key以确保其有效性和正确功能
- **ChatGPT:刷新API key🔄🔑**: 刷新现有API key以获得新的API key
- **ChatGPT:为什么这段代码出现了BUG?🐛💻**: 使用查找代码错误功能来分析和突出代码中的错误
- **ChatGPT:为我这段代码添加测试➕🧪💻**: 使用解释代码功能来更好地理解您的代码
- **ChatGPT:重构这段代码并告诉我你改动了哪里?🔧💻**: 重构代码并清楚地了解您改变了什么
- **ChatGPT:为我这段代码添加测试➕🧪💻**: 为您的代码轻松添加测试
- **ChatGPT:自定义提问✏️❓**: 为ChatGPT生成自定义查询
- **ChatGPT:增加预定义提示词➕**: 通过组合快捷键和输入，添加预定义的提示词
- **ChatGPT:修改显示语言🌍**: 通过快捷键和命令来设置您想要的语言。默认是英文
- **ChatGPT:设置自定义的代理服务器🌐**: 通过输入自己的代理服务器信息，设置并使用自己的代理服务器
- **ChatGPT:清空列表🗑️**: 可以清空当前的会话
- **ChatGPT:导出markdown📤**: 可以导出当前的会话为markdown文件

## 📖 使用
### 🔧 安装扩展
从[VSCode市场](https://marketplace.visualstudio.com/items?itemName=zhang-renyang.chat-gpt)安装扩展

###  提问❓
按下快捷键`Ctrl+Shift+P`，输入`ChatGPT:发起提问 ❓`，按Enter键，输入问题，再次按Enter键，就会自动打开回答面板进行回答

或者点击左侧的ChatGPT图标，输入你想说的内容，按Enter键，等待几秒钟，ChatGPT的回复就会出现。

在答案页面上，第一个小图标是复制到剪贴板，第二个小图标是将答案插入到当前光标位置，第三个小图标是创建并打开文件并将答案插入到当前光标位置。

### 🔑 API key
###  📚 什么是API key？
OpenAI的API key是一种用于验证和授权访问OpenAI的API（应用程序编程接口）的机制。API key就像一个密码，允许开发者以安全的方式与OpenAI的服务进行交互。API key在建立服务器和客户端之间的连接中是一个关键因素，用于验证请求的合法性。通常，只有拥有有效API key的用户才能访问特定的API。

以下是使用OpenAI API key的一般步骤：

- 创建OpenAI账户：你首先需要[点击这里](https://platform.openai.com/signup)创建一个OpenAI账户，然后在该账户中生成你的API key。

- 生成API key：在OpenAI的仪表盘上，[点击这里](https://platform.openai.com/account/api-keys)你可以生成一个新的API key。

###  绑定自己的API key🔀🔑
按下快捷键`Ctrl+Shift+P`，输入`ChatGPT:绑定自己的API key🔀🔑`，按Enter键，输入API key，再次按Enter键，API key就会被更新。

你也可以打开任何文件，右键点击，选择`ChatGPT:绑定自己的API key🔀🔑`，输入API key，按Enter键更新API key。如果更新成功，将显示API key的余额和到期日期以及支持的模型。如果更新失败，你将被提示重新输入API key。

###   验证API key✔️🔑
按下快捷键`Ctrl+Shift+P`，输入`ChatGPT:验证API key ✔️🔑`，按Enter键，API key就会被验证。

你也可以打开任何文件，右键点击，选择`ChatGPT:验证API key ✔️🔑`，并按Enter键验证API key。如果验证成功，将显示API key的余额、到期日期和支持的模型。如果验证失败，你将收到API key无效的通知。

如果你希望使用GPT-4，你需要[点击这里](https://openai.com/waitlist/gpt-4-api)申请GPT-4 API权限。

###   刷新API key🔄🔑
按下快捷键`Ctrl+Shift+P`，输入`ChatGPT:刷新API key 🔄🔑`，你就可以获得一个新的有效的API key。

###   为什么这段代码有错误？🐛💻
打开任何文件，选择一段代码（如果没有选择代码，将会考虑文件的全部内容），然后右键选择菜单中的`ChatGPT:为什么这段代码出现了BUG? 🐛💻`。这可以帮助你分析代码并突出显示任何错误。

###   帮我解释这段代码？💬📖
打开任何文件，选择一段代码（如果没有选择代码，将会考虑文件的全部内容），然后右键选择菜单中的`ChatGPT:讲解下面代码 💬📖`。这可以帮助解释你的代码。

###  重构这段代码并告诉我你改变了什么？🔧💻 
打开任何文件，选择一段代码（如果没有选择代码，将会考虑文件的全部内容），然后右键选择菜单中的`ChatGPT:重构这段代码并告诉我你改动了哪里? 🔧💻`。这可以帮助重构你的代码。

###  为我添加一些测试代码➕🧪💻 
打开任何文件，选择一段代码（如果没有选择代码，将会考虑文件的全部内容），然后右键选择菜单中的`ChatGPT:为我这段代码添加测试 ➕🧪`。这可以帮助为你的代码添加测试。

###  自定义问题✏️❓
打开任何文件，选择一段代码（如果没有选择代码，将会考虑文件的全部内容），然后右键选择菜单中的`ChatGPT:自定义提问 ✏️❓`。会弹出一个输入框，输入你的问题，按Enter键，你就会得到答案。

### 增加预定义提示词➕
按下快捷键`Ctrl+Shift+P`，输入`ChatGPT:增加预定义提示词 ➕`，按Enter键，就可以输入预定义的提示词，可以输入标题和内容。
输入之后在提问输入框可以键入`/`弹出预定义选择框，然后按上下方向键可以选择预定义提示词，回车或点击可以确定并自动填入提问输入框

###  设置语言🌍
按下快捷键`Ctrl+Shift+P`，输入`ChatGPT:修改显示语言 🌍`，按Enter键，选择你想要设置的语言。默认是英文。

###  设置自定义代理服务器🌐
按下快捷键Ctrl+Shift+P，输入`ChatGPT:设置自定义的代理服务器 🌐`，然后输入你自己的代理服务器，你就可以使用你自己的代理服务器了。

### ❓ 设置
- [OpenAI文档](https://platform.openai.com/docs/)
- [OpenAI API指南](https://platform.openai.com/docs/api-reference)

#### 🧠模型
OpenAI API由一组具有不同功能和价格点的[模型](https://platform.openai.com/docs/models)驱动。你也可以通过微调对我们的原始基础模型进行有限的定制，以适应你的特定使用场景。

##### GPT-3.5
GPT-3.5模型可以理解和生成自然语言或代码。在GPT-3.5系列中，我们最有能力和最具成本效益的模型是gpt-3.5-turbo，它已经针对聊天进行了优化，但也适合传统的完成任务。

在2023年6月27日，gpt-3.5-turbo将从gpt-3.5-turbo-0301更新为gpt-3.5-turbo-0613。

我们建议使用gpt-3.5-turbo而不是其他GPT-3.5

模型，因为其成本更低，性能更好。

##### GPT-4
GPT-4目前处于有限的beta测试阶段，只对获得许可的人开放。请加入等候名单以获得访问权限。

GPT-4是一个大型的多模型（接受文本输入并发出文本输出，将来可以接受图像输入），它可以比我们之前的任何模型更准确地解决困难的问题，这要归功于它更广泛的一般知识和先进的推理能力。像gpt-3.5-turbo一样，GPT-4针对聊天进行了优化，但也适合传统的完成任务，都使用Chat Completions API。在我们的GPT指南中了解如何使用GPT-4。

#### 🌡️温度
在OpenAI API中，`temperature`是一个控制生成文本随机性的参数。它的值在0和1之间，包含两端。

当`temperature`接近1时，模型生成的文本将更具随机性。换句话说，当模型选择下一个单词时，它将在所有可能的单词中做出更均匀的选择，即使某些单词的概率较低。这可能会产生更具创新性的输出，但也可能导致输出的连贯性和一致性降低。

当`temperature`接近0时，模型生成的文本将更具确定性。也就是说，模型在选择下一个单词时，将更倾向于选择概率最高的单词。这可能会产生更连贯和一致的输出，但可能缺乏创新性。

总的来说，`temperature`参数可以帮助你在创新性和连贯性之间找到平衡。如果你希望生成的文本更具创新性，你可以尝试增加`temperature`的值；如果你希望生成的文本更连贯，你可以尝试降低`temperature`的值。


## 🗣️ 交流
- 欢迎加入

QQ讨论群进行讨论
- ChatGPT①群 794147724【满员】
- ChatGPT②群【未满员】 [点击加入](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=meREBUj-zAqgRqNEAvdDOI-PB4yUIvp_&authKey=CKwikgmiZKyRlxADmsn22nwHQawfTiseShOK2qzfEh5j%2F3eGC3dd70D60ZH0IKE6&noverify=0&group_code=724138520)
- 或通过扫描QQ二维码加入<br/>
<img src="https://gptlesson1.oss-cn-beijing.aliyuncs.com/group2.png" height="128">

</div>
</div>