# VoiceArknights | 明日方舟，有嘴就行

基于 ASR 技术 与 《MAA 明日方舟小助手》的明日方舟半自动化控制（其实是整活项目

## 使用说明

1. 安装依赖

    ```bash
    pip install -r requirements.txt
    ```

2. 下载 MAA

    目前带单控的接口 MAA 还没有作为正式版本发布，所以请下载 [最新内测版](https://github.com/MaaAssistantArknights/MaaRelease/releases)，这里只有 Windows 的，mac 或者 linux 可以去 MAA 的 [主仓库 CI](https://github.com/MaaAssistantArknights/MaaAssistantArknights/actions) 里面找。或者等一段时间正式版发布  

    解压到 maa 文件夹（小写），使用下面的目录结构

    ```tree
    ├─maa
    │  ├─Python
    │  ├─resource
    │  └─xxxx.dll
    ├─src
    │  ├─vad
    │  └─......
    └─main.py
    ```

3. 运行

    ```bash
    python main.py
    ```

## 开源库

- [python-vad](https://github.com/wangshub/python-vad): 🔈 Use python to achieve voice activity detection, this little program may be helpful for voice application
- [PaddleSpeech](https://github.com/PaddlePaddle/PaddleSpeech): Easy-to-use Speech Toolkit including Self-Supervised Learning model, SOTA/Streaming ASR with punctuation, Streaming TTS with text frontend, Speaker Verification System, End-to-End Speech Translation and Keyword Spotting. Won NAACL2022 Best Demo Award.
- [MaaAssistantArknights](https://github.com/MaaAssistantArknights/MaaAssistantArknights): 《明日方舟》小助手，全日常一键长草！| An Arknights assistant compatible with EN, JP, KR, ZH_TW clients
