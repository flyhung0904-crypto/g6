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
  collection_position: 篇一（篇名與合輯名待收稿時再定，Lighter 2026-09-07「不用管，最後收稿再說」）
  word_count_target: 23500
  word_count_hard_cap: 25000
  chapter_count: 5
  start_date: 2026-09-07
  end_date: 2026-09-14

core_message:
  logline: 兩名同志酒吧公關在熟客召集的聚會後發現常客死在整理間，追查那句「他睡了」的來源，看見自己賴以工作的熟悉如何被拿去替別人決定什麼叫沒事。
  dual_axis:
    - 懼熟線：葉子謙推進——他一直在替別人假設，學會問之前先學會了猜
    - 代決線：潘紹軒推進——他的「我看一眼就知道」是全店省下確認的工具
  core_image: 城市裡的每個人都可能是對方的胃
  subtypes: [同志懸疑, 社會派推理, 職場犯罪]
  shelf_category: 同志文學／同志懸疑（2026-09-07 Lighter 拍板；⛔ 不歸純推理櫃、⛔ 不歸 BL）

redlines:
  - level: absolute
    description: 全篇無女性角色，含背景出場者與回憶人物
  - level: absolute
    description: 正文上限 25,000 字，工具實數計
  - level: absolute
    description: 支配關係寫在職場與社會層，不壓縮成雙男主之間的控制
  - level: absolute
    description: 不寫私密影像；殺人動機不放在欠債、侵占、分紅、交易失敗
  - level: absolute
    description: 不由男公關職稱推定性服務，不混用其他店型制度
  - level: absolute
    description: 署名猶安，不與真人掛勾、不由筆名反推

redline_released:
  - description: 命案數與凶手人選（v1＝凶手方立勤，已作廢；v2＝真凶杜昱宸，待簽）
    ruling: Lighter 2026-09-07「3 可以開放」；檢核可提替代方案，⛔ 改動前先問

spoiler_policy:
  social: 全禁謎底與凶手
  essay: 可寫命案發生與職場權力主題，不點凶手、不寫四重反轉內容
  criticism: 全開

ai_out_of_scope:
  - none_specified

downstream_chain:
  - skill: tw-mystery-planning
    scope: 只跑 M1-M4 四角色交叉檢核，不重做企劃
    status: in_progress
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
  character_relations: 人物與關係.md
  info_asymmetry_table: 訊息與線索.md
  chapter_continuity_log: 章節與連續性.md
  issues_pool: _issues.md
  source_plan: 企劃.md（v4 重作版，唯一真相源）
  source_research: 前置材料\熟客_同志男公關_職業普查與創作校準.md

narrative_spec:
  person: 第三人稱限知
  pov_rotation: 章節輪轉（1、3、5 葉子謙；2、4 潘紹軒）
  chapter_length: 4700（單章上限 5200，超過即退回六章制重排）
  scene_ratio: 命案與解謎 50%／職業生活與社會處境 40%／雙男主情感 10%

character_physical_card:
  - {role: 主角・視角一, name: 葉子謙, age: 23, occupation: 公關（九個月）, height: 172, build: 偏瘦・肩窄, distinctive_features: [住板橋騎車, 說話前先停一下]}
  - {role: 主角・視角二, name: 潘紹軒, age: 29, occupation: 公關（三年）・帶新人, height: 178, build: 中等・手臂有線條, distinctive_features: [走路快腳步輕, 記得每個人喝什麼]}
  - {role: 死者, name: 簡柏庭, age: 27, occupation: 前公關・健身房教練・熟客・收錢辦事, height: 180, build: 練過・肩背厚, distinctive_features: [進門先開吧台下抽屜, 口頭禪「你不用說，我知道」]}
  - {role: 明面嫌疑, name: 紀立群, age: 26, occupation: 店長（公關升任）, height: 175, build: 中等偏壯, distinctive_features: [說話前先看手機, 左手戴錶收班摘下]}
  - {role: 第三方, name: 高承翰, age: 25, occupation: 吧台兼外場（兩年）・收另一家店介紹費, height: 182, build: 高瘦・手長, distinctive_features: [走動最多, 口袋永遠有開瓶器]}
  - {role: 真凶, name: 杜昱宸, age: 23, occupation: 公關（五個月）, height: 168, build: 瘦・肩窄, distinctive_features: [手上常有杯具或抹布, 被叫到時先笑再回答, 店服偏大袖口蓋住手背]}

progress:
  current_skill: tw-mystery-planning
  current_phase: planning（M1 重構版待簽收）
  written_chapters: []
  word_count_actual: 0

relations:
  is_sequel: false
  related_works: []

lighter_signoff:
  claude_md: false
  case_spec: false
  downstream_chain: true
  cross_artifacts: false
  active_projects_append: not_asked

versions:
  - version: 1.0
    date: 2026-09-07
    note: cold-start full 初版
---

# 熟客 case-spec

## 五、完成判準（⛔ 動筆前定，⛔ 不做完回頭放寬）

- **S1** 正文五章，總字數 23,500±1,000、上限 25,000，以工具實數計（含標點與數字、不含空白）。
- **S2** 全篇出現的人物零名女性，含背景與回憶；以逐章掃描確認。
- **S3** 命案在第 1 章結束前被發現，第 2 章明確進入他殺調查。
- **S4** 六次翻各自落在第 2、3（兩次）、4、5（兩次）章，且每次都改變下一步行動。
- **S9** 全篇出現具體地名、店的形制、與錢怎麼算三類本土材料各至少三處。
- **S10** 「你不用說，我知道」全篇出現次數 ≤2（工具實數）。
- **S5** 訊息差表 12 條中，讀者取得時點與視角人物已知時點一致，⛔ 無視角人物明知卻對讀者隱去的重大事實。
- **S6** 至少三場重要核對發生在營業時間之外（白天、通勤、租屋處）。
- **S7** 支配關係的每一次出現都落在職場或社會層；雙男主之間零控制情節。
- **S8** 交付前跑完 tw-verification-runner，禁令自掃歸零。

## 六、待確認

- [待確認：七名人物的物理特徵（身高、體型、走路特徵、服裝慣性）──企劃全缺，⛔ 動筆前要填齊]
- [待確認：命案動線的實際比例平面草圖──企劃要求核對，尚未製作]
- [待確認：篇名《熟客》與合輯名《聚首》語意接近，且「聚首」同時是企劃裡一條線的名字，是否調整其一]
- [待確認：真凶＝杜昱宸（21）是否定案；representation 疑慮見 _issues.md I-11]

## 訪談記錄（2026-09-07）

- **模式**：full
- **企劃位階**：當定稿企劃，先過四角色檢核（Lighter 選）
- **合輯**：開合輯根目錄與合輯層 CLAUDE.md；目前只確定書名《聚首》與本篇
- **不要 AI 插手的環節**：都不指定，全部交給我
- **紅線**：六條中第③條開放，其餘照收
- **時程**：一週內交完稿
- **暴雷**：三層標準分級
