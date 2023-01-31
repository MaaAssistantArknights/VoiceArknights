# VoiceArknights | 明日方舟，有嘴就行

基于 ASR 技术 与 《MAA 明日方舟小助手》的明日方舟半自动化控制（其实是整活项目

## 效果演示

[B 站视频](https://www.bilibili.com/video/BV1Y34y1f7zG)

## 使用说明

1. 安装依赖

    ```bash
    pip install -r requirements.txt
    ```

2. 下载 MAA

    下载 [MAA](https://github.com/MaaAssistantArknights/MaaAssistantArknights/releases)，解压到 maa 文件夹（小写），使用下面的目录结构  

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

3. 修改 `main.py` 文件中的 adb 路径和地址
4. 运行

    ```bash
    python main.py
    ```

## 开源库

- [python-vad](https://github.com/wangshub/python-vad): 🔈 Use python to achieve voice activity detection, this little program may be helpful for voice application
- [PaddleSpeech](https://github.com/PaddlePaddle/PaddleSpeech): Easy-to-use Speech Toolkit including Self-Supervised Learning model, SOTA/Streaming ASR with punctuation, Streaming TTS with text frontend, Speaker Verification System, End-to-End Speech Translation and Keyword Spotting. Won NAACL2022 Best Demo Award.
- [MaaAssistantArknights](https://github.com/MaaAssistantArknights/MaaAssistantArknights): 《明日方舟》小助手，全日常一键长草！| An Arknights assistant compatible with EN, JP, KR, ZH_TW clients

## 打赏

请作者喝杯咖啡吧~ （请备注语控项目，感谢你的资瓷 ✿✿ヽ(°▽°)ノ✿）

<div>
<img alt="sponsor" src="https://user-images.githubusercontent.com/18511905/171821963-be1247d1-2959-4d2f-91c1-095a215dd601.jpg" width=262 height=408/>
<img alt="sponsor" src="https://user-images.githubusercontent.com/18511905/171821974-c5b13928-c66a-4168-b472-02b7048a2eff.png" width=298 height=408/>
</div>
