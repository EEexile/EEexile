# EEexile

[中文](#中文) · [English](#english)

语音信号处理 · 音频 AI · 全双工交互 · 多模态情绪识别

## 中文

### 关于我

关注语音助手如何判断什么时候该听、该等、该停、该接话，也关注音频、文本和视频怎样互补，帮助模型识别情绪。

### 实习与团队成果

**语音算法实习 · 全双工语音交互**

团队围绕电话场景的误打断问题，构建了覆盖噪声、附和、有效发言和明确打断的数据，迭代流式打断判别模型，并开展停播策略评测。公开项目以可运行示例呈现 VAD 之后的两条决策链路。

### 代表项目

**语音交互**

- [全双工语音交互决策](https://github.com/EEexile/full-duplex-barge-in-demo)  
  AI 播报时判断是否停播，AI 监听时判断是否可以接话。仓库包含架构图、场景回放和可运行的浏览器演示。

**语音与多模态情绪识别**

- [CDMTL-SER](https://github.com/EEexile/CDMTL-SER)  
  联合建模离散情绪类别和连续的效价、唤醒度、支配度。
- [MMSD](https://github.com/EEexile/MMSD)  
  面向音频与文本的情绪识别，使用多任务学习和自蒸馏。
- [ReCSI](https://github.com/EEexile/ReCSI)  
  在已有音频与文本识别模型上，结合残差修正、置信度校准和同说话人推断。
- [TriMEF](https://github.com/EEexile/TriMEF)  
  面向多模态情绪识别，研究模态交互前后的专家融合与目标人脸可观测性。

### 技术方向

| 方向 | 关注内容 |
| --- | --- |
| 语音交互 | 流式 VAD、话轮检测、打断识别、场景评测 |
| 语音建模 | Python、PyTorch、Whisper、Qwen3-ASR |
| 情绪识别 | 音频、文本与视频融合，多任务学习，自蒸馏 |

## English

Speech processing · Audio AI · Full-duplex interaction · Multimodal emotion recognition

### About

I am interested in how voice assistants decide when to listen, wait, stop speaking, and respond, and how audio, text, and video complement one another in emotion recognition.

### Internship and team work

**Speech algorithms internship · Full-duplex voice interaction**

The team built data covering noise, backchannels, speech, and explicit interruptions, iterated on a streaming interruption classifier, and evaluated playback control policies. The public demo illustrates both decision paths after voice activity detection.

### Selected projects

| Project | Focus |
| --- | --- |
| [Full-duplex Voice Interaction](https://github.com/EEexile/full-duplex-barge-in-demo) | Playback interruption and response timing, with a runnable browser demo |
| [CDMTL-SER](https://github.com/EEexile/CDMTL-SER) | Joint categorical and dimensional speech emotion recognition |
| [MMSD](https://github.com/EEexile/MMSD) | Multitask self-distillation for audio-text emotion recognition |
| [ReCSI](https://github.com/EEexile/ReCSI) | Residual correction, calibration, and speaker-structured inference |
| [TriMEF](https://github.com/EEexile/TriMEF) | Expert fusion and target-face observability for multimodal emotion recognition |
