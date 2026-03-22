# LyricSync · 双语字幕打轴工具

[English](#english) · [中文](#中文)

---

## 中文

为外语翻唱视频创作者设计的双语字幕工具。

**在线体验 → [lyricsync-theta.vercel.app](https://lyricsync-theta.vercel.app)**

### 解决的问题

- 剪映双语字幕需要 SVIP，且翻译质量差、分句节奏不可控
- Whisper 等自动识别工具对 rap、快歌时间戳断句不准

### 功能

- 粘入双语交替歌词自动拆分，或粘入原文一键 AI 翻译
- 行数不对齐时自动提示并修复
- 手动打轴：跟着音频节奏按键标记每句时间点，支持调速
- 导出标准 .srt 字幕文件，直接导入剪映使用

### 技术栈

HTML / CSS / JavaScript · Vercel Serverless · 智谱 AI GLM-4-Flash

---

## English

A bilingual subtitle timing tool for creators making foreign language cover videos.

**Try it → [lyricsync-theta.vercel.app](https://lyricsync-theta.vercel.app)**

### Problem

- Tools like CapCut require paid subscriptions for bilingual subtitles, with poor translation quality and uncontrollable sentence segmentation
- Auto-recognition tools like Whisper struggle with rap and fast-paced songs

### Features

- Paste bilingual lyrics to auto-split, or paste original lyrics for one-click AI translation
- Detects and fixes mismatched line counts automatically
- Manual timing: mark each line in sync with the audio, with adjustable playback speed
- Export standard .srt subtitle files, ready to import into any video editor

### Tech Stack

HTML / CSS / JavaScript · Vercel Serverless · Zhipu AI GLM-4-Flash
