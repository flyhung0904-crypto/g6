---
name: shuke
display_name: 熟客
case_type: 創作
subtype: 合輯內單篇
cold_start_mode: full
cold_start_date: 2026-09-07

lighter_role: [作家]
pen_name: 猶安

basic_info:
  collection: 聚首
  collection_position: 篇一（篇名與合輯名語意接近，Lighter 2026-09-07「太近沒關係」，不改）
  word_count_target: 23500
  word_count_hard_cap: 25000
  chapter_count: 5
  start_date: 2026-09-07

core_message:
  logline: 一個熟客死在同志酒吧，全店都說他是喝多了跌倒。兩個公關接到他生前轉過來的客人，才發現他死前替店裡最小的那個人辦好了一整份離開，而那份離開在他死後照樣生效。
  core_suspense: 兩個人都說「我知道他」，一個把他送走，一個為了留下他殺了人；沒有人問過他。
  dual_axis:
    - 懼熟線：宇辰推進——會問的人，問之前先猜好答案
    - 代決線：立航推進——他看一眼說「老樣子」，事情就成了意外
  core_image: 城市裡的每個人都可能是對方的胃
  subtypes: [同志懸疑, 職場犯罪]
  shelf_category: 同志文學／同志懸疑（⛔ 不歸純推理櫃、⛔ 不歸 BL）

redlines:
  - level: absolute
    description: R1 全篇無女性角色，含背景出場者與回憶人物
  - level: absolute
    description: R2 正文上限 25,000 字，工具實數計
  - level: absolute
    description: R3 支配關係寫在職場與社會層，不壓縮成雙男主之間的控制
  - level: absolute
    description: R4 不寫私密影像；殺人動機不放在欠債、侵占、分紅、交易失敗
  - level: absolute
    description: R5 不由男公關職稱推定性服務，不混用其他店型制度
  - level: absolute
    description: R6 署名猶安，不與真人掛勾
  - level: absolute
    description: R7 魏與信翔、家豪與信翔禁曖昧化
  - level: absolute
    description: R8 代辦者（魏）的權力要有店內依據
  - level: absolute
    description: R9 全篇不出現任何法律
  - level: absolute
    description: R10 不寫法醫、警察、鑑識（2026-10-09）

redline_released:
  - description: 命案數與凶手人選
    ruling: Lighter 2026-09-07「3 可以開放」；2026-10-09 選定方案三，真凶改為家豪

spoiler_policy:
  social: 全禁謎底與凶手
  essay: 可寫命案發生與職場權力主題，不點凶手、不寫三次翻轉內容
  criticism: 全開

downstream_chain:
  - skill: tw-mystery-planning
    scope: v5 重寫
    status: v5 交付，待 Lighter 簽收與審議
  - skill: tw-novel-writing
    status: pending
  - skill: tw-novel-revision
    status: pending
  - skill: tw-verification-runner
    status: pending
  - skill: tw-mystery-manuscript-review
    status: optional

cross_artifacts:
  redline_list: 紅線清單.md
  source_plan: 企劃.md（v5，唯一真相源）
  plot_walkthrough: 情節線與懸疑.md
  character_relations: 人物與關係.md
  info_asymmetry_table: 訊息與線索.md
  chapter_continuity_log: 章節與連續性.md
  voice_calibration: 語感校準.md
  issues_pool: _issues.md
  source_research: 前置材料\職業設定.md、前置材料\熟客_同志男公關_職業普查與創作校準.md
  floor_plan: 前置材料\岸邊平面圖.png（場地有效、v4 動線註記作廢）

narrative_spec:
  person: 第三人稱限知
  pov_rotation: 章節輪轉（1、3、5 宇辰；2、4 立航）
  chapter_length: 4700（第 4 章超過 5,000 即依企劃 §十四挪段）
  per_chapter_load: 一次翻（或鋪陳）＋一個職場現場＋一段兩人之間，⛔ 不加第四件

character_physical_card:
  - {role: 視角一, name: 宇辰, age: 23, occupation: 公關（十個月）, height: 172, build: 偏瘦・肩窄, distinctive_features: [住板橋騎車, 開口前先停一下]}
  - {role: 視角二, name: 立航, age: 29, occupation: 公關（四年）・週三週四開店, height: 179, build: 中等・手臂有線條, distinctive_features: [記得每個人喝什麼, 開店先拿杯架右上角的杯子]}
  - {role: 死者, name: 魏仲凱, age: 29, occupation: 熟客・小股東, height: 183, build: 高壯有肚子, distinctive_features: [皮外套掛椅背, 坐最裡面那席, 喝多睡後方長椅]}
  - {role: 被安排的人, name: 信翔, age: 22, occupation: 公關（七個月）, height: 167, build: 瘦, distinctive_features: [店服偏大袖口蓋手背, 被叫到時先笑]}
  - {role: 真凶, name: 家豪, age: 25, occupation: 吧台（兩年）・週二週三收班, height: 176, build: 結實手大, distinctive_features: [最後一個杯子放杯架右上角, 講話快]}

progress:
  current_skill: tw-mystery-planning
  current_phase: v5 交付，待決三項已裁，待審議
  written_chapters: []
  word_count_actual: 0

lighter_signoff:
  plan_v5: false

versions:
  - version: 1.0
    date: 2026-09-07
    note: cold-start full 初版
  - version: 2.0
    date: 2026-10-09
    note: 企劃 v5 重寫，人物與凶手全換，立 R10
---

# 熟客 case-spec

## 五、完成判準（⛔ 動筆前定，⛔ 不做完回頭放寬）

- **S1** 正文五章，總字數 23,500±1,000、上限 25,000，以工具實數計（含標點與數字、不含空白）。
- **S2** 全篇出現的人物零名女性，含背景與回憶；逐章掃描確認。
- **S3** 第 1 章結束前讀者知道魏死了、全店說是意外；第 2 章結束前「意外」被撤掉。
- **S4** 三次翻各落在第 2、3、4 章，揭曉在第 5 章，每次都改變下一步行動。
- **S5** 訊息差表中，讀者取得時點與視角人物已知時點一致；唯一例外是第 11 條（立航一直知道右上角的習慣），且第 1 章已讓讀者看見。
- **S6** 至少三場重要核對發生在營業時間之外（白天、通勤、分租房）。
- **S7** 支配關係的每一次出現都落在職場或社會層；雙男主之間零控制情節。
- **S8** 交付前跑完 tw-verification-runner，禁令自掃歸零。
- **S9** 全篇出現具體地名、店的形制、與錢怎麼算三類本土材料各至少三處。
- **S10** 全篇零法醫、零警察、零鑑識、零法律（R9、R10），逐章掃描確認。
- **S11** 「他會懂的」「他不會想回去，我知道」各至多一次；「老樣子」第 5 章零次。

## 六、待確認

- [已裁 2026-10-09：家豪的去向＝B，不交代]
- [已裁 2026-10-09：店裡的人不必有姓；信翔本名「黃信翔」只在退租單出現一次]
- [已完成 2026-10-09：平面圖重畫為 v5 動線]
- [待辦：v5 送審議（動筆前置 gate）]
