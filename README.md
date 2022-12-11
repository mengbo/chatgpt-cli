# chatgpt-cli

这是一个基于命令行的简单聊天机器人，利用了 [OpenAI 的 python 库](https://beta.openai.com/docs/libraries/python-bindings) ，参考了 [Building a Chatbot with OpenAI's GPT-3 engine, Twilio SMS and Python](https://www.twilio.com/blog/openai-gpt-3-chatbot-python-twilio-sms) 一文。

`chatgpt-cli.py` 是聊天机器人的脚本，`imagecreate-cli.py` 是生成图片的脚本。

注意，OpenAI 的 python 库使用的系统环境变量 `OPENAI_API_KEY` 需要设置。

建议使用 PDM 设置开发环境，命令如下：

```shell-session
$ pdm use python3
$ pdm update
```

[![pdm-managed](https://img.shields.io/badge/pdm-managed-blueviolet)](https://pdm.fming.dev)

