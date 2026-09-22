# MiMo 语音工坊（静态直连版）

基于小米 MiMo-V2.5-TTS 系列的语音合成 / 音色设计 / 声音克隆平台。

本仓库为构建产物，由源码仓库的 `npm run build:static` 生成。

- 纯静态部署，浏览器直连 MiMo 官方接口（已确认 CORS 允许）
- API Key 仅保存在访问者浏览器 localStorage，不上传任何服务器
- 三种模式：mimo-v2.5-tts / mimo-v2.5-tts-voicedesign / mimo-v2.5-tts-voiceclone
