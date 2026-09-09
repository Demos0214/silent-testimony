# 沉默证词 · AI 审讯室（Silent Testimony）

一个单文件 AI 审讯游戏：随机生成案件卷宗，三名嫌疑人各藏秘密，真凶在撒谎。
戳破口供矛盾、抬升心理防线、锁定真凶并提交定罪证据链——每一局都不一样。

- 玩法闭环：立案（AI 生成卷宗）→ 审讯（对话博弈 + 出示证据）→ 交代 → 指控宣判 → S~C 评级
- 接入方式：支持 DeepSeek / 智谱 GLM / Kimi / 通义 / 硅基流动等 OpenAI 兼容接口，只填 Key，本局锁定模型
- 免费可玩：内置演示案例「雨夜画室」，无需 API Key 即可体验完整流程
- 部署形态：单文件 HTML，双击即玩，零后端零依赖

## 运行

直接用浏览器打开 `silent-testimony.html` 即可。

## 文件

- `silent-testimony.html` — 游戏本体（含全部逻辑与样式）

---

© 2026 Demos Wang. All rights reserved.
