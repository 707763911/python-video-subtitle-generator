# Python Video Subtitle Generator

Python 视频字幕生成与合成工具。仓库内视频/音频为脱敏合成素材，不包含客户内容。

## 功能
- 音频提取
- ASR/字幕时间轴生成
- SRT / ASS 导出
- 软字幕封装
- 硬字幕烧录
- 批量处理

## 技术栈
Python、FFmpeg、Whisper/ASR（按实际实现）

## 快速开始
```bash
pip install -r requirements.txt
python generate_subtitle.py --input samples/input.mp4 --output output.srt
python burn_subtitle.py --video samples/input.mp4 --subtitle output.srt --output out.mp4
