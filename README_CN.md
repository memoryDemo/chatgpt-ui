# 与GPT聊天

Chat with GPT是一个开源，非官方的ChatGPT应用程序，具有额外的功能和更多的方法来定制您的体验。它将ChatGPT与ElevenLabs连接起来，为ChatGPT提供真实的人类声音。

尝试托管版本:https://chatwithgpt.netlify.app

或者[self-host with Docker](#running-on-your-own-computer)。

由OpenAI的新ChatGPT API提供支持，这个应用程序使用TypeScript + React开发。我们欢迎来自社区的拉请求!

https://user-images.githubusercontent.com/127109874/223613258-0c4fef2e-1d05-43a1-ac38-e972dafc2f98.mp4

## 特性

-🚀**快速**响应时间。
-🔎**通过您过去的聊天对话搜索**。
-📄查看并自定义系统提示- **秘密提示**系统在您的消息之前显示AI。
-🌡通过设置温度设置来调整响应的**创造性和随机性。更高的温度意味着更多的创造力。
-💬通过连接您的ElevenLabs文本到语音帐户，为ChatGPT AI提供**逼真的人类声音**。
-🎤**语音识别**由OpenAI Whisper提供
- **公开共享url **您最喜爱的在线聊天会话。
-📋轻松**复制和粘贴** ChatGPT消息。
-✏️编辑您的消息
-🔁重新生成ChatGPT消息
-🖼**完整的markdown支持**包括代码，表格和数学。
-🫰仅为您使用的ChatGPT API付费。

带上你自己的API密钥

### OpenAI

要开始使用GPT聊天，您需要在设置屏幕上添加OpenAI API密钥。点击主页上的“连接您的OpenAI帐户以开始”开始。一旦添加了API密钥，就可以开始与ChatGPT聊天了。

你的API密钥只存储在你的设备上，不会传输给除了OpenAI之外的任何人。请注意，OpenAI API密钥使用是按现收现付费率收费的，与您的ChatGPT订阅分开。

### ElevenLabs

要使用真实的AI文本转语音功能，您需要通过单击任何消息旁边的“播放”添加ElevenLabs API密钥。

您的API密钥只存储在您的设备上，不会传输给除ElevenLabs之外的任何人。

## 在自己的电脑上运行

要在你自己的设备上运行，你可以使用Docker:

```
Docker运行-v $(pwd)/data:/app/data -p 3000:3000 ghcr.io/cogentapps/chat-with-gpt:release
```

然后导航到http://localhost:3000查看应用程序。

# #更新

```
Docker pull ghcr.io/cogentapps/chat-with-gpt:release
```

# #许可证

与GPT的聊天是根据MIT许可证授权的。有关更多信息，请参阅许可证文件。