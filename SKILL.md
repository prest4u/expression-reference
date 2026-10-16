---
name: expression-reference
description: 构思或修改口播、科技介绍、品牌文案、ToB 方案、工作沟通及学科说明、论文片段和教学文本。按当前场景与学科选读中英文真实作品的 Reference，调整材料、顺序和声音距离，修复 AI Slop，保留事实与作者立场。
metadata:
  version: "0.5.1-preview.2"
---

# Expression Reference

让表达服务于说话者、读者、双方关系、媒介和读者要完成的任务。审美允许多个成立方向；事实、引文和承诺保持原有含义。从用户材料推断中心与立场，重要推断要说明；只问会改变成稿的关键缺口。保留用户认可的 baseline，声音样本取自用户亲自认可的表达。

## 出稿前选读 Reference

**调用本技能构思或改稿，必须先用读取工具打开与当前任务对应的场景或主学科 Reference，短稿也要读。** 入口列出路径，具体写法从对应文件取用。文件无法读取时说明这一项，不能声称已参考。

| 文稿用途 | 先读的文件 |
|---|---|
| AI 应用口播 | [spoken.md](references/spoken.md) |
| 科技介绍 | [tech.md](references/tech.md)；解释机制、步骤或排障判断时选 [technical-explanation.md](references/technical-explanation.md) |
| 品牌/产品文案 | [brand.md](references/brand.md) |
| ToB 方案正文/摘要 | [tob.md](references/tob.md) |
| 短工作沟通 | [communication.md](references/communication.md) |
| 教学设计、课堂反思、学习研究 | [education.md](references/disciplines/education.md) |
| 医学研究摘要、健康科普 | [medicine-health.md](references/disciplines/medicine-health.md) |
| 数学推导、统计解释 | [mathematics-statistics.md](references/disciplines/mathematics-statistics.md) |

其他学科或用途不清时，用[学科索引](references/disciplines/index.md)定位再读主学科文件；已知对应路径就直接打开。学科稿可直接组织正文。第二份场景/学科只在它会改变当前写法或主张时读取，例如医学产品页同时需要品牌与医学；普通邮件无需学科索引。

**节省 token：** 带“短稿选读”的文件先读前 16 行；足够支撑本题就起草，需要原作分析或复杂论证再取同一文件的相关节。其他文件读相关正文。独立的读取可在同一轮并行完成；同一任务已读的部分不重复读。不遍历目录、不拼接全库、不默认加载诊断或来源记录。详细文章分析和练习继续留在各文件。

按交付语境选择语言；英文或 fusion 另读 [language.md](references/language.md) 的相关说明，结合所选文件的英文参照构思。fusion 按术语、界面、引语等功能使用。翻译按用户要求保真；语言切换不扩主张，不默认交双版。

## 将修改落实到正文

先选择中心与材料关系，再起草。读者不需要的背景、旁支、空泛评价与相邻同义复述可删或合并；缺失的推理可展开。开场引出的问题就近接到动作、材料或推理。结构、句长、抽象、留白、教学重复按本题用途选择；不设删字比例、禁词评分或名人仿声。

真实作品只借写作选择。原作者的经历、产品性能、数据和机构承诺不能移植到用户稿件。保留定义、量词、引文、数值、单位、研究对象、时间、假设与影响结论的条件；没有材料的功能、体验、心理或因果解释不补写。“未报告”“未做”按材料表达，不扩大成“不可能判断或计算”。

交稿前读一遍改稿，检查新加的具体细节和判断是否都有输入支持，是否改了主张强度或承诺；修复受影响的句子。保持原义，不为自然感加功能、反馈、经历或情绪。有难以解决的具体问题再取 [diagnostics.md](references/diagnostics.md) 对应项；只给诊断备注不足以完成改稿。

## 交付

交付请求的正文及必要取舍、缺失材料，不默认展示选读流程、评分表或通用警告。只检测时给具体问题；改稿时给成稿。朗读、视听和读者效果未执行就说明未测。反馈留在用户指定项目，不改全局偏好。

需要追查来源、已读范围或旧测试时再读 [evidence.md](references/evidence.md) 及当前文件的来源段。正式引用或当下专业结论需核原文与版本；官方本地化稿算一组双语材料。文件中的原创练习用于解释选择；实际改进仍需观察成稿与使用结果。
