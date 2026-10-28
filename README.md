# Leo.Ai · AI 做视频工具实测裁决库

> 我是 Leo Pan（Leo.Ai），小红书「Ai的花椒味」（Leo77778）。我用代码和 AI 做短视频，单条视频播放 211 万、近 7 日观看 203 万（后台数据）。
> 这是我标星的 200 多个仓库的**实查裁决**：每一个都真实打开看过——星数、许可证、最近更新、跟我的生产管线合不合——然后给一个明确结论。不是抄链接的收藏夹。
> 每周更新。

## 裁决分级

- 🟢 **在用**：已经进了我的生产管线，出了成品
- 🔧 **拆件**：整仓不合用，但拆了其中零件/方法进我的工具箱
- 👀 **索引**：看过、判断过，暂时不用，留个索引等场景
- ❌ **否决**：明确不用，附理由——省你踩坑的时间

---

## 🟢 在用

| 仓库 | 一句话 | 我的裁决 |
|---|---|---|
| [feitangyuan/onetake](https://github.com/feitangyuan/onetake)（★3,393） | 新闻剪辑式视频引擎 | 我的生产引擎之一，战报片就出自它 |
| [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar)（★8,770） | 代码绘制视频 Skill 集 | 方法论与质检口径在用 |
| [Vincentwei1021/video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft)（★14,162） | 152 张电影感镜头卡 | 镜头语言弹药库 |
| [guanmo-ai/design-style](https://github.com/guanmo-ai/design-style)（★137） | 每天一个设计风格 | 小而精，风格拆解的稳定来源 |
| huashu-motion（花叔） | HTML 动画包装 | 包装层在用；铁律是定制开发，不套模板 |

## 🔧 拆件

| 仓库 | 拆了什么 |
|---|---|
| [wx4766/html-to-video](https://github.com/wx4766/html-to-video)（★149） | 整仓不换引擎；把它的 qa.js 移植成了我自查链的「画面验收门」 |
| [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo)（★1,147） | 数字人主线不用；拆了 8 个包装组件做成 PIL 可调用代码 |
| [AbubakrChan/product-launch-motion](https://github.com/AbubakrChan/product-launch-motion)（★373，MIT） | 产品发布片的弹簧/运动模糊/节拍音效方法，拆技术卡中 |
| [whaleyxbt/claude-motion](https://github.com/whaleyxbt/claude-motion)（★700，MIT） | 它的 beats.py（BPM/小节/drop 检测）正对我的拍格短板 |
| [cth9191/animate](https://github.com/cth9191/animate)（★1,019，MIT） | 三道确认门流程与我的首帧门禁同构；风格插件库可借鉴 |

## 👀 索引

| 仓库 | 为什么先放着 |
|---|---|
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes)（★74,073，Apache-2.0） | HTML→确定性 MP4 的正规军；待实测试点后再裁决是否入链 |
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)（★135,911） | 一键成片名气大；与我的定制管线不是一条路，等设备到位再议 |
| [xpzouying/xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp)（★16,616） | 能力清单核完、分级方案定了；平台规则灰色，本人决定先放一下 |
| [PurpleDoubleD/locally-uncensored](https://github.com/PurpleDoubleD/locally-uncensored)（★2,811，AGPL-3.0） | 本地无审查 AI 工作室；要 GPU 硬件，手机党用不上 |
| [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh)（★775） | 姿势图库汉化版；注意：图片明确不得商用，只当查阅字典 |
| frederick-kk/ppt-rebuilder-king（★12，MIT） | PPT 图片→可编辑 PPTX 还原；小仓，我不交付 PPTX，用时再验 |
| [Vincentwei1021/video-talkcraft](https://github.com/Vincentwei1021/video-talkcraft)（★1,827） | 口播解说片方法正对口（字级配音同步/反 PPT 镜头系统/三重验收）；但许可证是 PolyForm 非商用、本体商用需作者授权，引擎又是 Remotion——只学方法，不入管线 |

## ❌ 否决

| 仓库 | 否决理由 |
|---|---|
| [anYuJia/better-douyin](https://github.com/anYuJia/better-douyin)（★988） | 开源的只是壳、真应用闭源还要激活码；非官方客户端 + AI 控号 = 封号风险 |
| Remotion（★68,328） | 框架是好框架；商用条款 + React 重写成本，与现有栈不合 |
| [nateherkai/herk-edit-kit](https://github.com/nateherkai/herk-edit-kit)（★2,286） | 许可证未标注，来路不明不碰；且是真人口播剪辑路子 |
| Barty-Bart/motion-graphics（★896） | 功能对口，但许可证未标注，先观望 |

---

## 我的裁决标准

1. 许可证清楚（不明的不用）
2. 还在维护（看最近推送，不看总星数虚名）
3. 跟我的管线契合，或者有一个能拆走的好零件
4. 涉及账号的，先算封号风险，再谈功能

## 关于我

- 小红书：**Ai的花椒味**（Leo77778）——用代码和数据重构商业逻辑，每天一条自动化生成的硬核笔记
- 接单：AI 定制短视频（数据可视化 / 奇观广告），小红书主页商品橱窗
- 本库的裁决来自真实生产：被否决的，多半是我真金白银踩过或者差点踩的坑

*最后更新：2026-10-28 · 裁决为个人实测意见，不构成使用建议*
