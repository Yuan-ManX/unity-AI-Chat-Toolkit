# 项目更新日志

## 2023.8.11 update
### 新增功能
增加了针对whisper-webservice这个项目的api集成代码，部署下面这个项目，可以通过本次更新的代码调用语音识别的api
https://github.com/ahmetoner/whisper-asr-webservice
## 2023.8.6 update
### 新增功能
1、集成了Oculus的口型插件，AI小姐姐语音对话的时候，可以实现对a i u e o五种元音的识别和口型映射了。
[注意：因为Oculus插件包比较大,所以源码里只保留了window的dll库，针对安卓以及IOS的库，需要的话请自行下载，并放入tool/LipSync下的plugins文件夹]
### 修复缺陷
1、修复了百度语音合成脚本，使用的app key未授权语音合成服务时，返回信息类型不能正确处理，并打印的问题

## 2023.7.27 update
### 新增功能
1、集成openai的whisper语音识别api，实现语音识别功能
2、增加webgl平台中文输入解决方案[全屏无效，暂无其他好的解决方案]

## 2023.7.24 update
### 修复缺陷
1、修复百度语音合成脚本，获取token异常，以及语音识别精度低的问题

## 2023.7.22 create
创建本仓库，提供unity调用大语言模型api以及相关语音服务api的插件，主要功能：
### 新增功能
**LLM大语言模型交互**
1、集成chatgpt的api，实现chat聊天功能
2、集成chatglm官方接口格式的api，实现chat聊天功能
3、集成rwkv runner项目的api，实现chat聊天功能
**语音模型交互**
1、集成Azure语音服务api，实现语音合成以及语音识别功能
2、集成百度AI开放平台语音服务api，实现语音合成与语音识别功能
**其他**
1、增加发布WebGL，实现语音录制解决方案的代码，实现在webgl端的录音功能



